## Adafruit I2S MEMS Microphone Breakout - ICS-43434 PCB

<a href="http://www.adafruit.com/products/6049"><img src="assets/6049.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit I2S MEMS Microphone Breakout - ICS-43434. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6049

### Description

Listen to this good news - we now have a breakout board for a super tiny ICS43434 I2S MEMS microphone. Just like 'classic' electret microphones, MEMS mics can detect sound and convert it to voltage, but they're way smaller and thinner. This microphone doesn't even have analog out, it's purely digital. The I2S is a small, low-cost MEMS mic with a range of about 50Hz - 15KHz, good for all general audio recording/detection. The chip has a built in low-pass filter that cuts frequencies above 24KHz.

For many microcontrollers, adding audio input is easy with one of our analog microphone breakouts. But as you get to bigger and better microcontrollers and microcomputers, you'll find that you don't always have an analog input, or maybe you want to avoid the noise that can seep in with an analog mic system. Once you get past 8-bit micros, you will often find an I2S peripheral that can take digital audio data in! That's where this  I2S Microphone Breakout featuring the TDK ICS43434 comes in.

Instead of an analog output, there are three digital pins: Clock, Data, and Left-Right (Word Select) Clock. When connected to your microcontroller/computer, the 'I2S Controller' will drive the clock and word-select pins at a high frequency and read out the data from the microphone. No analog conversion required!

The microphone is a single mono element. You can select whether you want it on the Left or Right channel by connecting the Select pin to power or ground. If you need stereo, pick up two microphones! You can set them up to be stereo by sharing the Clock, WS, and Data lines but having one with Select to ground, and one with Select to high voltage. No firmware or driver configuration is required, you'll get 24-bit output instantly.

This I2S MEMS microphone is bottom ported, so make sure you have the hole in the bottom facing out towards the sounds you want to read. It's a 1.6-3.6V max device only, so it is not for use with 5V logic (it's really unlikely you'd have a 5V-logic device with I2S anyway). Many beginner microcontroller boards don't have I2S, so ensure it's a supported interface before you try to wire it up! This microphone is best used with Cortex M-series chips like the SAMD21 or SAMD51, ESP32, RP2040 or RP2350, or single-board computers like the Raspberry Pi.

[For code, libraries, wiring examples, CAD files, Fritzing, and more, check out the guide!](https://learn.adafruit.com/adafruit-i2s-mems-microphone-breakout/)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
