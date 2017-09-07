# niubi-headphones
Flexible circuit board design for adding a headphone jack to an iPhone 7

The design of this project is free for everyone. You have my full permission to make modification and improvement however you like.

Here is a picture of the board on the bottom flex cable.

I have used the internal circuit board from an official Apple headphone adapter.  The circuit connects this board to the lightning jack on the bottom flex connector.  When something is plugged into the lightning jack, the signal is switched from the headphone adapter to the lightning jack.  There is a 1 megaohm resistor that pulls the shield of the lightning connector to 3v.  This is shorted to ground when a connector is plugged into the headphone jack. This is how the switching chip senses that something was plugged in.  Whenever something is plugged or unplugged, one of the two timers fires, temporarily disabling the switching chip for 100ms (I think), which appears to be necessary for the phone to sense that something has been plugged in.

There are a couple limitations of this design:
- You cannot use the headphone jack while anything is plugged into the lightning jack.
- You need to move taptic engine and battery upward and shave the headphone jack, case, and screen to get enough room for the flex pcb, headphone adapter board, and flex pcb to fit.

## Contribute

If you decide to improve or manufacture this - I would love to hear from you.  You can contact me here: http://strangeparts.com/contact.
