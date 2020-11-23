# VIC-20-Hyper-Expander
The Hyper Expander is a cartridge for the Commodore VIC-20, which provides up to 16kB EPROM and up to 32kB RAM. It is a super-set of the original Commodore VIC-1211A Super Expander, which provides only 3k of RAM.
The Hyper Expander can hold up to two 27C512 EPROMs, the 8k memory bank of both EPROMs (A13...A15) can be selected for both EPROMs. The same selection applies to both of them. Each EPROM (IC1 and IC2) can be jumpered to two chip selects. That is BLK2 or BLK5 for IC1 and BLK1 or BLK3 for IC2. 
The RAM is a 32kB 62256 type static RAM. The memory is divided into four banks. A 74LS148 decodes the active chip selects to one of each memory bank. The used chip selects can be configured with JP5 and JP4.

<img src="https://github.com/svenpetersen1965/VIC-20-Hyper-Expander/blob/main/Rev.%200/pictures/6763_Hyper_Expander_Cartridge.JPG" width="300" alt="VIC-20 Hyper Expander">

