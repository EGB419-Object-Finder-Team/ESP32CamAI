# ESP32-CAM Simple AI Robot #




## Demonstration

Longpth's original demonstration:
[![ESP32-CAM: Simple AI Robot (Object Detection | Object Tracking | Lane Tracking)](http://img.youtube.com/vi/4C2c0xs6eFg/0.jpg)](https://www.youtube.com/watch?v=4C2c0xs6eFg "ESP32-CAM: Simple AI Robot (Object Detection | Object Tracking | Lane Tracking)")

## Dependencies
Download https://github.com/Links2004/arduinoWebSockets as zip file and add this library to your Arduino Libraries by Sketch/Include Library/Add Zip...<br/>

Android application: https://play.google.com/store/apps/details?id=com.p4f.esp32camai

## Programming ESP32-CAM Board

https://randomnerdtutorials.com/program-upload-code-esp32-cam/

- short summary:
* you need a FTDI programmer to program
* hook it up according to the following list:
ESP32-CAM	FTDI Programmer
GND	        GND
5V	        VCC (5V)
U0R	        TX
U0T	        RX
GPIO 0	    GND




Longpth's comments:


I configured my board as Tools/Board/ESP32 Wrover Module, and define CAMERA_MODEL_AI_THINKER for the pin definition. Because there are some different kind of ESP32-CAM modules, so please check your board and your pin definition respectively.

I clarified my module was trying to run the ESP32 example CameraWebserver first, then keep the setting for my other projects, but it maybe different from yours.

## LICENSE
Longpth authored under BSD-2 licence.  his code is free to use.  the libraries used appear to all be public, so should be no problem to use them.


longpth's part that contains his code is released under BSD 2-Clause License. Regarding other libraries used in this project, please follow the respective Licenses.
