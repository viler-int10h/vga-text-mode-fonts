# Bitmap fonts compatible w/VGA text mode

Compiled for use with the [Fontraption font editor](https://int10h.org/blog/2019/05/fontraption-vga-text-mode-font-editor/).  Contains **1760** font files (as of 2020-11-25).

* See [FONTS.TXT](FONTS.TXT) for detailed information, font descriptions, origins, and credits.
* For compatibility with Fontraption (and DOS in general), filenames are in the 8.3 format.
* As a convention, file extensions are ".F??" with two final digits specifying the font's height.

All fonts here are monospaced, 8 pixels wide, and up to 32 lines tall.  They're stored in the native raw binary format of the VGA BIOS routines: a sequence of 256 characters, each up to 32 bytes long.  One byte per scanline, one bit per pixel.

For convenicence: the "PREVIEWS" folder contains a .png preview of each font (using *non*-8.3 filenames).

----

***NOTE:*** **Git doesn't preserve file dates!**  Dates are an important historical cue in a collection like this -- to have them intact, grab the latest archive from the **[Releases page](../../releases)**.
