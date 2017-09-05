# EAGLE CAD PARTS

Date: `04-09-2017`<br>
By: `Roland van Straten`

In this repo you will find some usefull parts for use with `EAGLE`.


## Wireless Modules
### Insight SiP
Wireless Modules based on the nRF52832, with embedded antenna, both crystals and DCDC converter.

All pins, except `P0.00` and `P0.01` are available.

PART | PACKAGE | SIZE
----- | -----  | ----
ISP1507 | LGA | 8.0x8.0x1.0mm  


### Murata
Wireless Modules based on the nRF52832, with embedded antenna, 32MHz crystal. `DCC`, `P0.00` and `P0.01` are available to implement DCDC and 32kHz crystal.

Subset of available pins

PART | PACKAGE | SIZE
----- | -----  | ----
MBN52832 | WSM-BL241-ADA-008 | 7.4x7.0x1.0mm  


### Pycom OEM Modules
This library is a collection of the [Pycom](http://pycom.io) OEM Modules that are based on the `ESP32` from [Espressif](http://www.espressif.com).

The library is __NOT YET VERIFIED__ especially the `GPy` module.

MODULE | RF1 | RF2 | RF3 | RF4 |
----- | ----- | ----- | ----- | ----- 
W01 | |  WiFi | Bluetooth | BLE  
L01 | LoRa | WiFi | Bluetooth | BLE
S01 | Sigfox | WiFi | Bluetooth | BLE | Sigfox
G01 | LTE M1/NB1 | WiFi | Bluetooth | BLE 


### WIFI2GO
`WIFI2GO` is a module from [ImageCraft](http://imagecraft.com) that is available with different processor options. However the part in this library is the `STM32L411RCT6`. The board also has a Texas Instruments `CC3100` Wi-Fi chip and integrated antenna. Please refer to the website of Imagecraft for further information on availability and pricing.

MODULE | SIZE | CPU | Flash | SRAM | WiFi
----- | ----- | ----- | ----- | ----- | -----
WIFI2GO | 46x36mm | STM32F411RCT6 | 256kB | 128kB | CC3100



## Analog
### Linear Technology
Dual and Quad Operational Amplifiers 70MHz bandwidth

PART | PACKAGE
----- | -----  
LT1364CN | PDIP8  
LT1364CS | SO08
LT1365CN | PDIP14  
LT1365CS | SO16


## Texas Instruments
Power Supplies

PART | PACKAGE | PART | PACKAGE 
----- | -----  | --- | ---
TPS60400 | SOT23-5 | TPS60400-Q1 | SOT23-5
TPS60401 | SOT23-5 | TPS60401-Q1 | SOT23-5
TPS60402 | SOT23-5 | TPS60402-Q1 | SOT23-5
TPS60403 | SOT23-5 | TPS60403-Q1 | SOT23-5


## Micro-Controllers
### STMicroelectronics 
#### STM32L476xxx Micro-controllers

This file contains the following parts:

PART | PACKAGE | SIZE | Flash | SRAM | FARNELL
----- | ----- | ----- | ----- | ----- | -----
STM32L476RCT6 | LQFP64 | 10x10mm | 256kB | 128kB | 2518170
STM32L476RET6 | LQFP64 | 10x10mm | 512kB | 128kB | 2494459
STM32L476RGT6 | LQFP64 | 10x10mm | 1024kB | 128kB | 2494460
 | | |  | | 
STM32L476VCT6 | LQFP100 | 14x14mm | 256kB | 128kB | 2518171
STM32L476VET6 | LQFP100 | 14x14mm | 512kB | 128kB | 2494461
STM32L476VGT6 | LQFP100 | 14x14mm | 1024kB | 128kB | 2494462
 | | |  | | 
STM32L476RET6 | LQFP64 | 10x10mm | 512kB | 320kB | 2758825
STM32L476RGT6 | LQFP64 | 10x10mm | 1024kB | 320kB | 2725138
 | | |  | | 
STM32L476VET6 | LQFP100 | 14x14mm | 512kB | 320kB | 2758827
STM32L476VGT6 | LQFP100 | 14x14mm | 1024kB | 320kB | 2725139

___The parts are interchangeable to somem extend if the guidelines of STM are followed.___


### Disclaimer

The information is provided as is.

Information is subject to change without notice. No rights can be obtained from this publication.
