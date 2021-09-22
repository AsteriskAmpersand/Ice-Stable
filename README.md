# Iceborne Community Edition #

Welcome to the download page for Iceborne Community Edition. Join us at https://discord.gg/xPDVbhZgFJ to follow the development of this mod!

Iceborne Community Edition is a holistic rework of MHW: Iceborne. We attempt to address multiple major gripes a significant section of the playerbase had with an otherwise great game. The goal of ICE is to preserve the spirit of the game's core design, but improve on its limitations and flaws to provide a more enjoyable experience that can still be recognized as Monster Hunter gameplay.

- - - -

# Installation Guide #

## First Time Installation ##
Follow these steps if you've never installed ICE before:
1. Install Stracker's Loader and all it's prerequisites found here: <https://www.nexusmods.com/monsterhunterworld/mods/1982/>
2. Click on the green "Code" button and then "Download ZIP".
3. Extract the contents of the ZIP directly to your root Monster Hunter World install folder (where MonsterHunterWorld.exe is located).
4. When asked about file conflicts, overwrite any existing files.
5. (Optional) Install any mods you want to use with ICE in the "ICE\ntPC" folder. Install any plugins in "ICE\plugins".
6. Launch game in Admin Mode (required only on first time installs)
7. Check save file management section when you are asked to create a new save file when launching the game.

## Updating Or Re-installing ICE ##
Follow these steps if you want to grab the latest version of ICE:
1. Click on the green "Code" button and then "Download ZIP".
2. Extract the contents of the ZIP directly to your root Monster Hunter World install folder (where MonsterHunterWorld.exe is located).
3. When asked about file conflicts, overwrite any existing files.

## Turning ICE ON / OFF ##
ICE supports easy on/off in case you want to switch back and forth between mods.
- If you want to disable ICE: Rename the main ICE folder to anything else.
- If you want to re-enable ICE: Rename the main ICE folder back to "ICE"
- If you want to reinstall ICE just download from repo and unzip into MHW.exe folder

## Uninstallation ##
If you want to uninstall ICE:
- (Easy Version) In the Monster Hunter World folder, delete the main ICE folder.
- (Full Version) In the Monster Hunter World folder, delete the main ICE folder, cryptbase.dll, loader.dll, ice_managed_code.dll. Then reinstall Stracker's Loader if you need it for other mods: <https://www.nexusmods.com/monsterhunterworld/mods/1982/>

## Migrating from old ICE ##
If you were trying ICE before we switched to github downloads, follow these one-time steps to update your ICE install:
1. Delete your old nativePC folder meant for ICE (save any mods you still want though, if you don't have a copy elsewhere)
2. Click on the green "Code" button and then "Download ZIP".
3. Extract the contents of the ZIP directly to your root Monster Hunter World install folder (where MonsterHunterWorld.exe is located).
4. When asked about file conflicts, overwrite any existing files.
5. (Optional) Install any mods you want to use with ICE in the "ICE\ntPC" folder. Install any plugins in "ICE\plugins".
6. Launch game in Admin Mode (required only on first time installs)
7. Check save file management section when you are asked to create a new save file when launching the game.

- - - -

# Save File System #
ICE manages your character data in a separate save file named "SAVEDATA_ICE". The game normally uses the file named "SAVEDATA1000". These are both located in the standard save folder found at: "...\Steam\userdata\<steamId>\582010\remote\"

Because ICE encorporates changes that are not backwards compatible with the base game, it is necessary for us to separate your save data in this way.

If enabled, ICE will automatically use the "SAVEDATA_ICE" save file. Otherwise, your game will continue to use the "SAVEDATA1000" save file as normal.
Should you want to copy your progress over to ICE:
1. Remove "SAVEDATA_ICE" if it exists (or throw it another folder for safe keeping).
2. Make a new copy of "SAVEDATA1000".
3. Rename that copy to "SAVEDATA_ICE".

As always, it is recommended to make backups of your saves. It only takes one mistake to lose all your save data.

## Save File Management ##
If you boot up the game with ICE enabled for the first time and it says no save data detected, but you want to use your existing character data, then just follow these steps:
1. Hit yes to create a new ICE save but DON'T select a language.
2. If you want to start a new save file, then continue with the setup process and skip the rest of the steps. Otherwise...
3. Close the game after the game creates the save file but before selecting a language.
4. Navigate to your save folder at "...\Steam\userdata\<steamid>\582010\remote\".
5. Delete the "SAVEDATA_ICE" file that's in that folder.
6. Make a copy of your "SAVEDATA1000" file and rename that copy to "SAVEDATA_ICE"
7. Start the game again.

- - - -

# Change Log #

Coming soon. Check our discord's #change-log channel for now.
