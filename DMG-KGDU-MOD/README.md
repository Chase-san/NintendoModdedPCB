# DMG-KGDU-10

This board is used by the USA versions of Pokemon Gold, Silver, and Crystal.

The original featured cut holes that were used for debugging purposes, these have been omitted.

It features a 44-pin ROM and a 28-pin RAM module.

| Ref   | Package     | Description | Notes | 
| :---: | :---------: | :---------- | :---- |
| U1    | TSOP-II-44W | Program ROM | Wide |
| U2    | LQFP-32     | MBC3 | |
| U3    | SOIC-28EW   | SRAM | Extra Wide |
| U4    | SOIC-28     | System Reset | |
| C1,C2 | 0603 (in)   | 15pF Capacitor | |
| C3, C4, C5, C6 | 0603 (in) | 0.1pF Capacitor | |
| R1    | 0603 (in)   | 1kOhm Resistor | |
| R2    | 0603 (in)   | 330kOhm Resistor | |
| X1    | 6x2 mm      | 32.768 kHZ Cystal | 12.5 pF Load and 35 kOhm ESR |

This particular board was based on the outlines taken from HDR boards, however all routes and footprints have been changed to more directly reflect the original board.

## Images
![Front](https://github.com/Chase-san/NintendoPCB/blob/main/DMG-KGDU/images/front.png)
![Rear](https://github.com/Chase-san/NintendoPCB/blob/main/DMG-KGDU/images/back.png)

