# swancolorHD Lite main pcb

## About
This board is a customized version of the swancolorHD main board developed by [zwenergy](https://github.com/zwenergy).  

The changes are as follows:  
- Adding a main power switch  
- Change to USB Type-C power supply   
- Remove controller parts  
- Changed connection with WonderSwan color pcb to [FPC](../FPC/) + [Connector PCB](../Connector/)  

### PCB BOM
| **Reference** | **Part** | **Link** |
|---------|------|------|
|FPC1| FFC connector with 24 pins, 1.0mm pitch, bottom contacts | [LCSC](https://www.lcsc.com/product-detail/C3446114.html)|
|U1  | Tang Nano 9k | [AliExpress](https://aliexpress.com/item/1005004275570427.html)|
|U2  | TPS62221DDCT | [LCSC](https://www.lcsc.com/product-detail/C2073237.html)|
|C1  | 4.7 uF capacitor (1206) | - |
|C2  | 22 uF capacitor (1206) | - |
|L1  | 4.7uH Inductors (1206) | - |
|CN1 | B2B-PH-K-S | - |
|CN2 | B4B-PH-K-S(LF)(SN) | - |
|SW1, SW2 | SK12D07VG6 | - |
|R3  | 220 Ω resistor (1206) | - |
|R4  | 220 kΩ resistor (1206) | - |

* Implement either R3 or R4.  
* Implement either U2,C1,C2,L1 or [ASM1117 1.5V DC-DC Converter Module](https://ja.aliexpress.com/item/1005006043683365.html) (Please pay attention to the orientation of the power supply).  

### Other Parts  
| **Part** | **Link** |
|----------|----------|
| 24pin 1.0mm pitch Forward Direction(Type-B) FFC 1000mm | [AliExpress](https://aliexpress.com/item/1005006889063970.html)|
| USB Type-C power supply connector female | [AliExpress](https://aliexpress.com/item/1005006297697300.html)|
| self-locking switch 3-6V 8mm dia with LED | [AliExpress](https://aliexpress.com/item/1005005628118782.html)|
| header socket 1x24  (2 pcs)| - |

* Please change the FFC to your preferred length.