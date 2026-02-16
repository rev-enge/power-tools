# Description

The Fein KBU35QW is a Universal magnetic core drill machine able to drill up to 35 mm holes.

The electronics consist of 3 boards:

* One in de body next to the drilling head.
* One in the head of the machine the the top.
* One in the side of the machine to control the motor (speed).

# Important safety note

The electronics are supplied directly from the life mains power with no insulation whatsoever!
So be very careful when doing any repairs on it and always pull the main plug before opening it.

When measuring on individual boards always use an insulation transformer so its not attached to the mains.

# Identification of the boards

These can be found on various exploded views on the internet and the associated Fein partnumber:

* Main controller board (large board): exploded view #990: 30762641980
* Top speed control board (small board): exploded view #210: 30762560990
* Motor regulation board: exploded view #160: 30762562990

# Description

The small board handles the buttons to set the motor speed and activating the magnet.
Two cables run of this board, a flex foil for the motor drive logic and a 3 wire cable to to
 larger powersupply magnet/board.

The large board is the input for the power, does the EMC filtering and controls the magnet,
 checks if the magnet is holding to a iron beam or whatever.
It also supplied the power to the motor via 2 faston connections.

# Utilities used to create the drawings

The schematic diagram snippets are made with KiCad 6.0.11
