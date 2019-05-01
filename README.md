# Arc theme for Enlightenment
Original arc design from [horst3180](https://github.com/horst3180/arc-theme), Enlightenment theme by [LeBlue](https://github.com/LeBlue/enlightenment-arc-theme), modified by [Okra](https://github.com/okratitan/enlightenment-arc-theme), [LightDot](https://github.com/lightdot/enlightenment-arc-theme) and others.

There are still widgets and e-modules missing, an overview is shown below.


![A screenshot of the Arc-Darker theme](https://github.com/lightdot/enlightenment-arc-theme/blob/master/screenshots/shot.png)

### Install

To install just save the latest [arc-dark.edj](https://github.com/lightdot/enlightenment-arc-theme/releases/latest/download/arc-dark.edj) and/or [arc.edj](https://github.com/lightdot/enlightenment-arc-theme/releases/latest/download/arc.edj) to the themes directory `$HOME/.elementary/themes/` of a user or, to install system-wide, run `make install` after building the theme from the source.

#### Installing on Arch Linux

Packages for Arch Linux are [available in AUR](https://aur.archlinux.org/packages/?K=enlightenment-arc-theme&do_Search=Go).

### Building from source

To build the arc themes you need will need
* `edje_cc`
* `make`

To build:

```
make orig-theme
make
```

### Rebuilding or adding assets

You will need
* `inkscape`
* `optipng`

All assets are already exported as .png and included. Inkscape and optipng are used to export the png-assets from the .svg source if you want to add or reexport the images. To reexport type:

`make assets`

## Overview components

### Elementary

* \[ ] access
* \[ ] actionslider
* \[X] bg
* \[ ] border
* \[ ] bubble
* \[X] button
* \[ ] calendar
* \[X] check
* \[ ] clock
* \[ ] colorsel
* \[ ] colorclass
* \[ ] conform
* \[X] ctxpopup
* \[ ] cursor
* \[ ] dayselector
* \[ ] datetime
* \[ ] diskselector
* \[X] entry
* \[ ] fileselector
* \[ ] flipselector
* \[X] focus
* \[X] frame
* \[X] gengrid
* \[X] genlist
* \[X] hover
* \[ ] icon
* \[ ] index
* \[X] inwin
* \[X] label
* \[ ] layout
* \[X] list
* \[ ] map
* \[X] menu
* \[ ] multibuttonentry
* \[X] naviframe
* \[X] notify
* \[ ] panel
* \[X] panes
* \[ ] photo
* \[ ] photocam
* \[ ] player
* \[X] popup
* \[ ] pointer
* \[ ] progress
* \[X] radio
* \[X] scroller
* \[X] segment_control
* \[X] separator
* \[X] slider
* \[ ] slideshow
* \[X] spinner
* \[ ] thumb
* \[X] toolbar
* \[ ] tooltip
* \[ ] video
* \[ ] win

### Enlightenment widgets

* \[X] button
* \[X] check
* \[ ] colorwell
* \[ ] cslider
* \[ ] entry
* \[X] deskpreview
* \[X] fileman
* \[ ] fontpreview
* \[X] frame
* \[X] ilist
* \[X] label
* \[X] menu
* \[X] preview
* \[X] radio
* \[X] scrollframe
* \[X] slider
* \[ ] spectrum
* \[X] textblock
* \[X] toolbar

### Enlightenment desktop general

* \[X] about-e
* \[X] about-theme
* \[X] background
* \[X] border
* \[X] bryce
* \[ ] bryce_editor
* \[ ] comp
* \[ ] comp_compat
* \[ ] comp_effects
* \[X] conf
* \[ ] desklock
* \[X] deskmirror
* \[X] dialog
* \[X] gadman
* \[ ] init
* \[ ] pointer
* \[X] shelf
* \[X] sys
* \[X] syscon
* \[ ] transitions
* \[ ] wallpaper
* \[X] winlist
* \[ ] wizard

### Enlightenment modules

* \[ ] appmenu
* \[ ] backlight
* \[x] battery
* \[ ] bluez4
* \[ ] clock
* \[ ] colors
* \[ ] connman
* \[ ] cpufreq
* \[ ] edgebindings
* \[ ] evrything
* \[ ] ibar-ibox
* \[ ] illume
* \[ ] luncher
* \[ ] music_control
* \[ ] mixer
* \[X] notification
* \[ ] packagekit
* \[X] pager
* \[X] pager16
* \[ ] randr
* \[X] start
* \[ ] sysinfo and gadgets
* \[ ] systray
* \[X] tasks
* \[ ] temperature
* \[ ] time
* \[ ] wireless
* \[ ] xkbswitch

### icons

* \[X] border-icons
* \[X] border-mixer
* \[ ] icons
