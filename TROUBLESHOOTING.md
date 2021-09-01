---
layout: default
title: Troubleshooting
---
### "*Wabbajack throws an error after authorizing through Nexus.*"

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

### "*Wabbajack is stuck during installation.*"

Simply restart Wabbajack, you will not lose progress on your downloads.

### "*A file fails to download.*"

Try resetting your Wabbajack client.

To completely reset your Wabbajack settings, start off by closing Wabbajack if it is open. Afterwards, press `Windows + R` on your keyboard and type in `%localappdata%`. You should see a Windows Explorer window pop up, find and delete the folder called Wabbajack inside.

Afterward, open the client back up and navigate to the client settings and enable "Net Workaround".

![](https://i.ibb.co/FDPDrfk/Discord-VPN.png)

Alternatively, you can try and manually install the failed mod downloads. You can find links to recently added and updated mods in the [Changelog](https://keizaal.github.io/Keizaal/CHANGELOG.html).

Place the manually downloaded mods in your downloads folder where the other Wabbajack downloads are in your Mod Organizer. Do not extract them. Note that some of these are big files and may take a while.

### "*A vanilla file fails to install.*"

If a file like `Skyrim - Meshes0.bsa` fails to install verify Skyrim's local cache via Steam.

### "*Skyrim_Default.ini fails to install.*"

Ensure that Skyrim's language is set to English in Steam.

### "*There are no relevant files inside the Game Folder Files folder.*"

Keizaal uses the [Stock Game system](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)){:target="_blank" rel="noopener"}, this means that the Game Folder Files step is not necessary.

### "*ModOrganizer.exe throws and error when trying to launch.*"

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

### "*Plugins are getting deactivated in the right panel.*"

You have likely surpassed the 255 .esp limit. When this happens Mod Organizer will automatically disable plugins in order to ensure that the game can launch.

Note that I **WILL NOT** provide support to installations of Keizaal that have been modified.

### "*UI elements appear to be getting cut off the screen.*"

Enable Widescreen Fixes under the optional section in Mod Organizer. If that doesn't work, disable Widescreen Fixes and enable Dialogue Interface ReShaped (16 by 10).

### "*Skyrim is capped at 72 FPS.*"

The mod Movement Behavior Overhaul will cause animations to break if the framerate goes over 75 FPS, so I've capped the FPS to 72 in order to prevent that.

### "*The compass is missing.*"

Press the "X" button to toggle the compass on and off.

### "*The crosshair is missing.*"

Restart your game. The crosshair should reappear when you load you save.

### "*When updating Keizaal, Wabbajack deletes mods added on top of the list.*"

During every update Wabbajack will clean out the mods folder to ensure that everything gets installed properly. However, you can add the prefix `[NoDelete]` to the names of the mods you would like to keep and Wabbajack will be sure to ignore them.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/12.%20No%20Delete.PNG)

Note that I **WILL NOT** provide support to installations of Keizaal that have been modified.

### "*.ini and .txt configuration files aren't present in the mod's folder.*"

The Settings application can handle the majority of tweaks that you would generally want to make. However, some of the more niche settings may be handled by .inis that Settings can't edit. These will need to be edited manually.

In order to manually edit the .inis you will first need to find the "Keizaal Settings" mod in the left pane of Mod Organizer. It should be near the bottom. Once you find it, right click on it and select "Information".

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/8.%20Keizaal%20Settings.PNG)

Once you have done that a window should pop up. Once that window appears select the ".ini Files" tab at the top.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/9.%20Navigate%20to%20.inis.PNG)

You should now see a list of all the .ini files present in Keizaal. You can edit and save these settings from this interface.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/10.%20Edit%20.inis.PNG)

Some configuration settings may be stored in a non-.ini format. If that is the case you can edit them through the "Text Files" tab.

---

Contact Tate Taylor on [his community Discord server](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} for individual help and guidance. If you make modifications to Keizaal, you do so at your own risk. No support will be provided.

Please note that manual installations are **NOT SUPPORTED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everybody's time.
