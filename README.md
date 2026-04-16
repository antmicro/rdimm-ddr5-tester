# Data Center RDIMM DDR5 Tester

Copyright (c) 2021-2025 [Antmicro](https://www.antmicro.com)

[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/ddr5-tester)

![](img/datacenter-rdimm-ddr5-tester.png)

## Overview

This project contains open hardware design files for an experimental platform built around Xilinx Kintex-7 FPGA.
The main purpose of this platform is to develop and customize RAM controllers supporting DIMM DDR5 RAM modules used in data centers.
The design files were prepared in KiCad.

## Project structure

The main directory contains KiCad PCB project files, a
LICENSE and README. The remaining files are stored in the following
directories:

-   `lib` - contains the component libraries
-   `img` - contains graphics for this README
-   `doc` - contains PDF schematics

## Key Features

-   Kintex-7 FPGA - XC7K160T-2FBG676C
-   DDR5 DIMM connector
-   HDMI output connector
-   Ethernet RJ45 connector with 1GbE transciever
-   USB-C debug connector with FT4232HQ FTDI USB controller
-   JTAG
-   microSD card slot
-   16 MBytes S25FL128S QSPI FLASH memory
-   S27KL0641 HyperRAM
-   External 7-12V power input
-   5 user LEDs
-   4 user buttons

## License

This project is published under the [Apache-2.0](LICENSE) license.
