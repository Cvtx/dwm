# dwm - dynamic window manager

dwm is an extremely fast, small, and dynamic window manager for X.
dwm is available at [suckless.org](https://suckless.org).

This is my personal dwm build.

# Applied patches
+ attachside
+ restartsig
+ hide vacant tags
+ swallow

# Requirements

To build dwm you need the Xlib header files.

# Installation

	git clone https://github.com/Cvtx/dwm
	cd dwm    
    sudo make clean install

\[Optional\] Edit config.mk to match your preferences.

# Running dwm

Open your .xinitrc file and add the following line to it.	

    exec dwm	

This will start dwm using startx.

# Configuration
The configuration of dwm is done by creating a custom config.h
and (re)compiling the source code.