# Sound-Reactive-LED-Tutorial-
Code Art Miami Workshop

Light up your jewelry with sound!
This guide will help you upgrade your bracelet or neckace to have sound reactive LEDs. 
This build uses a mic amp sensor and Gemma to light up NeoPixels to music. 

Features:
- Sound reactive
- On/Off switch
- Programmable

Before you begin: 
- https://learn.adafruit.com/adafruit-guide-excellent-soldering
- https://learn.adafruit.com/introducing-gemma
- https://www.youtube.com/watch?v=U_Q3djsktQs 

I have also made an Adafruit wishlist with all materials: 
- https://www.adafruit.com/wishlists?wid=419330 

Assembly:

The circuit is not complicated at all! Follow the diagram below. 

Circuit Summary:
- Arduino Gemma D0 -> NeoPixels IN
- Arduino Gemma D2 -> Mic OUT
- Arduino Gemma GND -> NeoPixels GND
- Arduino Gemma 3V -> Mic VCC
- Arduino Gemma Vout -> NeoPixels PWR
- NeoPixel ring GND-> Mic GND
- Battery negative GND-> Black wire on JST cable
- Battery positive BAT-> Switch corner pin
- Switch middle pin-> Red wire on JST cable

At this point, the soldering is complete. Lets program the Arduino before final assembly. You will need the Adafruit NeoPixel library for the sketch: https://github.com/adafruit/Adafruit_NeoPixel 

Grab the Arduino sketch and load it onto the Gemma. Putting the Gemma into the bootloader mode is documented here: https://learn.adafruit.com/introducing-gemma/setting-up-with-arduino-ide 

Note: If you do not see a red pulsing light when you plug your Gemma in, it is because you do not have the correct USB port. Gemma is only compatible with USB 2.0 (most new computers have USB 3.0). You will need to buy an adaptor to get this to work. 

Next: 
Upload the code and test to see if everything is working properly. Here is an example: https://drive.google.com/open?id=157zQu41bRiIV3DR1RgWY7Z18QgspMqXXHg 

Now you are ready to get creative!

Next, enclose it with felt, ribbon, etc, and embellish with flowers, rhinestones, etc. 

Congradulations! you now have a new fun piece of jewelry! 


