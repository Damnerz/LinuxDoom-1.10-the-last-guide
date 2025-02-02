# The ULTIMATE LINUXDOOM 1.10 GUIDE EASY DOOM.

_Note_: Tested on Linux Mint 22.

- Linux
- Git (`sudo apt install git`)
- xserver-xephyr (`sudo apt-get install xserver-xephyr`)

### 64-bit
==========================================================

- libc6-dev (`sudo apt-get install libc6-dev`)
- libx11-dev (`sudo apt-get install libx11-dev`)
- libxext-dev (`sudo apt-get install libxext-dev`)
- libnsl-dev (`sudo apt-get install libnsl-dev`)

### 32-bit
==========================================================

- libc6-dev:i386 (`sudo apt-get install libc6-dev:i386`)
- libx11-dev:i386 (`sudo apt-get install libx11-dev:i386`)
- libxext-dev:i386 (`sudo apt-get install libxext-dev:i386`)
- libnsl-dev (`sudo apt-get install libnsl-dev:i386`)

## Build and Run

```bash
$ git clone the repository.
$ cd DOOM_fixed/linuxdoom-1.10 
$ make # 64 bit build
$ make x86 # 32-bit build
$ cd linux/ 
Get the Doom wad or the Doom shareware.
...
# in an other terminal, run:
$ Xephyr :2 -ac -screen 320x200x8 # start an X server with Xephyr
...
# in the first terminal, run:
$ DISPLAY=:2 
$ ./linuxxdoom 
```

                  =================     ===============     ===============   ========  ========                                                             
                  \\ . . . . . . .\\   //. . . . . . .\\   //. . . . . . .\\  \\. . .\\// . .  //
                   ||. . ._____. . .|| ||. . ._____. . .|| ||. . ._____. . .|| || . . .\/ . . .||
                   || . .||   ||. . || || . .||   ||. . || || . .||   ||. . || ||. . . . . . . ||
                   ||. . ||   || . .|| ||. . ||   || . .|| ||. . ||   || . .|| || . | . . . . .||
                   || . .||   ||. _-|| ||-_ .||   ||. . || || . .||   ||. _-|| ||-_.|\ . . . . ||
                   ||. . ||   ||-'  || ||  `-||   || . .|| ||. . ||   ||-'  || ||  `|\_ . .|. .||
                   || . _||   ||    || ||    ||   ||_ . || || . _||   ||    || ||   |\ `-_/| . ||
                   ||_-' ||  .|/    || ||    \|.  || `-_|| ||_-' ||  .|/    || ||   | \  / |-_.||
                   ||    ||_-'      || ||      `-_||    || ||    ||_-'      || ||   | \  / |  `||
                   ||    `'         || ||         `'    || ||    `'         || ||   | \  / |   ||
                   ||            .===' `===.         .==='.`===.         .===' /==. |  \/  |   ||
                   ||         .=='   \_|-_ `===. .==='   _|_   `===. .===' _-|/   `==  \/  |   ||
                   ||      .=='    _-'    `-_  `='    _-'   `-_    `='  _-'   `-_  /|  \/  |   ||
                   ||   .=='    _-'          '-__\._-'         '-_./__-'         `' |. /|  |   ||
                   ||.=='    _-'                     ___________                     `' |  /==.||
                   =='    _-'                        Since  1993                         \/   `==
                    \   _-'                          ===========                          `-_  /
                      `''                                                                    ``'



