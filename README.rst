You want to build a multiwii firmware from the command line ?

This is the right place.

Prerequisites:

CMake - http://www.cmake.org/cmake/resources/software.html
Arduino SDK - http://www.arduino.cc/en/Main/Software

Linux requirements:
gcc-avr - AVR GNU GCC compiler
binutils-avr - AVR binary tools
avr-libc - AVR C library
avrdude - Firmware uploader

Setup:
See with multiwii what you need to change in config.h.

Compile:
mkdir build
cd build
cmake ..
make

All credits to multiwii and arduino-cmake authors. I just mashed them together.

arduino-cmake license :  Mozilla Public License, v. 2.0
Multiwii license : GNU GPL v3

