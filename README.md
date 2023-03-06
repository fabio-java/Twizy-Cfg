## Twizy-Cfg SEVCON configuration shell with Web-based Remote Serial Monitor ##
This repository is a fork of [twizy-cfg](https://github.com/dexterbg/Twizy-Cfg) project by [dexterbg](https://github.com/dexterbg), a minimalistic SEVCON Gen4 configuration shell for Arduino.

This version works only with ESP32 boards because has a Web-based Serial Monitor to let it be more user-friendly.
Using this particular serial monitor you are able to input commands without USB cable connection, using WiFi connection instead through a browser from any devices.
The Remote Serial Monitor is available on this local address: **192.168.1.4/webserial** using this password: **twizy1234cfg** (that you can change editing [addWebMonitor.ino]() file)

**You will also need these additional libraries:**

* [WebSerialLite by asjdf](https://github.com/asjdf/WebSerialLite)
* []()

It's a port of my SEVCON core functionality from the OVMS project, with a simple command interface on the Arduino serial port.
