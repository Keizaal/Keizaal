
# Table of Contents
- [Information](#information)
- [Setup](#setup)
  - [Clean Install](#clean-install)
- [Keizaal Installation](#keizaal-installation)
- [Playing Keizaal](#playing-keizaal)
    - [Mod Configuration](#mod-configuration)
    - [Hotkeys](#hotkeys)
- [Additional Configuration (Optional)](#additional-configuration-optional)
  - [Optional Mods](#optional-mods)
  - [Settings](#settings)
  - [Mod Notes](#mod-notes)
- [Updating](#updating)
  - [Semantic Versioning](#semantic-versioning)

## Information

Keizaal takes up 172.5GB of hard drive space (85.8GB installation with 86.7GB of downloads) and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance. You will run into very, very long loading times and stuttering with a standard hard disk drive. This modlist was developed on a computer running [these specs](https://pcpartpicker.com/list/3ygt4d){:target="_blank" rel="noopener"}, on this system a stable and consistent 50 - 60 FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

Please note that automated downloads from Nexus are only available through Wabbajack with an active premium membership. If you do not have a premium membership, Wabbajack will prompt you to manually download the necessary files.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone’s time.

## Setup

Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe).

Create a new folder called “Wabbajack” in a location **outside of the Program Files**. Extract Wabbjack.exe into this folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/1.%20Installing%20Wabbajack.png)

### Clean Install

To completely reinstall Skyrim, it is advised that you use the [Skyrim Shredder](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=113028&game_id=1704){:target="_blank" rel="noopener"}. It will remove Skyrim and all data related to it, but not the modlist.

Reinstall Skyrim in a location **outside of the Program Files**. If you have issues reinstalling Skyrim outside of Program Files, try using the [Steam Library Setup Tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide){:target="_blank" rel="noopener"}.

Run the Skyrim: Special Edition launcher through Steam and let it detect your settings, then close the launcher. **This is only necessary once**.

## Keizaal Installation

Create a new folder called “Keizaal” in a location **outside of the Program Files**.

Open Wabbajack.exe and select the Keizaal modlist from the Wabbajack UI.

Once the installation window opens ensure that the “Installation Location” matches the Keizaal folder you just created. The download location should populate automatically

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/2.%20Installing%20Keizaal.png)

When you’re ready, press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When Wabbajack is finished, the left panel should say "Installation Complete". Keizaal is ready to play!

## Playing Keizaal

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Mod Configuration

All of the Mod Configuration Menus menus and .inis in Keizaal have been pre-configured to my recommended settings. The only thing you need to do when you start a new game is play.

### Hotkeys

There are several hotkeys that you should be aware of while playing Keizaal. Most of them can be edited via the in-game Mod Configuration Menu. The default keys are as follows:

**X** - Toggle Compass

**N** - Toggle Mini Map

**K** - Zoom Mini Map

**,** - Call Horse

**Shift+F12** - Toggle ENB

## Additional Configuration (Optional)

This following section outlines some optional confiurations. Nothing here is necessary, but it may be of some interest to users who like to tweak.

### Optional Mods

There are a handful of mods that I have included that are disabled by default; these mods aren’t part of the main Keizaal package. If you choose to activate an optional mod, be sure to sort your load order before you begin playing. Simply press the sort button in the top right-hand corner of Mod Organizer to sort all of your plugins!

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/11.%20LOOT.png)

I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

### Settings

If you want to edit some of Skyrim's settings you can do so by pressing the gear button in the top right-hand corner of Mod Organizer.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/6.%20BethINI.PNG)

After you have launched the application, be sure to **close Mod Organizer before you change any settings**!

Alternatively, you can manually edit your base game's .ini files. You can do so by navigating to the top of Mod Organizer, clicking on the puzzle piece, then selecting ".ini Editor".

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Manual%20.inis.PNG)

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/5.%20Mod%20Notes.PNG)

## Updating

If Keizaal receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating. Updating is like installing. You only have to make sure that you select the same path and tick the "Overwrite Existing Modlist" button.

**Wabbajack will delete all files that are not part of Keizaal when updating!**

This means that any additional mods you have installed on top of Keizaal will be deleted. However, you can add the prefix `[NoDelete]` to the names of the mods you would like to keep and Wabbajack will be sure to ignore them.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/12.%20No%20Delete.PNG)

Keep in mind that modifying Keizaal will forfeit any support that you would normally recieve.

### Semantic Versioning

Keizaal uses semantic versioning in order to quickly determine the size of an update and if it is savegame compatible or not. This is what the version numbers mean:

- <ins>**1**</ins>.0.0 = A large update that is **NOT** savegame compatible and fundamentally changes the list.
- 1.<ins>**1**</ins>.0 = An update that is **NOT** savegame compatible.
- 1.1.<ins>**1**</ins> = An update that **IS** savegame compatible.
- 1.1.1.<ins>**1**</ins> = A small hotfix that **IS** savegame compatible.

In layman's terms, if the first two version numbers have not changed it is savegame compatible.

You can find your current version of Keizaal at the top of Mod Organizer. If the version isn't listed you're probably using a pre-3.4.0 version.
