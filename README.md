# Coreboot-W530
BIOS and Binary Blobs for the Lenovo W530 and my build of [Coreboot](https://www.coreboot.org/) for my personal W530.

This repository includes the "original bios" for the W530 (patched to remove wifi-card restrictions and enable the "advanced" menu) as well as the components required to compile a coreboot firmware.

I used a Raspberry Pi to both extract the BIOS and flash back the compiled Coreboot BIOS.

File Descriptions below:
* 10de,0ffc.rom - VGA Bios for the Nvidia Optimus K1000 extracted from the "original" bios
* 8086,0166.rom - VGA Bios for the Native Intel Graphics card
* MX25L3206E-4MB.bin - Dump of the "original" bios 4MB chip
* MX25L6406E-8MB.bin - Dump of the "original" bios 8MB chip
* config - Coreboot Config File
* descriptor.bin - Descriptor file extracted from the "original" bios
* gbe.bin - Gigabyte Ethernet Bios extracted from the "original" bios
* k1000m-vbios_10de_0ffc.rom - VGA Bios for the Nvidia Optimus K1000 extracted from the "original" bios
* k2000m-vbios_10de_0ffb.rom - VGA Bios for the Nvidia Optimus K2000 extracted from the "original" bios
* left.rom - 8MB chip split bios of the compiled Coreboot BIOS
* me.bin - Neutered Intel Management Engine file extracted from the "original" bios
* newbios.rom - Combined left and right corebot BIOS
* original-bios.bin - Dump of the "original" bios 
* right.rom - 4MB chip split bios of the compiled Coreboot BIOS
* w530-coreboot-4.11.bin - Final compiled coreboot image based on coreboot 4.11
* w530-coreboot-4.12.bin - Final compiled coreboot image based on coreboot 4.12
