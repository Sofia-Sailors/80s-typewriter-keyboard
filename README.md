# 80s-typewriter-keyboard
custom raspberry pi pico-based keyboard to fit into a vintage Smith Corona digital typewriter

# The Idea
The initial idea came as an inspiration from the Cyberdeck community and a free typewriter I got at an antiques show. This is just the keyboard part of the whole project.
 "Image "
 
Originally, I planned on repurposing the keyboard that it came with, but that proved to be too challenging, as it would require reverse engineering the strange pcb and creating a new connector, and it would just be easier to design and make a brand-new keyboard pcb for the project.
"OG PCB"   "New PCB Render"

# The Planning
I started by first figuring out the layout, using the online Keyboard Layout Editor (KLE) and using the origional keyboard as a reference. https://www.youtube.com/watch?v=7O8xGd7Pd88&t=2046s
Then, I researched how to design a PCB. Using KiCad and some videos (https://www.youtube.com/watch?v=7O8xGd7Pd88&t=2046s) I was able to grasp the basic concept of what I needed to do.

# The Design(ing)
Using the KLE design paired with the video, I got to work. I used the marbastlib keyboard library for KiCad along with the keebio(?) library. The video does a good job at explaining the basics of what I need to do, but I wanted a different controller. I ended up turning back to the internet for ideas, namely in regards to Raspberry Pi Pico-powered keyboards. I ended up using zli117's Pico-Keyboard (https://github.com/zli117/Pico-Keyboard) as my base for wiring up the cnnections to the Pico. 
# Assembly + Programming
I used JLC to manufacture the board and ordered parts from Adafruit and Digikey. I used kli117's PicoMK firmware (https://github.com/zli117/PicoMK) to programm the board.
# Parts + Price
* Cherry MX Black Hyperglide ~ 70 --$26.60
* Kailh switch sockets ~ 4 packs of 20 -- $19.80
* 1N4148 diodes ~ cheaper to buy 100, used ~~ 70 -- $4.47
* Raspberry Pi Pico ~ 1 w/header pins -- $500
