# UBLCKDGMS

This is supposed to be a collection of unblocked games that only need a web server or less to work & can be used on github pages

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
   3. make sure that it supports as low as just a web server (run npx serve in your fork's clone's directory)
   4. make sure that it makes no requests to other website other then for arbritrary reasons such as leader boards
      1. you can check this by going into devtools in your browser while running the game & going into network tab & making sure it makes no requests other then the host(localhost, 127.0.0.1, file:// etc.)
3. create a pull request to my repo
