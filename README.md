# UBLCKDGMS

This is supposed to be a collection of web games that only need a web server or less to work & can be used on github pages

## Blocked? NO PROBLEM

1. fork this repository along with with its other repositories such as [ublckdgms2](https://github.com/omaribnzakaria/ublckdgms2) & [ublckdgms3](https://github.com/omaribnzakaria/ublckdgms3) & MAKE SURE to keep the names the same. they are seperated into different repositories to make sure to not go over github's 10GB per page limit
2. Change _config.yml to your preferences, changing url is mandatory as keeping the same url as mine will break deployment
3. change index.html & the flash games titles to your preferences, MAKE SURE TO CREDIT ME & KEEP THE PRE-EXISTING CREDITS
4. your new unblocked website will be at `your github username`.github.io/ublckdgms/

## Codeword use

just go to https://omaribnzakaria.github.io/ublckdgms/birdseed/`code`

## Add your own games
1. Fork the repo
2. add your game in its own folder in your fork
   1. make sure that it contains index.html
   2. make sure that it actually runs the game itself in web browser
   3. make sure that it supports as low as just a web server (run npx serve in your fork's clone's directory in the terminal)
      1. make sure you have NodeJS, npm, vercel serve & all that other stuff to test on a web server
         1. this means that you need a computer that can support installations of these tools so no chromebooks unless you use the linux VM which is blocked on enrolled ones
            1. I would be happy to test it on my computer
   4. make sure that it makes no requests to other website other then for arbritrary reasons such as leader boards
      1. you can check this by going into devtools in your browser while running the game & going into network tab & making sure it makes no requests other then the host(localhost, 127.0.0.1, file:// etc.)
   5. you can try & find your game in the sources below
3. create a pull request to my repo

some techy word definitions for y'all non-nerds
- repo: short for repository, a place where code is stored for stuff like access between multiple ppl, such as this repo
- fork: basically a seperate version of the original repo where the fork creator can add their own stuff to, can make a pull request to  merge the forks changes into the original repo
- git: a tool to basically manage & control features & versions to make it easier to manage what & what doesn't get added
- clone(in the git sense): your local copy of the repo
- local: resides entirely on your device

## Sources:
- [genizy](https://github.com/genizy/web-port) for most of the games, contains web ports of pc games
- [crisisapple89](https://github.com/crisisapple89/crisisapple89.github.io) for funny shooter
- Vimm's layer(I am legally not allowed to link this, just search it up on google) for the emulated game roms
- [EmulatorJS code generator](https://emulatorjs.org/editor) to generate code for the emulator
- [3kh0 assets](https://gitlab.com/3kh0/3kh0-assets) assets for another unblocked games website
- [Xash3D](https://github.com/yohimik/webxash3d-fwgs) for the half life & counterstrike porting tech, someone work on the counterstrike port on their own time & then follow the steps above if they can
- [HTML-Games-V2](https://github.com/tw31122007/HTML-Games-V2) for the Moto-X3M & Vex 3 games, contains alot of web browser games
- [Flash Storage dot games](https://flashstorage.games/) for the flash swf files
- [Ruffle](https://ruffle.rs/downloads#website-package) for flash emulation on browser
- [Web Balatro Builder](https://w0w53r.github.io/web-balatro/) generates a balatro web port when given the BALATRO.exe or BALATRO.love file, can add mods