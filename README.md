# Iceborne Community Edition #

Welcome to the download page for Iceborne Community Edition. Join us at https://discord.gg/xPDVbhZgFJ to follow the development of this mod!

Iceborne Community Edition (ICE) is an overhaul mod for MHW: Iceborne, driven by community feedback and suggestions. ICE preserves the spirit of the game's core design and direction, but offers improvements to the game in an effort to provide a more balanced and diverse experience for all hunters.

This mod is a work-in-progress, and still in developement. 

ICE is compatible with online play. ICE hunters are matched exclusively with other ICE hunters to prevent negatively affecting vanilla hunters.

Features:
- Smoother Progression: Play through at your own pace, without being held back by cutscenes or unreasonable grinds.
- Quality-of-Life Additions: Spend more time enjoying each hunt, and less time in menus or stuck in base.
- Clutch Claw Rework: Let the Clutch Claw take a backseat, as you re-experience the fast-paced combat of MHW as it was originally intended. 
- Weapon Moveset Reworks: Master the 14 weapon types in new ways, with increased depth and variety in optimal combos for hunters.
- Skill Reworks: Make more impactful choices when it comes to skill loadouts. More variety, more active skills, less passives.
- Bug Fixes: Play the game with less pesky bugs to hold you back.

- - - -

# Table of Contents #

