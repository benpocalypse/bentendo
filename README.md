# Bentendo DMG
My take on an all in one carrier board for a Raspberry Pi Zero based handheld gaming system. 

## Backstory
I had designed this so that my 4 year old son would have an actual handheld retro system that could be kid friendly. However, after I had designed, layed out, and ordered all the parts, I only found enough free time to partially populate one of them. I hate to see all of my effort go to waste, so I'm putting this out there if anyone else is interested in trying to build one, or to fork my design and improve it.

The design of this board uses a cheap 3.2" screen that runs on the Pi's GPIO pins. I've actually tested this part, and it's workingn as expected. I designed the controll to use membrane pads like an actual SNES controller (or similar.) The idea was that I would just take one of those cheap SNES USB game pads, and steal the buttons/pads from them, as you can see in the picture below.

The board was designed in KiCAD, and has a BOM in it that can be directly ordered from Digikey. I've also included datasheets for all the important bits in the project as well.

Here is a 3D rendering of the board, made using FreeCAD in combination with KiCAD: 
![3D rendering of the board](https://raw.githubusercontent.com/benpocalypse/bentendo/master/bentendo/Pictures/3d_layout.png "3D rendering of the board")

And here is a picture of the actual board, with some components on it for a dry fit test:
![Acutal board!](https://raw.githubusercontent.com/benpocalypse/bentendo/master/bentendo/Pictures/pcb_fit_test.png "Acutal board!")

And finally, a WIP case design I made in TinkerCAD:
![3D Case WIP](https://raw.githubusercontent.com/benpocalypse/bentendo/master/bentendo/Pictures/case_rendering.png "3D Case WIP")

[Here is a link to the WIP case design in Tinkercad if anyone is interested in finishing it.](https://www.tinkercad.com/things/e0lRKZJP2nW-copy-of-bentendo/editv2?sharecode=PuAttOyUiWXwXqGZIPV6nHmcgTj4fWSICqTZiEBz1Hc=)

## The Future
I still plan on coming back to this, but really wanted to put it up on GitHub so that the bits don't get lost to a computer or hard drive failure. I think I'll eventually get some time this fall to build and debug the boards I have. There may be a revision in the future...who knows...


