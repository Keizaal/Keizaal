---
layout: default
title: Installation Guide
---
# Table of Contents
- [Information](#information)
  - [Automated Downloads](#automated-downloads)
- [Setup](#setup)
  - [Clean Install](#clean-install)
- [Installation](#installation)
  - [Wabbajack Installation](#wabbajack-installation)
  - [Keizaal Installation](#keizaal-installation)
  - [Anniversary Edition Initialization](#anniversary-edition-initialization)
- [Playing](#playing)
  - [Mod Configuration](#mod-configuration)
  - [Hotkeys](#hotkeys)
- [Optional Configuration](#optional-configuration)
  - [Optional Mods](#optional-mods)
  - [Settings](#settings)
  - [Mod Notes](#mod-notes)
- [Updating](#updating)
  - [Semantic Versioning](#semantic-versioning)

# Information

Keizaal takes up roughly 88GB of hard drive space (38GB installation with 50GB of downloads) and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance. You will run into very, very long loading times and stuttering with a standard hard disk drive. 

Note that [Anniversary Edition](https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade/) is **required** in order to install Keizaal.

If you run into any issues installing Keizaal please refer to the [Troubleshooting Guide](https://keizaal.github.io/Keizaal/TROUBLESHOOTING.html){:target="_blank" rel="noopener"}. It covers all of the common errors that may occur and will walk you through how to fix them.

### Automated Downloads

Automated downloads from Nexus are only available through Wabbajack with an active [premium membership](https://users.nexusmods.com/account/billing). If you do not have a premium membership, Wabbajack will prompt you to manually download the necessary files.

If you activate premium membership after beginning a Wabbajack install, you can restart Wabbajack to enable automated downloads.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone’s time.

# Setup

Before the Keizaal installation can begin there are a few preliminary setup steps that need to be done.

### Clean Install

A clean install of Skyrim is **required** in order to correctly install Keizaal.

Navigate to your Skyrim installation on Steam. Right-click on Skyrim and click the "Uninstall" button.

![](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/15.%20Uninstall.PNG)

Reinstall Skyrim in a location **outside of the Program Files**. If you have issues reinstalling Skyrim outside of Program Files, try using the [Steam Library Setup Tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide){:target="_blank" rel="noopener"}.

Run the Skyrim: Special Edition launcher through Steam and let it detect your settings, then launch the game. If you have no installed Anniversary Edition content yet, you will be prompted to do so now. After that feel free to close exit to your desktop.

If you have the Anniversary Edition, make sure to let Skyrim download all the additional content at this time.

# Installation

Next, both Wabbajack and Keizaal will need to be downloaded and installed.

### Wabbajack Installation

Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe).

Create a new folder called “Wabbajack” in a location **outside of the Program Files**. Extract Wabbjack.exe into this folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/1.%20Installing%20Wabbajack.png)

### Keizaal Installation 

Create a new folder called “Keizaal” in a location **outside of the Program Files**.

Open Wabbajack.exe and select the Keizaal modlist from the Wabbajack UI.

Once the installation window opens ensure that the “Installation Location” matches the Keizaal folder you just created. The download location should populate automatically

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/2.%20Installing%20Keizaal.png)

When you’re ready, press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When Wabbajack is finished, the left panel should say "Installation Complete".

# Playing

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

Whenever you launch Skyrim from Mod Organizer this message will pop up:

![](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/NotAnError.png)

**THIS IS NOT AN ERROR, DO NOT PRESS "UNLOCK"**. Simply wait a bit and Skyrim will open normally.

### Mod Configuration

All of the Mod Configuration Menus and .inis in Keizaal have been pre-configured to my recommended settings. The only thing you need to do when you start a new game is play.

### Settings

If you want to edit some of Skyrim's settings you can do so by manually editing your base game's .ini files. You can do so by navigating to the top of Mod Organizer, clicking on the puzzle piece, then selecting ".ini Editor".

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Manual%20.inis.PNG)

Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/5.%20Mod%20Notes.PNG)

# Updating

If Keizaal receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating. Updating is like installing. You only have to make sure that you select the same path and tick the "Overwrite Existing Modlist" button.

**Wabbajack will delete all files that are not part of Keizaal when updating!**

This means that any additional mods you have installed on top of Keizaal will be deleted. However, you can add the prefix `[NoDelete]` to the names of the mods you would like to keep and Wabbajack will be sure to ignore them.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/12.%20No%20Delete.PNG)

Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

### Semantic Versioning

Keizaal uses semantic versioning in order to quickly determine the size of an update and if it is savegame compatible or not. This is what the version numbers mean:

- <ins>**1**</ins>.0.0 = A large update that is **NOT** savegame compatible and fundamentally changes the list.
- 1.<ins>**1**</ins>.0 = An update that is **NOT** savegame compatible.
- 1.1.<ins>**1**</ins> = An update that **IS** savegame compatible.
- 1.1.1.<ins>**1**</ins> = A small hotfix that **IS** savegame compatible.

In layman's terms, if the first two version numbers have not changed it is savegame compatible.

You can find your current version of Keizaal at the top of Mod Organizer. If the version isn't listed you're probably using a pre-3.4.0 version.

---

If you run into any issues installing Keizaal please refer to the [Troubleshooting Guide](https://keizaal.github.io/Keizaal/TROUBLESHOOTING.html){:target="_blank" rel="noopener"}. It covers all of the common errors that may occur and will walk you through how to fix them.

Contact me (Tate Taylor) on [my community Discord server](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} for individual help and guidance. Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone’s time.
