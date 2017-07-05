# Pepper

Simple programs you can use with Choregraphe Version 2.5.5.5 for getting started with Pepper robot. 🤖


#### How to use this repository

1. `git clone git@github.com:lillypiri/pepper.git`
2. Open Choregraphe
3. File --> Open Project --> RecognisingNAOMarks --> RecognisingNAOMarks --> RecognisingNAOMarks.pml

(Select folder names and .pml according to the program you want to open.)

This will open the project in Choregraphe for you, and it should be ready to run on your Pepper.

Make sure you are connected to your Pepper, and run the program.

Note that for some exercises, it's best if Autonomous Life (the heart icon) is turned off.


#### Recognising NAOMarks

For this exercise you will need NAOMarks 64 & 68, downloadable from the Aldebaran Documentation [here](http://doc.aldebaran.com/2-1/_downloads/NAOmark.pdf).

After you run this program in Choregraphe, hold up NAOMark 64 or 68 in front of Pepper's camera. Pepper will perform the corresponding action.


### Finite State Machine using Bumpers and LEDS

This exercise uses Pepper's feet bumpers, eye LEDs and ear LEDs. There are four states stored.

When you run the program, press Pepper's left or right bumpers. The state will change. For example, if you press Pepper's left foot bumper once, the eye LEDs will change to Pink, and the ear LEDs will stay lit up. If you press the left foot bumper again, the eye LEDs will stay pink, but the ear LEDs will turn off.
