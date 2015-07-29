# About
[![OSHPark PCB Top Thumbnail](artwork/thumb_top.png?raw=true)](artwork/top.png?raw=true)
[![OSHPark PCB Bottom Thumbnail](artwork/thumb_bottom.png?raw=true)](artwork/bottom.png?raw=true)

Custom Raspberry Pi Add-on board used for launching the [Galactic Aztec] rocket to interface with the [Galactic Aztec Igniter Connector]. The board was designed to be stackable with other add-on boards via the designated [pin configuration].

Custom EagleCAD parts on this board can be found in the [SDSU Rocket Eagle Libraries].

## Wiring
The igniter and break wires that ran from the add-on board to the rocket's igniter were [CAT6 cables] that ran thru [RJ45 couplers] and followed the following [T-568B] wiring configurations:

### Igniter
| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | Supply Voltage |
| 2   | Orange       | Ground         |
| 3   | Green/White  | Supply Voltage |
| 4   | Blue         | Ground         |
| 5   | Blue/White   | Supply Voltage |
| 6   | Green        | Ground         |
| 7   | Brown/White  | Supply Voltage |
| 8   | Brown        | Ground         |

### Break Wire
| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | 3.3V           |
| 2   | Orange       | Signal         |
| 3   | Green/White  | 3.3V           |
| 4   | Blue         | Signal         |
| 5   | Blue/White   | 3.3V           |
| 6   | Green        | Signal         |
| 7   | Brown/White  | 3.3V           |
| 8   | Brown        | Signal         |

# Bill of Materials
| Qty | Description                          | Part Number         | Vendor   |
|:---:|--------------------------------------|--------------------:|----------|
| 1   | Header Stacking 2x20 Tall 23mm       | [1979]              | Adafruit |
| 2   | Diode 50V 1A PTH                     | [1N4001FSCT-ND]     | DigiKey  |
| 2   | Transistor NPN 40V 0.6A TO-92 PTH    | [2N5551TAFSTB-ND]   | DigiKey  |
| 3   | Jack RJ45 CAT5/CAT5e                 | [380-1046-ND]       | DigiKey  |
| 1   | LED Red Vf=1.8V If=2mA 0603          | [475-1195-2-ND]     | DigiKey  |
| 1   | Molex Mini Fit Jr. 4-pos Right Angle | [WM1352-ND]         | DigiKey  |
| 1   | LED Red Vf=2V If=20mA 0603           | [754-1359-1-ND]     | DigiKey  |
| 1   | Resistor 1.8kΩ 1/4W 1% 0603          | [P1.8KBYCT-ND]      | DigiKey  |
| 1   | Resistor 1.2kΩ 2W 1% 2512            | [A116034CT-ND]      | DigiKey  |
| 2   | Resistor 1k 1/4W 1% PTH              | [RNF14FTD1K00CT-ND] | DigiKey  |
| 1   | Header Female 1x6 0.1" Pitch         | [S7039-ND]          | DigiKey  |
| 2   | Relay 5V 5A SPST-NO (1 Form A)       | [Z945-ND]           | DigiKey  |


[Galactic Aztec]: http://rocket.sdsu.edu/rockets
[Galactic Aztec Igniter Connector]: https://github.com/twyatt/galactic-aztec-igniter-connector
[pin configuration]: https://docs.google.com/spreadsheets/d/1zGslKhH-ZteeA8sbbTjQlF-Neb-wJ3quIlFH6I8Cvgs/edit?usp=sharing
[CAT6 cables]: http://amzn.com/B00DUYDFVY
[RJ45 connector pin configuration]: https://docs.google.com/spreadsheets/d/1SQShVjZaio6u5dARqMazgQztgd2wGieyxO2AVLGVz4Q/edit?usp=sharing
[RJ45 couplers]: http://amzn.com/B00GE1DHRC
[SDSU Rocket Eagle Libraries]: https://github.com/twyatt/SDSURocket-Eagle-Libraries
[T-568B]: https://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
[1979]: http://www.adafruit.com/products/1979
[1N4001FSCT-ND]: http://www.digikey.com/product-detail/en/1N4001/1N4001FSCT-ND/1532742
[2N5551TAFSTB-ND]: http://www.digikey.com/product-detail/en/2N5551TA/2N5551TAFSTB-ND/973959
[380-1046-ND]: http://www.digikey.com/product-detail/en/SS-7188-NF/380-1046-ND/388308
[475-1195-2-ND]: http://www.digikey.com/product-detail/en/LS%20L29K-H1J2-1-Z/475-1195-1-ND/810356
[WM1352-ND]: http://www.digikey.com/product-search/en?x=0&y=0&lang=en&site=us&keywords=538-39-30-1040
[754-1359-1-ND]: http://www.digikey.com/product-detail/en/APG1608SURKC%2FT/754-1359-1-ND/1919171
[P1.8KBYCT-ND]: http://www.digikey.com/product-detail/en/ERJ-PA3F1801V/P1.8KBYCT-ND/5036145
[A116034CT-ND]: http://www.digikey.com/product-detail/en/5-2176070-1/A116034CT-ND/4280086
[RNF14FTD1K00CT-ND]: http://www.digikey.com/product-detail/en/RNF14FTD1K00/RNF14FTD1K00CT-ND/1975018
[S7039-ND]: http://www.digikey.com/product-detail/en/PPPC061LFBN-RC/S7039-ND/810178
[Z945-ND]: http://www.digikey.com/product-detail/en/G6B-1114P-US-DC5/Z945-ND/148724
