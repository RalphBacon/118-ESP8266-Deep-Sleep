# ESP8266 Deep Sleep and Bare Bones ESP8266-12E (easy)
We covered the Arduino's Deep Sleep in videos #115 & #116 so now it's the turn of the ESP8266 to have a snooze.
 
It works differently to the Arduino ATmega328P so be prepared to implement your solutions differently with an ESP8266. It's not difficult at all but does require some thinking about how to continue where you left off.

We also explore how much current an ESP8266-12E takes when in Deep Sleep mode (spoiler alert: not much). But remember the ESP8266 is a power-hungry beast at the best of times with all that Wi-Fi connectivity.

In order to measure the current, we have to build a Bare Bones version of the ESP8266 board using a simple breakout PCB, making it very easy to mount on a breadboard.

ESP8266 (supports various modules) Vertical Breakout Board (UK Seller but generally available)
https://www.ebay.co.uk/itm/ESP8266-ESP-12-E-F-ESP-08-ESP-07-WiFi-Vertical-Breakout-Adapter-Board-UK-SELLER/400962734633

Same as above but WITH an ESP8266-12f module to solder onto it (very easy)
https://www.ebay.co.uk/itm/ESP8266-ESP-12F-WiFi-Wireless-Module-Vertical-Breakout-Adapter-Board-UK-FAST/401021445107

Behind the scenes ESP library containing (among many other useful things) the function to determine why the module woke up  
Note, these two files are part of a much larger library for the ESP8266, but linked here for reference.  
https://github.com/esp8266/Arduino/blob/master/cores/esp8266/Esp.h  
https://github.com/esp8266/Arduino/blob/master/cores/esp8266/Esp.cpp  

Everything you ever need to know about the ESP8266, published on May 14, 2017 by Ivan Grokhotkov  
https://media.readthedocs.org/pdf/arduino-esp8266/docs_to_readthedocs/arduino-esp8266.pdf  

Espressif's own short document on lower power solutions, v1.1, published 2016.  
https://www.espressif.com/sites/default/files/9b-esp8266-low_power_solutions_en_0.pdf  

Have I missed any links? Let me know in the comments section below the video!

---

If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so :)

My channel and blog are here:  
------------------------------------------------------------------  
https://www.youtube.com/RalphBacon  
https://ralphbacon.blog  
------------------------------------------------------------------  

