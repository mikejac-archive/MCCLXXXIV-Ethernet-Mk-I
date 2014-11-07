MCCLXXXIV Ethernet Mk I
=========
If I could, I think I would call this board "Arduino Ethernet+". But the name "Arduino" is protected, so no go for that. MCCLXXXIV is roman numbers for "1284".

Features
- Atmel atmega1284p (128KB Flash, 32kB RAM, clockspeed is 20MHz).
- Wiznet W5200 Ethernet Controller (10/100Mbps). Interrupt from W5200 to atmega1284p is jumper selectable.
- RS485 Driver. Can be connected/disconnected from the UART pins of the atmega1284 by jumpers.
- RJ45 Ethernet Jack is Power-over-Ethernet (PoE) ready. The V+ and V- from the jack goes to a terminal block on the board.
- Onboard powersupply accepts up to 18VDC as input and can deliver 1.5A at 5VDC.
- All I/Os from the atmega1284p are available on screw-terminals. The atmega1284p has 8bit more I/Os compared to the atmega328p.
- The board has headers that are compatible with regular Arduino shields.
- Board is 100mm by 80mm. There are M4 holes at each corner as well as a M4 hole in the middle.

Note: This board has _no_ USB on it and has to be programmed via the ICSP header with an appropiate programmer.
