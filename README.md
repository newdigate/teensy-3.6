####Teensy 3.6 audio display projects

I'd like to explore whats possible with a teensy 3.6, the sgtl5000 audioboard, and an ILI9341 tft display board;
* https://www.pjrc.com/teensy/index.html
* https://www.pjrc.com/store/teensy3_audio.html
* https://www.pjrc.com/store/display_ili9341.html

I have a little bit of electrical engineering knowledge but I don't have alot of practical experience. I am a software engineer by trade and Im interested in audio applications of the teensy devices; 

I've wired the three components together using breadboard and jumper wires. Although it does work intermittently, the digital i2s audio connection is very fragile and mostly results in heavy digital distorion. I've tried to rule out all the obvious potential faults - swapped teensy mainboards, swapped audioboards, swapped different versions of teensy devices... the problem seems to be with my breadboard, or the jumper wires. I need to check it out with a decent oscilliscope. So I've decided to build a custom PCB. I think this should solve my distorion issue.    

###### Fritzing
A few months ago I started noticing some really nice diagrams (mostly arduino) flavor while searching for pull-up resistor solutions for arduino. I was curious about how people were creating these nice breadboard diagrams (I love a diagram). I discovered Fritzing this way. 

When I started this project a week or two ago, I thought it would be good to use Fritzing to build the PCB, since the custom parts for previous teensy models already exist in fritzing. My first step was to build svg files for breadboard view, schematic view and pcb view for fritzing. This was my first pcb project, ever. 

Now that I've made a couple of iterations of my custom teensy 3.6 part in fritzing, I've learned a few things. 
  * Fritzing makes really nice visual diagrams of breadboards.
  * It has a decent collection of components.
  * It is a great platform for teachers, students and enthusiasts. 
  * Making a custom parts for the first time is pretty tough. But all the information is out there.  
  * It crashes. Work must be saved frequently;    
  * The documentation on making custom parts is a little out dated.
  * Autorouting is not usable (schematic, or pcb).
  * There seems to be no way of making nets. (except for ground and vcc?)
  * It is not practical to build a PCB in fritzing. Unfortunately. 
  
Having learnt these things I am glad there is a teensy 3.6 component for fritzing.

I have also decided to go forward using Eagle to create PCBs and Fritzing to create sweet breadboard diagrams. 

![teensy breadboard schematic for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_breadboard.png?raw=true "teensy 3.6 breadboard schematic for fritzing")

![teensy schematic for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_schematic.png?raw=true "teensy 3.6 schematic for fritzing")

![teensy pcb for fritzing](https://github.com/newdigate/teensy-3.6/blob/master/fritzing/png/teensy3-6_default_fritzing_pcb.png?raw=true "teensy 3.6 schematic for fritzing")

### About Teensy:
Teensy is an awesome microcontroller development kit from pjrc.com http://www.pjrc.com/teensy/index.html
