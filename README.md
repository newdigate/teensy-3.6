# Teensy 3.6 audio display projects

I'd like to explore whats possible with a teensy 3.6, the sgtl5000 audioboard, and an ILI9341 tft display board;
* https://www.pjrc.com/teensy/index.html
* https://www.pjrc.com/store/teensy3_audio.html
* https://www.pjrc.com/store/display_ili9341.html

I have a little bit of electrical engineering knowledge but I don't have alot of practical experience. I am a software engineer by trade and Im interested in audio applications of the teensy devices; 

I've wired the three components together using breadboard and jumper wires. Although it does work intermittently, the digital i2s audio connection is very fragile and mostly results in heavy digital distorion. I've tried to rule out all the obvious potential faults - swapped teensy mainboards, swapped audioboards, swapped different versions of teensy devices... the problem seems to be with my breadboard, or the jumper wires. I need to check it out with a decent oscilliscope. So I've decided to build a custom PCB. I think this should solve my distortion issue.    

[some things I learned about Fritzing](https://github.com/newdigate/teensy-3.6/tree/master/fritzing)

### About Teensy:
Teensy is an awesome microcontroller development kit from pjrc.com http://www.pjrc.com/teensy/index.html
