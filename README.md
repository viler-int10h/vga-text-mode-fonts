# Bitmap fonts compatible w/VGA text mode

This collection was originally released for use with the [Fontraption font editor](https://int10h.org/blog/2019/05/fontraption-vga-text-mode-font-editor/), but it's now a separate project for ease of maintenance.

All fonts here are monospaced, 8 pixels wide, and up to 32 lines tall.  They're stored in the native raw binary format of the VGA BIOS routines: a sequence of 256 characters, each up to 32 bytes long.  One byte per scanline, one bit per pixel.

* See [FONTS.TXT](FONTS.TXT) for detailed information, font descriptions, origins, and credits.
* For compatibility with Fontraption (and DOS in general), filenames are in the 8.3 format.
* As a convention, file extensions are ".F??" with two final digits specifying the font's height.

**NOTE:** Git doesn't preserve file dates!  Dates are an important historical cue in a collection like this -- to have them intact, grab the latest archive from the [Releases page](./releases).
