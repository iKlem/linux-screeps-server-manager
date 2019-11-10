# linux-screeps-server-manager
###### Version: 0.8.1

# This repository is now archived & deprecated. Please use [screeps-launcher](https://github.com/screepers/screeps-launcher) instead of this script for your server maintenance

### Description
Screeps server manager for Linux with auto installer and easy-to-use script.  
The manager has been tested on :
* Debian 8 Jessie (64 bits)
* Ubuntu GNOME 15.04 (64 bits)
* Manjaro Linux 16.10 (GNOME version - 64 bits)  

*Feel free to notify me if the manager doesn't work properly on specific distributions.*

### Features
* __Only 1 server at the moment__
* Easy to use
* Automatic installer
* Start & Stop the server
* Access to the Screeps CLI
* Pretty colors and prompt :3

### Dependencies
*N.B.: You can install these dependencies with the `./screepsserver install-deps` command*
* Python 2
* build-essential (Debian / Ubuntu)
* tmux
* NodeJS 6

### Installation
* Download or clone this repository : `git clone https://github.com/iKlem/linux-screeps-server-manager.git NAME_FOR_SERVER`
* Go to your new folder and set the execute right on the script : `chmod +x screepsserver`
* Launch the installer with `./screepsserver install` OR `./screepsserver i`
* Follow the instructions when needed during installation

![Install.GIF](https://cdelalande.fr/files/install-2.gif)

### After Installation
* If you run the script without sudo or root permissions, you have to install the dependencies.
* Don't forget to configure the .screeprc with your changes
* You can launch `./screepsserver help` for a list of available commands

### Problem or ideas ?
If the script doesn't work, the colors aren't pretty or you want to share some ideas you can create an issue.  
Add in the title of your issue the [IDEA] or [BUG] tag, this will help me :)  

### Credits
* [akuukis](https://screeps.com/a/#!/profile/akuukis) & [coteyr](https://screeps.com/a/#!/profile/coteyr) for sharing their lines of scripts _(on old version)_.
* The dev @ [Screeps](https://screeps.com) for making a great game :D
* The [Linux Game Server Managers](https://github.com/GameServerManagers/LinuxGSM) for the inspiration
