# thematrix
Python code to interface with an LED matrix

# Gear
- I got 2 of these - 64x32 RGB LED matrix - http://www.adafruit.com/product/2278
- One of these - 5v, 10A power supply - http://www.adafruit.com/product/658
- One of these - Adafruit RGB Matrix HAT + RTC for Raspberry Pi - Mini Kit -  http://www.adafruit.com/product/2345
- And a Real Time Clock battery for the HAT. 
- I'm using a Raspi2 as the base OS.

# Goal
I was trying to make a customizable output for a Raspi2 to interface with a multicolor display. I wanted to send/create custom text in Python and send to the device. The matrix would be hung on the wall and show the data I send it.

# Code
The code (thematrix.py) contains functions to allow you to scroll (up/down or left-2-right/right-2-left) text on a display. Since I put two LED matrices chained together, my code is for a 128x32 total display. You may have to alter if you have a bigger or smaller LED matrix.

I commented the code for ease of use/hacking (since my Python skills are rusty at best). I also left in there some code for displaying images (PPM format) on the display instead of text.
