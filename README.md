# EZBZ
System  to monitor the number of people in a room using WIFI signals

Public site of EZBZ:  ezbz.rf.gd

This project uses a raspberry pi 3, and custom wifi drivers to monitor the congestion of people in a room.

The pi uses its WIFI chip to create a second wifi interface in "monitor" mode, in addition to its original "managed" mode. 

It listens to the the open, unencrypted, MAC address packet sent by WIFI devices and updates the number of people in a room (after normalization).

The data is sent to an SQL database.
The public site updates its data with a call to the database (using php) on every entry.


Oron Werner

