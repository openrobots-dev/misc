Getting started with ARM Cortex-Mx cross-development
====================================================

This guide will explain how to setup a complete toolchain and graphical IDE based entirely on free and open source components for Linux, Windows and OSX.


### What this guide covers ###

This guide wants to give all the tools needed to produce an ARM executable binary file, to flash it on a microcontroller and to run and debug it, with or without a graphical IDE.

The guide covers the installation and setup of the components needed to get a working cross-development toolchain:

* a compiler to produce executable ARM Cortex-Mx code
* a linker script to generate the binary file
* a script to flash the firmware on the microcontroller
* a makefile to automate the process

The guide include some optional topics too:

* the use of OpenOCD and GDB to debug the code running on the target microcontroller
* the installation of Eclipse IDE to get a graphical development solution
* the setup of ChibiOS/RT and the execution of a demo project


### What this guide does not cover ###



### Credits ###

This guide is based on other existing tutorials found on internet, most of the credits go to the corresponding authors.

In particular, thanks goes to:

* [GCC for ARM EABI](https://github.com/jsnyder/arm-eabi-toolchain) by James Snyder
* [summon-arm-toolchain](https://github.com/esden/summon-arm-toolchain) by Piotr Esden-Tempski
* [CodeSourcery GNU Toolchain for the ARM on a Mac](http://www.micromouseonline.com/blog/2009/05/07/codesourcery-gnu-toolchain-for-the-arm-on-a-mac) by Peter Harrison
* [Setting up an Eclipse-based IDE](http://www.chibios.org/dokuwiki/doku.php?id=chibios:guides:eclipse1) by Giovanni Di Sirio
* [Using an Eclipse-based IDE](http://www.chibios.org/dokuwiki/doku.php?id=chibios:guides:eclipse2) by Giovanni Di Sirio
