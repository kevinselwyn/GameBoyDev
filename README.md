# GameBoyDev
An example gameboy game project for use with the
[Game Boy Development Environment](https://youtube.com/NesHacker) YouTube video.

## How to Build the ROM

### Depedencies
* [RGBDS](https://github.com/rednex/rgbds) - Game Boy Assembly & Linking Tools
* [GNU Make](https://gnuwin32.sourceforge.net/packages/make.htm) - Build system
tool (usually you'll only need to install this on Windows).

### Use Make to Build the ROM
With the assembler installed, open a command-line and run make:

```
$ make
```

This will run the make script and produce the `bin/GameBoyDev.gb` rom.

### Build Settings (ROM name, etc.)
For changes to how the game is assembled and linked, change the parameters in
[project.mk](./project.mk) (don't make changes to the [MakeFile](./Makefile)
directly).

## Attribution
This project was derived from
[gb-boilerplate](https://github.com/ISSOtm/gb-boilerplate), for further details
please see [README-gb-boilerplate.md](./README-gb-boilerplate.md).
