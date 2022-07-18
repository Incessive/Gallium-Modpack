# Gallium-Modpack
Balanced magic/tech/create focused modpack. (somewhat)

# Overview

## Setup

### To make the installation process easier, I recommend using cubeLauncher: https://github.com/o7q/cubeLauncher
After downloading the modpack from this repository, extract the archive and drop & drag the contents onto the cubeLauncher window.\
To configure a world: Insert the "paraglider-server.toml" file into the serverconfig folder within your world save file.

## Multiplayer Setup:

After downloading the modpack from this repository, inside the ".cube" folder run the forge .jar executable installer.\
Select install server and choose an empty directory.\
Drag the mods folder into the server directory.\
There are two client-only mods that cannot be ran on a server. 

Ensure that both of these mods are removed from the server mods folder before starting:\
~ 3dskinlayers-forge-1.4.6-mc1.18.2.jar\
~ NekosEnchantedBooks-1.18.2-1.7.0.jar\
(If you do not remove these mods it will result in a crash.)\

Start the server and then stop the server after the world generates.\
After generating the world, insert the "paraglider-server.toml" file into the serverconfig folder within the server world save file.