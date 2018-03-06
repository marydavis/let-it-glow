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
