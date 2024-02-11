# Origin Multiplayer Setup

This is the official repository for the Origin Multiplayer Setup.

This setup aims to fix all issues with Stronghold Crusader multiplayer, via game modifications.

Origin-v1.4

Not a finished product - the setup is still undergoing development.

### Quick installation

The setup only works with version 1.41 of the game and modifies the Extreme executable.

You can check your version in the game's main menu, under the exit gate. Make sure that the Extreme executable is present in the game folder as well.
- If you happen to have an older version of the game, you can update for free using the [FireFly patch](http://www.strongholdcrusaderhd.com/patch.html)
- If you don't own the game yet, you can buy the current newest version from [Steam](https://store.steampowered.com/app/40970/Stronghold_Crusader_HD/)

Back up your game folder by copying it elsewhere before installing.

Download the [Origin Installer](https://github.com/Altaruss28/Origin/raw/main/OriginInstaller.exe), insert the installer into your game folder and run it. It will automatically download and install everything that's needed.

If you intend on playing multiplayer with the setup through [GameRanger](https://www.gameranger.com/) - select the modified Extreme executable in (lobbyExplorer)/Edit/Options/Games.
Afterwards, open an Extreme lobby and start the game like normal.

### After installation

Two shortcuts will be created in the game folder - 
- "OriginMod - Updater" is used for updating the setup
- "OriginMod - CustomGraphicConfigurator" is used for enabling custom graphics which come with the setup

You can also manually install a [recommended graphics pack](https://drive.google.com/file/d/1f6gETtZSEHc0zsw0GnZCNJBrAszlxUEg/view?usp=sharing).
Simply move all the ".gm1" files into the "gm" folder inside your game folder.
You should get a prompt asking you whether you want to replace the files - allow that and the graphics set will be installed.

You should consider installing [DDraw Compat](https://github.com/narzoul/DDrawCompat/releases/download/v0.3.1/DDrawCompat-v0.3.1.zip) for better game performance and recording.
Simply insert the .dll into your game folder, next to the game executable.

If you want to get in touch with the multiplayer community, join our [Discord server](https://discord.gg/SaAx3RubHF).

## Changelog

An incremental changelog can be found [here](Documentation/incrementalChangelog.md).
It only covers the changes after the initial remake of the Bootstrap rebalance.

### Starting changes

The player starts with 0 gold, only 100 wood and 100 bread, as well as no units but the lord, making it practically impossible to just sell everything and rush.
This way, games are played with 0 no-rush, avoiding scripted economies and encouraging natural progression over time, just like in most RTS games.
The setup still includes starting gold settings for AIs and practice matches.

### Bugfixes and QoL features

The setup uses the [UCP](https://unofficialcrusaderpatch.github.io/), with all of its relevant features enabled.
It also includes a custom made AI pack, serving for offline practice or as an occasional replacement for a player.

### Custom map pack

The setup includes a custom map pack, including diverse, vanilla-like yet 100% balanced maps, contrary to the extremely simplistic ones used in vanilla multiplayer.

### Rebalances

The setup fixes all the glaring imbalances of the vanilla game, it also moves more in the direction of what seemed to be FireFly's original intentions.

The precise rebalance changes are summarized in form of stat spreadsheets - 
- [SHC Vanilla/Origin Stats](https://docs.google.com/spreadsheets/d/1d87q-HgE3XSqTcaYnSKE_r03JsgBWnNfprGisYajTlA/edit?usp=sharing)
