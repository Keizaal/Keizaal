# Troubleshooting

### "*Wabbajack throws an error after authorizing through Nexus.*"

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

### "*A mod fails to download.*"

If Wabbajack fails to download a mod, try downloading them manually. Place these in your downloads folder where the other Wabbajack downloads are. Do not extract them. Note that some of these are big files and may take a while.

### "*ModOrganizer.exe throws and error when trying to launch.*"

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

### "*The NPCs during the Helgen intro are just standing in place*."
 
Make sure you correctly copied the Game Folder Files over to your Skyrim directory.

Please refer to [this section](https://pierredespereaux.github.io/Keizaal/INSTALLATIONGUIDE.html#copying-the-game-folder-files) for information on how to do so.

### "*Skyrim is capped at 72 FPS.*"

The mod Movement Behavior Overhaul will cause animations to break if the framerate goes over 75 FPS, so I've capped the FPS to 72 in order to prevent that.

### "*Skyrim is acting strangely after automatically sorting the load order.*"

**NEVER USE LOOT OR MOD ORGANIZER TO AUTOMATICALLY SORT YOUR LOAD ORDER!** Keizaal's plugins have been carefully sorted manually in order to ensure that everything works as intended. Sorting the load order using an automatic tool **will** cause issues. If you have used an automated program to sort your load order, you forfeit all support I would normally provide until you restore your load order to Keizaal's default. You should be able to restore your load order to default by rerunning Wabbajack.

### "*Tweaks made with BethINI aren't correctly changing the settings in-game.*"

BethINI can handle the majority of tweaks that you would generally want to make. However, some of the more niche settings may be handled by .inis that BethINI can't edit. These will need to be edited manually.

### "*Manual .ini tweaks aren't correctly changing the settings in-game.*"

For ease-of-use I have placed all the custom .inis for every mod in Keizaal within a mod called "Keizaal Settings" at the bottom of Mod Organizer.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Keizaal%20Settings.png)

______________________________________________________________________________________________________________________________________________________________________


Contact Pierre Despereaux on either the [Wabbajack](https://discordapp.com/invite/wabbajack){:target="_blank" rel="noopener"} or [Keizaal](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} Discord server for individual help and guidance. If you make modifications to Keizaal, you do so at your own risk. No support will be provided.

Please note that manual installations are **NOT SUPPORTED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone's time.
