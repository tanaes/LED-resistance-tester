# LED-resistance-tester
Simple PCB for dialing in current limiting resistors for LEDs

## Inspiration

This project was broadly inspired by [this blog post on Sparkfun](https://news.sparkfun.com/5461), combined of course with the unceasing voice in my head to *design another stupid PCB*. 

## Usage

I set this board up to have four LED test 'stations' each on two parallel power rails. The idea is that you can easily match your brightness on, say, 5V and 24V. There's a jumper to link the two rails, too, in case you just want to test 8 different LEDs at the same voltage. There are big, ø5mm plated holes that are just the right size for grabbing with alligator clips for powering, as well as 5mm terminal blocks. 

LED current is set with DIP switches jumping over a ~ decadal series of common resistor values, with a minimum series resistance of 220Ω and a maximum of about 41kΩ (because DIP switches are fun).

Solder jumpers in parallel to the DIP switches offer an alternative (archival) mechanism, on the theory that one might want to dial this in for a particular vendor series and then toss it in a drawer for future reference. 

There are footprints for 0603 and 0805 SMT plus THT LEDs per channel, as well as big test pads for double-checking resistance values. 

Big white silkscreen areas are present on the front and back, in principle as a place to write down what the heck you have soldered onto the board for when you come across it in that drawer a year from now. 