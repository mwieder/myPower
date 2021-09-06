# myPower
Power monitoring and logging using the Raspberry Pi

myPower is a simple monitoring and logging program for the Raspberry Pi. It collects live power usage data from the LeChacal RPICT8 current HAT and CT Sensors. myPower logs the data to daily files calculating each day's KiloWatt Hour Usage. [http://lechacal.com/wiki/index.php?title=RPICT8_Version_5]

**myPower Remote App is Still In Development**
When the "myPower Remote" app connects to myPower via Wifi the data can be viewed in a user friendly format with a line graph and pie chart. Monthly, Yearly, and lifetime KiloWatt Hour Usage can also be viewed and graphed using the "myPower Remote" app.

INSTALL INSTRUCTIONS

--REQUIRES the LeChacal RPICT8 HAT on a Raspberry Pi--

1. Complete setup of the LeChacal RPICT8 HAT as per the instructions on their Wiki -  [http://lechacal.com/wiki/index.php?title=RPICT8_Version_5]

2. Download and Unzip myPower-main.zip (this project) to preferred Folder (Usually /home/pi/myPower)

3. Right click the myPower file, go to properties -> permissions and allow anyone to execute (or CHMOD) 

4. run the myPower executable

5. Log files are CSV type and will be saved into /home/pi/myPower/log


The myPower program was created using LiveCode community version 7.0.4
Livecode Community 7.0.4 for Windows -> https://drive.google.com/file/d/12pmye5RoCY0KfHj_ayjftTeS7RpJrc0Y/view?usp=sharing
