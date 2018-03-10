# Let it glow
*Repo name is either a tribute to [Indiana Jones](https://youtu.be/PAfZ7V2VyD8?t=106) or [Frozen](https://www.youtube.com/watch?v=moSFlvxnbgk&feature=youtu.be&t=60) - you decide.*

## Intro to an Arduino project (using Elegoo Super Starter Kit)
[![Waffle.io - Columns and their card count](https://badge.waffle.io/marydavis/let-it-glow.svg?columns=all)](https://waffle.io/marydavis/let-it-glow)

### Setup
  1. [Download IDE](https://www.elegoo.com/download/)
  
  1. [Download Elegoo Super Starter Kit Tutorial](https://www.elegoo.com/tutorial/Elegoo%20Super%20Starter%20Kit%20for%20UNO%20V1.0.2017.10.31.zip)
  1. Install the IDE

### Let's make sure it works
  1. Take the Elegoo Uno R3 board out of bottom left section. *(I keep my antistatic bag for storage)*
  1. Take the blue USB cable out of the top section.
  1. Plug your board into your computer using the cable.
  1. Your board should have a solid green and a solid orange light on it.
  1. Open the Arduiono IDE.
  1. Confirm board setup, click `Tools` in the top toolbar which should include the below:
      * `Board: Arduino/Genuino Uno` - if not, select it from the list.
      * `Port: Arduino/Genuino Uno` - don't worry if it has other information too, just make sure it has the board in it.
 
  1. Next, click `File` in the top toolbar.
  1. Open the Blink example by going to `Examples -> 01.Basics -> Blink`.
  1. Click the ➡️(right arrow) for Upload, it is next to the check mark above the "Blink" tab name.
  1. You should see it sending information in the console at the bottom of the screen and several lights flashing on your board.
  1. Now you should see the orange light on your board flashing every 1 second. 
  
  **If so, you are ready for the project!**

## The Project Begins
*(this project starts from a tutorial for easier setup)*

### Parts List 
*(everything except the board can be found in the top compartment of the kit)*

  1. **Arduino board** - Elegoo Uno R3
  1. **USB cable** - for connecting board to computer
  1. **Breadboard** - great way to try things out, not permanent, no soldering
  1. **1 RGB LED** - clear LED with 4 metal prongs (legs)
  1. **4 M-M wires (male to male)** - one for each leg of LED
  1. **3 x 220ohm resistors** - prevents too much power going to LED, which would burn out without them *(the stripes are important, they are used to show the value of ohms. Here is a neat [color code calculator](https://www.allaboutcircuits.com/tools/resistor-color-code-calculator/).
 
  #### Images of Parts
  All Packaged Parts:

  ![Packaged Parts](images/rgb-packaged-parts.jpg "Packaged Parts")
  
  Unpackaged New Parts:

  ![New Parts](images/rgb-new-parts.jpg "New Parts")

### Instructions
  1. Let's start plugging things into the breadboard.
    * **Make sure to unplug your Arduino, we don't want any power going to it while we are plugging things in.**

  1. Diagram and pictures are included below to be used along with instructions.
  1. First plug in the RGB LED - each leg in a different hole in the breadboard in a column, ex. column "b"
      * The longest leg is the GROUND
      * The legs are as following: RED, GROUND, GREEN, BLUE
  1. Next are resistors, one for each color (skipping the ground) 
      * Resitors will cross the channel (the cut out between column "e" and "f").
      * Power does not cross the channel, this allows us to plug in the power on one side of the channel and the LED on the other side making the resistor connect the two.
      * Plug one metal end into the same row as the leg on one side of the channel and then in the same row on the other side of the channel.
  1. Now for the wires
      * I used wires that matched the color lights, but any color will do.
      * Use 1 wire for each leg.
      * All wires except for the ground will be on the otherside of the channel away from the LED.
  1. Plug the ground wire into the Arduino black hole labelled `GND`, then into the hole in the breadboard that doesn't have a resistor near the LED.
  1. The red wire is plugged into the Arduino board `-6` then into the row of the red leg. *(remember this is power and must be across the channel away from the LED)
      * The numbers of where they are plugged in are used in the code so make sure they are right.
  1. The green wire is plugged into the Arduino board `-5` then into the row of the red leg. 
  1. The blue wire is plugged into the Arduino board `-3` then into the row of the red leg.
  
  **MAKE SURE NONE OF THE RESISTORS ARE TOUCHING EACH OTHER**

  #### Diagram and Pictures
  Elegoo Diagram:

  ![Diagram](images/rgb-elegoo-diagram.png "Diagram")

  Elegoo picture:

  ![Elegoo picture](images/rgb-elegoo-picture.png "Elegoo picture")

  Wire Overview:

  ![Wire Overview](images/rgb-wired-overview.jpg "Wire Overview")

  Wire Closeup:

  ![Wire Closeup](images/rgb-wired-closeup.jpg "Wire Closeup")


  #### Run the Code

  1. Open Elegoo Super Starter Kit Tutorial Folder *(downloaded in setup)*
      *  *For more detailed information and schematics, checkout the tutorial by opening the Elegoo Super Starter Kit Tutorial pdf and going to Lesson 4 (pg 47)*
 
  1. Open Code folder -> Lesson 4 folder -> Open `.ino` file in IDE
  1. As you can see, the code is simplified C++ and commented throughout explaining each section.
  1. Plug your Arduino into your computer.
  1. Click the upload button (right arrow) and off it goes!
  1. Your light should now be changing colors!


 #### Next Steps
  1. Edit the code and "save as" your own file.
  1. Click the "checkmark" to make sure it compiles.
  1. Click the "right-arrow" to upload.
  1. See your changes go live!

### Ready for More (some ideas)
  1. Add button to turn on/off
  1. Add the 9V battery - allowing it to be removed from computer!
  1. Add a lamp shade for a pretty light
  1. Add the humidity/thermometer and make code to change the lights depending on levels.
  1. Could make permanent by moving to a circuit board and solder

## Awesome Places for Fun Projects

[Hackster.io](https://www.hackster.io/)

[Arduino Project Hub](https://create.arduino.cc/projecthub)






