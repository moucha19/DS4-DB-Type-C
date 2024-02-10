# USB-C daughterboard for DualShock 4 controller

## Features 

* Almost drop-in replacement **for JDS-040**
    + Original dimensions are maintained
    + Screw hole is in the right spot
    + However, you still need to enlarge the connector hole in the controller case
* Compatible with USB-C to USB-C cables
* Board schematic is as close as possible to the original
* All components can be purchased from [LCSC](https://www.lcsc.com/)

![JDS-040 render](img/jds-040.png)

## Bill of Materials

| Designator | Footprint                                                 | LCSC    |
|------------|-----------------------------------------------------------|---------|
| C1         | *10nF*  SMD 0402 Capacitor | [C15195](https://www.lcsc.com/product-detail/C15195.html)  |
| D2         | LED RGB Foshan FM-3510RGBA-SG           | [C727903](https://www.lcsc.com/product-detail/C727903.html) |
| F2         | *5V 500mA* SMD 0603 Fuse       | [C210356](https://www.lcsc.com/product-detail/C210356.html) |
| FL1        | TDK MCZ1210DH Common mode filter              | [C383353](https://www.lcsc.com/product-detail/C383353.html) |
| J1         | USB-C Receptacle GT-USB-7025             | [C963213](https://www.lcsc.com/product-detail/C963213.html) |
| J2         | JUSHUO AFC42-S12FMA-1H or MOLEX 5034801200 | [C466532](https://www.lcsc.com/product-detail/C466532.html) or [C587969](https://www.lcsc.com/product-detail/C587969.html) |
| R1,R2      | *5.1k*  SMD 0402 Resistor  | [C105872](https://www.lcsc.com/product-detail/C105872.html) |

## PCB Assembly

This is a very small and finicky board. Because you need to solder fine pitch connectors and components on both sides of the board, I made no optimizations for the SMT assembly. It may still be a viable option but since the part count is very low, you can manage the assembly on your own if you have a right equipment. 

Hot air gun is very handy, especially for soldering of the USB-C and FPC connectors. I tinned all of the pads first and then simply positioned the connectors under the hot air. Rest of the components is manageable with a reasonably fine soldering iron.

