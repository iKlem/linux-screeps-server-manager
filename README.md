# linux-screeps-server-manager
Screeps server manager for Linux with auto installer and easy-to-use script.  
__This file has been tested on Debian 8 Jessie (64 bits)__

###### Version: 0.2.1
### Features
* __Only 1 server at the moment__
* Easy to use
* Automatic installer
* Start & Stop the server
* Access to the Screeps CLI
* Pretty colors and prompt :3

### Dependencies
* tmux
* NodeJS (>= 4)
* npm
* node-gyp

### Installation
* Download or clone this repository : `git clone https://github.com/iKlem/linux-screeps-server-manager.git NAME_FOR_SERVER`
* Go to your new folder and set the execute right on the script : `chmod +x screepsserver`
* Launch the installer with `./screepsserver install` OR `./screepsserver i` (with OR without sudo)
* Follow the instructions when needed during installation

### After Installation
* If you run the script without sudo or root permissions, you have to install the dependencies.
* Don't forget to configure the .screeprc with your changes
* You can launch `./screepsserver help` for a list of available commands

### Problem or ideas ?
If the script doesn't work, the colors aren't pretty or you want to share some ideas you can create an issue.  
Add in the title of your issue the [IDEA] or [BUG] tag, this will help me :)

### Credits
* [akuukis](https://screeps.com/a/#!/profile/akuukis) & [coteyr](https://screeps.com/a/#!/profile/coteyr) for sharing their lines of scripts.
* The dev @ [Screeps](https://screeps.com) for making a great game :D
* The [Linux Game Server Managers](https://github.com/GameServerManagers/LinuxGSM) for the inspiration

