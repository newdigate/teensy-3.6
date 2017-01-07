####Teensy 3.6 audio display projects

I'd like to explore whats posible with a teensy 3.6, the sgtl5000 audioboard, and an ILI9341 tft display board;
* https://www.pjrc.com/teensy/index.html
* https://www.pjrc.com/store/teensy3_audio.html
* https://www.pjrc.com/store/display_ili9341.html

I have a little bit of electrical engineering knowledge but I don't have alot of practical experience. I am a software engineer by trade and Im interested in audio applications of the teensy devices; 

I've wired the three components together using breadboard and jumper wires. Although it does work intermittently, the digital i2s audio connection is very fragile and mostly results in heavy digital distorion. I've tried to rule out all the obvious potential faults - swapped teensy mainboards, swapped audioboards, swapped different versions of teensy devices... the problem seems to be with my breadboard, or the jumper wires. I need to check it out with a decent oscilliscope. So I've decided to build a custom PCB. I think this should solve my distorion issue.    

Fritzing seems to be my easiest option to build a pcb. Maybe later I will check out oshpark.com

My first step is to build svg files for breadboard view, schematic view and pcb view for fritzing. This is my first pcb project.

![teensy breadboard schematic for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_breadboard.png?raw=true "teensy 3.6 breadboard schematic for fritzing")

![teensy schematic for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_schematic.png?raw=true "teensy 3.6 schematic for fritzing")

![teensy pcb for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_pcb.png?raw=true "teensy 3.6 schematic for fritzing")

### About Teensy:
Teensy is an awesome microcontroller development kit from pjrc.com http://www.pjrc.com/teensy/index.html
