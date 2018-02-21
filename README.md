Original site
=
[https://github.com/webusb/arduino](https://github.com/webusb/arduino)


WebUSB ❤ ️Arduino
================

This repository contains an Arduino library for WebUSB-enabling your sketches. Example sketches and JavaScript code are available in the demos directory.

Compatible Hardware
-------------------

WebUSB requires an Arduino model that gives the sketch complete control over the USB hardware. This library has been tested with the following models:

 * Arduino Leonardo
 * Arduino/Genuino Micro
 * Arduino/Genuino Zero
 * Arduino MKR1000
 * Arduino MKRZero
 * Arduino MKRFox1200
 * Adafruit Feather 32u4

Getting Started
---------------

1. Install at least version 1.8.5 of the [Arduino IDE](https://www.arduino.cc/en/Main/Software).

2. Install WebUSB/arduino environment by Board Manager of Arduino IDE<br />
  https://kimio-kosaka.github.io/webUSB-arduino/package_webUSB_index.json

3. Select WebUSB board<br />
  Tools --> Board --> 'Arduino Micro (WebUSB)' or 'Arduino Leonardo (WebUSB)'

4. Load up 'rgb' sketch<br />
  File --> Examples --> WebUSB --> rgb

5. Compile and upload it to your device.

6. When the sketch is finished uploading you should see a notification from Chrome: "Go to [https://kimio-kosaka.github.io/webUSB-arduino/index.html](https://kimio-kosaka.github.io/webUSB-arduino/index.html) to connect." Try it out!

  **Windows:** This notification is currently disabled in Chrome on Windows due to [Chromium issue 656702](https://crbug.com/656702). Implementation of new, more stable USB support for Windows is tracked on Chromium issues [422562](https://crbug.com/422562) and [637404](https://crbug.com/637404).
