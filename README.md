# rofi-power-menu
> Script to shutdown, reboot or log out on minimalist Linux distributions. 

## Features
1. Using rofi to display power management menu
2. Script can be easily translated by modifying `lang_*` variables

## Dependencies
Before you use this application, you need to install the following dependencies - either by using your package manager (like apt, pacman) or by manually compiling source codes.

- rofi (for displaying menus)
- libnotify (for sending desktop notifications)

## Important information
This script assumes, that your minimalist Linux installation uses dwm or i3 as window manager and light-locker as your screen locking utility. If you are using something else, there is nothing stopping you from modifying the script and adding the commands that your installation uses to lock screen or log out.

## Usage
1. Install required dependecies.
2. Clone this repo
3. Copy rofi-power-manu.sh to any directory in your $PATH environmental variable
4. Give rofi-power-menu.sh execution rights by running `chmod a+x rofi-power-menu.sh`
5. Run rofi-power-menu.sh to open power management menu

## Technologies used
This script has been written in pure POSIX-compliant Linux shell (`/bin/sh`). Script should run on any Linux distribution where all required dependencies can be installed.
