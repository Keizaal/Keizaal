Current version: 01/09/21 3.4.1.2

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/keizaal/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/keizaal/badge.json)

# Installation Guide

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Keizaal%20Banner.png)

# What is Keizaal?

Keizaal is a simple modlist that seeks to enhance and expand on Skyrim without compromising Bethesda’s original vision that we all fell in love with back in 2011.  

1.  This modlist is lite and intends to maintain the Vanilla feel. A lot of the time modlists can become ridiculously huge and bloated, but this modlist wants to be nice and lean. Less is more. 
2.  Immersion is paramount. I'm a lore buff and immersion is very important to me. If a mod is not lore accurate or takes me out of the game in any way it will be excluded. Consistency also falls into this category, if a mod has a completely different aesthetic from Vanilla or any of my other mods then it will probably not be included.
3.  Mods must have decent longevity. This modlist wants to be somewhat relevant, in theory, forever.
4.  Stability is the most important thing. This rule basically supersedes all the above. If a mod introduces major stability concerns it will be quickly cut.

You can find a full list of the mods included in Keizaal [here](https://modwat.ch/u/Keizaal/). If you're still curious about what exactly Keizaal has in store for you, have a look at the overview [here](https://www.wabbajack.org/#/modlists/info?machineURL=keizaal).

# Table of Contents
- [Setup and Information](#setup-and-information)
- [Clean Install](#clean-install)
  - [Reinstalling Skyrim](#reinstalling-skyrim)
  - [Creation Club Update Protection](#creation-club-update-protection)
- [Keizaal Installation](#keizaal-installation)
  - [Installing the ENB (Optional)](#installing-the-enb-binaries-optional)
- [Playing Keizaal](#playing-keizaal)
  - [Optional Mods](#optional-mods)
  - [Mod Notes](#mod-notes)
  - [Mod Configuration Menu and .inis](#mod-configuration-menus-and-inis)
  - [Updating](#updating)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

## Setup and Information

This modlist takes up 200GB of hard drive space and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance, but a standard hard disk drive will suffice.

Install the latest version of Wabbajack from its [GitHub page](https://github.com/wabbajack-tools/wabbajack/releases).

Create a new folder called “Wabbajack” in the root of your main drive, the default is (C:). Extract Wabbjack.exe into this folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Installing%20Wabbajack.png)

This modlist was developed on a computer running [these specs](https://pcpartpicker.com/list/Xg7trr), on this system a stable and consistent 50 - 60 FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

### Clean Install

To completely reinstall Skyrim, it is advised that you use the [Skyrim Shredder](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=113028&game_id=1704) tool to completely delete the game. It will remove Skyrim and data related to it, but not the modlist.

### Reinstalling Skyrim

Open Steam and ensure that Skyrim is uninstalled through on it.

Reinstall Skyrim in the root of your main drive, the default is (C:). **It is not recommended to install Skyrim in your Program Files folder**.

Run the Skyrim: Special Edition launcher through Steam and let it detect your settings, then close the launcher. **This is only necessary once**.

### Creation Club Update Protection

Every time the Creation Club releases new content SKSE breaks. A fixed version of SKSE usually releases fast, but to ensure your game isn’t broken for a few days follow these steps:

1.  Open your Steam Library
2.  Find The Elder Scrolls V: Skyrim Special Edition and open the properties
3.  Click Properties
4.  Click the Updates tab
5.  Under the Automatic Updates section, select “Only update the game when I launch it”

## Keizaal Installation

Create a new folder called “Keizaal” in the root of your main drive, the default is (C:).

Open Wabbajack.exe, it should be in the Wabbajack folder in the root of your main drive.

Select the Keizaal modlist from the Wabbajack UI.

Once the installation window opens ensure that the “Installation Location” matches the Keizaal folder you just created (default should be C:\Keizaal\). The download location should populate automatically

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Installing%20Keizaal.png)

When you’re ready press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When the installation is done the left panel should say “Installation Complete '' at the button. At this time it is safe to close Wabbajack.

### Installing the ENB Binaries (Optional)

If you have an older or less powerful machine you may skip this step.

[Click here to go to enbdev.com.](http://enbdev.com/download_mod_tesskyrimse.htm)

Download the most recent version of the ENB binaries. Once the archive is downloaded, open it and open the “WrapperVersion” folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Installing%20ENB.png)

Extract everything in “WrapperVersion” to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe).

Keizaal comes with its own prepackaged ENB preset. If, for whatever reason, you don't want to use this prepackaged preset I *urge* you to at least use an ENB that doesn't break imagespace modifiers. I believe any ENB that breaks imagespace modifiers is automatically bad, no matter how pretty it may look.

## Playing Keizaal

Navigate to your Keizaal installation folder (default is C:\Keizaal\) and open the “Game Folder Files” folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Installing%20Game%20Folder%20Files.png)

Extract everything in it to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe). Keizaal is ready to play!

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Optional Mods

There are a handful of mods that I have included that are disabled by default. These mods aren’t part of the main Keizaal package and are mainly made up of mods that rely on Creation Club content in order to function. If you choose to activate an optional mod, be sure to move the mod's plugin (on the right pane of MO2) **above all** of the plugins with the "Keizaal" prefix, unless otherwise instructed in the mod's notes.

I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

Here is an example of one such note:

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Notes.png)

### Mod Configuration Menus and .inis

All of the MCM menus and .inis in Keizaal have been pre-configured to my recommended settings. The only thing you need to do when you start a new game is play.

### Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the overwrite existing Modlist button.

## Troubleshooting

**Wabbajack throws an error after authorizing through Nexus.**

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

**A mod fails to install.**

If Wabbajack fails to download a mod, try downloading them manually. Place these in your downloads folder where the other Wabbajack downloads are. Do not extract them. Note that some of these are big files and may take a while.

- [Bearnado Markarth Mashup](https://drive.google.com/uc?export=download&id=1D139AzjXYuiTMjboFa_gmT3mXrmsR0zG)
- Skyrim Realistic Overhaul
  - [Part One](https://www.moddb.com/downloads/start/116891?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads)
  - [Part Two](https://www.moddb.com/downloads/start/116927?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads)
  - [Part Three](https://www.moddb.com/downloads/start/116934?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads)
  - [1.8 Update](https://www.moddb.com/downloads/start/139489?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads)
- [WiZkiD Candle Flames](https://drive.google.com/uc?export=download&id=1ZA8r-McnBcxjCdUBnA4wRW1jZzhHciO2)
- [WiZkiD DynDOLOD Bright Waterfalls Meshes Fix](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD DynDOLOD Ultra Detailed Ships LOD](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD High Poly Alchemy Table](https://drive.google.com/uc?export=download&id=1Z8oJLvXwwXDdQULW_7RW1NG8N6l3H17B)
- [WiZkiD Sky Textures](https://drive.google.com/uc?export=download&id=1lsg11a3blf825KVZsKaevKB5-khmaP9l)
- [WiZkiD Storm Lighting Improved Thunder Sounds](https://drive.google.com/uc?export=download&id=1Fg-w1TQgC7WIYOSsOXNFd02egFgn6u3R)
- [WiZkiD Tree Selection](https://drive.google.com/uc?export=download&id=1BhxtOpeaEHEkli6QKLrhi1bQyNYIdgXG)
- [WiZkiD Unique Flowers and Plants](https://drive.google.com/uc?export=download&id=1_KjVdxNr5v08uU3xudaNXaRWwyTfe38M)
- [WiZkiD Variety](https://drive.google.com/uc?export=download&id=1g5yCvLG0Fw-WvPOzEDNMaqBdTwT6eg65)
- [WiZkiD Water Wells with Real Water](https://drive.google.com/uc?export=download&id=1wnWsbLND5rxgJV-keeJG4Ev33XkROugI)
- [Telvanni Reborn](https://www.dl.dropboxusercontent.com/s/3vr91f0l2ju1fyu/Telvanni%20Reborn-34601-1.7z?dl=0)

**ModOrganizer.exe throws an error when trying to launch.**

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

**Skyrim can't get past character creation without crashing.**

Change your Windows regional format to "English (United States)", as seem below.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/Images/Troubleshooting%20Regional%20Format.png)

**Keizaal is acting strangely after automatically sorting the load order.**

**NEVER USE LOOT OR MO2 TO AUTOMATICALLY SORT YOUR LOAD ORDER!** Keizaal's plugins have been carefully sorted manually to ensure that everything works as intended. Sorting the load order using an automatic tool **will** cause issues. If you have used an automated program to sort your load order, you forfiet all support I would normally provide until you restore your load order to Keizaal's default. You should be able to find a backup of the lists' load order in Profiles/Keizaal inside your MO2 installation folder.

Contact Pierre Despereaux on either the [Wabbajack](https://discordapp.com/invite/wabbajack) or [Keizaal](https://discord.gg/eYZJFP8) Discord server for individual help and guidance. If you make modifications to Keizaal, you do so at your own risk. No support will be provided.

Please note that manual installations are <ins>**NOT SUPPORTED**</ins>. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone's time.

## Credits

**Simon Magus** for tolerating my constant badgering about my load order

**Paleo the Parrot**, **VictorF**, and **ElectricSparx** for helping me understand xEdit

**Shade088** for all his help getting Keizaal’s graphical suite operational

**Catir** for Keizaal's beautiful banner and icons

**Total**,  **Lively**, and **Double Dog** for helping me get the Wabbajack installer operational over several long nights

**uggcaveman** for saving Keizaal that one time

**Dylan James** for helping me understand what I wanted out of this modlist

**halgari** and entire **Wabbajack Team** for creating such a fantastic resource

The wonderful **mod authors** for making this modlist possible
