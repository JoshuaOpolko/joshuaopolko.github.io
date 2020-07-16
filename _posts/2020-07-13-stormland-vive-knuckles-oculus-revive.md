---
layout: page
title: Oculus Stormland on HTC Vive With Index Knuckles
subtitle: Get more out of your Vive (or HTC Vive Cosmos/Valve Index/Windows Mixed Reality) with Revive!

---
![](./assets/img/Stormland.png =100x20)
Are you the proud owner of an HTC Vive looking for new games? Tired of seeing the same old SteamVR titles month after month? Looking for quality entertainment but not sure where to find it? 

Look no further friend, you need [Oculus](https://www.oculus.com/experiences/rift/)! Many Oculus games can be [played](https://github.com/LibreVR/Revive/wiki/Compatibility-list) on Vive with the right software. [Stormland](https://www.oculus.com/stormland/?locale=en_US) for example is an epic adventure game created by [Insomniac Games](https://insomniac.games), the same folks who brought you [Ratchet and Clank](https://insomniac.games/game/ratchet-and-clank-ps4/)! 

Big names like this are needed in Virtual and Augmented Reality (known collectively as [XR](https://en.wikipedia.org/wiki/Extended_reality) so let’s jump in and take a look at running this Oculus title on a Vive.

#### You need Revive!
[Revive](https://github.com/LibreVR/Revive) integrates Oculus software with OpenXR to run Oculus games on your Vive.

Additionally, in case there are any issues with your Vive Wands, [Valve Index Controllers](https://www.valvesoftware.com/en/index/controllers) make for great replacements.

#### My System:  
* [Intel 8700 I7](https://ark.intel.com/content/www/us/en/ark/products/126686/intel-core-i7-8700-processor-12m-cache-up-to-4-60-ghz.html)
* 32 GB RAM 
* [Nvidia Geforce 1080ti](https://www.nvidia.com/en-sg/geforce/products/10series/geforce-gtx-1080-ti/)
* [SteamVR](https://store.steampowered.com/app/250820/SteamVR/)
* [Valve Index Controllers](https://www.valvesoftware.com/en/index/controllers)
* HTC Vive Headset 
* [BaseStation ver 1.0](https://www.vive.com/eu/accessory/base-station/)

#### Installation: 
1. Install Oculus and Revive by following the steps in the Installation section of their [github](https://github.com/LibreVR/Revive). 
2. Purchase and install [Stormland](https://www.oculus.com/experiences/rift/1360938750683878/?ranking_trace=117254459210015_1360938750683878_SKYLINEWEB_15sLveFiOUbKwuHmu) from the [Oculus Store](https://www.oculus.com/).

#### Configure Controllers: 
1. Control Bindings (Steam Workshop)
2. Controller Type (SteamVR)
3. Disable thumb-pad press binding

#### Optional (Can't Install): 
Some users encounter an Oculus bug that results in the inability to install titles purchased from [Oculus](https://www.oculus.com/experiences/rift/). This can be resolved by setting a different default location for your Oculus games. After doing this the games will install and run normally. 

Ensure that the location you are saving your downloaded Oculus games to is not _C:\Program Files\Oculus_. 

To set a new location for your saved games, follow the steps in this [link](https://www.windowscentral.com/how-change-where-you-save-oculus-rift-games-your-pc).

Create a new folder for the game location or just put it in Documents or wherever you want other than _C:\Program Files\Oculus_.

#### Optional (Restart your progress):  
Stormland saves your progress locally and in the cloud. There is a single save file that tracks your progress and does not allow for multiple saves or multiple users. 

In case you want to restart the game or have another person start their own progress, there really isn't a proper way to do it in the game. To get around this, the local save files can be deleted, renamed or moved in order to start the game over. Ordinarly your progress and abilities depend on the availability of your save files so only complete this step is you are happy to lose all your progress in Stormland.

1. Go offline with the computer Steam is installed on. Either disable the Wifi, disable Ethernet or disconnect pull the cable.
2. Launch File Explorer and go to _C:\Users\your_username\AppData\Local\Oculus\AppData\139725073420658\3257792424300278\cloud\data_

3. Delete or move the two save files in this location:
* stormland_gamedata_071220.save
* stormland_userprefs.save_ from the location below:

Your files and folders may contain different numbers than the examples on this page.

