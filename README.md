# VIC-20-Hyper-Expander
The Hyper Expander is a cartridge for the Commodore VIC-20, which provides up to 16kB EPROM and up to 37kB RAM. It is a super-set of the original Commodore VIC-1211A Super Expander, which provides only 3k of RAM.

The Hyper Expander can hold up to two 27C512 EPROMs, the 8k memory bank of both EPROMs (A13...A15) can be selected for both EPROMs. The same selection applies to both of them. Each EPROM (IC1 and IC2) can be jumpered to two chip selects. That is BLK2 or BLK5 for IC1 and BLK1 or BLK3 for IC2. 

The RAM od two 32kB 62256 type static RAMs. The memory is divided into seven banks. Two 74LS148s decodes the active chip selects to one of each memory bank. The used chip selects can be configured with JP5 and JP4.

<img src="https://github.com/svenpetersen1965/VIC-20-Hyper-Expander/blob/main/Rev.%202/pictures/9386_-_Hyper_Expander_v2_standard.JPG" width="300" alt="VIC-20 Hyper Expander">

The BOM values do not include a case
* The calculated BOM value of Rev. 0 is: 12.86€ (12.12.2020)
* The calculated BOM value of Rev. 1 is: 15.23€ (11.04.2021)
* The calculated BOM value of Rev. 2 is: 16.17€ (02.11.2021)

# RAM issues
I was recently reported (May 2022), that there were cross-link issues with the Alliance 45ns and 55ns RAMs. I believe, that those might be too fast and that it is not an issue of the brand. Replacing those RAMs with slower models (70ns) has solved this problem. A friend has successfully used 100ns and 120ns RAMs as well (he had built a couple of the Hyper Expander). I am mainly using 70ns and 80ns RAMs and never found any issues with them. At least, my test software can recognize those problems.

<img src="https://github.com/svenpetersen1965/VIC-20-Hyper-Expander/blob/main/Rev.%202/pictures/HypEx_badRAM.jpg" width="300" alt="45ns RAM issue">

# Testsoftware
Find the Testsoftware here: https://github.com/svenpetersen1965/VIC-20-RAM-Expansion-Test-Software
