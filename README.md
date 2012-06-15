# Ubuntu Ultimate Install Script

Install and configure archlinux has never been easier!

## Prerequisites

- You need to have Ubuntu already installed and rebooted
- Git
- A working internet connection
- Logged in as 'root'

## How to use

### With git
- Install git: `apt-get install git`
- get the script: `git clone git://github.com/helmuthdu/uui`
- run the script: `cd aui && ./uui`

### Without git
- get the script: ` wget --no-check-certificate https://github.com/helmuthdu/uui/tarball/master -O - | tar xz`
- run the script: `./uui`

## What does the script do?

- Install additional repositories
- System upgrade
- Create and configure new user
- Configure pacman package signing
- Install base system
- Install GPU Drivers
- Ensuring access to GIT through a firewall
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Games [HoN, World of Padman, Wesnoth...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure LAMP Server
- Many More...
