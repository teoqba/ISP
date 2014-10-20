Arduino Tiny ISP code modified to program ATMEGA MCU hooked up to slow oscilator crystals

Original code:
https://code.google.com/p/arduino-tiny/downloads/detail?name=tiny-isp-2-0100-0001.zip&can=2&q=

Modifications:
TinyISP_SPI.cpp - line 152 and 162 - delay time increased in bit-banging SPI code for slow clocks. Values 55 works for 32768Hz. For slower clocks, they need to be increased further. 

