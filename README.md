# dwm-kostas

***Newpatch*** branch is used for applying new patches to `dwm` before merging them to the main branch. It's primary used as a fail-safe in case of errors.

Table of Contents
=================
* [dwm-kostas](#dwm-kostas)
* [My custom dwm build](#My-custom-dwm-build)
* [Patches that I have applied](#Patches-that-I-have-applied)
* [Keybindings](#Keybindings)
* [Installation](#Installation)

# My custom dwm build
Custom dwm build for my Linux install. I've decided to try out dynamic window manager and I will document my progress here.

# Patches that I have applied
* [Alpha](https://dwm.suckless.org/patches/alpha/) - for transparency;
* [Fullgaps](https://dwm.suckless.org/patches/fullgaps/) - for gaps between windows.
* [Fullscreen](https://dwm.suckless.org/patches/fullscreen/) - dwm fullscreen patch.
* [Warp](https://dwm.suckless.org/patches/warp/) - patch that warps mouse cursor to the center of the focused window.

# Keybindings
In this section I will present custom keybindings that I made for my build of _dynamic window manager_.

|		 Keybind		|				Function			|
|:---------------------:|:---------------------------------:|
|	Fn + Down arrow		|	Lower volume					|
|	Fn + Up arrow		|	Raise volume					|
|	Fn + Left arrow		|	Lower brightness				|
|	Fn + Right arrow	|	Raise brightness				|
|	PrintScreen			|	Take screenshot					|
|	Shift + PrintScreen |	Copy screenshot to clipboard	|
|	Mod + PrintScreen	|	Paste screenshot from clipboard	|
|	Mod + Pause			|	Lock screen						|
|	Mod + z				|	Extend displays					|
|	Mod + s				|	Open default app for active tag	|

# Installation

1. Clone this git repository:

`git clone https://github.com/KostasEreksonas/dwm-kostas.git`

2. Go to the folder cloned repository:

`cd dwm-kostas`

3. Build the package:

`make`

4. Run a clean install of this package with ***root*** privilleges:

`make clean install`

5. Done!
