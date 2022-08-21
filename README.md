# myPower
Power monitoring and logging using the Raspberry Pi

myPower is a simple monitoring and logging program for the Raspberry Pi. It collects live power usage data from the LeChacal RPICT8 current HAT and CT Sensors. myPower logs the data to daily files calculating each day's KiloWatt Hour Usage. [http://lechacal.com/wiki/index.php?title=RPICT8_Version_5]

This is my reworked version of Bill Hanken's original. I needed more than eight current sensors, so I had to reconfigure the software to work with two RPICT8 boards.


**myPower Remote App** -> https://github.com/mwieder/myPower-Remote
see the original here
myPower Remote App -> https://github.com/km6wye/myPower-Remote

When the "myPower Remote" app connects to myPower via Wifi the data can be viewed in a user friendly format with a 

* line graph
* pie chart
* Monthly KiloWatt Hour Usage
* Yearly KiloWatt Hour Usage 
* Lifetime KiloWatt Hour Usage
https://github.com/km6wye/myPower-Remote


INSTALL INSTRUCTIONS

--REQUIRES the LeChacal RPICT8 HAT on a Raspberry Pi--
--and optionally the LeChacal RPICT8 HAT on a Raspberry Pi--

The Raspberry Pi OS must be configured first [http://lechacal.com/wiki/index.php?title=Howto_setup_Raspbian_for_serial_read]

After that's working you're ready to configure the RPICT HATs.

1. Complete setup of the LeChacal RPICT8 HAT as per the instructions on their Wiki -  [http://lechacal.com/wiki/index.php?title=RPICT8_Version_5]. My rpict.conf file is in this archive.

2. Download and Unzip myPower-main.zip (this project) to preferred Folder (Usually /home/pi/mypower)

3. run the myPower executable

4. Log files are CSV type and will be saved into /home/pi/mypower/log


The myPower program was created using LiveCode community version 7.0.4 windows -> https://drive.google.com/file/d/12pmye5RoCY0KfHj_ayjftTeS7RpJrc0Y/view?usp=sharing
Raspberry Pi -> https://drive.google.com/file/d/1WnDLACdyEc7aueDhE_xX7on-HjK1LEuw/view?usp=sharing

