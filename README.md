# QuakeGX Wii

the quake port for the wii but for modern toolchains

find the original source here: https://code.google.com/archive/p/quake-gamecube/source/default/source

to compile, just run make.

To run your resulting binary on a real wii,
copy the QuakeGX.elf file to dist/wii/apps/quake/boot.elf, then copy PAK0.PAK from the shareware version of Quake into dist/wii/apps/quake/ID1/PAK0.PAK and copy the resulting quake folder to your apps folder on your SD card or USB.

You can also copy over any other PAK files(such as mods, the full game, etc.) over and they'll run fine.
