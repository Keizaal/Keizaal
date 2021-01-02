Current version: 12/28/2020 3.3.4.3

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/keizaal/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/keizaal/badge.json)

# Installation Guide

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Keizaal%20Banner.png)

# What is Keizaal?

Keizaal is a simple modlist that focuses on improving what is already presented to us in vanilla Skyrim without compromising Bethesda’s original vision that we all fell in love with back in 2011.

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
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

## Setup and Information

This modlist takes up 100GB of harddrive space and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance, but a standard hard disk drive will suffice.

Install the latest version of Wabbajack from the #builds channel in the [Wabbajack Discord](https://discordapp.com/invite/wabbajack).

Create a new folder called “Wabbajack” in the root of your main drive, the default is (C:). Extract Wabbjack.exe into this folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Installing%20Wabbajack.png)

This modlist was developed on a system running [these specs](https://pcpartpicker.com/list/s8MYfP), on this system a stable and consistent 45 - 50FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

### Clean Install

Wabbajack requires a clean install of Skyrim to work properly, this step is only necessary once.

Delete the following directories:

1.  C:\Program Files (x86)\Steam\steamapps\common\Skyrim Special Edition
2.  Open Windows Search and copy/paste %LOCALAPPDATA%
3.  Delete the Skyrim Special Edition folder
4.  Navigate to Users\YOURNAME\Documents\My Games\
5.  Delete the Skyrim Special Edition folder

If you cannot find these directories you either didn’t have Skyrim installed or had it installed to a non-default location.

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

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Installing%20Keizaal.png)

When you’re ready press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When the installation is done the left panel should say “Installation Complete '' at the button. At this time it is safe to close Wabbajack.

### Installing the ENB Binaries (Optional)

If you have an older or less powerful machine you may skip this step.

[Click here to go to enbdev.com.](http://enbdev.com/download_mod_tesskyrimse.htm)

Download the most recent version of the ENB binaries. Once the archive is downloaded, open it and open the “WrapperVersion” folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Installing%20ENB.png)

Extract everything in “WrapperVersion” to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe).

Keizaal comes with its own prepackaged ENB preset. If, for whatever reason, you don't want to use this prepackaged preset I *urge* you to at least use an ENB that doesn't break imagespace modifiers. I believe any ENB that breaks imagespace modifiers is automatically bad, no matter how pretty it may look.

## Playing Keizaal

Navigate to your Keizaal installation folder (default is C:\Keizaal\) and open the “Game Folder Files” folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Installing%20Game%20Folder%20Files.png)

Extract everything in it to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe). Keizaal is ready to play!

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your .esp files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the .esp plugins and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Optional Mods

There are a handful of mods that I have included that are disabled by default. These mods aren’t part of the main Keizaal package and are mainly made up of mods that rely on Creation Club content in order to function. I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

Here is an example of one such note:

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Notes.png)

## Troubleshooting

**Wabbajack throws an error after authorizing through Nexus.**

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

**A mod fails to download.**

If a mod fails to download Keizaal may be down and require a recompile. Check the Wabbjack Discord and be patient as an update is made.

**ModOrganizer.exe throws an error when trying to launch.**

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

**Skyrim can't seem to get past character creation without crashing.**

[Changie your Windows regional format](https://support.microsoft.com/en-us/office/change-the-windows-regional-settings-to-modify-the-appearance-of-some-data-types-edf41006-f6e2-4360-bc1b-30e9e8a54989) to "English (United States)", as seem below.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/images/Troubleshooting%20Regional%20Format.png)

Contact Pierre Despereaux on either the [Wabbajack](https://discordapp.com/invite/wabbajack) or [Keizaal](https://discord.gg/eYZJFP8) Discord server for individual help and guidance.

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
