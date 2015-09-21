# ECE153A_ILI9340
- 2.2 TFT Lcd Driver library for interfacing to Artix-7 FPGA.
- Originally created by Chieh Lu for ECE 253 Graduate student project Fall 2014
- Updated for use in ECE153A course.


The [datasheet](http://www.adafruit.com/datasheets/ILI9340.pdf) for the LCD screen driver (ILI9340) which is avilable from [Adafruit](https://www.adafruit.com/products/1480)


This library is designed for use with the ECE153A Fall Course at UCSB. The course is built around a Microblaze softcore processor implemented on the Artix-7 FPGA Chip which is used on the Nexys4DDR development board. It is intended to be used with Vivado 2014.1 and the AXI GPIO module provided by Xilinx as part of the IP cores available in Vivado. This is a software implementation of the SPI interface using the general purpose AXI GPIO IP core.


###Getting Started
1. Download the git repository into your */src* code folder
2. Within your *main.c* include the library header  *#include "ECE153A_ILI9340/ILI9340.h"*

###Library Features
* Fill Screen
* Draw Rectangle
* Write Single Character (A-C), at any position on the screen
* Draw a Horizontal Line
* Draw a Vertical Line

### Planned Features
*ASCII Table Characters, from code 32 - 126


