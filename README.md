Grove_IR_Matrix_Temperature_sensor_AMG8833
==================  

Introduction of sensor
----------------------------  
The AGM8833 is a high Precision Infrared Array Sensor based on Advanced MEMS Technology.

***

Before use:
=============
hardware:
>* A raspberry-PI board to run the example. 
>* A PI-screen to observe the gragh.  

software:
>* sudo apt-get update
>* sudo apt-get install -y build-essential python-pip python-dev python-smbus git
>* sudo apt-get install -y python-scipy python-pygame
>* sudo pip install colour
>* sudo raspi-config,to enable the IIC service.  
    select Advanced options  
    select I2C  
    select yes  

Usage  
=======
Attatch the sensor to raspberry-PI board,Please refer to the schematic of the corresponding Raspberry Pi version for the specific wiring method.
Test the wiring,type command in cmd line:
>* sudo i2cdetect -y 1(raspberry-pi 2B use I2C1),if get the correct IIC address,wiring is OK.  
>* download or  git clone this repository,enter corresponding directory,typing:  
    python thermal_cam.py


***
This software is written by downey  for seeed studio<br>
Email:dao.huang@seeed.cc
and is licensed under [The MIT License](http://opensource.org/licenses/mit-license.php). Check License.txt for more information.<br>

Contributing to this software is warmly welcomed. You can do this basically by<br>
[forking](https://help.github.com/articles/fork-a-repo), committing modifications and then [pulling requests](https://help.github.com/articles/using-pull-requests) (follow the links above<br>
for operating guide). Adding change log and your contact into file header is encouraged.<br>
Thanks for your contribution.

Seeed Studio is an open hardware facilitation company based in Shenzhen, China. <br>
Benefiting from local manufacture power and convenient global logistic system, <br>
we integrate resources to serve new era of innovation. Seeed also works with <br>
global distributors and partners to push open hardware movement.<br>
