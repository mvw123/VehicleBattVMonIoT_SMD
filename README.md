Vehicle battery voltage monitor IoT SMD
=======================================

Vehicle battery voltage monitor IoT. Measures the voltage of a 12V car battery. Sends this to a receiver device which pushes the data to the cloud.

This PCB is designed to fit in the car strapped between the battery terminals. It uses either a LoRA RFM95 module, or a sub Ghz modules RFM69HCW module. Other parts of the design mostly use low cost modules to reduce the hand assembly time. Some through hole components, SMD 0805 and SMD diodes require hand assembly.

Designed using Eagle cad 7.5.0 light.

Incorporates support for:- 
* Arduino Pro Mini, 3.3V, 8MHz version only. (5V version will damage circuit)
* RFM69HCW or RFM95W/96W/97W/98W module
* SMA 50 ohm antenna connector
* 16 bit ADC module TI ADS1115
* Sensirion SHT31 temperature/humidity sensor module
* DC-DC converter
* Fuse and reverse voltage protection
* [Optional] RGB LED to visually indicate voltage levels
* [Optional] EUI-64 LoRA node identity chip for debug
* [Optional] Winbond flash storage
* [Optional] OLED display interface for debug purposes
* [Optional] HM-10 Bluetooth LE module carrier footprint

CAD B - [WIP]
=============

Not released yet, needs CAD updates. 

CAD A - [FAULTY]
===========================

Board has CAD issues, see issues list. needed some wiring and re-work. 
Board released for manufacture 3 Aug 2017
Software partially written

MVW
www.guvvy.co.uk
