# VIC-20-Hyper-Expander
The Hyper Expander is a cartridge for the Commodore VIC-20, which provides up to 16kB EPROM and up to 37kB RAM. It is a super-set of the original Commodore VIC-1211A Super Expander, which provides only 3k of RAM.

The Hyper Expander can hold up to two 27C512 EPROMs, the 8k memory bank of both EPROMs (A13...A15) can be selected for both EPROMs. The same selection applies to both of them. Each EPROM (IC1 and IC2) can be jumpered to two chip selects. That is BLK2 or BLK5 for IC1 and BLK1 or BLK3 for IC2. 

The RAM od two 32kB 62256 type static RAMs. The memory is divided into seven banks. Two 74LS148s decodes the active chip selects to one of each memory bank. The used chip selects can be configured with JP5 and JP4.

<img src="https://github.com/svenpetersen1965/VIC-20-Hyper-Expander/blob/main/Rev.%201/pictures/8161_-_Hyper_Expander_Cartridge.JPG" width="300" alt="VIC-20 Hyper Expander">

The calculated BOM value of Rev. 0 is: 12.86€ (12.12.2020)
The calculated BOM value of Rev. 1 is: 15.23€ (11.04.2021)
