# gba-hello-world
My first ever "Hello world" for the Game Boy Advance 👾 

It displays three pixels (RGB) on the console screen.

# Play
This respository already contains the compiled ROM (.gba) file. 

I recommend to open it with your favourite GBA emulator. I use [VisualBoy Advance](https://sourceforge.net/projects/vba/files/) for MacOS.

# Compile
*"The hardest part is getting started"*

1. **Install [devkitPRO's pacman](https://github.com/devkitPro/pacman/releases/latest)**. 

DevkitPRO's pacman is a package manager just like any other but built exclusively for retro gaming development built by the devkitPRO team.

2. **Install the GBA rules with pacman**. 

Once pacman is intalled you can run the following command:

```
$ sudo dkp-pacman -S gba-dev
```

3. **Run the Makefile**

Run the following command at the root folder of this repo and it will compile the .gba rom file.
```
$ make
```

For windows you can check out the oficial [devkitPRO documentation](https://devkitpro.org/wiki/devkitPro_pacman) (sorry)


# Resources
- [VisualBoy Advance GBA emulator](https://sourceforge.net/projects/vba/files/)
- [Writing a GBA game](https://www.reinterpretcast.com/writing-a-game-boy-advance-game)
- [TONC's guide for GBA development](http://www.coranac.com/tonc/text/toc.htm)
- [GBA examples](https://github.com/devkitPro/gba-examples)


