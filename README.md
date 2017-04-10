# Arc-OSX-Icons

### Introduction

The icon collection consists of a modern free desktop icon theme pack whose design is based around the use of bold colours and simple geometric shapes to compose icons with pixel perfect rendering. 

##

### Why use this icon pack?

The reason behind this icon theme pack is to enable new users to easily install the preconfigured arc icon theme to look and feel consistent to how I intended OSX-Arc theme collection to look, having been asked a few times “how do I get my desktop looking like the screen shots?” I decided to remix and preconfigure this icon pack to enable new users to just extract it directly to their icons folder without having to configure the arc icon theme themselves and also it allowed me to pack all the recommended icon themes in one source.

##

![](https://github.com/LinxGem33/Arc-OSX-Icons/blob/master/arcscreen.png?raw=true)

##

### Packages

Distributions can now install the source code packages for easy installation of the icon theme collection the link to the releases page is below.

> [arc-osx-icon-theme](https://github.com/LinxGem33/Arc-OSX-Icons/releases)

##

### What's included in the pack?

The icon pack consists of four elements each element has been packaged to create a preconfigured theme pack,the contents of which can be seen listed below.

| Included Icons  | Icon feature  |
|---|---|
|  **Arc-OSX-P**  | light icon theme  |
|  **Arc-OSX-D**  | dark icon theme    |
|  **Paper**      | dependency |
|  **Paper-Mono-Dark** | dependency |


##

### Manual Installation

How To Install:

1. Download

2. Extract to /usr/share/icons
or ~/.icons (create it (in your home folder) if necessary);

3. Change via distribution specific tweak tool.

##
Installation via autotools: 

    git clone https://github.com/LinxGem33/Arc-OSX-Icons --depth 1 && cd Arc-OSX-Icons
    ./autogen.sh --prefix=/usr
    sudo make install

Alternatively you may copy the `src` folder to `~/.icons` or to `/usr/share/icons` for system-wide use.

### Uninstall

Run

    sudo make uninstall

from the same directory as this README resides in, or

    sudo rm -rf /usr/share/icons/src

## 

### Bugs

Bugs should be reported [here](https://github.com/LinxGem33/Arc-OSX-Icons/issues) on the Github issues page.

## 

### License & Terms ![](https://github.com/LinxGem33/Arc-OSX-Icons/blob/master/COPYING)

Arc-icon theme is available under the terms of the GPL-3.0 license See [`COPYING`](https://github.com/LinxGem33/Arc-OSX-Icons/blob/master/COPYING) for details.

> "[Paper Icons](https://github.com/snwh/paper-icon-theme)" by [Sam Hewitt](http://samuelhewitt.com/) is licensed under [CC-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/)
