Antminer S9
===========

This repository aims to collect information about Bitmain Antminer S9 control boards. These boards are Zynq 7010 based single board computers capable of running Linux.

![AntMiner S9 V1.0 board photo](AntMiner_ControlBoard_XC7010_V1.0.png)

The Antminer S9 control board has onboard flash, Fast Ethernet and SD card slot. It is particularly interesting as it has more GPIOs available than the EBAZ-4205 board.

The plan is to provide several files ready to use with Petalinux build tools as well as Petalinux adjustments for the board, allowing different customizability levels:

* Vivado project
* Exported Vivado hardware (XSA) to allow for creating a Petalinux project without having to install Vivado
* Ready made images to put on SD card or TFTP server ?

This readme will be rewritten later on.

Sources
--------

* https://github.com/guannan-he/Antminer_s9_pynq
* https://github.com/Xilinx/u-boot-xlnx/blob/master/arch/arm/dts/bitmain-antminer-s9.dts
* https://github.com/KarolNi/S9miner_sample

Licence
-------

This project is released on GPL2.0 licence except for schematic files. Schematics copyright Bitmain Technologies Ltd.