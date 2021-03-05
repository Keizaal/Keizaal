
![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/branding/Keizaal%20Website%20Banner.png)

---

# Table of Contents
- [Information](#information)
  - [Terms of Service](#terms-of-service)
- [Setup](#setup)
  - [Clean Install](#clean-install)
- [Keizaal Installation](#keizaal-installation)
  - [Copying the Game Folder Files](#copying-the-game-folder-files)
- [Playing Keizaal](#playing-keizaal)
  - [Mod Configuration](#mod-configuration)
- [Additional Configuration (Optional)](#additional-configuration-optional)
  - [Switching the ENB](#switching-the-enb)
  - [Optional Mods](#optional-mods)
  - [Mod Notes](#mod-notes)
  - [BethINI](#bethini)
- [Updating](#updating)
  - [Semantic Versioning](#semantic-versioning)

## Information

Keizaal takes up 235GB of hard drive space (138GB installation with 94.8GB of downloads) and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance. You will run into very, very long loading times and stuttering with a standard hard disk drive. This modlist was developed on a computer running [these specs](https://pcpartpicker.com/list/3ygt4d){:target="_blank" rel="noopener"}, on this system a stable and consistent 50 - 60 FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

Please note that automated downloads from Nexus are only available through Wabbajack with an active premium membership. If you do not have a premium membership, Wabbajack will prompt you to manually download the necessary files.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone’s time.

### Terms of Service

In downloading this modlist you are agreeing to obey the following rules concerning Keizaal and Wabbajack in general:

1. Be a polite participant and respect others. This is a friendly and welcoming place so treat everyone with respect. Excessive cursing or any kind of abuse, hate speech, doxxing or discrimination against others is not welcome. Violators will be warned and repeat offenders will be banned.

2. No brigading, doxxing, trolling or harassment of any kind toward other websites, servers, groups, individuals or mod authors. Poor behaviour reflects on the community as a whole and impacts how Wabbajack is perceived and treated by the wider modding community which in turn undermines the entire point of Wabbajack - to make modding more accessible and open to everyone. Wabbajack moderators reserve the right to take action against members who are found to be disruptive in the wider community.

3. No political or religious discussion.

4. No NSFW content outside of designated channels. Real world explicit content is not allowed under any circumstances - breaching this will result in an instant ban. All content, including your messages, links, images, avatars and nicknames, may not contain explicit or implied sexual or gory content unless it is in a specifically designated NSFW flagged channel and is relevant to game modding. Any content such as illustrated or digitally altered pornography which depicts minors such as lolicon, shotacon, or cub is prohibited server wide. Moderators reserve the right to change your nickname and request an avatar change.

5. No spamming. This is not Twitch chat, offenders will be muted, kicked and/or banned as appropriate. Spamming @ mentions will result in mute. Spamming links to websites or other servers etc. is prohibited as are self-promotion links.

6. No impersonating Wabbajack Staff or other users. Do not try to impersonate a developer, moderator, mod author or any other member.

7. Game and mod piracy is strictly prohibited. Use of pirated content and/or unauthorised redistribution of content will result in a permanent ban.

8. DO NOT CONTACT MOD OR GUIDE AUTHORS FOR SUPPORT. Support will only be provided in the relevant channels on this server.

9. DO NOT CONTACT MOD AUTHORS FOR OLD VERSIONS OF THEIR MODS. Do not ask how to bypass/obtain a mod that has been updated, wait for the Wabbajack installer to be updated.

10. All support queries should be directed to the appropriate channel in this server. Any conflicts/bugs/issues that arise are likely to result from the specific combination of mods in a given list, therefore mod authors and mod guide authors who are not familiar with the specific installer should not be subjected to helping Wabbajack users if they do not wish to.

11. If you make modifications to these Modlists, you do so at your own risk. Unless otherwise specified, no support or advice will be provided. Any discussion of changes to modlists should be done in general channels only and not support channels.

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

When you’re ready press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When Wabbajack is finished, the left panel should say "Installation Complete". At this time it is safe to close Wabbajack.

### Copying the Game Folder Files

Navigate to your Keizaal installation folder and open the “Game Folder Files” folder. This folder contains the list's ENB and all the necessary systems files to ensure Keizaal works properly.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/3.%20Game%20Folder%20Files.png)

Copy everything in it to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe). Keizaal is ready to play!

## Playing Keizaal

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Mod Configuration

All of the Mod Configuration Menus menus and .inis in Keizaal have been pre-configured to my recommended settings. The only thing you need to do when you start a new game is play.

## Additional Configuration (Optional)

This following section outlines some additional, optional confiurations. Nothing here is necessary, but it may be of some interest to users who like to tweak.

### Switching the ENB

Keizaal comes with its own prepackaged ENB preset. If, for whatever reason, you don't want to use this prepackaged preset, I urge you to at least use an ENB that doesn't break imagespace modifiers. I believe any ENB that breaks imagespace modifiers is automatically bad, no matter how pretty it may look.

[ENB and ReShade Manager](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=76937&game_id=1704){:target="_blank" rel="noopener"} is a great tool for easily switching between ENB presets. If you decide against using Keziaal's preset, I recommend this program to easily remove all traces of the preset from your Skyrim directory.

### Optional Mods

There are a handful of mods that I have included that are disabled by default; these mods aren’t part of the main Keizaal package. If you choose to activate an optional mod, be sure to move the mod's plugin (on the right pane of Mod Organizer) **above all** of the plugins with the "Keizaal" prefix unless otherwise instructed in the mod's notes.

I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

### BethINI

BethINI is a powerful tool that replaces Skyrim's Vanilla launcher settings menu, you can utilize it to tweak the game's settings. In order to use it, select it from the dropdown in the top right-hand corner of Mod Organizer, then start it the same way you'd launch Skyrim. 

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/6.%20BethINI.png)

After you have launched BethINI, be sure to **close Mod Organizer before you change any settings**!

Alternatively, you can manually edit your base game's .ini files. You can do so by navigating to the top of Mod Organizer, clicking on the puzzle piece, then selecting ".ini Editor".

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Manual%20.inis.PNG)

## Updating

If this Modlist receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the overwrite existing Modlist button.

### Semantic Versioning

Keizaal uses semantic versioning in order to quickly determine the size of an update and if it is savegame compatible or not. This is what the version numbers mean:

- <ins>**1**</ins>.0.0 = A large update that is **NOT** savegame compatible and fundamentally changes the list.
- 1.<ins>**1**</ins>.0 = An update that is **NOT** savegame compatible.
- 1.1.<ins>**1**</ins> = An update that **IS** savegame compatible.
- 1.1.1.<ins>**1**</ins> = A small hotfix that **IS** savegame compatible.

In layman's terms, if the first two version numbers have not changed it is savegame compatible.

You can find your current version of Keizaal at the top of Mod Organizer. If the version isn't listed you're probably using a pre-3.4.0 version.
