# deep-sleep-api1
Deep Sleep with API controlled by HA front end version1 huzzah esp8266

Here is the fully working, unpolished version 1 of deep sleep control using api, 
controlled HA front end dashboard using huzzah esp8266.
https://github.com/terren272/deep-sleep-api1

There's a LOT of junk and notes in there, but lots of information about what can and cannot be done.
I had to teach myself SO many things along the way, including, finally, how to use discord and github.
Let me know if you have any questions. AND I have no idea how you could contact me, so, hmm.

I HIGHLY recommend using a display AND the comm port log for development.
The wifi log misses SO many things, especially at boot time, but the comm port log gets all there is to get.  
Using a display and LEDs are the ONLY ways to get offline status and feedback, 
which is critical to handling what your device does when it cannot connect.

So much can and will be removed from this early development phase version for deployment, like:
the display and all associated messages to it, and to the log, and perhaps the log itself eventually
all the unused variables and data, etc.  

The purpose of this device is to be 
a car battery monitor that wakes up every 3 hours to report the battery voltage
The maximum sleep duration for this device was measured to be 213 minutes.
Home assistant will log the ADC value when connected, and it's history can be viewed from the front end 
without having to push data anywhere, though I would like to do that with confirmation, eventually.


