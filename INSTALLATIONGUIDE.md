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
- [Playing](#playing)
  - [Profiles](#profiles)
  - [Mod Configuration](#mod-configuration)
- [Updating](#updating)
  - [Versioning](#versioning)
- [Modification](#modification)
  - [Mod Notes](#mod-notes)
  - [Settings](#settings)

# Information

**Keizaal requires [Skyrim Anniversary Edition](https://store.steampowered.com/sub/626153/).** 

This modlist takes up roughly 93GB of hard drive space (66GB installation with 26GB of downloads) and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid-state drive for optimal performance. You will run into very long loading times and stuttering with a standard hard disk drive. 

If you run into any issues installing Keizaal, please refer to the [Troubleshooting Guide](https://keizaal.github.io/Keizaal/TROUBLESHOOTING.html){:target="_blank" rel="noopener"}. It covers all of the common errors that may occur and will walk you through how to fix them.

### Automated Downloads

Automated downloads from Nexus are only available through Wabbajack with an active [premium membership](https://users.nexusmods.com/account/billing). If you do not have a premium membership, Wabbajack will prompt you to manually download the necessary files.

If you activate the premium membership after beginning a Wabbajack install, you can restart Wabbajack to enable automated downloads.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations, and attempting to troubleshoot each user individually is simply not realistic; it would likely be a waste of everyone’s time.

# Setup

Before the Keizaal installation can begin, there are a few preliminary setup steps that need to be done.

### Clean Install

A clean install of Skyrim is **required** to correctly install Keizaal.

Navigate to your Skyrim installation on Steam. Right-click on Skyrim and click the "Uninstall" button.

![Uninstall Image](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/15.%20Uninstall.PNG)

Reinstall Skyrim in a location **outside of the Program Files**. If you have issues reinstalling Skyrim outside of Program Files, try using the [Steam Library Setup Tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide){:target="_blank" rel="noopener"}.

Run the Skyrim Special Edition launcher through Steam and let it detect your settings, then launch the game. If you have not installed Anniversary Edition content yet, you will be prompted to do so now. After that, feel free to close and exit to your desktop.

# Installation

Next, both Wabbajack and Keizaal will need to be downloaded and installed.

### Wabbajack Installation

Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe).

Create a new folder called “Wabbajack” in a location **outside of the Program Files**. Extract Wabbjack.exe into this folder.

![Wabbajack Installation Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/1.%20Installing%20Wabbajack.png)

### Keizaal Installation 

Create a new folder called “Keizaal” in a location **outside of the Program Files**.

Open Wabbajack.exe and select the Keizaal modlist from the Wabbajack UI.

Once the installation window opens, ensure that the “Installation Location” matches the Keizaal folder you just created. The download location should populate automatically.

![Keizaal Installation Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/2.%20Installing%20Keizaal.png)

When you’re ready, press the triangular start button.

After starting the installation, a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log in and authorize Wabbajack on Nexus, and the installation will proceed. Wabbajack will now install the modlist; this will take a while, so be patient. When Wabbajack is finished, the left panel should say "Installation Complete".

# Playing

Now that Keizaal has been installed, you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![Playing Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button, there is a way to add a Skyrim shortcut to your desktop for added convenience.

Whenever you launch Skyrim from Mod Organizer, this message will pop up:

![Not An Error Image](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/NotAnError.png)

**THIS IS NOT AN ERROR, DO NOT PRESS "UNLOCK"**. Simply wait a bit, and Skyrim will open normally.

### Profiles

Keizaal is designed to enhance and expand upon what the vanilla game offers. While systems such as perk trees and combat have seen some expansions, they remain largely unchanged from the base game.

If you're looking for a different experience, Keizaal also includes a secondary profile that integrates the complete [SimonRim](https://next.nexusmods.com/profile/SimonMagus/mods?gameId=1704){:target="_blank" rel="noopener"} suite into the mod list. To switch to this profile, simply select it from the drop-down menu at the top of Mod Organizer.

![SimonRim Image](https://raw.githubusercontent.com/Keizaal/Keizaal/refs/heads/main/assets/images/installation%20guide/SimonRim.jpg)

### Mod Configuration

All of the Mod Configuration Menus and .inis in Keizaal have been pre-configured to the recommended settings. The only thing you need to do when you start a new game is play.

# Updating

If Keizaal receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating. Updating is like installing. You only have to make sure that you select the same path and tick the "Overwrite Existing Modlist" button.

### Versioning

Keizaal uses a four-digit versioning scheme to quickly assess the size and savegame compatibility of an update. Here’s what the version numbers indicate:

<ins>**1**</ins>.0.0 = MASSIVE update that is NOT savegame compatible and fundamentally changes the list\
1.<ins>**1**</ins>.0 = MAJOR update that is NOT savegame compatible\
1.1.<ins>**1**</ins> = MINOR update that IS savegame compatible\
1.1.1.<ins>**1**</ins> = PATCH fix that IS savegame compatible

In layman's terms, if the first two version numbers have not changed, it is savegame compatible.

You can find your current version of Keizaal at the top of Mod Organizer. If the version isn't listed you're probably using a pre-3.4.0 version.

# Modification

**Offical support for modified installations of Keizaal WILL NOT be provided.** However, if you'd like to make your own changes, there are a few important points to keep in mind.

If you attempt to update a modified installation of Keizaal, **Wabbajack will delete all files that are not part of Keizaal** during the update process.

This means that any additional mods you have installed on top of Keizaal will be deleted. To prevent this, you can add the prefix **[NoDelete]** to the names of the mods you want to keep and Wabbajack will ensure they are ignored during updates.

![No Delete Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/12.%20No%20Delete.PNG)

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how the mod as been configured.

![Mod Notes Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/5.%20Mod%20Notes.PNG)


### Settings

If you want to edit some of Skyrim's settings, you can do so by manually editing your base game's .ini files. You can do so by navigating to the top of Mod Organizer, clicking on the puzzle piece, then selecting "INI Editor".

![Settings Image](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Manual%20.inis.PNG)

---

If you run into any issues installing Keizaal, please refer to the [Troubleshooting Guide](https://keizaal.github.io/Keizaal/TROUBLESHOOTING.html){:target="_blank" rel="noopener"}. It covers all of the common errors that may occur and will walk you through how to fix them.

Join [Tate Taylor's community Discord server](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} for individual help and guidance.

Offical support for modified verions of Keizaal **WILL NOT** be provided. 

Offical support with manual installation is **NOT OFFERED**. There are simply too many variables that go on during manual installations, and attempting to troubleshoot each user individually is simply not realistic; it would likely be a waste of everyone’s time.
