# Keizaal
Current version: 11/21/2020 3.2.2

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/keizaal/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/keizaal/badge.json)

![](https://lh5.googleusercontent.com/qg1yiTiIK8-eiPjZw1Fe50LJ4oe2FUNfvLZAeczNKNBsTJtm9SsPr6ERvVSHBn0F3XOYPo7xRZoSY_L17N5AKLs51SU8XjFZLWzbF7wPCgGr1zS48Ap30ULjp_6rqwMmif5-oh78)

# What is Keizaal?

Keizaal is a simple modlist that seeks to enhance and expand on Skyrim without compromising Bethesda’s original vision that we all fell in love with back in 2011.  

1.  This modlist is lite and intends to maintain the Vanilla feel. A lot of the time modlists can become ridiculously huge and bloated, but this modlist wants to be nice and lean. Less is more. 
2.  Immersion is paramount. I'm a lore buff and immersion is very important to me. If a mod is not lore accurate or takes me out of the game in any way it will be excluded. Consistency also falls into this category, if a mod has a completely different aesthetic from Vanilla or any of my other mods then it will probably not be included.
3.  Mods must have decent longevity. This modlist wants to be somewhat relevant, in theory, forever.
4.  Stability is the most important thing. This rule basically supersedes all the above. If a mod introduces major stability concerns it will be quickly cut.

You can find a full list of the mods included in Keizaal [here](https://modwat.ch/u/Keizaal/). If you're still curious about what exactly Keizaal has in store for you, have a look at the overview [here](https://www.wabbajack.org/#/modlists/info?machineURL=keizaal).

## Setup and Information

This modlist takes up 100GB of harddrive space and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance, but a standard hard disk drive will suffice.

Install the latest version of Wabbajack from the #builds channel in the [Wabbajack Discord](https://discordapp.com/invite/wabbajack).

Create a new folder called “Wabbajack” in the root of your main drive, the default is (C:). Extract Wabbjack.exe into this folder.

![](https://lh3.googleusercontent.com/J2TSlfEol5ph4dQ1satHzWZS4B3JGHuGCTguSnDv7PBs0CI61psyN3LNZ2xVW-lslGcSbix65cU4_joIjYO5Hz0OGET8Rjlev0Oi7bxLNOzkRXdvxBDAK7d058LanhUJWb9MPG6M)
This modlist was developed on a system running [these specs](https://pcpartpicker.com/list/7JD9n7), on this system a stable and consistent 45 - 50FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

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

### Creation Club Updating Protection

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

![](https://lh4.googleusercontent.com/P7t5u3IoiDj4ERKY-KInr3n5eBEgJqiqgBk4wJgpI4nqCL6OX1OhcDhW_7VGfnpNwN3wVwLwPYTGNAuybSh6Mx08ImAs6LXayiwInRbbrH3Y4-hVDE0lPql49Qm7LCLQGbKfZs4a)
When you’re ready press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When the installation is done the left panel should say “Installation Complete '' at the button. At this time it is safe to close Wabbajack.

### Installing the ENB (Optional)

If you have an older or less powerful machine you may skip this step.

[Click here to go to enbdev.com.](http://enbdev.com/download_mod_tesskyrimse.htm)

Download the most recent version of ENB. Once the archive is downloaded, open it and open the “WrapperVersion” folder.

![](https://lh6.googleusercontent.com/SPfkD5mRAFwiXKdriV7B2GvDdcqs7wLS4DeF1eHO-gzGd--AHX1tavpmxRA8GFnCpyrqcZ-vCyo0IdgrShtZWXmcadYFaLyBfFMZjLFqJiGrDQFrYhFxffWIqOL5gsSD0VSRqq06)
Extract everything in “WrapperVersion” to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe).

## Playing Keizaal

Navigate to your Keizaal installation folder (default is C:\Keizaal\) and open the “Game Folder Files” folder.

![](https://lh5.googleusercontent.com/AcN_DN0Xr133rwF-ntqbHbcv6e7GVs0ChBY7as__v_EkTaoGotVkR6E_JCDzO0m-QHmpjGqT7WG74cikRaYKOb2Ojr_O8aZ4I-A6He-CxjWkQ-tUB7G8a3uMRPj7lJQ0934U-_q5)
Extract everything in it to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe). Keizaal is ready to play!

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your .esp files on the right.

![](https://lh4.googleusercontent.com/_bSzqh7vA4QHZ3m7cnCj2s0-hW-LqXU8vLryDidqN0DDNa4MhOV7HupaDjEEBdIztDf0qg9FHeotUEqIjdhrQg2xddNM33TMQIIvwX0yzSQCphBtwdGT7vRzfb-Wv2j64CPY_K02)
You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the .esp plugins and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Optional Mods

There are a handful of mods that I have included that are disabled by default. These mods aren’t part of the main Keizaal package and are mainly made up of mods that rely on Creation Club content in order to function. I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

## Troubleshooting

**Wabbajack throws an error after authorizing through Nexus.**

Download the [.Net Framework 4.8 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net48). Be sure to restart your computer afterward.

A mod fails to download.

If a mod fails to download Keizaal may be down and require a recompile. Check the Wabbjack Discord and be patient as an update is made.

**ModOrganizer.exe throws an error when trying to launch.**

Download the x64 version of the [MSVC 2019 Runtime Library](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Be sure to restart your computer afterward.

Contact Pierre Despereaux on either the [Wabbajack](https://discordapp.com/invite/wabbajack) or [Keizaal](https://discord.gg/eYZJFP8) Discord server for individual help and guidance.

## Credits

**Simon Magus**
for tolerating my constant badgering about my load order

**Paleo the Parrot**, **VictorF**, and **ElectricSparx**
for helping me understand xEdit

**Shade088**
for all his help getting Keizaal’s graphical suite operational

**Total**,  **Lively**, and **Double Dog**
for helping me get the Wabbajack installer operational over several long nights

**uggcaveman**
for saving Keizaal that one time

**Dylan James**
for helping me understand what I wanted out of this modlist

**halgari** and entire **Wabbajack Team**
for creating such a fantastic resource

The wonderful **mod authors**
for making this modlist possible
