# Troubleshooting

### "*Wabbajack throws an error after authorizing through Nexus.*"

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

### "*A mod fails to download.*"

If Wabbajack fails to download a mod, try downloading them manually. Place these in your downloads folder where the other Wabbajack downloads are. Do not extract them. Note that some of these are big files and may take a while.

- [Bearnado Markarth Mashup](https://drive.google.com/u/0/uc?export=download&confirm=Jziu&id=1D139AzjXYuiTMjboFa_gmT3mXrmsR0zG){:target="_blank" rel="noopener"}
- [Keizaal Resources](https://github.com/PierreDespereaux/Keizaal/releases/download/4.0.1/Keizaal.Resources.7z)
- Skyrim Realistic Overhaul
  - [Part One](https://www.moddb.com/downloads/start/116891?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [Part Two](https://www.moddb.com/downloads/start/116927?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [Part Three](https://www.moddb.com/downloads/start/116934?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [1.8 Update](https://www.moddb.com/downloads/start/139489?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
- [WiZkiD Candle Flames](https://drive.google.com/uc?export=download&id=1ZA8r-McnBcxjCdUBnA4wRW1jZzhHciO2)
- [WiZkiD DynDOLOD Bright Waterfalls Meshes Fix](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD DynDOLOD Ultra Detailed Ships LOD](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD Grass and Landscape](https://drive.google.com/u/0/uc?export=download&confirm=qk9_&id=18rmerskUeBZecsdeU_QRpG1QXrIylyA9){:target="_blank" rel="noopener"}
- [WiZkiD Sky Textures](https://drive.google.com/u/0/uc?export=download&confirm=XM-E&id=1lsg11a3blf825KVZsKaevKB5-khmaP9l){:target="_blank" rel="noopener"}
- [WiZkiD Storm Lighting Improved Thunder Sounds](https://drive.google.com/u/0/uc?export=download&confirm=VB0Q&id=1Fg-w1TQgC7WIYOSsOXNFd02egFgn6u3R){:target="_blank" rel="noopener"}
- [WiZkiD Tree Selection](https://drive.google.com/u/0/uc?export=download&confirm=MIlo&id=1BhxtOpeaEHEkli6QKLrhi1bQyNYIdgXG){:target="_blank" rel="noopener"}
- [WiZkiD Unique Flowers and Plants](https://drive.google.com/uc?export=download&id=1MPW2y4cjL31B2Oncx1OMeuTITartQ4q-)
- [WiZkiD Variety](https://drive.google.com/u/0/uc?export=download&confirm=l4nJ&id=1g5yCvLG0Fw-WvPOzEDNMaqBdTwT6eg65){:target="_blank" rel="noopener"}
- [WiZkiD Water Wells with Real Water](https://drive.google.com/uc?export=download&id=1wnWsbLND5rxgJV-keeJG4Ev33XkROugI)

### "*ModOrganizer.exe throws and error when trying to launch.*"

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

### "*The NPCs during the Helgen intro are just standing in place*."
 
Make sure you correctly copied the Game Folder Files over to your Skyrim directory.

Please refer to [this section](#copying-the-game-folder-files) for information on how to do so.

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
