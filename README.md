GT Spacetime steps to update
============================

DISCLAIMER: I HAVE ONLY TESTED THIS WITH SUPER METROID

1. Update to 1.11.0 firmware (https://sd2snes.de/blog/archives/1261)
2. Make a backup of your sd2snes/fpga_base.bit and sd2snes/fpga_base.bi3 files
3. Replace the files with the ones from this repository

The SD2SNES/FxPak/FxPak Pro update the FPGA each time you boot the device,
so simply swap those files with your backup if you want to switch back to 1.11.0

If you are interesting in building these files yourself,
I used docker and this repository:
https://github.com/alttpo/sd2snes-build-docker

