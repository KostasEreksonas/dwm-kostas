# dwm-kostas

Custom build of suckless dynamic window manager for my Arch Linux install.

Table of Contents
=================
* [Applied Patches](#Applied-Patches)
* [Keybindings](#Keybindings)
* [Installation](#Installation)

# Applied Patches
* [Alpha](https://dwm.suckless.org/patches/alpha/) - for transparency.
* [Default Tag Apps](https://dwm.suckless.org/patches/default_tag_apps/) - dedicate each tag for certain tasks.
* [Fullgaps](https://dwm.suckless.org/patches/fullgaps/) - for gaps between windows.
* [Fullscreen](https://dwm.suckless.org/patches/fullscreen/) - dwm fullscreen patch.
* [Hide Vacant Tags](https://dwm.suckless.org/patches/hide_vacant_tags/) - prevent dwm from drawing vacant tags.
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
