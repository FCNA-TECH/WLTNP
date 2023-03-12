# WLTNP

 WLTNP- Wireless Letterbox Transciever Notification Project

 This is a project commissioned by my oldest sister, my task is to create a program that detects when a letter
 has entered the postbox and send an alert to her phone.

 I will carry out this task using two units: the letterbox unit and the homebase unit. both communicating with 
 each other via the HC-12 radio tranceiver and the notification being sent ia the ESP8266 NodeMcu V3 CH340G Wifi module.
 I am using the Arduino IDE language of C++ to program this.

 The Letterbox Unit(TLU) - An arduino nano powered by a 9v battery placed inside the letterbox, An Ultrasonic sensor will 
 be placed inside the letterbox and be used to detect distance and any letter that comes through and send a signal to the 
 homebase using a HC-12 module as these modules have a 1km range and should penetrate through the walls 

 The Homebase Unit(THU) - An arduino nano powered by a 9v battery placed on a desk or wherever you see fit, the HC-12 module
 in the THU will recieve the signal that a letter has been detected and use the ESP8266 to send a signal to the smartphone using 
 the IFTTT Libary and Software.
 
 
 Parts List:
 2 x Arduino NANO Boards
 2 x HC-12 Radio Modules
 2 x Breadboards (one small enough to fit inside letterbox, the other as big as you want as that will go on your desk)
 2 x 9v batteries
 1 x ESP8266 Wifi Module
 1 x Ultraasonic sensor
 

  Designed By Ferdinand Anyaeriuba 
  Started - 12/03/2023
  Completed - 
