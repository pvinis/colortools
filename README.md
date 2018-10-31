# colortools

[![Build Status](https://travis-ci.org/pvinis/colortools.svg?branch=master)](https://travis-ci.org/pvinis/colortools)

A list of shell scripts to print system colors and true colors in the terminal. Every time I looked for one of these scripts, I ended up finding another one, spending more time than I wanted. Now we have them all in one place. Like many other tools on the terminal, these scripts are not useful to everyone, but are really useful to some. Enjoy :)

## Install
	$ brew install pvinis/pvinis/colortools

## Usage
	$ colortools
	$ colortools-256

## List of tools

- **colortools-true**  
  Prints `TRUECOLOR` using a nice dark red true color.  
  ![colortools-true](/images/colortools-true.png?raw=true "colortools-true")  
  Thanks to [this](https://gist.github.com/XVilka/8346728) XVilka gist.

- **colortools-truezigzag**  
  Prints `/\/\/\/\/` using true colors for background.  
  ![colortools-truezigzag](/images/colortools-truezigzag.png?raw=true "colortools-truezigzag")  
  Thanks to [this](https://gist.github.com/XVilka/8346728) XVilka gist.

- **colortools-truebar**  
  Prints colorbars using true colors for background and foreground.  
  ![colortools-truebar](/images/colortools-truebar.png?raw=true "colortools-truebar")  
  Thanks to [this](https://github.com/JohnMorales/dotfiles/blob/master/colors/24-bit-color.sh) JohnMorales repo, and [this](https://github.com/gnachman/iTerm2/blob/master/tests/24-bit-color.sh) iTerm repo.

- **colortools-system-gyw**  
  Prints system colors as foreground and background, with normal and bold `gYW` text.  
  ![colortools-system-gyw](/images/colortools-system-gyw.png?raw=true "colortools-system-gyw")  
  Thanks to [this](https://raw.githubusercontent.com/mikker/dotfiles/master/bin/colortest.sh) mikker repo.

- **colortools-system**  
  Prints system colors as foreground and background, with normal and bold text.  
  ![colortools-system](/images/colortools-system.png?raw=true "colortools-system")  
  Thanks to [this](https://raw.githubusercontent.com/robertknight/konsole/master/tests/colortest.sh) robertknight repo.

- **colortools-system-blink**  
  Prints system colors as foreground and background, with normal, bold and blinking text.  
  ![colortools-system-blink](/images/colortools-system-blink.png?raw=true "colortools-system-blink")  
  Thanks to [this](https://raw.githubusercontent.com/robertknight/konsole/master/tests/colortest.sh) robertknight repo.

- **colortools-256**  
  Prints system colors, grayscale ramps and several color cubes using 256 colors for background and foreground.  
  ![colortools-256](/images/colortools-256.png?raw=true "colortools-256")  
  Thanks to [this](https://github.com/robertknight/konsole/blob/master/tests/color-spaces.pl) robertknight repo, and Todd Larason.