- [ICE Manager](#ice-manager)
- [Legacy - Installation Guide](#installation-guide)
- [Legacy - Save File System](#save-file-system)
- [Known Issues](#known-issues)
- [Change Log](#change-log)
  - [General Changes](#general-changes)
  - [Weapon Changes (Stable Build)](#weapon-changes-stable-build)
  - [Weapon Changes (Experimental Build)](#weapon-changes-experimental-build)

- - - -

# ICE Manager #
As of the latest release. ICE now has a version manager. It can be found here: <https://github.com/AsteriskAmpersand/Ice-Experimental/releases>.

The ICE Manager simplifies the ICE install and update process. As well as transferring save files and mods on your first install.

![](https://cdn.discordapp.com/attachments/920464605367644200/985342975871680602/unknown.png)

- You can first pick whichever version of ICE you prefer (the manager allows switching versions with one click). 
- You can transfer your base game save file and mods to ICE (mods may not all be compatible, the game will tell you of this when first booting up). 
- You can also update from now on, simply by clicking the "Update" button.
- You can Disable and Enable ICE with a single click as well
- You can fully uninstall ICE if you so desire.



# Installation Guide #

This instructions are no longer necessary, simply grabbing the [ICE Manager](#ice-manager) should be all that you need to install ICE.

## First Time Installation ##
Follow these steps if you've never installed ICE before:
1. Install Stracker's Loader and all it's prerequisites found here: <https://www.nexusmods.com/monsterhunterworld/mods/1982/>
2. On this Github page, click on the green "Code" button and then "Download ZIP".
3. Extract the contents of the ZIP file to a temporary location (Desktop, Downloads, etc).
4. Copy all the contents within the "ice-stable-main" (or "ice-experimental-main") folder directly to your root Monster Hunter World install folder (default path is `...\Steam\steamapps\common\Monster Hunter World\`. You have the right folder if "MonsterHunterWorld.exe" exists in that folder).
5. When asked about file conflicts, overwrite any existing files.
6. (Optional) Install any mods you want to use with ICE in the `...\Monster Hunter World\ICE\ntPC\` folder. Install any plugins in `...\Monster Hunter World\ICE\ntPC\plugins\`.
7. Launch game in Admin Mode (required only on first time installs). 
8. Check save file management section when you are asked to create a new ICE save file when launching the game.

## Updating Or Re-installing ICE ##
Follow these steps if you want to grab the latest version of ICE:
1. Click on the green "Code" button and then "Download ZIP".
2. Extract the contents of the ZIP file to a temporary location (Desktop, Downloads, etc).
3. Copy all the contents within the "ice-stable-main" (or "ice-experimental-main") folder directly to your root Monster Hunter World install folder (default path is `...\Steam\steamapps\common\Monster Hunter World\`. You have the right folder if "MonsterHunterWorld.exe" exists in that folder).
4. When asked about file conflicts, overwrite any existing files.

## Turning ICE ON / OFF ##
ICE supports easy on/off in case you want to switch back and forth between mods.
- If you want to disable ICE: Rename the main ICE folder to anything else.
- If you want to re-enable ICE: Rename the main ICE folder back to "ICE"
- If you want to reinstall ICE just download from repo and unzip into MHW.exe folder

## Uninstallation ##
If you want to uninstall ICE:
- (Easy Version) In the Monster Hunter World folder, delete the main ICE folder.
- (Full Version) In the Monster Hunter World folder, delete the main ICE folder, cryptbase.dll, loader.dll, ice_managed_code.dll. Then reinstall Stracker's Loader if you need it for other mods: <https://www.nexusmods.com/monsterhunterworld/mods/1982/>

## Installing Other Mods with ICE ##
If you want to install mods alongside ICE, we strongly recommend hunters stick with cosmetic/visual mods only. Gameplay mods will likely cause conflicts and compatibility issues. If you do wish to try gameplay mods at your own risk, we ask you to be considerate of other hunters and play offline only, just like you would without ICE.
1. Install mods in the `...\Monster Hunter World\ICE\ntPC\` folder. This ntPC folder is used instead of nativePC, while ICE is enabled.
2. Similarly, plugins are installed in the `...\Monster Hunter World\ICE\ntPC\plugins\` folder.
While ICE is enabled, mods and plugins are only loaded from the above folders. This allows you to manage your mods for ICE separately.

## Migrating from old ICE ##
If you were trying ICE before we switched to GitHub downloads, follow these one-time steps to update your ICE install:
1. Delete your old nativePC folder meant for ICE (save any mods you still want though, if you don't have a copy elsewhere).
2. On this Github page, click on the green "Code" button and then "Download ZIP".
3. Extract the contents of the ZIP file to a temporary location (Desktop, Downloads, etc).
4. Copy all the contents within the "ice-stable-main" (or "ice-experimental-main") folder directly to your root Monster Hunter World install folder (default path is `...\Steam\steamapps\common\Monster Hunter World\`. You have the right folder if "MonsterHunterWorld.exe" exists in that folder).
5. When asked about file conflicts, overwrite any existing files.
6. (Optional) Install any mods you want to use with ICE in the `...\Monster Hunter World\ICE\ntPC\` folder. Install any plugins in `...\Monster Hunter World\ICE\ntPC\plugins\`.
7. Launch game in Admin Mode (required only on first time installs)
8. Check save file management section when you are asked to create a new save file when launching the game.

- - - -

# Save File System #
This instructions are no longer necessary, simply grabbing the [ICE Manager](#ice-manager) should be all that you need to transfer your save file. First install ICE through the manager (on your preferred version), and then simply click Transfer Save.

ICE manages your character data in a separate save file named "SAVEDATA_ICE". The game normally uses the file named "SAVEDATA1000". These are both located in the standard save folder found at: `...\Steam\userdata\<steamId>\582010\remote\`

Because ICE incorporates changes that are not backwards compatible with the base game, it is necessary for us to separate your save data in this way. This system also allows hunters to quickly switch between ICE and vanilla freely without having to swap out save files. If enabled, ICE will automatically use the "SAVEDATA_ICE" save file. Otherwise, your game will continue to use the "SAVEDATA1000" save file as normal.

As always, it is recommended to make backups of your saves. It only takes one mistake to lose all your save data.

## Creating Your ICE Save File ##
If you boot up the game with ICE enabled for the first time and it says no save data detected, but you want to use your existing character data, then just follow these steps:
1. Hit yes to create a new ICE save but DON'T select a language.
2. If you want to start a new save file, then continue with the setup process in-game and skip the rest of the steps. Otherwise, continue with step 3.
3. Close the game after the game creates the save file but before selecting a language.
4. Navigate to your save folder at `...\Steam\userdata\<steamid>\582010\remote\`.
5. Delete the "SAVEDATA_ICE" file that's in that folder.
6. Make a copy of your "SAVEDATA1000" file and rename that copy to "SAVEDATA_ICE"
7. Start the game again.

## Updating Your ICE Save File ##
If you've continued to play on your vanilla save and want to overwrite your ICE save progress, then follow these steps:
1. Remove "SAVEDATA_ICE" if it exists (or throw it into another folder for safe keeping).
2. Make a new copy of "SAVEDATA1000".
3. Rename that copy to "SAVEDATA_ICE".

## Photo Data ##
ICE currently does not isolate photo/image data. As such, if you do use the in-game photo feature, make sure to backup the 3 photo data files in your save folder at `...\Steam\userdata\<steamid>\582010\remote\`. If the game detects a mismatch between your save file and your photo data, it will ask to create a new one, which would delete your photo data in the process.

- - - -

# Known Issues #

## Language Support ##
ICE currently only officially supports English language for text. You can use any voice language you prefer though.

## Incorrect Text / Descriptions ##
Much of the text found in ICE has not yet been updated to reflect changes made to the game. Our primary focus is on testing gameplay changes first, in an effort to avoid losing time and effort to keep descriptions up-to-date as we try different changes. Once we're further in development, we'll put more effort into covering changes we've made, and also updating descriptions from the game that are inaccurate or ambigious.

## Photo Data ##
ICE currently does not isolate photo/image data. As such, if you do use the in-game photo feature, make sure to backup the 3 photo data files in your save folder at `...\Steam\userdata\<steamid>\582010\remote\`. If the game detects a mismatch between your save file and your photo data, it will ask to create a new one, which would delete your photo data in the process.

- - - -

# Change Log #

## General Changes ##

### ──────────【 Multiplayer / Matchmaking 】────────── ###
While ICE is installed and enabled, hunters will only be matched with other ICE hunters. This is true when using matchmaking to find sessions or when creating/joining SOS. This is done for compatibility reasons and also out of courtesy to non-ICE hunters, so that non-ICE lobbies are not negatively impacted by any changes or differences in gameplay. Unlike other gameplay altering mods, hunters can freely play online with ICE.

### ──────────【 Clutch Claw Rework 】────────── ###
The dominance of the Clutch Claw has been drastically reduced to bring back the original combat pacing from base World. The goal is for softening to be a strong optional tool for the Hunter to use as desired, rather than a required component in general play.
- Softening effect on monster HZV has been reduced to `HZV+5` (down from `0.75*HZV + 25`).
- Monster "Clagger" behavior has been removed. Instead monsters will flinch, trip, and topple like they used to, before Iceborne.
- Clutch Claw weapon attacks:
  - All weapons can now soften with a single use, as if they are heavy weapons.
  - Most weapons can now generate slinger ammo, as if they are light weapons.
  - Clutch Claw Boost skill (Shaver Decoration) no longer has any effect for now.

### ──────────【 Monster Hitzones 】────────── ###
Since Capcom balanced Monster hitzone values (HZV) in Master Rank to accommodate the powerful effects of softening, some Monster hitzone values have been rebalanced with the following general goals:
- Compensate for the Clutch Claw nerfs as necessary.
- Ensure all hunter weapons have primary weakzones to aim for, without the need for softening.
- Ensure that secondary weakzones that previously required softening, are either always weakzones or can still become weakzones.

Full details for individual monsters can be found here: https://docs.google.com/spreadsheets/d/1nzN2zYD1VbeEuKGlrYPRDZPHjfyy0y-SawwSEaTZ8OQ/edit?usp=sharing

In addition, the following monsters received changes that are worth calling out specifically.

- Alatreon:
  - Head & Neck: Shot HZV increased to 50 (up from 30).
  - Body: Shot HZV decreased to 30 (down from 45).
  - Arms: Shot HZV increased to 40 (up from 20).
- Behemoth:
  - Head: Blunt HZV increased to 65 (up from 55).
  - Arms: Blunt HZV increased to 45 (up from 40).
- Lavasioth:
  - "Broken" HZVs for Head, Body, Legs, and Tail increased to match "Heated" HZVs.
  - Various HZVs raised to prevent bouncing with White or Purple sharpness.
- Lunastra:
  - Head: Sever HZV increased to 45 (up from 40) for both HR and MR.
  - Body: Sever and Blunt HZV increased to 20 (up from 17) for MR.
  - Back: Sever and Blunt HZV increased to 20 (up from 17) for MR.    
  - Hindlegs:
    - Sever HZV increased to 45 (up from 30) for both HR and MR.
    - Blunt HZV increased to 40 (up from 25) for both HR and MR.
    - > This change makes the hindlegs a proper secondary weakzone for Blademasters.
  - Wings:
    - Shot HZV increased to 45 (up from 40) for both HR and MR.
    - > This change makes the wings a proper secondary weakzone for Gunners.
- Kulve Taroth (MR):
  - All HZVs changed to match those found in HR.
- Namielle:
  - Sever, Blunt, and Shot HZVs increased while in Normal state.
  - Fire HZVs increased while in Dehydrated state.
  - > These changes partially reduce the drastic swings in weaknesses across the two states.
- Uragaan:
  - Forearms: Sever and Blunt HZV increased to 40 (up from 25 and 30).
- Velkhana:
  - Arch-Tempered HZV modifiers:
    - Shot HZV Multipliers increased to 1.1x/1.0x/0.9x (up from 1.0x/0.8x/0.6x)
    - These multipliers ensure that the head hitzone still counts towards WEX zones for gunners under the following conditions:
      - Any time during aura Lv1
      - Any time during aura Lv2
      - Tenderized or broken head during aura Lv3
    - > These values were chosen to follow what we assume to be Capcom's original intent. They are below tenderized values in the vanilla softening formula and below melee multipliers values.

### ──────────【 Progression 】────────── ###

#### 【 Master Rank 】 ####
Master Rank experience gain has been doubled between MR25 and MR100 to help reduce the long grind that is required to unlock augments and play with other players in their Guiding Lands. While this grind may have served a purpose early on in Iceborne, the existence of DLC content that can be accessed immediately at low MR makes this grind awkward and out of place.

#### 【 Guiding Lands 】 ####
The Guiding Lands total zone experience cap mechanic has been disabled. Normally, a hunter would have to complete around 7100+ hunts in Lv7 GL zones in order to level all their zones to 7. While this did add a long term goal and encouraged multiplayer sessions for sharing GL zones, we find this unnecessary as:
1. The requirement was far too extreme for the vast majority of players to ever make a real dent in, let alone fully complete.
2. The Iceborne multiplayer community is naturally diminishing over time.

#### 【 Guaranteed Decorations 】 ####
Certain Decorations are now guaranteed to drop at least once during game progression. These were added for decorations that are particularly game changing and considered mandatory for certain weapons or playstyles.
<https://cdn.discordapp.com/attachments/920464605367644200/1001848843232620625/unknown.png>

#### 【 Decoration Drop Rates 】 ####
Decoration drop rates have been completely reworked and drastically improved.
- Decorations are classified by their value, which is based on the strength and usability of skills provided.
- Higher value decorations will drop from higher rarity Feystones. 
- Full details can be found here: <https://www.nexusmods.com/monsterhunterworld/mods/2162>

#### 【 Dracolites 】 ####
Dracolites have been added to Guiding Lands drop tables, providing hunters the option to continue upgrading their Safi'Jiiva weapons outside of the siege should either the siege not be available, or because they want some more variety in their hunts.

#### 【 Guiding Lands Materials 】 ####
- Guiding Lands Material mining and gathering rates have been strongly boosted.
- Full details can be found here: <https://www.nexusmods.com/monsterhunterworld/mods/2164>

#### 【 High Rank Augments 】 ####
Smithy costs for the following have been adjusted to better balance material usage in High Rank, and allow Rarity 6 weapons to act as a stronger progression step before Rarity 7 or 8 augmented weapons.
- Augments for Rarity 6 weapons changed to use 1x Streamstone instead of 1x Warrior's Streamstone.
- Augments for Rarity 7 weapons changed to use 1x Warrior's Streamstone (down from 2x Warrior's Streamstones).

New melding recipes have been added at the Elder Melder to allow hunters to trade Warrior's and Hero's Streamstones. See details for Elder Melder under [Quality of Life](https://github.com/AsteriskAmpersand/Ice-Stable#-quality-of-life-) for more details.

### ──────────【 Skills 】────────── ###
While a more comprehensive rework and rebalancing of skills is planned for ICE in the future, some skills have been tweaked in the mean time with the an emphasis on increasing the variety of competitive options for hunters. This is mainly accomplished by:
1. Changing skills to have a more meaningful impact on gameplay.
2. Increasing the value of skills at lower levels.
> Weapon-specific interactions with certain skills will be covered in each weapon's section instead of here.

#### 【 General Changes 】 ####
- Coalescence:
  - Attack bonus changed to 6/12/18 (was 12/15/18).
- Flinch Free:
  - "Brace Jewel 3" decoration size decreased to Lv1 (from Lv3).
  - Now affects airborne launches from other hunters. Lv2 will reduce the effect to a normal trip. Lv3 will negate the launches entirely. (See "Airborne Launches" under "Quality of Life" section for more details)
- Focus:
  - Bonus gauge generation increased to 10/18/25% (up from 5/10/20%).
  - > This change helps gauge-based weapons reach certain meaningful breakpoints.
- Fortify:
  - Duration increased to 9.1 hours (up from 50 minutes). 
  - > This partially reverts a nerf from IB, as Capcom's nerf only encouraged players to restart their Guiding Lands session every 50 minutes, rather than addressing any balance issues with Fortify.
- Heroics: Base Attack bonus changed from 0/5/5/10/15/25/40% to 5/10/15/20/25/30/40%.
- Item Prolonger:
  - Increased bonus to 33%/66%/100% (from 10%/25%/50%).
- Maximum Might:
  - Affinity bonus changed to 10%/20%/30%/40%/50% (from 10%/20%/30%/40%/40%).
  - Max Stamina time requirement changed to 0/0/0/0/0 (from 5/5/5/5/0).
  - Lingering buff duration changed to 0/0/0/1/2 (from 2/3/3/4/0).
  - Lingering buff duration changed to only apply at level 4 (1 second) and level 5 (2 seconds).
- Non-Elemental Boost:
  - Base Attack bonus increased to 10% (up from 5%).
  - > This reverts a nerf from IB.
- Power Prolonger: 
  - Dual Blades & Switch Axe bonus decreased to 1.15x/1.30x/1.40x (down from 1.3x/1.6x/2.0x).
  - Long Sword, Charge Blade, & Insect Glaive bonus changed to 1.15x/1.30x/1.40x (was 1.1x/1.2x/1.4x).
- Quick Sheathe:
  - Speed bonus changed to 15/30/40% (from 10/20/40%).
- Weakness Exploit:
  - Affinity bonus changed to 15/30/50%. Softening requirement removed. 
  - > This reverts a nerf from IB and is intended to reduce reliance on Clutch Claw softening.

- Critical Element / True Critical Element (Set Bonus Skill):
  - Great Sword multipliers decreased to 1.35x/1.55x (down from 1.5x/1.7x).
  - Hunting Horn multipliers decreased to 1.35x/1.55x (down from 1.5x/1.7x).
- Critical Status / True Critical Status (Set Bonus Skill):
  - Great Sword multipliers decreased to 1.2x/1.4x (down from 1.4x/1.6x).
  - Hunting Horn multipliers decreased to 1.2x/1.4x (down from 1.4x/1.6x).
- Dragonvein Awakening / True Dragonvein Awakening (Set Bonus Skill):
  - Element Limit Override increased to 3.5x/4.0x of Base Element (up from 2.2x/2.55x generally, up from 1.8x/2.35x for Bowguns).
  - Status Limit Override increased to 3.5x/4.0x of Base Status (up from 1.7x/2.0x).
- Element Conversion (Set Bonus Skill):
  - Conversion rate increased to 8x for all weapons (up from 5x, or 2x for Bowguns).
  > This change brings the power level of the Alatreon set close to other element-based sets, allowing it to be used as a competitive alternative.
- Master's Touch (Set Bonus Skill):
  - Changed from triggering on critical hits to triggering on hitting weak spots.

### ──────────【 Equipment 】────────── ###

#### 【 Element/Status Balancing 】 ####
Some weapon types have been rebalanced to increase the variety in competitive equipment options for hunters to choose from. Some weapons will be able to better take advantage of at least the element/status available on their weapon, despite optimizing for Attack overall. Other weapons may now be able to run full element builds for certain playstyles or specific matchups.

#### 【 Armor Changes 】 ####
While a more comprehensive rework and rebalancing of armors is planned for ICE to increase the variety in build options for hunters that have meaningful impact on gameplay (with effects like Frostcraft from Velkhana), some specific sets have been adjusted in the mean time to preserve the limited options the game already did offer.

> Dev Comment: We understand these changes result in a decrease in the endgame power of hunters. While these endgame sets served as a nice final reward from Capcom for "finishing" the game, we don't think the power creep introduced by these sets are healthy in the context of ICE where we will be continually adding to the game. If/when we get around to incorporating additional endgame content, we may come back to revisit these changes when it's appropriate to have gear at these power levels.

- Fatalis and Velkhana Gamma Sets have been reduced in skills and deco slots. Fatalis Set no longer has access to Transcendence.
- These sets should still be competitive compared to options before their introduction.
- Changes to armors will be tracked separately on the Armor Spreadsheet.

#### 【 Weapon Changes 】 ####
Safi'Jiiva Light Bowguns:
  - Ammo tables have been updated to match Aquashot, but for each of their respective element types.
Fatalis Weapons:
  - Normalized (with the exception of LBG) to 340 Attack, -30% affinity.
  - > While weapons are normally dealt with on a more specific basis, this is a cross-weapon nerf that was necessary both because of the inconsistencies it generates with weapon progression as well as the aberrant stat values it had in specific outliers.

#### 【 Augments and Upgrades 】 ####
- Health Regen augment:
  - Healing Effect:
    - High Rank effect decreased to 7%/11%/15% (down from 10%/15%/20%)
    - Master Rank effect changed to 5%/8%/11%/14% (was 7.5%/9%/11%/14%)
  - Cooldown:
    - For melee weapons, cooldown between procs decreased to 0.00s (down from 0.2s).
    - For ranged weapons, cooldown between procs decreased to 0.125s (down from 0.2s).
    - > The above changes were made to avoid inconsistent healing rates as result of movesets, weapon mechanics, and the engine's inability to correctly handle variable frame rates. Healing on ranged weapons will be virtually unchanged compared to intended rates from vanilla.
- Awakened Abilities:
  - Attack V: Attack bonus for Greatsword and Hammer increased to 10 (up from 9), to match other weapons.
  - Attack VI: Attack bonus for Greatsword and Hammer increased to 15 (up from 14), to match other weapons.

#### 【 Stat Limits 】 ####
- Attack Limit increased to 3.0x of Base Attack (up from 2.0x). This reverts a nerf from IB.
- Element Limit increased to 3.0x/+30 of Base Element (up from 1.6x/+15 generally, up from 1.57x/+15 for Bowguns).
- Status Limit increased to 3.0x of Base Status (up from 1.6x).
- Stun Buildup Limit increased to 3.0x of Base Stun Buildup (up from 2.0x).
- Exhaust Buildup Limit increased to 3.0x of Base Exhaust Buildup (up from 2.0x).
- Mount Buildup Limit increased to 3.0x of Base Mount Buildup (up from 2.0x).

### ──────────【 Quality of Life 】────────── ###

#### 【 User Interface Changes 】 ####
- Equipment UIs now show true Attack (aka Raw) and true Element Damage/Buildup values for weapons.
  - > This removes the useless bloat multipliers that were artificially inflating numbers in UIs, but weren't actually being used by the game for any calculations.
- Chat UI:
  - Maximum message length increased to 60 (up from 40).
  - The selected chat channel no longer changes during certain actions (joining party/session/etc).
- Quantity selection UIs now support two new behaviors when increment/decrementing by 1:
  - Decrementing below 1 will now loop around to the maximum possible quantity.
  - Incrementing above the maximum possible quantity will now loop around to 1.
  - > These changes allow faster buying, selling, or melding of full stacks of items.
- Many UIs have been made more responsive to inputs and interactions. Some examples are listed below.
  - Start Menu:
    - Intro and outro animations sped up.
    - Automatically skips the intro animation without needing a "Skip Animation" input.
  - Quest Board:
    - Automatically accelerates the camera zoom effect without needing a "Skip Animation" input.
    - Quest list loading delay removed.
  - Menu Lists (Item Box, NPC options, etc):
    - Removed delay between each option fading in.
  - Other UIs:
    - Intro and outro animations sped up.
- Item Loadout and Equipment Loadout maximum name length increased to 20 (up from 16).

#### 【 Systems Changes 】 ####
- Despawn time for item drops from Monsters increased to 30 minutes (up from 1 or 2 minutes).
  - > This was done to help avoid situations where a hunter has to choose between interrupting their epic fight or forfeiting their rightfully earned loot. This wasn't a very interesting decision, in our opinion.
- Cutscenes:
  - A cutscene skip option has been enabled on most cutscenes in the game. Given most players will be experiencing ICE as a second (or later) playthrough, this QoL improvement should help shorten the time required to complete main story quests across all ranks.
  - > This is still a work-in-progress feature. Some cutscene audio might not skip correctly due to not being defined by the game as cutscene audio.
- Quest End Timer:
  - The timer for returning to base can now be skipped by holding the "Cancel Animation" input for 2 seconds ("Options" on PS, "Menu" on XB, X on PC).
- Astera Lift System:
  - Hunters can now utilize the lift system from the entrance of Astera, where they generally arrive after quests or expeditions (in front of the Resource Center).
  - When traveling to the "Tradeyard" using the lift system, the hunter will now arrive in the center of the Tradeyard.
  - > These changes are intended to decrease the amount of downtime that would otherwise be required to navigate around Astera, allowing hunters to spend more time hunting and less time walking.
- Botanical Research Center:
  - Fertilizer usage limit per quest removed (was 1 per quest).
  - Fertilizer maximum stackable duration increased to 20 quests (up from 9).
  - > Theses changes remove the constant attention required to maintain the Botanical Research Center. Hunters will only have to check on their BRC to reapply fertilizers as often as they need to collect their harvests (about every 15 to 20 quests once fully upgraded). These changes also make it so that restarting fertilizers (if expired) isn't a significant hassle.
  - Fertilizer balancing:
    - Research Point costs for Mega Fertilizer, Choice Mushroom Substrate, Thick Summoner Jelly, and Ancient Catalyst have been reduced. 
    - Ancient Catalyst duration increased to 5 quests (up from 4), to justify its higher cost relative to normal Catalyst.
    - > Since these fertilizers have lost their main advantage of allowing hunters to stack fertilzers faster between quests, they are now positioned as slightly more efficient versions of the basic fertilizers.
- Elder Melder:
  - Seasonal event tickets can be melded from 2 similar event tickets (down from 3).
  - Whetfish Fin and Whetfish Fin+ can be melded. The plus variant is unlocked in MR.
  - High Rank augment materials:
    - Any of the 7 types of Warrior's Streamstones can be melded from 2 Warrior's Streamstones of any other type.
    - Any of the 7 types of Hero's Streamstones can be melded from 2 Hero's Streamstones of any other type.
    - 2 Warrior's Streamstones can be melded from a single Hero's Streamstone of the same type.
    - Hero's Streamstones can be melded from 4 Warrior's Streamstones of the same type.
  - Guiding Lands materials:
    - Elder Dragonvein Bone can be melded from Elder Spiritvein Bone.
    - Dragonvein Solid Bone can be melded from Spiritvein Solidbone.
    - Heavy Dragonvein Bone can be melded from Spiritvein Slogbone.
    - > These options were added to allow hunters to directly downgrade tempered bones into non-tempered variants, similar to other Guiding Lands materials.
- Steamworks:
  - The time required to complete each three-button round has been drastically reduced.

#### 【 Combat Changes 】 ####
- Mantle Expiration:
  - When a mantle expires, it will now automatically be unequipped without any interaction from the hunter.
- Airborne Launches:
  - Hunters can now protect themselves from being launched airborne by other hunters, using any of the available options that would protect against being knocked onto their butts. For example, Flinch Free Lv2 will reduce the launch to a trip, and Flinch Free Lv3 will negate the launch entirely.
  - Monster attacks are unaffected by this change.
- Guarding with Shield Weapons:
  - Guarding behavior changed to ignore attacks from other hunters.
  - Hunters will still see a hit effect (sparks), but the guarding hunter no longer consumes stamina and does not get locked into any follow-up guard reaction animations.
  - This change does not affect how hunters react to attacks they cannot block (attacks from behind, unblockable attacks, etc).
  - > In vanilla, shield weapons experienced extra downsides compared to other weapons when fighting in close proximity with other hunters. In particular, Lance hunters could have their Counter Thrusts triggered early by another hunter, resulting in getting hit by the Monster attack that they were preparing to counter. With this change, these potentially frustrating situations are removed from the game.
  
### ──────────【 Bug Fixes 】────────── ###

- DPS Tick Fix: The engine components responsible for specifically handling ticking damage effects have been upgraded to mitigate the negative effects of frame rate on player damage output. In some cases, player damage could be reduced as much as 25% just for not playing at a stable 60fps. Some examples here: <https://bit.ly/MHWEffectsOfFPS>
- Corrected some attacks that were incorrectly gaining extra hits at lower frame rates.
- Moonshots Fix: Aim behavior has been adjusted for Bow and Bowgun at short ranges to mitigate the occurrence of projectiles that incorrectly fly straight up (seemingly towards the moon/sky) and completely miss the intended target. This is sometimes refered to as "moonshots" by the community. An example can be seen here around the midpoint of the clip: <https://twitter.com/Irh_umbreon/status/1409001644411408391>
- Other weapon-specific bug fixes will be covered in each weapon's section instead of here.

### ──────────【 Monster Changes 】────────── ###

#### ──────────【 Monster Hitzones / Softening 】────────── ####
Details for this section are covered under General Changes near the top of this Change Log.

#### ──────────【 Alatreon 】────────── ####
Due to element damage output increasing significantly on many weapon types, Alatreon's weapon-specific element topple multipliers have been adjusted. A lower multiplier means a weapon's element damage will count for less and the hunter will need to deal more total element damage to reach each topple.
- Great Sword modifier decreased to 0.8x (down from 1.1x).
- Hunting Horn modifier decreased to 0.8x (down from 1.0x).
- Gunlance modifier decreased to 1.0x (down from 1.1x).


## Weapon Changes (Stable Build) ##

### ──────────【 Slinger 】────────── ###

The following changes to Slinger damage are intended to address one or more of the following goals:
1. Incorporate damage scaling on all Slinger ammos to allow them to not fall behind as the Hunter progresses through the game.
2. Balance Slinger Burst damage so it doesn't completely overshadow other options in early-game, due to Slinger Burst being balanced specifically around Master Rank.
3. Maintain "Field" ammos as niche utility options with the most value in early game, but ultimately low damage options due to their availability.
4. Balance "Monster" ammos to all have good value throughout progression, without being overpowered in early game.
  - Pierce Pods will continue to be the highest damage option.
  - Thorn Pods will continue to be high damage, with added Stun and Exhaust Buildup.
  - Bomb Pods will continue to be good against low HZV targets.
  - Dragon pods will continue to be best for Dragon damage and Elderseal Buildup, but will provide good general damage as well.
5. Remove some inconsistencies between normal and burst variants of some ammos.
  - Brightmoss now deals Thunder damage on both versions.
  - Bomb Pod now deals Fire damage on both versions.


- All Ammo Types:
  - Non-element damage now scales with Attack.
- Slinger:
  - Brightmoss:
    - Element Damage changed to 30 Thunder (was none), to match its burst variant.
  - Bomb Pod (Explosion):
    - MV changed to 30 HZI (was 35 Fixed Damage).
  - Pierce Pod:
    - MV decreased to 6 (down from 10).
  - Thorn Pod:
    - Initial Hit:
      - MV increased to 10 (up from 5).
      - Stun Buildup increased to 30 (up from 10).
      - Exhaust Buildup increased to 15 (up from 10).
    - Explosions:
      - MV decreased to 10 (down from 20).
      - Stun Buildup decreased to 30 (down from 45).
      - Exhaust Buildup decreased to 15 (down from 20).
  - Dragon Pod:
    - MV increased to 30 (up from 5).
- Slinger Burst:
  - Stone:
    - MV decreased to 10 (down from 15).
  - Scatter Nut / Crystalburst:
    - MV decreased to 12 (down from 18).
  - Bomb Pod (Explosion):
    - MV changed to 40 HZI (was 100 Fixed Damage).
    - Element Damage changed to 20 Fire (was none), to match non-burst variant.
  - Pierce Pod:
    - MV decreased to 8 (down from 20).
  - Thorn Pod:
    - Initial Hit:
      - Stun Buildup decreased to 30 (down from 90).
      - Exhaust Buildup increased to 15 (up from 10).
      - Generates 2 stuck pods (down from 3).
    - Explosions:
      - MV decreased to 10 (down from 20).
      - Stun Buildup decreased to 30 (down from 45).
      - Exhaust Buildup decreased to 15 (down from 20).
    - Dragon Pod Explosions:
      - MV increased to 15 (up from 5).
      - Element Damage decreased to 50 Dragon (down from 80 Dragon).
      
### ──────────【 Clutch Claw 】────────── ###

- Claw Shot:
  - Maximum range increased to 13m for Blademasters (up from 9m).
  - > This change makes Claw Shot's range consistent between Blademasters and Gunners.


### ──────────【 Great Sword 】────────── ###

#### 【 New Alternate Playstyle: Combo Great Sword 】 ####
The following changes are intended to offer a new playstyle option for GS that is competitive with the current TCS-focused playstyle, without replacing it. Combat will be focused around utilizing non-charging combo attacks to lead into Jumping Wide Slash as a powerful combo finisher. Finding openings to fit powered-up Jumping Wide Slashes safely, will be core to mastering this playstyle. This playstyle will favor elemental builds.
- New Combo System:
  - Overhead Slash, Wide Slash, and Rising Slash increase combo count by 1, up to a maximum of 3.
  - Jumping Wide Slash can be used immediately after the above moves by pressing △ + R2 on PS, or Y + RT on XB. 
  - Jumping Wide Slash's power level will match the Hunter's current combo count.
  - Side Blow, Tackle, and Slinger Burst can be used without resetting the current combo count.
  - Combo count resets when performing any other actions or attacks not mentioned above (idle, evading, charging attacks, sheathing, etc).
- Overhead Slash:
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Wide Slash:
  - MV increased to 39 (up from 26).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Rising Slash:
  - MV increased to 50 (up from 38).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Side Blow:
  - Stun buildup increased to 40 (up from 20).
  - Exhaust buildup increased to 30 (up from 15).
- Jumping Wide Slash:
  - MV increased to 80/120/150 (up from 75/96/118).
  - Element and Status Modifiers increased to 4.0x/6.0x/7.5x (up from 2.2x/3.15x/3.5x).
  - Partbreak Modifier increased to 1.2x/1.3x/1.4x (up from 1.0x/1.0x/1.0x).
  - Recovery frames can be partially canceled by sheathing.
- Wide Slash v2:
  - MV increased to 42 (up from 26).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Rising Slash v2:
  - MV increased to 54 (up from 41).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Side Blow v2:
  - Stun buildup increased to 50 (up from 30).
  - Exhaust buildup increased to 35 (up from 20).


#### 【 General Changes 】 ####
- Charged Slash:
  - Element and Status Modifiers increased to 1.20x/1.55x/1.80x (up from 1.0x/1.3x/1.5x).
- Strong Charged Slash:
  - Element and Status Modifiers increased to 1.65x/1.80x/2.05x (up from 1.4x/1.5x/1.7x).
- True Charge Slash:
  - First Hit:
    - Element Modifier increased to 1.2x (up from 1.0x).
    - Status Mod decreased to 0.0x (down from 1.0x). 
      - > This change prevents niche cases where the first hit might cause the monster to move out of range of the second hit.
  - Second Hit:
    - Element Modifier increased to 1.65x/1.8x/2.05x (up from 1.4x/1.5x/1.7x).
    - Status modifiers increased to 2.85x/3.00x/3.25x (up from 1.4x/1.5x/1.7x).
      - > This change compensates for the loss of status application on the first hit.
  - Second Hit (Power):
    - Element Modifier increased to 1.65x/1.8x/2.15x (up from 1.4x/1.5x/1.8x).
    - Status modifiers increased to 2.85x/3.00x/3.35x (up from 1.4x/1.5x/1.8x).
      - > This change compensates for the loss of status application on the first hit.
- Strong Wide Slash:
  - Element and Status Modifiers increased to 1.20x/1.55x/1.80x (up from 1.0x/1.3x/1.5x).
- Kick: 
  - Stun value increased to 20 (up from 10).
  - Exhaust value increased to 15 (up from 5).
- Clutch Claw Weapon Attack:
  - First Hit:
    - Element and Status Modifiers increased to 1.5x (up from 1.0x).
  - Second Hit + Repeated Hits + Final Hit:
    - Combined into a single larger hit.
    - MV changed to 90 (was at minimum 6+6+60).
    - Element and Status Modifiers changed to 3.0x (was at minimum 1.0x+0.5x+1.0x).
    - Partbreak Modifier changed to 1.5x (was 0.0x+0.0x+1.0x).
      - > This change compensates for the first hit having a Partbreak Modifier of 0.0x.
    - Softening Buildup changed to 70 (was 30+40+0).

### ──────────【 Sword & Shield 】────────── ###

#### 【 New Parry Option 】 ####
The following changes are intended to give Hunters an additional defensive option that fits the theme of the weapon (parrying with a buckler shield) while increasing variety in gameplay. Hunters that master this new technique will be able to weave counter-attacks against weaker Monster attacks into their existing play.
- Parry (previously Guard Slash):
	- Now has a guardpoint starting from 0.10s from the start of the animation, lasting 0.20s (12 frames at 60fps).
	- When hit during the guardpoint, small knockbacks will result in immediately counter-attacking with a Shield Bash. This Shield Bash can combo into Leaping Slash (△ on PS, Y on XB) or directly into Perfect Rush (O on PS, B on XB).
	- Consumes 25 stamina on use.
  - Most attacks that previously could combo into Backstep, now can also combo into Parry.
  - > Hunters will need to recognize and react accordingly to which attacks they can and cannot parry, as many Monster attacks will be too strong for a small shield. In addition, when comboing directly from Shield Bash into Perfect Rush, the Shield Bash will effectively replace the first hit in Perfect Rush I. Skilling for Guard is advised, to maximize the number of attacks that can be parried.

#### 【 Helm Breaker 】 ####
The Helm Breaker attack (aka Helm Splitter) has been reworked to offer a sword-based alternative to Falling Bash. This change provides Hunters with additional combo choices and allows them to choose between the benefits of sword vs shield attacks, just as they can for ground-based moves.
- Helm Breaker
  - Can now be performed in the air after a successful Charged Slash using △ + O on PS or Y + B on XB (was only available after scaling a wall).
  - Jump trajectory adjusted to be more similar to Falling Bash.
  - MV changed to 40+24+24 (was 14 per hit).
  - Element and Status Modifier changed to 1.0x+1.0x+1.0x (was 0.3x per hit).
  - Mount Buildup removed (was 25).

#### 【 Quality of Life Changes 】 ####
- Backstep (aka Backhop):
	- During a forward roll, Hunters can now hold a desired direction and queue a directional Backstep before the roll ends.
		- > Previously, early inputs would result in comboing into a backwards Backstep and late inputs would result in comboing into other attacks, leaving only a small 0.250s window that was difficult for Hunters to consistently hit. With this change, early inputs are no longer an issue.
	- When starting a Guard, the time available to input a Backstep safely has been increased to 0.417s (up from 0.283s).
		- > This increases the window that Hunters have by 50%, which should greatly increase the reliability of using Backstep right after a guard.
- Slinger Aim vs Slinger Burst Aim Mode Toggle:
	- The Hunter's current selected mode will now still be retained upon sheathing (previously was resetting to Slinger Aim Mode).

#### 【 General Changes 】 ####
Many of the following changes are targeted at one or more of the following goals:
- Increasing the variety of combos and options available to Hunters.
  - > Less used slashing attacks can now be better combined with existing high damage slashes (Lateral Slash + Return Stroke) to create longer and stronger combos without needing to utilize the weaker Spiral Slash as often. In addition, shield attacks can be comfortably used in place of slashes, allowing Hunters to trade only a small amount of damage for added Stun buildup.
- Reducing the dominance of Perfect Rush. 
  - > The changes to Perfect Rush's damage help provide shorter combos (Slash combos, Shield combos, Falling Bash, Helm Breaker) a chance at competing in shorter windows of opportunities, while still maintaining Perfect Rush's advantage of dealing high damage for larger windows. In many situations, it can be better to use other options if the Hunter does not have a large enough window to safely perform up to Perfect Rush II.

- Chop:
	- MV increased to 17 (up from 14).
- Side Slash:
	- MV increased to 14 (up from 13).
- Rising Slash:
	- MV increased to 15 (up from 14).
- Short Shield Bash:
	- MV increased to 15 (up from 6).
- Shield Attack:
	- MV increased to 20 (up from 8).
- Shield Bash:
	- MV increased to 20 (up from 16).
- Hard Bash:
	- MV increased to 36 (up from 31).
- Perfect Rush I:
	- MV decreased to 40+40+50 (down from 45+45+60).
- Perfect Rush II:
	- MV increased to 60 (up from 55).
- Slinger Burst:
  - Now combos into Charged Slash (O on PS, B on XB).
  - > Previously, only Slinger Burst into Perfect Rush I/II provided a strong option for gap closing into medium windows of opportunity (~5 seconds). With this addition, Hunters have a new option to trade damage for faster attacks through Falling Bash and Helm Breaker.
- Clutch Claw Weapon Attack:
	- Final Hit:
		- Partbreak Modifier increased to 2.35x (up from 1.00x).
		- > This change compensates for the first three hits having a Partbreak Modifier of 0.0x.

### ──────────【 Dual Blades 】────────── ###

#### 【 Demon Mode & Archdemon Mode 】 ####
Demon Gauge generation and consumption has been reworked in an effort to make the management of Demon vs Archdemon Mode a more impactful component of Dual Blades gameplay. These changes should provide Hunters more options for combos as they flow back and forth between the two modes. Demon Mode will continue to be the primary method of dealing high damage at the cost of stamina, while Archdemon Mode will offer supplemental damage while stamina regenerates.

- Demon Mode:
	- Stamina consumption increased to 10/s (up from 5/s).
	- Demon Gauge generation has been reduced overall.
		- Most attacks generate 2.75% per hit (up from 2.5%).
		- Heavier hitting attacks generate 5.5% per hit (up from 5%).
    - The last two hits of Sixfold Demon Slash generate 8.25% (down from 20% per hit).
		- > This mainly addresses specific moves that were disproportionately generating far more Demon Gauge than other moves, and trivializing gauge generation.
	- Automatically de-activates if the Hunter is sent flying by an attack, to avoid wasting stamina.
	- Turning Demon Mode Off:
		- When performed after an attack, the downward swing with both weapons now has an active hitbox with the following stats:
			- MV of 8+8
			- Element and Status Modifier of 0.6x+0.6x 
		- Can be performed sooner after Blade Dance.
		- > These changes allow Demon Mode attacks to flow directly into Archdemon Mode attacks, enabling the Hunter to continue fighting while regenerating stamina.

- Archdemon Mode:
	- Enables the use of Demon Mode Dashes.
		- Each dash will consume 5% Demon Gauge while not in Demon Mode.
		- > Known Issue: These dashes do not have a proper animation for handling weapon grip style (standard vs reverse). This will be fixed in a future update.
	- Rising Slash:
    - Uses Demon Mode versions with higher damage and faster animation.
    - Attack Speed increased by 20% while Archdemon Mode is active.
  - Double Slash:
    - Attack Speed increased by 20% while Archdemon Mode is active.
    - Damage has been enhanced (see General Changes section).
  - Double Slash Return Stroke:
    - Attack Speed increased by 20% while Archdemon Mode is active.
    - Damage has been enhanced (see General Changes section).
  - Circle Slash: 
    - Attack Speed increased by 20% while Archdemon Mode is active.
    - Damage has been enhanced (see General Changes section).
	- Left/Right Roundslash:
		- Consumes 5% Demon Gauge while not in Demon Mode.
		- Damage has been enhanced (see General Changes section).
	- Demon Flurry:
		- MV increased to 12+12+9+9+9+22+22 (up from 9+9+7+7+3+17+17).
		- Element and Status Modifier increased to 0.8x+0.8x+0.6x+0.6x+0.6x+1.5x+1.5x (up from 0.8x+0.8x+0.8x+1.0x+1.0x+1.0x).
		- Now combos into Demon Flurry Rush.
		- > These changes properly set up Demon Flurry as a strong Archdemon Mode attack that is worth its Demon Gauge cost, without overshadowing Demon Mode.

#### 【 Status Buildup Modifiers 】 ####
Each attack's Status Modifier has been increased to match their Element Modifier.

To understand the reasoning for this change, it is best to cover the history of these modifiers.
- During MHW, Dual Blades had a 1.0x modifier for both Element and Status on every attack. This was generally the case for most weapons (and still is the case even in Iceborne).
- With the launch of Iceborne (v10.10), Capcom was concerned about the power level of element-based builds, and some weapons received overly massive nerfs to their Element and Status Modifiers. For Dual Blades, they nerfed both modifiers by 20% to 60% depending on the attack (with Status being nerfed either the same or slightly more than Element).
- With the Stygian/Safi Update (v12.01), Capcom partially reverted the nerfs. Depending on the attack, some Element Modifiers nerfs were fully reverted or were reduced to only 40% compared to MHW. Some Status Modifiers were very slightly increased, but the majority were untouched.

While Iceborne did receive some significant increases in element-based build power (examples include additional Element Up skill levels, buffs to Critical Element multipliers, massive element multiplier on Purple Sharpness), the same cannot be said of status-based builds. As such, it is likely Capcom simply overlooked these Status Modifiers when they decided to go back and partially revert the Element Modifier nerfs.

#### 【 General Changes 】 ####
Most following changes are targeted at increasing the variety of combos and options available to Hunters:

- Double Slash:
  - MV increased to 9+12 (up from 8+10).
  - Element and Status Modifier increased to 0.7x (up from 0.6x).
- Double Slash Return Stroke:
  - MV increased to 12+15 (up from 9+10).
  - Element and Status Modifier increased to 0.9x (up from 0.6x).
- Circle Slash:
  - MV increased to 12+15+15 (up from 9+11+11).
  - Element and Status Modifier increased to 0.9x (up from 0.7x).
- Left/Right Fade Slash:
	- MV increased to 11+11 (up from 7).
	- Element and Status Modifier increased to 0.75x+0.75x (was 0.8x).
	- > This move found very little use in vanilla with such low damage and minor repositioning value. With this change, both Fade Slashes can be used to situationally loop and extend the Demon Slash combo, during windows of opportunity that are too short for stronger/longer follow-up attacks.
- Rising Slash (Demon Mode):
	- MV increased to 12 (up from 9).
	- > Rising Slash bridges many different moves, but was too heavily dragging down the efficacy of any combo that included it.
- Left/Right Roundslash:
	- MV increased to 19+11+7 (up from 15+7+5).
	- Element and Status Modifier increased to 0.8x+0.8x+0.8x (up from 0.6x+0.6x+0.6x).
	- > While the damage on these attacks may have seemed reasonable per hit, the damage was too low relative to animation length for a Demon Mode attack.
- Left/Right Double Roundslash:
	- MV increased to 24+14+9 (up from 19+11+7).
	- > While the damage on these attacks may have seemed reasonable per hit, the damage was too low relative to animation length for a Demon Mode attack.
- Special Claw Attack:
	- Claw Attack:
		- Can be performed outside of Demon Mode, if Archdemon Mode is active. Consumes 20% Demon Gauge if used in this way.
		- Can be performed after Left/Right Roundslash (L2 on PS, LT on XB).
		- Can be performed after Blade Dance (L2 on PS, LT on XB).
		- Can be performed after Demon Flurry (L2 on PS, LT on XB).
		- > Using a directional input in addition to the input indicated above, will instead result in performing an Evade Shot.
	- Spinning Rising Slash:
		- Element and Status Modifier increased to 1.25x+1.25x+1.25x+1.25x (up from 1.0x+1.0x+1.0x+1.0x).
	- > These changes allow Spinning Rising Slash to be used as a combo finisher, since the move can no longer be used to extend Monster Claggers in ICE.
- Clutch Claw Weapon Attack:
  - Final Repeated Hits:
    - Partbreak Modifier changed to 2.0x (was 0.0x).
    - > This change compensates for the first five hits having a Partbreak Modifier of 0.0x.


### ──────────【 Long Sword 】────────── ###

#### 【 Spirit Economy Rework 】 ####
Spirit generation and consumption has been reworked in an effort to make Spirit management a more impactful component of Long Sword gameplay. The new Spirit changes will offer Hunters a deeper system that better ties together the LS moveset. A summary of the biggest changes are listed here, but full details can be found in the General Changes section, along with explanations of the changes.
- Foresight Slash no longer generates 100% spirit on success, but it also no longer deletes 100% spirit on use. 
- Spirit regeneration buffs from Iai Slash and Spirit Helmbreaker have been drastically reduced.
- Spirit Roundslash no longer deletes remaining Spirit on use, however its cost has been increased.
- Spirit consuming moves have been adjusted where necessary to justify their Spirit costs.
- Spirit Decay has been removed.

#### 【 General Changes 】 ####
The following changes generally fall in one of a few categories:
- Adjustments to Raw vs Element damage balance to increase the variety in competitive weapon options
- Small buffs to bring up weaker or under-utilized moves
- Adjustments to Spirit consuming moves, to ensure their benefits match their Spirit costs
However, there is one notable change which has a large potential effect on playstyle: Iai Spirit Slash now can level up the Spirit Gauge on a successful counter, but at a cost of 35% Spirit. With this change, ISS is now a high risk and high reward alternative to FSS. Hunters now have the option to choose between these two counters with different strengths and weaknesses to suit a given situation, rather than relying heavily on Foresight Slash and Spirit Roundslash.
The full changes are as follows:
- Spirit Decay:
  - Spirit Decay has been removed (was 5% lost every 6 seconds, reset on attacks).
  - > This mechanic in theory encourages Hunters to be more aggressive, but not so much in implementation. Because of how lenient the timer is, and the fact that IS and SHB regen buffs disable decay entirely, the decay only really came into play on area transitions. As such, this change is intended for QoL purposes.
- Step Slash:
  - MV increased to 26 (up from 24).
- Overhead Slash:
  - MV increased to 24 (up from 21).
- Thrust:
  - Element and Status Modifiers decreased to 0.5x (down from 1.0x).
  - Spirit generation decreased to 10% (down from 12%).
- Rising Slash:
  - MV decreased to 15 (down from 18).
  - Element and Status Modifiers decreased to 0.7x (down from 1.0x).  
- Fade Slash: 
  - Spirit generation decreased to 24% (down from 26%).
  - Combo timings now match Lateral Fade Slash timings more closely (was slower).
- Lateral Fade Slash:
  - Spirit generation decreased to 24% (down from 26%).
- Spirit Blade I:
  - Without Spirit: MV increased to 18 (up from 14).
  - With Spirit: MV increased to 32 (up from 26).
- Spirit Blade II:
  - MV increased to 32 (up from 30).
- Spirit Blade III:
  - MV increased to 15+20+35 (up from 14+19+34).
- Spirit Roundslash:
  - Recovery & sheathing animation length reduced.
  - MV increased to 52 (up from 38).
    - > DPS output now above normal attacks, but still below other Spirit attacks.
  - Spirit Cost increased to 35% (up from 25%).
  - Spirit deletion after use has been removed (was deleting 100% spirit).
  - On successful attack at Red Gauge: 10% Spirit is refunded.
- Spirit Thrust:
  - MV decreased to 24 (down from 26).
  - Spirit generation decreased to 0% (down from 10%).
  - Partbreak Modifier decreased to 0.0x (down from 1.0x).
  - > Avoids situations where flinch/trips on first hit cause the rest of the attack to miss.
- Spirit Helm Breaker:
  - MV decreased to 10/15/24 (down from 10/15/25).
  - Element and Status Modifiers increased to 0.4x/0.6x/1.0x per Gauge level (up from 0.3x).
  - Last Hit:
    - Partbreak Modifier increased to 4.0x (up from 3.0x).
    - > Compensates for Spirit Thrust having a Partbreak Mod of 0.0x.
  - Now additionally combos into Fade Slash or Lateral Fade Slash.
  - Reliability increased slightly.
  - Red Gauge: Spirit regen buff changed to 2%/s for 30 seconds (was 6.67%/s for 15s).
  - White/Yellow Gauge: Spirit regen buff changed to 2%/s for 20 seconds (was 6.67%/s for 10s).
- Foresight Slash:
  - Spirit cost increased to 25% (up from 10%).
  - Spirit deletion after use has been removed (was deleting 100% spirit).
  - Spirit generation on successful counters decreased to 25% (down from 100%).
  - > In vanilla, FSS's ability to instantly fill the Spirit bar (or delete the bar on failed counters) negated most of the value in generating Spirit with other moves. With these changes, FSS is no longer a Spirit generator, but it still remains a powerful defensive tool.
- Special Sheathe:
  - Quick Sheathe bonus effect changed to apply fully to sheathing animation.
  - Upon sheathing, can be canceled by rolling after a 1 second delay.
- Iai Slash:
  - MV decreased to 16+12 (down from 18+13).
  - Spirit generation increased to 5% per hit (up from 0%).
  - Spirit regen buff changed to 2%/s for 20 seconds (was 6.67%/s for 15s).
  - Successful counter changes buff duration to 30 seconds.
  - Now combos into Spirit Blade II (was previously Spirit Blade I).
- Iai Spirit Slash:
  - On successful counters, upgrades Spirit Gauge by one level.
  - Spirit Cost increased to 35% (up from 0%).
  - On successful counters at Red Gauge: 10% Spirit is refunded.
  - > With these changes, ISS is now a high risk and high reward alternative to FSS. Hunters now have the option to choose between these two counters with different strengths and weaknesses to suit the situation.
  - The damage and properties of the first hit have been moved into the second hit.
    - MV changed to 0+78/0+92/0+120 by Gauge level (was 19+55/31+72/39+86).
    - Element and Status Modifiers changed to 0.0x+2.0x (was 1.0x+1.0x).
    - Partbreak Modifier changed to 0.0x+1.0x (was 0.0x+1.5x).
  - Can now combo into Fade Slash or Lateral Fade Slash.
  - Canceling recovery animation with dodge roll can now be done slightly earlier.
- Clutch Claw Weapon Attack:
  - Repeated Hits:
    - MV increased to 18 (up from 6).
    - Element and Status Modifier increased to 0.6x (up from 0.2x).
    - Spirit generation increased to 10% per hit (up from 5%).
    - Overall delay between hits increased to 0.21 seconds (up from 0.07).
    - > These changes increase the damage per hit by 3x, but reduce the number of hits by 3x.
    - Partbreak Modifier increased to 1.4x (up from 1.0x).
      - > This change compensates for the first hit having a Partbreak Modifier of 0.0x.

#### 【 Quality of Life 】 ####
- Spirit Gauge HUD components sharpened for improved visual clarity.
- A subtle mark has been added to the gauge, representing the 35% Spirit needed for Spirit Roundslash and Iai Spirit Slash.

### ──────────【 Hammer 】────────── ###

#### 【 Power Charge Dash Addition 】 ####
- Power Charge when you are already in Power Charge State instead starts a dash which removes Power Charge State and instead sets the Charge Level to 3. This move is treated as part of a Charge and can combo into any Charge follow-up or continued into a Charge.
	
#### 【 Combo Continuation 】 ####
The following combo continuation is intoduced and is inteded to be a possible continuation of the above listed addition of the Power Charge Dash.
- Spinning Bludgeon into Spinning Strong Upswing can now combo into Big Bang IV
- By Releasing R without Directional Input it combos into [Half] Brutal Big Bang
- By Releasing R with Directional Input it combos into Spinning Bludgeon
- By Holding R through it, it leads back into Charging.
- The Dash has 30 frames of Hyperarmor (Frame 10 to Frame 40)

#### 【 Multiplayer Playability 】 ####
Certain moves for Hammer lacked the necessary innate knockback resistance needed to be appropriately used in multiplayer, despite their core role in Hammer gameplay. The following moves will now grant the Hunter innate minor knockback resistance (roughly equivalent to Flinch Free III):
- Big Bang Combo
- Side Slap -> Overhead Smash II -> Upswing Combo

### ──────────【 Hunting Horn 】────────── ###

#### 【 Draw Attack 】 ####
Forward Smash (aka Forward Slam) will no longer be performed when drawing the weapon while moving. Instead, the Hunter will now simply perform a draw motion to unsheathe the weapon onto their shoulder. The Hunter can choose to continue moving, or input an attack during the draw motion. This allows Hunters to perform any of their normal moves (to play a note they desire) or perform various recitals, greatly enhancing the flexibility of the weapon.

> Known Issues: The animations and transitions for the new draw animation is unfinished, and will not look smooth for the time being. This will be addressed later.

#### 【 Melody Changes 】 ####
- Attack Up (L):
  - Can be played with Purple + Red + Orange + Red (was previously Purple + Orange + Orange + Red).
- Element Attack Boost S/L:
  - Element Damage bonus increased to +15%/+20% (up from +8%/+10%).
- Element Effectiveness Up:
  - Element Damage bonus changed to +5% (was +5%, +8%, or +10% depending on Element Attack Boost).
- Earplugs S:
  - Replaced by Earplugs L
- Wind Pressure Negated:
  - Replaced by All Wind Pressure Negated

#### 【 General Changes 】 ####
Hunting Horn has a lot of untapped potential, mainly as a result of poor damage tuning across its kit. While it has many interesting and unique attacks, most of them are too weak or situational to see much use. ICE aims to address these issues in the following ways:
- Damage output (when fully buffed) has been made competitive with other weapons. While it will likely still be on the weaker side when it comes to individual damage output, it now won't be lagging so horribly behind that it encourages Hunters to take other weapons entirely.
- Shockwaves and Echo Waves now are affected by affinity and can deal critical damage. They are also affected by Sharpness. These changes allow these attacks to properly scale along with the Hunter and stay relevant across all points in progression.
- Recital and Encore damage has been raised to allow these moves to play a larger role in fights. They should be a strong option that a Hunter can choose to fit in where possible when they have songs queued, instead of relying only on Echo Attack and Superpound for general damage.
- Echo Wave "Dragon" has been replaced with Element Echo Wave. Element Echo Waves deal damage based on the element type and damage of the equipped weapon. Some elemental Hunting Horns have had their notes changed to allow them to play Element Echo Waves.
- Impact and Element Echo Wave are now positioned as high damage options that Hunters can mix in with existing combos for extra damage. Single Echo Waves after a Recital can offer a decent boost in damage, while preparing 3 Echo Waves ahead of time can lead to staggering levels of damage during extra long damage opportunities.

The full details can be found below:
- Right Swing:
  - MV increased to 36 (up from 27).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Left Swing:
  - MV increased to 36 (up from 22).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Forward Smash (aka Forward Slam):
  - MV increased to 42 (up from 28).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Backwards Strike (aka Back Slam):
  - MV increased to 54 (up from 37).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Hilt Stab:
  - MV increased to 12 (up from 10).
  - Element and Status Modifiers decreased to 0.60x (down from 1.0x).
- Overhead Smash (aka Superpound):
  - MV increased to 16+50 (up from 14+39).
  - Element and Status Modifiers increased to 1.2x+1.2x (up from 1.0x+1.0x).
- Flourish:
  - MV increased to 16+32 (up from 15+22).
  - Element and Status Modifiers increased to 1.2x+1.2x (up from 1.0x+1.0x).
- Echo Attack (aka Echo Spin):
  - First Hit:
    - MV increased to 12 (up from 10).
    - Element and Status Modifiers decreased to 0.60x (down from 1.0x).
  - Spinning Hits:
    - MV decreased to 16 (down from 17).
- Recital:
  - MV increased to 32 (up from 29).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Encore:
  - MV increased to 40 (up from 35).
  - Element and Status Modifiers increased to 1.5x (up from 1.0x).
- Midair Recital:
  - MV increased to 40 (up from 35).
  - Element and Status Modifiers increased to 1.5x (up from 1.0x).
- Shockwave:
  - MV increased to 32 (up from 27).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
  - Now affected by affinity and can deal critical damage.
  - Now affected by sharpness damage modifiers.
- Impact Echo Wave:
  - MV changed to 40/100/160 (was 50/100/150).
  - Status Modifier increased to 1.2x/3.0x/4.8x (was 0x/0x/0x).
  - Now affected by affinity and can deal critical damage.
  - Now affected by sharpness damage modifiers.
- Element Echo Wave (previously Echo Wave "Dragon"):
  - MV changed to 30/75/120 (was 45/65/85).
  - Deals element damage based on the equipped weapon's element type and damage.
    - Base Dragon damage removed (was 60/120/180).
    - Base Elder Seal Buildup removed (was 15/30/55).
    - Element damage no longer scales with Attack stat.
    - Element Modifier increased to 4.0x/10.0x/16.0x (up from 1.0x/1.0x/1.0x).
    - > While the increase to element modifier looks significant, it is mainly compensating for the equally significant loss of Attack stat scaling.
  - Now affected by affinity and can deal critical damage.
  - Now affected by sharpness damage modifiers.
- Jumping Smash:
  - MV increased to 40 (up from 35).
  - Element and Status Modifiers increased to 1.2x (up from 1.0x).
- Clutch Claw Weapon Attack:
  - Element and Status Modifiers increased to 1.2x+1.2x (up from 1.0x+1.0x).
  - Second Hit: 
    - Partbreak Modifier increased to 1.65x (up from 1.0x). 
    - > This change compensates for the first hit having a Partbreak Modifier of 0.0x.

### ──────────【 Lance 】────────── ###

#### 【 General Changes 】 ####
Lance has a solid playstyle and was only lacking damage to compete with other weapons. As such, most attacks were simply increased in power to an appropriate level relative to other weapons. In addition, the Raw vs Element balance of its attack was adjusted to increase the variety of competitive weapon options.

- Mid Thrusts:
  - MV increased to 23/23/30 (up from 20/20/27).
  - Element and Status Modifiers increased to 0.8x/0.8x/0.9x (up from 0.7x/0.7x/0.7x).
- High Thrusts:
  - MV increased to 25/25/30 (up from 22/22/27).
  - Element and Status Modifiers increased to 0.8x/0.8x/0.9x (up from 0.7x/0.7x/0.7x).
- Wide Sweeps:
  - MV increased to 32/32/40 (up from 20/20/20).
  - Element and Status Modifiers increased to 1.0x/1.0x/1.2x (up from 0.7x/0.7x/0.7x).
  - Changed to have Mind's Eye effect.
- Counter Thrust:
  - Element and Status Modifiers increased to 1.1x (up from 0.7x).
- Power Guard:
	- When held for 1.2s, increases Counter Thrust physical damage by 1.3x and grants the effects of Guard Up (previously only granted the effects of Guard Up).
	- > This change is intended to give an alternative incentive for committing to a Power Guard, rather than solely for Guard Up. While this option is powerful, it is limited by OFG procs, stamina usage, increased chip damage, and high animation commitment.
- Leaping Thrust:
  - MV increased to 11 (up from 8).
  - Element and Status Modifiers increased to 0.4x (up from 0.3x).
- Dash Attack:
	- Startup time significantly reduced when used after Mid Thrust III, High Thrust III, or Wide Sweep III.
	- No longer cancels when running into walls or terrain.
  - MV increased to 12 (up from 11).
  - Element and Status Modifiers increased to 0.5x (up from 0.2x).
- Finishing Thrust:
  - MV increased to 60 (up from 50).
  - Element and Status Modifiers increased to 1.6x (up from 0.8x).
- Finishing Twin Thrust:
  - MV increased to 30+60 (up from 25+50).
  - Element and Status Modifiers increased to 0.8x+1.6x (up from 0.7x+0.8x). 
- Reverse Attack:
  - MV increased to 60 (up from 50).
  - Element and Status Modifiers increased to 1.6x (up from 0.8x).
- Jumping Thrust / Advancing Jump Thrust:
  - MV increased to 32 (up from 30).
  - Element and Status Modifiers increased to 1.0x (up from 0.7x).
- Dash Attack (Midair):
  - MV increased to 30 (up from 25).
  - Element and Status Modifiers increased to 1.0x (up from 0.7x).
- Shield Attack:
  - MV increased to 24 (up from 14).
  - Partbreak Modifier increased to 1.2x (up from 1.0x).
  - Stun buildup increased to 45 (up from 27).
  - Exhaust buildup increased to 30 (up from 27).
- Counter Claw (Second Hit):
  - MV increased to 24 (up from 16).
  - Stun buildup increased to 35 (up from 30).
  - Exhaust buildup decreased to 30 (down from 33).
- Mounting Finishing Thrust: 
  - MV increased to 40+20+80 (up from 40+10+20).
	- Element Modifiers changed to 1.0x+0.5x+2.0x (was 1.0x+1.0x+1.0x).
	- Status Modifiers changed to 1.0x+0.5x+2.0x (was 0.7x+0.7x+0.7x).
	- Third Hit:
		- Partbreak Modifier increased to 1.75x (up from 1.0x).
		- > Compensates for first two hits having a Partbreak Mod of 0.0x.
- Clutch Claw Weapon Attack:
  - Second Hit: 
    - Partbreak Modifier increased to 1.75x (up from 1.0x).
    - > This change compensates for the first hit having a Partbreak Modifier of 0.0x.


### ──────────【 Gunlance 】────────── ###

#### 【 XanSamHi's Omnilance Rework 】 ####
Gunlance has received a significant rework with four major changes:
- Normal, Long, and Wide shelling types have been unified into a single new "Omni" type, which combines the strengths of all three. Hunters can now actively choose between all shelling attacks in combat, rather than being locked into spamming only a single optimal shelling attack for an entire hunt.
- The shelling level system has been reworked to span 9 shelling levels, to help smooth out weapon progression as High Rank effectively only had 1 shelling level (Lv4) compared to Low and Master Rank having 3 each. Now High Rank will also have 3 levels. This rework also includes better shelling level balance across all Gunlances, so there are more competitive weapon options available at all levels of progression.
- Wyrmstake Blast has been removed due to various problems with the implementation and the mostly negative impacts it had on Gunlance gameplay. Since Gunlance received Wyrmstake Blast instead of Master Rank's 1.5x Fixed Damage multiplier, we have re-enabled this damage multiplier and rebalanced Shelling attacks around it.
- As a replacement for Wyrmstake Blast, the (previously decorative) shield has gained a core role in Gunlance gameplay in the form of a guardpoint on Quick Reload. This guardpoint enables a more aggressive playstyle and allows Hunters to keep pressuring monsters if timed correctly. For small or medium knockbacks, Hunters can follow-up with any options already available after a Quick Reload, including comboing into an Overhead Smash and Full Burst.

The details for these changes are below:
- Base shell capacity for Omni type is 4. Capacity Boost skill can increase this by 2 (was 1).
- All Shelling Attacks:
  - Now affected by Master Rank's 1.5x Fixed Damage modifier.
- Shelling (Uncharged):
  - Based on "Wide" Shelling.
  - Consumes 2 shells per use (up from 1), allowing for up to 3 shots per magazine (was 3 shots).
  - Fixed Damage changed to 16/19/22/28/32/36/44/50/56 (was 18/26/32/40/48/54/61).
  - Fire Damage changed to 8/9/10/11/12/13/14/15/16 (was 6/8/10/11/12/13/14).
- Charged Shelling:
  - Based on "Long" Charged Shelling.
  - Consumes 2 shells per use (up from 1), allowing for up to 3 shots per magazine (was 4 shots).
  - Fixed Damage changed to 32/38/44/56/64/72/88/100/112 (was approximately 28/42/59/68/87/101/118).
  - Fire Damage changed to 8/9/10/11/12/13/14/15/16 (was 9/11/14/16/18/20/22).
  - Partbreak Modifier decreased to 1.4x (down from 1.5x).
  - Charge time now affected by Artillery, instead of Focus.
    - Artillery Lv3 grants a charge time reduction of 45% (equivalent to Focus Lv2).
    - Artillery Lv5 grants a charge time reduction of 60% (equivalent to Focus Lv3).
- Burst Fire:
  - Based on "Normal" Burst Fire.
  - Fixed Damage changed to 16/19/22/28/32/36/44/50/56 per shell (was 8/12/16/20/24/28/32).
  - Fire Damage changed to 8/9/10/11/12/13/14/15/16 (was 4/5/6/7/8/9/10).
  - Fixed Damage multiplier decreased to 0.7x (down from 0.9x).
- Wyvern's Fire:
  - Based on "Wide" Wyvern's Fire.
  - Changed to a single larger hit (was 3 small hits).
  - Fixed Damage changed to 128/152/176/224/256/288/352/400/448 (was 66/75/79/86/103/112/120 per hit).
  - Fire Damage changed to 64/72/80/88/96/104/112/120/128 (was 15/18/21/24/27/30/33).
  - Cooldown Rate is no longer affected by Artillery skill.
- Wyrmstake Cannon:
  - Thrust:
    - Partbreak Modifier decreased to 0.0x+0.0x (down from 1.0x+1.0x).
    - > Avoids situations where flinch/trips on the first two hits cause the rest of the attack to miss.
  - Repeated Hits:
    - MV changed to 8/9/10/12/13/14/16/17/18 (was 6/8/11/14/17/20/23).
    - Element and Status Modifiers increased to 0.3x (up from 0.0x).
    - Partbreak Modifier increased to 1.0x (up from 0.3x).
  - Final Explosion:
    - Fixed Damage changed to 16/19/22/28/32/36/44/50/56 (was 31/36/41/46/55/61/67).
    - Fire Damage changed 8/9/10/11/12/13/14/15/16 (was 12/15/18/21/24/27/30).
- Wyrmstake Blast:
  - This attack has been removed for now.
- Quick Reload:
  - Can be performed instead of Full Reload in most situations (except after a Backstep / Backhop).
  - New Guardpoint added:
    - Guardpoint starts after a 0.1s delay, and lasts 0.40s.
    - Interrupts reloading if used against a medium or high knockback attack.
  - Now usable while at full ammo.
- Full Reload:
  - Can only be performed after a after a Backstep / Backhop.
  - Now usable while at full ammo.
- Step Dodges / Hops:
  - Can now combo into Shelling attack, Charged Shelling attack, or Quick Reload using their respective usual keybinds.
  - Forward Step: Distance increased to 3.0m (up from 2.3m).
  - Left Sidestep: Distance changed to 2.8m (was 2.6m), to match Right Sidestep distance.

#### 【 Sharpness Changes 】 ####
The following changes were made to reduce the significant sharpness consumption of Gunlance that generally makes Razor Sharp mandatory on every build. We believe this is an excessive restriction on build variety, given the high quantity of skills that Gunlance Hunters want to use already.
- Shelling (Uncharged): Sharpness consumption decreased to 1 per use (down from 2).
- Charged Shelling: Sharpness consumption decreased to 1 per use (down from 2).
- Full Burst: Sharpness consumption decreased to 1 per shell (down from 2).
- Wyvernfire: Sharpness consumption decreased to 5 per use (down from 10).
- Razor Sharp / True Razor Sharp:
  - Sharpness cost reduction for shelling attacks decreased to 0 (down from 1).
  - Sharpness cost negation chance for shelling attacks increased to 50%/70% (up from 10%/20%).
  - > The above changes result in RS/TRS changing from an average cost reduction of 55%/60% to 50%/70% on Shelling, Charged Shelling, and Full Bursts. Its value is now more consistent with other melee weapons.

### ──────────【 Switch Axe 】────────── ###

#### 【 Sword Gauge Rework 】 ####
Sword Gauge generation has been changed to be focused around the active use of Axe Mode attacks, instead of either waiting for Sword Gauge or only using Morph Attacks. In addition, gauge generation and consumption has been increased to reduce resource pooling and encourage more proactive switching between modes to manage Sword Gauge and Amp Charge.

- Sword Mode minimum gauge requirement decreased to 0% (down from 30%).
- Reload: Gauge generation decreased to 5% (down from 30%).
- Axe Mode Passive Gauge Regen (4% per 1.5s):
  - Changed to only activate while sheathed.
  - There is now an additional 10s delay after most combat actions before the regen effect will activate.
- Axe Mode Attacks:
  - Gauge generation increased to 8% per hit (up from 0%).
  - Gauge generation benefits from Focus skill.
    - > In vanilla, Focus was in an unfortunate position where it did affect Amp generation, but not enough to warrant the use of the skill. Focus now has a significantly more noticeable effect that will reduce the required number of hits to reach amped sword mode, increasing its overall viability without making it a necessity for general SA gameplay. It can now be a good option when facing Monsters where Axe Mode is less useful. 
- Axe Mode Morph Attack: 
  - Gauge generation decreased to 10% (down from 15%). 
  - > This attack still counts as an Axe Mode Attack, so it will generate 18% gauge in total when successfully hitting a monster, which is a buff overall.
- Sword Mode Attacks:
  - Gauge consumption increased.
  - See General Changes section below for details on individual attacks.

#### 【 Morph vs Morph Slash 】 ####
Morph Slashes have been enabled where previously only a normal Morph was possible, to provide Hunters more ways to fluidly weave between Sword and Axe Mode attacks.

- "Axe: Morph Slash":
  - Normal Version:
    - Can now be performed from Left/Right Sidesteps or backwards roll using "Weapon Special Attack" (R2 on PS, RT on XB).
  - Advancing Version:
    - Can now be performed from Left/Right Sidesteps or backwards roll using "Weapon Special Attack" with a forwards directional input (R2 + Forward on PS, RT + Forward on XB).
    - Can now be performed from neutral stance using "Weapon Special Attack" with a forwards directional input (R2 + Forward on PS, RT + Forward on XB).
- "Sword: Morph Slash":
  - Normal Version:
    - Can now be performed from all step dodges using "Weapon Special Attack" (R2 on PS, RT on XB).
  - Advancing Version:
    - Can now be performed from all step dodges using "Weapon Special Attack" with a forwards directional input (R2 + Forward on PS, RT + Forward on XB).
    - Can now be performed from neutral stance using "Weapon Special Attack" with a forwards directional input (R2 + Forward on PS, RT + Forward on XB).

#### 【 Phial Type Rebalancing 】 ####
Too much of Switch Axe's damage output was locked behind phial bonuses (especially Power Phial), thus limiting the number of competitive weapons to choose from. To correct this, phial effects have been rebalanced, with much of their original power now baked directly into Sword Mode attacks instead.

- Power Phial: Total Attack multiplier decreased to 1.07x (down from 1.17x).
- Power Element Phial: Total Element multiplier decreased to 1.21x (down from 1.45x).
- Exhaust Phial: Bonus Stun buildup for Sword Mode increased to 10 (up from 5).
- Sword Mode attacks for all Phial types:
  - MVs increased. See General Changes section for details on individual attacks.
  - Element Modifiers of most attacks increased to 1.20x (up from 1.00x).

#### 【 Zero Sum Discharge Rework 】 ####
Iceborne introduced a convenient new way to access ZSD through the Clutch Claw. However, this could be combined with Health Regen Augment and certain mantles (such as Rocksteady or Temporal) to create a problematic gameplay loop of repeatedly using Claw ZSD to trivialize even the hardest content in the game. To prevent this, the following changes were made to bring back World's version of ZSD as a situational punishing tool or finisher.

- Amp State is now consumed upon completing a Zero Sum Discharge.
- Zero Sum Discharge:
  - Initial Thrust:
    - MV increased to 20 (up from 18).
    - Element Modifier increased to 1.2x (up from 1.0x).
  - Repeating Phial Bursts:
    - MV increased to 14 (up from 13).
    - Element modifier increased to 1.38x (up from 0.5x).
  - Finisher:
    - MV increased to 188 (up from 119).
    - Element Modifier increased to 1.2x (up from 1.0x).
    - The chance of hitting the wrong Monster part has been greatly decreased, especially for fast-moving Monsters.

#### 【 General Changes 】 ####
- When performed from neutral stance, "Axe: Side Slash" replaced with "Axe: Overhead Slash".
- "Axe: Side Slash":
  - MV increased to 30 (up from 23).
- "Axe: Forward Slash":
  - MV increased to 23 (up from 19).
- "Axe: Rising Slash":
  - MV increased to 32 (up from 31).
- "Axe: Overhead Slash":
  - MV increased to 50 (up from 45).
- "Axe: Fade Slash":
  - MV increased to 37 (up from 34).
- "Axe: Wild Swing":
  - Bonus multiplier after 2 swings decreased to 1.1 (down from 1.3).
- "Axe: Sweep Morph":
  - MV decreased to 16+58+29 (down from 20+70+35).
- "Sword: Phial Burst":
  - MV increased to 10 (up from 9).
  - Delay significantly decreased to mitigate situations of missing the intended attack location on fast moving monsters.
  - Now also applies to Axe mode attacks.
- "Sword: Overhead Slash":
  - MV increased to 38 (up from 29).
  - Element Modifier increased to 1.2x (up from 1.0x).
  - Sword Gauge consumption increased to 11% (up from 7%).
- "Sword: Right Rising Slash":
  - MV increased to 30 (up from 21).
  - Element Modifier increased to 1.2x (up from 1.0x).
  - Sword Gauge consumption increased to 11% (up from 7%).
- "Sword: Left Rising Slash":
  - MV increased to 25 (up from 18).
  - Element Modifier increased to 1.2x (up from 1.0x).
  - Sword Gauge consumption increased to 11% (up from 7%).
- "Sword: Double Slash":
  - MV increased to 31+34 (up from 22+26).
  - Element Modifier increased to 1.2x (up from 1.0x).
  - Sword Gauge consumption increased to 17% (up from 10%).
- "Sword: Bridging Slash": 
  - MV increased to 25 (up from 15).
  - Element Modifier increased to 1.2x (up from 1.0x).
- "Sword: Heavenward Flurry":
  - MV increased to 30+41 (up from 24+35).
  - Element Modifier increased to 1.2x (up from 1.0x).
  - Sword Gauge consumption increased to 17% (up from 10%).
- "Sword: Jumping Slash":
  - MV increased to 39 (up from 35).
  - Element Modifier increased to 1.2x (up from 1.0x).
- "Sword: Jumping Rising Slash":
  - MV increased to 39 (up from 35).
  - Element Modifier increased to 1.2x (up from 1.0x).    
- "Element Discharge":
  - Thrust:
    - MV increased to 11 (up from 10).
    - Element Modifier increased to 0.24x (up from 0.20x).
  - Ticks:
    - MV increased to 9 (up from 8).
    - Element Modifier increased to 0.6x (up from 0.5x).
  - Finisher:    
    - MV increased to 94 (up from 85).
    - Element Modifier increased to 1.2x (up from 1.0x).
- Element Discharge (Mounted):
  - Thrust:
    - MV increased to 22 (up from 20).
    - Element Modifier increased to 1.2x (up from 1.0x).
  - Ticks:
    - MV increased to 6 (up from 5).
    - Element Modifier increased to 0.6x (up from 0.5x).
  - Finisher:
    - MV increased to 110 (up from 100).
    - Element Modifier increased to 1.2x (up from 1.0x).
- Amp State:
  - Amp State versions of the above Sword Mode attacks now share the same MV and gauge consumption.
  - Amp State duration increased to 80 seconds (up from 45).
- Power Axe:
  - Duration increased to 80 seconds (up from 45).
- "Sword: Step" (AKA Hop):
  - Can now be cancelled into a roll (was previously only possible for forward steps).
  - Reduced recovery animation.
  - Forward Step: Distance increased to 2.45m (up from 1.8m).
  - Left Sidestep: Distance increased to 2.5m (up from 1.7m).
  - Right Sidestep: Distance increased to 2.5m (up from 2.0m).
  - Backstep: Distance increased to 2.35m (up from 1.7m).
  - > Sword Steps in vanilla have a significant issue with spacing, as the limited distance combined with the low i-frames make it difficult or in many cases impossible to i-frame or out distance attacks without investing in evasion skills. These changes aim to improve the overall survivability and mobility of Sword Mode. Also fixes an odd discrepancy where Left Sidestep is significantly shorter than Right Sidestep.
- Special Claw Shot:
  - MV increased to 8+61 (up from 7+55).
  - Element Modifier increased to 1.2x (up from 1.0x).
- Clutch Claw Weapon Attack:
  - Second Hit: 
    - Partbreak Modifier increased to 1.4x (up from 1.0x). 
    - > This change compensates for the first hit having a Partbreak Modifier of 0.0x.
    
### ──────────【 Charge Blade 】────────── ###

#### 【 General Changes 】 ####
- Amped Sword Mode:
  - While active, the remaining duration increases by 1 second per successful sword attack.
- Charge Phials:
  - Can now combo into Element Discharge II (R + Circle).
- Condensed Elemental Slash:
  - MV increased to 75 (up from 60).
- Amped Element Discharge:
  - MV increased to 90 (up from 82).
- Super Amped Element Discharge:
  - Timing of phial usage synchronized with the timing of the Phial explosions, to avoid losing phials when interrupted.
  - First Hit (Back Swing): 
    - Partbreak Modifier decreased to 0.0x (down from 1.00x). 
    - > Avoids situations where flinch/trips on first hit cause the rest of the attack to miss.
- Savage Axe Slash:
  - MV increased to 65 (up from 30).
  - Backwards movement greatly reduced to avoid forcing the Hunter out of range.
- Impact Phials:
  - > The following changes are targeted at increasing the effectiveness of Impact Phial CBs.
  - All Types: 
    - Scaling penalty for Bonus Attack removed (was 50%).
    - > This reverts a nerf from base MHW. This should result in roughly a 5% buff to phial damage in endgame gear.
  - Normal Type:
    - MV increased to 5 (up from 4).
    - Stun buildup and Exhaust buildup increased by 100% when triggered from guardpoints.
  - AED Type:
    - MV increased to 15 (up from 9).
    - Partbreak Modifier increased to 2.0x (up from 1.0x).
  - SAED Type:
    - MV increased to 30 (up from 25).
  - Sword Type:
    - MV increased to 4 (up from 2).
- Power Axe Ticks (Normal and AED/SAED Types):
  - > The following changes are targeted at increasing the effectiveness of Power Axe on Impact Phial CBs, without affecting the performance of PEP CBs.
  - Normal:
    - Element Modifier increased to 0.4x (up from 0.2x).
    - Status Modifier increased to 0.4x (up from 0.3x).
    - PEP's bonus Element Modifier decreased to +0.4x (down from +0.6x) to cancel out buff.
  - AED/SAED:
    - Element Modifier increased to 0.4x (up from 0.2x).
    - Status Modifier increased to 0.4x (up from 0.3x).
    - PEP's bonus Element Modifier decreased to +0.8x (down from +1.0x) to cancel out buff.

### ──────────【 Insect Glaive 】────────── ###

#### [ Equipment ] ####
- Default Kinsect Boost type on Safi IGs changed to Element Boost (was Speed Boost).

#### 【 Kinsect Changes 】 ####
- Extract Durations:
  - Red: Increased to 150 seconds (up from 90).
  - White: Increased to 180 seconds (up from 120).
  - Orange: Increased to 210 seconds (up from 150).
  - Triple: Increased to 150 seconds (up from 90).
- Extract "Low Duration" Warning Threshold:
  - Increased to 15 seconds (up from 10).
- Kinsect Charge Durations have been normalized for field ammo types (150s) and Monster ammo types (300s).
  - Pierce Pod: Unchanged (was 300).
  - Stone: Increased to 150 (was 75).
  - Redpit: Increased to 150 (was 90).
  - Scatternut: Increased to 150 (was 120).
  - Crystalburst: Increased to 150 (was 120).
  - Thorn Pod: Unchanged (was 300).
  - Puddle Pod: Unchanged (was 150).
  - Dragon Pod: Increased to 300 (was 150).
  - Bomb Pod: Unchanged (was 300).
  - Brightmoss: Increased to 150 (was 120).
  
#### 【 General Changes 】 ####
The changes below mainly are intended to bring up underpowered moves to increase the variety of useful attacks available to Hunters, or are intended to address Raw vs Element damage balance to increase the variety of competitive weapon options.
- Wide Sweep:
  - MV increased to 26 (up from 22).
  - Element and Status Modifiers increased to 1.0x (up from 0.8x).
- Strong Wide Sweep:
  - MV increased to 22+26 (up from 18+22).
  - Element and Status Modifiers increased to 0.8x+1.0x (up from 0.8x+0.8x).
- Strong Thrust:
  - Element and Status Modifiers decreased to 0.7x+0.7x (down from 0.8x+0.8x).
- Strong Double Slash:
  - MV increased to 22+20+32 (up from 16+14+28).
  - Element and Status Modifiers  increased to 0.8x+0.8x+1.0x (up from 0.6x+0.8x+0.8x).
  - Second Hit Only:
    - Damage type changed to Blunt (was Sever).
    - Stun Buildup increased to 20 (up from 0).
    - Exhaust Buildup increased to 10 (up from 0).
- Tornado Slash:
  - Element and Status Modifiers increased to 0.8x+1.0x (up from 0.8x+0.8x).
- Bridging Slash:
  - MV increased to 13 (up from 10).
  - Element and Status Modifiers increased to 1.0x (up from 0.7x+0.7x)
- Kinsect (Mark Target):
  - MV increased to 12 (up from 5).
  - Stun buildup increased to 12 (up from 5).
- Kinsect Dust Explosions:
  - Blast Type: Fixed Damage increased to 15 (up from 10).
  - Poison Type: Fixed Damage increased to 12 (up from 5).
  - Para Type: Fixed Damage increased to 10 (up from 3).
- Clutch Claw Weapon Attack:
  - Finisher Hit:
    - Partbreak Modifier increased to 2.0x (up from 1.0x).
    - > This change compensates for the first four hits having a Partbreak Modifier of 0.0x.
    
#### 【 Bug Fixes 】 ####
- Attempting to use "Kinsect: Harvest Extract" after dodging sideways to the left, will now correctly send the kinsect out. Previously, this would result in using "Thrust" or "Strong Thrust".

### ──────────【 Gunner Changes 】────────── ###

- Gunner defense penalty has been reworked, to help prevent issues in late endgame content where Monster damage has been increased to levels that make it very difficult for gunners to not get one-shot.
  - Gunners will mostly take the same damage as they did before this change (i.e. much higher than blademasters).
  - Gunners will only notice a change in late endgame content where one-shot attacks become more common.
  - When taking these one-shot attacks, Gunners can still take lethal damage without adequate defenses, but the reduced damage may help gunners survive some of the weaker one-shot attacks.
  - > For context: Gunners normally receive a 30% reduction in base defense (before flat additive bonuses), which in late endgame content roughly equates to 40% increased damage taken from all sources. The element resistance bonus for Gunners does not significantly help put a dent into this penalty because elemental Monster attacks consist of mostly raw damage (usually 66% to 75% raw).
- Spare Shot / True Spare Shot:
  - Proc algorithm changed to be deterministic, instead of random.
  - Procs once every 5 shots for Spare Shot and every 3.33 shots for True Spare Shot.

### ──────────【 Bow 】────────── ###

#### 【 General Changes 】 ####
- "Sticky Aim" behavior has been removed.
  - > In vanilla, when using certain moves like Power Shots and Charge Step, the aiming reticle will "stick" to where the Hunter was aiming. This can often lead to missed shots when the reticle stays in mid-air where the monster has already moved away from. While this behavior can be canceled by momentarily aiming at something else, this can be annoying and tiresome for many Hunters.
- Dragon Piercer:
  - MV increased to 21/25/30/36 (up from 19/20/23/24).
  - Element Modifier increased to 0.3x/0.3x/0.45x/0.45x (up from 0.15x/0.2x/0.3x/0.3x).
  - Status Modifier increased to 0.3x/0.35x/0.4x/0.5x (up from 0.15x/0.2x/0.3x/0.3x).
  - Fixed Damage Removed (was 1/1/2/2).
  - Damage and Buildup decreased to 4% after 18th hit (was 20%).
- Clutch Claw Weapon Attack:
  - Final Hit: 
    - Partbreak Modifier increased to 1.875x (up from 1.0x). 
    - > This change compensates for the first two hits having a Partbreak Modifier of 0.0x.
    
#### 【 Bug Fixes 】 ####
- Power Shot arrow spread patterns:
  - Fixed a bug causing Power Shot Lv2 and Lv3 arrow patterns to be right-biased.
  - Patterns are now correctly symmetrical.
  - Reference: <https://twitter.com/AsteriskAmpers1/status/1235082146743803904>
- Charge Step direction and aiming:
  - Fixed a bug causing Charge Step to move in directions different than the player's directional input, when performed while the Hunter is starting to aim.

  
### ──────────【 Bowgun Ammos 】────────── ###
Many of the following changes are intended to address ammo-to-ammo balance, with the intent of giving Hunters more competitive options when choosing an ammo for a particular matchup.
- Rapid Fire:
  - All individual projectiles within a shot must now be manually aimed.
  - > Previously, all additional projectiles would travel the same trajectory based on the first projectile.
- Normal Ammo: MV increased to 12/22/36 (up from 10/20/34).
- Pierce Ammo:
  - MV increased to 8/8/10 (up from 7/7/9).
  - Delay between ticks decreased to 0.050s/0.033s/0.033s (down from 0.067s/0.050s/0.050s).
  - Projectile speed increased to 30/30/25 m/s (up from 25/25/20).
  - Super Crit Start Distance decreased by 70%.
  - Damage reduced to 0% after the 6th hit (down from 20% after the 9th hit).
  - > These changes are intended to allow Pierce to perform more consistently across different sized monsters, making it a good option in more matchups.
- Spread Ammo:
  - Spread patterns changed to be grouped around a central point (was horizontal line).
- Sticky Ammo:
  - Damage Type changed to Blunt (was "HZV independent").
  - MV increased to 20/29/40 (up from 12/17/24).
  - Stun buildup decreased to 21/35/70 (down from 30/50/100).
  - > These changes are intended to address the fact that Sticky was too consistent across most Monsters.
- Slicing Ammo:
  - MV increased to 9 (up from 6).
  - Partbreak modifier increased to 1.4x (up from 1.0x).
- Wyvern Ammo:
  - MV increased to 100+10 (up from 70+19).
  - Fire damage decreased to 0+0 (was 40+20).
  - > Wyvern ammo wasn't particularly strong, but the fire damage further limited its usefulness.
- Elemental Ammo:
  - Physical and Element Damage decreased by 20.0%
  - Damage reduced to 0% after the 6th hit (down from 20% after the 9th hit).
- Dragon Ammo:
  - MV increased to 4 (up from 2).
  - Dragon damage increased to 36 (up from 18).
  - Damage reduced to 0% after the 6th hit (down from 20% after the 9th hit).
  - > The damage increase compensates for damage lost from reduction in number of hits.
- Cluster Ammo:
  - MV increased to 19/22/28 (up from 17/20/26).
  - Fire damage decreased to 0/0/0 (down from 5/8/10).
  - The nerf to ammo capacity from IB has been reverted.
  - > These changes allow the ammo to perform consistently across monsters.

### ──────────【 Heavy Bowgun 】────────── ###


#### 【 Melee Attack Hyper Armor 】 ####
- Bowgun melee attack has been given 15 frames of hyperarmor (from frame 7 to 22).
-> HBG wanted a way of dealing with calculated trades at short range but without completely invalidating its roll.
- The animation was shortened by 25%.
- If a hit connects it gets additional 15 frames of Hyperarmor and the animation finishes 10% faster.
-> This rewards using the move when in melee range, vs using it freely at farther ranges.
- It now consumes 25 points of stamina (affected by stamina cost reducers).
- If one attempts to perform the move without stamina it will perform the traditional melee attack (without hyperarmor or accelerated animation).
- The traditional melee attack now slows stamina regeneration to 10% during it's animation.
-> This limits the spamming potential of the move

#### 【 Numerical Changes 】 ####
- Close Range Up Mod: Maximum active range increased to 8m (up from 6m).
- Long Range Up Mod: Minimum active range decreased to 10m (down from 16m).
- Special Scope Mod:
  - Removed scoped FOV and blur effects.
  - Normal Ammo damage multiplier decreased to 1.20x (down from 1.30x).
  - Pierce Ammo damage multiplier decreased to 1.15x (down from 1.30x).
  - Spread Ammo damage multiplier removed (down from 1.30x).
- Shield Mod:
  - Increased Guard Strength now caps at Shield mods x2 (equivalent to CB & GS Guard Strength at 14/39/40+).
  - > Shield mods x3 now grants no bonus over Shield mods x2. Shield mods x4 still grants reduced chip damage.
- Clutch Claw Weapon Attack:
  - Backward impulse decreased to 300 (down from 800).
  - > With this change, Hunters will be dropped closer to the monster.
- Wyvernsnipe:
  - Main projectile: MV increased to 30 (up from 20).
  - Explosions: MV increased to 50/75/110 (up from 38/49/81).
- Wyvernsnipe Type 2:
  - Distance Match:
    - MV increased 165 (up from 98).
    - Stun buildup increased to 100 (up from 15).
  - HZV Match:
    - MV increased to 235 (up from 147).
    - Stun buildup increased to 200 (up from 40).
  - Perfect Match:
    - MV increased to 350 (up from 243).
    - Stun buildup increased to 300 (up from 60).

### ──────────【 Light Bowgun 】────────── ###

- Light Bowgun mod slot limit increased to 5 (up from 4).
- Close Range Up Mod: Maximum active range increased to 8m (up from 6m).
- Long Range Up Mod: Minimum active range decreased to 10m (down from 16m).
- Evade Reload Mod:
  - Ammo reloaded per mod increased to 3 (up from 1).
  - Now changes "Neutral unsheathed roll" to "evade reload slide", if equipped.
- Clutch Claw Weapon Attack:
  - Backward impulse decreased to 250 (down from 700).
  - > With this change, Hunters will be dropped closer to the monster.
- Wyvernblast:
  - Charge consumption decreased to 1/2/3 (down from 1/2/4).
- Wyvernblast Type 2:
  - MV increased to 43/75/87/130 (up from 26/49/73/110). 
  - Fire damage decreased to 0/0/0/0 (down from 3/5/6/7).

