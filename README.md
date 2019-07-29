# scrumpel7
Build your own Scrumpel7 ZX180 computer.
It contains 512 KB SRAM, 32 KB bank-switchable in two banks of 16 KB ROM (ROM can be disabled to have full RAM), 2 serial ports with fixed baudrate of 9600 Baud, 3 software SPI ports and 3 I/O ports (82C55).
The scrumpel6 IDE-card can also be used on this board which enables running CP/M.

NOTES:

1. On the silkscreen 74HCT573AN is printed, this must be 74HCT574AN.
2. The square solder joints on the leds must be connected to the Kathode (Short pin of LED).
3. The SPI connections are made for microSD module and the RTC DS3234 module.
