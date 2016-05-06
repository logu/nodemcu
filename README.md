# Node MCU

## What’s a Node MCU?

The Node is an open-source IoT (Internet of Things) platform. It uses the Lua programming language.

In terms of hardware, it runs an ESP8266 WiFi SoC from Espressif systems. 

It comes with 10 GPIOs, and each GPIO can be used for PWM, I2C and 1-wire. It also has 3.3V pins, GND pins, RX, TX, SCLK, MISO, MOSI and so on.

## Different versions

### ESP8266 LOLIN

### ESP8266 Witty

## Installing the USB driver
On mac osx yosemite you need to install driver : 

	1. download and install (http://www.wch.cn/download/CH341SER_MAC_ZIP.html)
	2. run `sudo nvram boot-args="kext-dev-mode=1"`
	3. Reboot

## Arduino IDE setup 

### Install the Arduino IDE
[Download Arduino IDE from Arduino.cc](http://www.arduino.cc/en/Main/Software) !!! 1.6.4 or greater !!!

### Install the ESP8266 Board Package
	* Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field in the Arduino v1.6.4+ preferences.
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/pref.png)
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/cardurl.png)
	* Use the Board manager to install the ESP8266 package.
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/gestionaire.png)
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/gestioncatre.png)
### Test 
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/cardchoose.png)
![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/exemples.png)

#### Nodemcu Witty

## Witty 

## Wiring 

![Screen](https://raw.githubusercontent.com/logu/nodemcu/master/doc/img/pinout.png)

## Resources

(https://learn.adafruit.com/adafruit-huzzah-esp8266-breakout/using-arduino-ide)
(https://gregwareblog.wordpress.com/2016/01/10/esp-witty/)

