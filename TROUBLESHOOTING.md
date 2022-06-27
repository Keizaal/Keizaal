---
layout: default
title: Troubleshooting
---
### "*Wabbajack is stuck during installation.*"

Simply restart Wabbajack, you will not lose progress on your downloads.

### "*A file fails to download.*"

Try resetting your Wabbajack client. Start off by closing Wabbajack if it is open, then press `Windows + R` on your keyboard and type in `%localappdata%`. You should see a Windows Explorer window pop up, find and delete the folder called Wabbajack inside.

Afterward open Wabbajack back up, navigate to the client settings, and enable "Use Network Workaround".

![](https://i.ibb.co/FDPDrfk/Discord-VPN.png)

Alternatively, you can try and manually install the failed mod downloads. You can find links to recently added and updated mods in the [Changelog](https://keizaal.github.io/Keizaal/CHANGELOG.html){:target="_blank" rel="noopener"}. 

Place the manually downloaded mods in your downloads folder where the other Wabbajack downloads are in your Mod Organizer. Do not extract them. Note that some of these are big files and may take a while.

### "*A vanilla file fails to download.*"

If Wabbajack fails to download any of the basegame files during the installation process, close Wabbajack, follow these steps, and then try running the installer again.
1. Verify the integrity of your game files through Steam, following [these instructions](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335){:target="_blank" rel="noopener"}.
2. Make sure that the game is set to English in Steam.
3. Open the game through Steam once to create any registry entries and INI files you don't already have, then immediately exit the launcher.

### "*ModOrganizer.exe throws and error when trying to launch.*"

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

### "*SKSE throws an error when the game launches.*"

![](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/SKSEPluginError.png)

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe) and select "Repair Installation" when you run the installer. Be sure to restart your computer afterward.

### "*Some mods in the Downloads tab aren't listed as installed.*"

This occsionally happens with certain mods, don't worry, they **are installed**.

### "*Mod Organizer says that skse64_loader.exe does not exist.*"

If you are experiencing problems such as the skse64_loader.exe being deleted, try adding the folder where Keizaal is installed to exclusions in your antivirus of choice.

**Note:** If you're using Webroot or any other free 3rd party antivirus it's likely that adding the folders to exclusions will not be enough and you'll need to disable or uninstall your 3rd party AV as they can incorrectly mark usvfs_proxy_x86.exe, among other files, as a virus, a file needed for Mod Organizer 2 to work. We recommend doing so anyway in case it's a free one, as Windows Defender is likely much better at stopping threats than that is (according to data from [av-test.org](https://www.av-test.org/en/antivirus/home-windows/){:target="_blank" rel="noopener"}).

If you still think a file is a virus, you can upload it to virustotal and get it scanned by multiple antiviruses. [Here](https://www.virustotal.com/gui/file/356c029b7bf0bed41460ceacf2c756560101b9b0977c349925d81d76392dd0c4/detection){:target="_blank" rel="noopener"} is a scan of the file mentioned above, of which two antiviruses report a false positive.

### "*Plugins are getting deactivated in the right panel.*"

You have likely surpassed the 255 .esp limit. When this happens Mod Organizer will automatically disable plugins in order to ensure that the game can launch.

Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

### "*The custom intro video is bugging out.*"

If you are having issues with the custom Keizaal intro video, enable the "Restore Vanilla Intro Video" mod in the Optionals section of Mod Organizer.

### "*UI Elementals are being cut off the screen"*

You probably have an 21:9 monitor, Skyrim's UI is designed only for a 16:9 aspect ratio. To fix this simply enable all the mods under "Ultrawide Fixes" in Mod Organizer.

![](https://raw.githubusercontent.com/Keizaal/Keizaal/main/assets/images/installation%20guide/18.%20Optional%20Mods.png)

After you have activated all the mods be sure to sort your load order before you begin playing. Simply press the sort button directly above your plugins to sort all of your plugins!

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/11.%20LOOT.png)

### "*Some sounds aren't playing.*"

If some sounds aren't playing correcting, follow these steps to fix the issue.
1. First download and install Link Shell Extension which can be found [here](http://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html){:target="_blank" rel="noopener"}.
2. Navigate to your Skyrim/Data folder and look for a file named Skyrim - Sounds.bsa. Copy this file and paste it somewhere on your main drive.
3. Delete Skyrim - Sounds.bsa from the Data folder.
4. Go back to where you copied Skyrim - Sounds.bsa on your main drive. Right click on it and you should see an option that says "Pink Link Source". Click that.
5. Go back to your Skyrim/Data folder. Right click anywhere and choose "Drop As" and then "Symbolic Link". You will see your sounds file with a shortcut symbol. You know it works when you see a little symbol next to the linked files.

### "*When updating Keizaal, Wabbajack deletes mods added on top of the list.*"

During every update Wabbajack will clean out the mods folder to ensure that everything gets installed properly. However, you can add the prefix `[NoDelete]` to the names of the mods you would like to keep and Wabbajack will be sure to ignore them.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/12.%20No%20Delete.PNG)

Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

### "*.ini and .txt configuration files aren't present in the mod's folder.*"

In order to manually edit the .inis you will first need to find the "Keizaal Settings" mod in the left pane of Mod Organizer. It should be near the bottom. Once you find it, right click on it and select "Information".

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/8.%20Keizaal%20Settings.PNG)

Once you have done that a window should pop up. Once that window appears select the ".ini Files" tab at the top.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/9.%20Navigate%20to%20.inis.PNG)

You should now see a list of all the .ini files present in Keizaal. You can edit and save these settings from this interface.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/10.%20Edit%20.inis.PNG)

Some configuration settings may be stored in a non-.ini format. If that is the case you can edit them through the "Text Files" tab.

Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

---

Contact me (Tate Taylor) on [my community Discord server](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} for individual help and guidance. Note that I **WILL NOT** provide support for installations of Keizaal that have been modified.

Support for manual installations is **NOT OFFERED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone’s time.
