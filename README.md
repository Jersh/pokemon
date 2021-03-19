# Pokemon

A work-in-progress project of botting/datamining tools for the generation 1 and 2 games of the Pokemon series.


# Build Instructions (64-bit only for now)

1. `git clone https://github.com/stringflow/pokemon`
2. Download the prebuilt 64-bit binary of [SDL2](https://www.libsdl.org/download-2.0.php) from their website and copy it to the root directory of the project.
3. Create a folder called `roms` and add ROM images to it. The files must be named `poke*.gbc` (i.e. `pokered.gbc`, `pokecrystal.gbc`, etc.).
4. The GBC bios file also needs to be saved to the 'rom' folder. file name should be gbs_bios.bin.
5. Open the project in vscode and run!

6. To view the game in action add "gb.Show();" after Line:182 in GSTotodile.cs
