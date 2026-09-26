# eykPad_nano
A small electronic pad used for timer and other cool stuff!
<br><br><br>

3D pcb image:


<img width="700" height="500" alt="Screenshot 2026-09-25 at 8 32 41 PM" src="https://github.com/user-attachments/assets/05148b7b-2c4c-46f1-a0b2-d818f2af1fe0" />




<br><br>
2D pcb image:


<img width="700" height="500" alt="Screenshot 2026-09-25 at 8 33 00 PM" src="https://github.com/user-attachments/assets/e3d79a3a-f278-4842-a478-dec48a0d70ca" />

<br><br>
eykNano is a multifunctional pad. It has a RaspberryPi Pico microcontroller, and is minimalistic and compact. (67x62mm)
The microcontroller is a RaspberryPi Pico, so it has a built in Micro-USB Type-B port.



<br><br>
Schematic image:


<img width="700" height="500" alt="Screenshot 2026-09-26 at 9 09 59 AM" src="https://github.com/user-attachments/assets/888601f3-bc9b-4418-bfe7-8d4b100cf0e2" />

The schematic is pretty simple. In the project, I added <b>nine</b> led lights, each with different color, <b>three</b> 
buttons (settings, next light, ok), and a 7 segment display (one digit, can allow useful features or games.

I will start with these basic three functions for this: 

-<b>A binary timer</b>. the lights represent minutes/seconds. The first light is 30 seconds, the second light is 1 minute, the third light is 2 minutes, and it doubles every light. That means you can set a timer for any multiple of 30 seconds up to 4 hours, 15 minutes and 30 seconds. When the timer is almost up (less than 10 seconds) the 7 segment LED display will count down. and once the timer ends, the LEDS flash on and off.

-<b>A memory game.</b> The nine lights will play a sequence, and you use the buttons to recreate the sequence. Like a normal memory game, it will become longer and harder over time, building up on the last sequence.

-<b>A reaction time test.</b> All the LEDS will flash on for a few seconds (randomized) and they will all turn off at the same time. The player has to press the (OK) button. Then, the lights will represent (in binary, milliseconds) how much time it took for you to press the button. (I might deduct a few milliseconds if there is a delay on pressing the button and the lights turning off)

Of course, that's not the only functions I will put for this project. I will add more cool features eventually.

<br><br>
BOM:

<img width="1842" height="563" alt="Screenshot 2026-09-26 at 10 34 38 AM" src="https://github.com/user-attachments/assets/bf3d5e7e-0f93-442c-ada5-edbe1c602c1c" />


