# linux-screeps-server-manager
Screeps server manager for Linux with auto installer and easy-to-use script

## /!\ This file has been tested on Debian 8 Jessie (64 bits) /!\

### Features
* __Only 1 server at the moment__
* Easy to use
* Automatic installer
* Start & Stop the server
* Access to the Screeps CLI
* Pretty colors :3

### Dependencies
* unzip
* git
* tmux
* build-essential

### Installation
* Create a folder on your server (ex: `screepsserver` or `screeps`)
* Connect with your Steam account and download the steamworks sdk [HERE](https://partner.steamgames.com/)
* Put the .zip in your folder
* Download the `screepsserver` in your folder
* Set the execute right on the script : `chmod +x screepsserver`
* And launch `./screepsserver install` (with OR without sudo)

### After Installation
* If you run the script without sudo or root permissions, you have to install the dependencies.
* Don't forget to change the .screeprc with your configuration
* You can launch `./screepsserver help` for a list of available commands

### Problem or ideas ?
If the script doesn't work, the colors aren't pretty or you want to share some ideas you can create an issue.  
Add in the title of your issue the [IDEA] or [BUG] tag, this will help me :)

### Credits
* [akuukis](https://screeps.com/a/#!/profile/akuukis) & [coteyr](https://screeps.com/a/#!/profile/coteyr) for sharing their lines of scripts.
* The dev @ [Screeps](https://screeps.com) for making a great game :D
* The [Linux Game Server Managers](https://github.com/GameServerManagers/LinuxGSM) for the inspiration
