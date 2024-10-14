# QuakeGX MOD

QuakeGX MOD is a port of Quake for the Wii with extra modifications.

Original source can be found at https://code.google.com/archive/p/quake-gamecube/source/default/source

## Compilation

To begin compilation, run `make` in the root directory of the repository. This will produce the binary, named `QuakeGX.dol` in the root repository directory.

To run the resulting executable on a real Wii, copy the QuakeGX.dol file to dist/wii/apps/quake/boot.dol, then copy PAK0.PAK from the shareware version of Quake and any other .pak files you may have into `dist/wii/apps/quake/ID1` and copy the `quake` folder to your apps folder on your SD card or USB.
