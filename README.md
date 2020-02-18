# Andres's build of st - the simple (suckless) terminal

The [suckless terminal (st)](https://st.suckless.org/) with some additional features that make's it awesome.
Based on version 0.8.2.

## Features
+ Desktop entry for desktop environments

## Included st patches

+ [newterm](https://st.suckless.org/patches/newterm/)
+ [alpha](https://st.suckless.org/patches/alpha/)
+ [alpha focus highlight](https://st.suckless.org/patches/alpha_focus_highlight/)
+ [scrollback](https://st.suckless.org/patches/scrollback/)
+ [solarized](https://st.suckless.org/patches/solarized/)

## Requirements
In order to build st you need the Xlib header files.

## Installation

St is installed into the ```/usr/local``` namespace by default. You can change that in the config.mk file.

```
git clone https://github.com/andresemartinez/st.git
cd st
sudo make install
```
## Customization
Aditional customazation can be done in the config.h file. This requires re-compiling.
