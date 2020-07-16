---
layout: page
title: Oculus Stormland on HTC Vive With Index Knuckles
subtitle: Get more out of your Vive (or HTC Vive Cosmos/Valve Index/Windows Mixed Reality) with Revive!

---
![Stormland](https://github.com/JoshuaOpolko/joshuaopolko.github.io/blob/master/assets/img/Stormland.png "Stormland rocks!")
[![Foo](http://www.google.com.au/images/nav_logo7.png)](http://google.com.au/)
[![Foo](https://github.com/JoshuaOpolko/joshuaopolko.github.io/blob/master/assets/img/Stormland.png)](http://google.com.au/)
Are you the proud owner of an HTC Vive looking for new games? Tired of seeing the same old SteamVR titles month after month? Looking for quality entertainment but not sure where to find it? 

Look no further friend, you need [Oculus](https://www.oculus.com/experiences/rift/)! Many Oculus games can be [played](https://github.com/LibreVR/Revive/wiki/Compatibility-list) on Vive with the right software. [Stormland](https://www.oculus.com/stormland/?locale=en_US) for example is an epic adventure game created by [Insomniac Games](https://insomniac.games), the same folks who brought you [Ratchet and Clank](https://insomniac.games/game/ratchet-and-clank-ps4/)! 

Big names like this are needed in Virtual and Augmented Reality (known collectively as [XR](https://en.wikipedia.org/wiki/Extended_reality) so let’s jump in and take a look at running this Oculus title on a Vive.

#### Your Vive needs a Revive!
[Revive](https://github.com/LibreVR/Revive/releases) allows you to play Oculus games on your [HTC Vive](https://www.vive.com/ca/accessory/controller/) as well as other systems. You can use your existing [Vive Wands](https://www.vive.com/ca/accessory/controller/) or any other controllers supported by [SteamVR](https://store.steampowered.com/app/250820/SteamVR/). The steps below show how to set up [Valve Index Controllers](https://www.valvesoftware.com/en/index/controllers) for use with Vive and the Oculus store. Revive also allows you to play Oculus games on your [HTC Vive Cosmos](https://www.vive.com/eu/product/vive-cosmos/features/), [Valve Index](https://www.valvesoftware.com/en/index/headset), [Windows Mixed Reality](https://www.microsoft.com/en-us/mixed-reality/windows-mixed-reality) systems and more.

Don’t forget to check the [compatibility list](https://github.com/LibreVR/Revive/wiki/Compatibility-list) _before_ making your purchase! Ensure the game you have your eye on works in Revive! At the time of this writing Stormland is listed as Working – Stormland fix. It perfectly out-of-the-box requiring only the controller customizations below. Performance is great. Looks the same as native SteamVR games for the most part. 

Having said that, Revive is not officially supported or endorsed by Oculus so they could decide to block Revive from working at any time. This means you assume the risk of all of the Oculus games you’ve purchase disappearing from Revive at any time... Oh well, such is the life of a jailbreaker/modder/experimenter/enthusiast/hobbiest/fan/open-source aficionado/pirate/cracker/hacker/anyone with curiosity/etc. Plus, you didn’t buy that beast of a VR machine just to play the equivalent of browser flash-games on it, did you? Did you?!? For those of us willing to take the risk there’s Revive. Let’s jump in!

#### My System for comparison:  
* [Intel 8700 I7](https://ark.intel.com/content/www/us/en/ark/products/126686/intel-core-i7-8700-processor-12m-cache-up-to-4-60-ghz.html)
* 32 GB RAM 
* [Nvidia Geforce 1080ti](https://www.nvidia.com/en-sg/geforce/products/10series/geforce-gtx-1080-ti/)
* [SteamVR](https://store.steampowered.com/app/250820/SteamVR/)
* [Valve Index Controllers](https://www.valvesoftware.com/en/index/controllers)
* HTC Vive Headset 
* [BaseStation ver 1.0](https://www.vive.com/eu/accessory/base-station/)

How to Install and Configure Revive for HTC Vive:
1.	Install Oculus Rift S Software by clicking the Download Software button from https://www.oculus.com/setup/
 
2.	Follow the installation default options until you get to the screen instructing you to connect your headset. Do not complete this step.
3.	Click the Skip Setup button. 
 
For Vive setups you will not be configuring the headset/hardware. The hardware setup step is left incomplete indefinitely. Proceed to the next step.
4.	Install the latest version of the ReviveInstaller.exe from github (the one with the highest version number – v2.1.1 as of July 2020)
 
5.	Launch Oculus and purchase Stormland
6.	Launch SteamVR and put on your headset.
7.	Open the SteamVR dashboard and click the new Revive button.
8.	Launch Stormland from the menu that appears. You can also launch it from the Steam menu.
 
So the game is working but you can’t click the Menu button as it hasn’t been customized for your Index Knuckles yet. It is still expecting Oculus controllers.
 
By default there is no way to press the Menu button with the Valve Index Controllers.
Press the System button on the Knuckles and select Show Old Binding UI
 
Select Stormland on Oculus
On the screen entitled “Change Bindings For Stormland on Oculus” you can select a pre-programmed binding. A binding is basically just a list of which actions go with which buttons. We can use the Official Binding for Revive/Index as a template and then tweak it to fix the A buttons (further down this page). 
 
How to Change Controller Bindings Valve Index (Knuckles) Controllers for Stormland: 
a.	Identify the Official Bindings section.
b.	Locate Revive for Index published by the developer. 
c.	Activate Revive for Index to set them as your Current Binding. 
Try running the game now to see if your controllers are working as you’d like. You’ll know immediately if it works as you will be now able to click the Menu button above. In my case these bindings did not work. Left A button did not bring up the Pause Menu and the Right A button was not set as Jump. 
If your A buttons are not working as you’d like click Edit (4) on your new Current Binding. This way you can manually assign the left and right A buttons.
 
Once you’ve clicked Edit you’ll see all buttons and bindings. The only two I’m concerned with here are the Left and Right A buttons. Each button can be edited by clicking the little pencil icon that appears when you point at the text in each box. 
 
After clicking the Edit (pencil icon) for the button you are re-assigning, you can assign the function you want.  Remember to disable Mirror Mode in the middle of the screen to set different controls for right and left controllers. We will do this to make the Left A activate the Pause Menu and the Right A to be the Jump button. The Actions you can apply to the button can be seen in the picture below:
 
Edit the button assignments for both A buttons to select the accompanying function for each. Valve Index buttons are so full of sensors that they have different settings for Touching the button versus Clicking it. We only want to change the Click behavior although obviously you can set the touch to anything you’d like. I left mine as they were.
After you’ve set the buttons correctly the button assignments should look like this:
 
Ensure the A buttons have been set as follows:
1.	Left A Button: Click = Menu button
2.	Right A Button: Click = A/X press
3.	Save Personal Binding
Click the Back button in the top left corner until you are back in the game. 
Try the buttons, Left A should now open the Pause Menu and Right A should make you jump. Depending on where you are in the game, it may not be possible to jump but you will see an electric field flash around you instead. This is fine, the button is working properly and will make you Jump again when you have left the base.
Disable thumb-pad press binding - By default, the Index Thumb Pads are assigned to open the Pause Menu. This becomes frustrating in-game when you accidentally press the pads which are located so conveniently under each thumb. The popup menu totally interrupts whatever you were doing, so it’s a good idea to disable the thumb-pad menu option. This can be disabled in-game as follows:
There you have it. All set to enjoy some sweet Oculus goodness on your Vive. Do it for yourself. Do it for the children. Do it for the Zuck who obviously sees into the future and wants you to be a part of it! Just look how happy it makes him when people use his stuff!
 
“In the Land of the Blind the One-Eyed Man is King” 
some guy

Potential Issues:
Issue: Oculus Games Won’t Install – as soon as I bought Stormland I started the download. The download completed but when I clicked the “Install” button nothing happened. This is what happens when your Oculus games are saved at C:\Program Files\Oculus\Software (or anywhere in the C:\Program Files\Oculus folder).
For some reason Oculus doesn’t like it’s games to be within it’s own Program Files folder. Easy enough to change, simply put the games anywhere else, create a new folder wherever you have space and use this new folder as default location for Oculus games. 
To set a new location for your saved games, follow the steps below:
1.	Launch the Oculus app from the Start menu, taskbar, or desktop.
2.	Click Settings.
3.	Click General.
4.	Click Edit in the Library Locations section.
 
5.	Click Add Location.
 
6.	Choose a new library location. You can use any folder you’d like, you can also create a new folder by right-clicking the background in the Select Folder window. Once created, you can select the new folder for the new location by double-clicking it and clicking Select Folder.
 
7.	Double-click your new or chosen folder and click Select Folder.
While you are in the settings, it is a good idea to set the new location as the default From the same menu as above (Settings/General)
1.	Identify the new location
2.	Click the elipses menu button
3.	Select Make Default
 
Now that your game file location is no longer C:\Program Files\Oculus\Software you will be able to install & play Oculus games. Woohoo! You made it! Give Stormland a try.
Also, in case of further issues there is a Revive wiki
If you’re really stuck or if you love Revive so much you simply must tell the developers and community, there’s a Revive Discord too.

Potential Issues:
Issue: Can’t restart your progress - Stormland doesn’t really provide an option for restarting your progress. It saves your game locally at whatever point you’ve reached and syncs this with your cloud save. You can’t just restart the game and choose a new save. This means multiple players have to share the same progress and isn’t ideal in cases where you have multiple people that want to start their own progress. As a workaround you have to delete or move your local saves, go offline, create new ones and then go back online to sync them with the cloud saves. This effectively over-writes your previous progress. 
Progress and preferences are kept in two files locally which are synchronized with your cloud saves. Two files track your progress and preferences. These files can be moved, copied or renamed to reset progress to start a new game.
In case you want to restart the game or have another person start their own progress, There really isn’t a proper way to restart Stormland in-game, so that a player can start from the beginning of the game. To get around this, the local save files below can be deleted, renamed or moved. Only complete these step is you want to lose your progress and settings in Stormland.
1.	Go offline with the computer Steam is installed on. Disable the Wifi or disconnect Ethernet – make sure you’re offline.
2.	Launch File Explorer and go to C:\Users\your_username\AppData\Local\Oculus\AppData\139725073420658\3257792424300278\cloud\data
3.	Delete, rename or move the two save files in this location:
o	stormland_gamedata_071220.save
o	stormland_userprefs.save 
Your files and folders may contain different numbers than the examples on this page. These files can be saved if you want to keep the progress stored in them. You can always copy them back into the data folder.
If you don’t see the appdata folder you can enable it with the steps below:
1.	Launch File Explorer
2.	In the File Explorer click View then Options and then Change Folder and Search Options

 

3.	In the next window that pops up select View and then down below in Advance Settings ensure “Show hidden files, folders and drives” is checked.
 
4.	Click OK
You will now see the the appdata folder in File Explorer. Go ahead and click through it until you are at the location below:
C:\Users\your_username\AppData\Local\Oculus\AppData\139725073420658\3257792424300278\cloud\data
1.	From there you can delete or rename the files contained in the folder. Your computer should still be offline at this point or it will simply retrieve your cloud saves and restore them to this location. To avoid this, launch Stormland while offline and begin the game. This means setting up dominant hand, etc and actually starting the level. This will create two new save and preference files. Once these have been created (you will see them again in C:\Users\your_username\AppData\Local\Oculus\AppData\139725073420658\3257792424300278\cloud\data) you can exit the game and go online again. When you next launch the game it will overwrite the cloud saves with the newly created files so your ‘progress restart’ will be replace the cloud saves. You are supposed to get a warning from Steam asking if you’d like to overwrite the cloud saves or the local saves but I did not get this alert. Instead SteamVR just loaded the new local save/pref files and used them to overwrite my cloud progress. This is what I wanted in t his case but be aware you can overwrite cloud saves easily and potentially lose your progress by following these steps.
Finally, you are all set! Fire up Stormland and experience the goodness of Oculus. Personally I think they should officially support Revive as ti gives Vive owners great exposure to Oculus software and makes people like me much more likely to consider buying Oculus hardware in the future. Also, Oculus publicly supports OpenXR. Other members include AMD, Apple, Epic Games, Google, Huawei, Intel, Nvidia, Qualcomm, Samsung, Sony, Valve, acer, Alibaba, Amazon, Broadcom, Facebook, EA, Hitachi, HP, HTC, Nintendo, Nokia, Panasonic, Red Hat, Unity, VMWare and MANY more! Personally I’d say that the future of VR/AR/XR is looking extremely promising! Hopefully this means that cross-platform interoperability is the plan for the future and we will be able to share software across platforms like this even more going forward. 

Thanks,

Josh

