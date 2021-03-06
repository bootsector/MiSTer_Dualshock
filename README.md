# MiSTer_Dualshock
FPGA native serial Dualshock interface for MiSTer

![alt text](https://i.imgur.com/dH7BLh0.png)

This is a very simple Dualshock serial interface for MiSTer FPGA that allows 
you to play on MiSTer with your Sony Dualshock 1/2 controllers and other
compatible devices and adapters.

This relies on native low latency FPGA serial interface that, in order to work,
needs implementation of the SPI (low level) Dualshock (high level) protocol in
MiSTer cores.

An experimental MiSTer Game Boy core with support for this adapter can be found at https://github.com/bootsector/Gameboy_MiSTer/releases/tag/v0.1

BOM:

USB 3.0 A connector:
https://www.aliexpress.com/item/1997169684.html

Dualshock connector:
https://www.aliexpress.com/item/32818887920.html

DC (rumble) connector:
https://www.aliexpress.com/item/33005175186.html
