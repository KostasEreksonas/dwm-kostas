# dwm-kostas

Custom build of suckless dynamic window manager for my Arch Linux install.

Table of Contents
=================
* [Installation](#Installation)
* [Keybindings](#Keybindings)
* [Applied Patches](#Applied-Patches)

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

# Applied Patches

* [Alpha](https://dwm.suckless.org/patches/alpha/)
* [Default Tag Apps](https://dwm.suckless.org/patches/default_tag_apps/)
* [Fullgaps](https://dwm.suckless.org/patches/fullgaps/)
* [Hide Vacant Tags](https://dwm.suckless.org/patches/hide_vacant_tags/)
* [Statuscmd](https://dwm.suckless.org/patches/statuscmd/)
* [Swallow](https://dwm.suckless.org/patches/swallow/)
* [Warp](https://dwm.suckless.org/patches/warp/)
