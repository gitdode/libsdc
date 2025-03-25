# libsdc

## About

Static avr-libc library providing basic support for SD cards.  

Tested with a few recent SD cards with 16/64 GB from SanDisk, Transcend and 
Samsung.

## TODO

- Write multiple blocks

## Usage

1. Include `libsdc.h` and `libsdc.a` in the project
2. To make the library device and CPU frequency independent, the
`_sdc*` functions in `libsdc.h` must be implemented in the application

## Features

- Read single block
- Read multiple blocks
- Write single block
