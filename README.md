Check out my blog post about this project: https://webbreacher.wordpress.com/2015/08/30/building-the-led-matrix/

# thematrix
Python code to interface with an LED matrix

# Gear
- I got 2 of these - 64x32 RGB LED matrix - http://www.adafruit.com/product/2278
- One of these - 5v, 10A power supply - http://www.adafruit.com/product/658
- One of these - Adafruit RGB Matrix HAT + RTC for Raspberry Pi - Mini Kit -  http://www.adafruit.com/product/2345
- And a Real Time Clock battery for the HAT. 
- I'm using a Raspi2 as the base OS.

# Code
The code (thematrix.py) contains functions to allow you to scroll (up/down or left-2-right/right-2-left) text on a display. Since I put two LED matrices chained together, my code is for a 128x32 total display. You may have to alter if you have a bigger or smaller LED matrix.

I commented the code for ease of use/hacking (since my Python skills are rusty at best). I also left in there some code for displaying images (PPM format) on the display instead of text.

# In Action
If you want to see it in action/running, check out my YouTube video at https://www.youtube.com/watch?v=ve_ZMlnGpg4
