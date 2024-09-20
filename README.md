# Nuked SC-55 with NVRAM stuff

Some old versions of Nuked SC-55 featured the ability to save the JV-880's NVRAM to a BIN file, which meant that your system settings would not be lost every time you close the emulator. However, this feature was later removed ["in favour of future solution"](https://github.com/nukeykt/Nuked-SC55/pull/35/commits/85d3c52aec7a4c80efc3931bd5136aaae2bab715).

Since that future solution hasn't materialised yet, this is just a fork that re-adds the old NVRAM code with a couple of modifications (such as making it only run while the emulator is in JV-880 mode, as otherwise NVRAM gets corrupted when you launch in another mode).

Windows builds can also be found on the [Releases Page](https://github.com/ColouMods/Nuked-SC55-NVRAM/releases).

<sub>(Full disclaimer: I've never worked in C++ before and don't really know what I'm doing, so apologies if my code sucks/looks ugly/has 10 million memory leaks.)</sub>