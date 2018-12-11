# EZBZ
Stand alone system to monitor the number of people in a room using WIFI signals

Notes:
------
- The system is currently on beta testings. 

- Public site has minimal UI. It is designed to only show the relevant data at this time, and not to have a great user experience.

- If you have knowledge in php and html web designing, and would like to contribute to this project - please let me know!


# Check out the public site of EZBZ at:  ezbz.rf.gd



Overview
--------
This project uses a raspberry pi 3, and custom wifi drivers to monitor the congestion of people in a room.


General steps
-------------
- The pi uses its WIFI chip to create a second WIFI interface in "monitor" mode, in addition to its original "managed" mode. 

- It listens to the open, unencrypted, MAC address packets sent by WIFI devices, normalize the data, and saves the number of people in    the room.

- The data is sent automatically to an SQL database using a python script

- The public site updates its data with a call to the database (using php) on every entry.



Detailed tutorial
-----------------
- TBA


Pictures
--------
- TBA



 
  
   
Thank you,

Oron Werner

suggestions are welcome
