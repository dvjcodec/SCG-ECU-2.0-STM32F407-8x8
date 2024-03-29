# SCG-ECU 2.0 - Standalone ECU for Speeduino and RusEFI. 

![Board](1675710963089.jpg?raw=true "Board")

![Board](1675710963438.jpg?raw=true "Board")

## Features:
* STM32F407
* external flash 512KB
* 8 out low-side for injectors - max. 7A
* 8 out high-side for igniters (COP) 5V or 12V
* 4 out low-side (HC1, HC2, IDLE, BOOST) - max. 7A
* 2 out low-side, low current (max. 0.7A) for RPM gauge and cooler relay
* build-in Wideband controller (SLC-FREE 2.0)
* stepper driver control
* inputs: TPS, IAT, CLT, O2, BARO, MAP
* CAN-Bus onboard
* 2x VR/Hall input
* baro sensor onboard
* 4-layer PCB

## Pinout
Pinout on my blog --> https://seasidecustoms.blogspot.com/p/scg-ecu-20.html

## JLCPCB production
All nececery files to manufacture this board in JLCPCB available in this Git. Some part are missing in JLCPCB file, because not available in JLCPCB catalogue. Part's number/value U can find on schematic. Mosfet's, MAX9926 available in Mouser. Correct part placement in part_placement.png file. Cypress chip is nececery if U want use Wideband controller. 

## YT video from test this ECU with M112 Mercedes V6 engine
https://www.youtube.com/watch?v=3s2p-b_rBg0

## Topic on Speeduino official board
https://speeduino.com/forum/viewtopic.php?t=5611

## LICENSE
Creative Commons NonCommercial

## Part's placement
Open file SCG-ECU_2.0_STM32F407_standalone_part_placement-EAGLE.brd in EAGLE to see part's name/value

## Special THNX
Special thnx for Benas Brazdziunas for preparing firmware, base_map and INI files

## I provide files for free. I am not responsible for any damage caused. You use at your own risk.
