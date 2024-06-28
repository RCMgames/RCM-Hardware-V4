# RCM-Hardware-V4

v1.3

* 4 motors and 7 servos OR 6 motors and 3 servos
* 3 additional input only pins
* 2 x 3 inches, 50.8 x 76.2 mm
* runs from 5 NiMH AA batteries OR 4.5-12v with the addition of voltage regulators (see list of components)
* [Qwiic](https://www.sparkfun.com/qwiic#faqs) connectors OR two more GPIO pins
* all components are hand-solderable through-hole parts except for the Qwiic connectors which are surface mount

Compatible with 38 pin devkitC ESP32 boards

program with [RCMv2](https://github.com/RCMgames/RCMv2)

### Alternatives
* An upgrade from [the original 3 versions of RCM boards](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide)

* Here are smaller and more powerful RCM boards: [BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE) and [Nibble](https://github.com/RCMgames/RCM-Hardware-Nibble)

## Options for purchasing

* [PCBWay link](https://www.pcbway.com/project/shareproject/W454600ASI60_gerbers_RCM_Hardware_V4_v1_3_38d50617.html) (PCBWay will give me a commission without increasing the price for you). (approximately $5 for 5 boards and manufacturing takes 1-7 days).
* send the gerbers to a PCB manufacturer of your choice (details you may be asked for: min hole: 0.3mm, min track/spacing 6/6mil, 1 oz Cu outer)

## Components
Solder by hand to assemble your boards.
| part | links | quantity | notes |
| ----- | ----- | ----- | ----- |
| RCM V4 circuit board | see options for purchasing above | 1 | |
| ESP32 devkitC 38 pin | [digikey](https://www.digikey.com/en/products/detail/espressif-systems/ESP32-DEVKITC-32E/12091810) or find on Amazon | 1 | |
| L293D | [digikey](https://www.digikey.com/en/products/detail/texas-instruments/L293DNE/379724) | 2 or 3 | |
| 16 pin IC socket | | 0 to 3 | depending on whether you solder the ICs directly and how many motors you want to use |
| 30k resistor | | 1 | |
| 10k resistor | | 1 | |
| 47uF capacitor | | 1 | |
| Qwiic connector (JST SH) | [digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/SM04B-SRSS-TB/926710) | 0 to 2 | |
| 4 male header pins | | 1 | for I2C pins |
| 5 male header pins | | 1 | for extra input pins |
| 7 male header pins | | 4 | for servos |
| 4 female header pins | | 3 | for motors (can also use one 12 pin strip instead) |
| 19 female header pins | | 2 | for esp32 |
| battery wires | 2 male header pins OR JST RCY OR 9V battery snap | 1 | [Amazon JST RCY](https://www.amazon.com/dp/B00Z04QFN2/) |
| servo buck boost 5v 2A | [Pololu](https://www.pololu.com/product/4085) | 0 or 1 | if you want to supply voltages above or below what servos can accept (supplies other than 5AAs) |
| esp32 buck 5v 0.6A | [Pololu](https://www.pololu.com/product/3792) | 0 or 1 | if you want to supply voltages above 7 volts (supplies other than 5AAs) |

![image](https://github.com/RCMgames/RCM-Hardware-V4/blob/02e49bd58bd07ffe95db38a5303c5c172d2a5ed9/photos/P1040795.JPG)
![image](https://github.com/RCMgames/RCM-Hardware-V4/blob/02e49bd58bd07ffe95db38a5303c5c172d2a5ed9/photos/P1040794.JPG)

## Acknowledgements
* I would like to thank [PCBWay](https://www.pcbway.com/) for sponsoring prototyping runs of this project. PCBWay produces very nice boards, supports open source hardware, and gave me great support as I worked on this project. Special thanks to Liam!
