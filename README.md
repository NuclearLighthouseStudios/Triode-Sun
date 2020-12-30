# Triode Sun Tube Preamp

These are the KiCAD schematics and board layout filed for my Triode Sun Tube Preamp pedal.  
If you just want the Gerber files or a PDF of the schematic check out the releases tab for downloads.

This PCB should be easily manufacturable with most online PCB houses by just uploading the gerber files.

This board is designed to be used with my Switchboard Pedal IO PCB which you can find [here](https://github.com/NuclearLighthouseStudios/Switchboard).

## BOM

| Reference       | Quantity | Value  | Description                                          |
| :-------------- | -------: | -----: | :--------------------------------------------------- |
| C2 C4           | 2        | 470n   | WIMA MKS2 63V                                        |
| C1 C3 C5        | 3        | 100n   | WIMA MKS2 63V                                        |
| C6              | 1        | 1µ     | WIMA MKS2 63V                                        |
| J1              | 1        |        | Pin Header, 6 pins, 2.54mm spacing                   |
| J2              | 1        |        | DC Barrel Jack with internal switch                  |
| Q1 Q2           | 2        | BC547B | 0.1A Ic, 45V Vce, Small Signal NPN Transistor, TO-92 |
| R1 R2 R5 R9 R10 | 5        | 1M     | Metal film resistor 1%, DIN 0207                     |
| R3 R11          | 2        | 10k    | Metal film resistor 1%, DIN 0207                     |
| R4 R12          | 2        | 39k    | Metal film resistor 1%, DIN 0207                     |
| R6 R7           | 2        | 390K   | Metal film resistor 1%, DIN 0207                     |
| R8              | 1        | 100K   | Metal film resistor 1%, DIN 0207                     |
| RV1 RV2         | 2        | 100k   | Alps RK09K1130C94 Potentiometer                      |
| U1              | 1        | ECC82  | ECC82 / 17AU7 in noval print socket                  |
