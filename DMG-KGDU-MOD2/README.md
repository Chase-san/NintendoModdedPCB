# DMG-KGDU-MOD2

This is an F-RAM and battery holder upgrade to the DMG-KGDU-10.

## Components

This board features a 32-pin ROM and a 28-pin RAM module.

| Ref   | Package     | Description  | Notes | 
| :---: | :---------: | :----------- | :---- |
| U1    | TSOP-II-44W | Program ROM  | ~10.1mm wide |
| U2    | LQFP-32     | MBC-3        | |
| U3    | SOIC-28W    | F-RAM        | ~8.3mm wide |
| U4    | SOIC-8      | System Reset | ~4.3mm wide |
| U5    | SOT-23-5    | Clock Sync   | OR Gate |
| C1,C2 | 0603 (in)   | 15pF Capacitor | |
| C3,C4,C6 | 0603 (in) | 15nF-0.1uF Capacitor | |
| C5    | 0603 (in)   | 33pF Capacitor | May be left empty. |
| R1    | 0603 (in)   | 1kOhm Resistor | |
| R2    | 0603 (in)   | 330kOhm Resistor | |
| X1    | 6mm x 2mm   | 32.768 kHZ Cystal | 12.5 pF Load and 35 kOhm ESR |
| Batt  | CR2025      | Battery Holder | |

It is highly recommended to use the following parts.

| Ref  | Manufacturer | Component |
| :--: | :----------: | :-------: |
| U3   | Infineon     | FM18W08   |
| U5   | Texas Instruments | SN74LVC1G32DBVR |
| Batt | MPD          | BK-6219   |

## Images
![Front](https://github.com/Chase-san/NintendoModdedPCB/blob/main/DMG-KGDU-MOD2/images/front.png)
![Rear](https://github.com/Chase-san/NintendoModdedPCB/blob/main/DMG-KGDU-MOD2/images/back.png)

