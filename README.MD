# Dankers Skyblock Mod
<div align="center">
  <a target="_blank">
    <img alt="version" src="https://img.shields.io/github/v/release/Quantizr/DungeonRoomsMod?color=%239f00ff&style=for-the-badge" />
  </a>
  <a target="_blank">
    <img alt="mcversion" src="https://img.shields.io/badge/MC%20Version-1.8.9-blue?color=%239f00ff&style=for-the-badge" />
  </a>
</div>


### What it does:
QOL changes that enhances your Hypixel Skyblock experience. Created to add features I couldn't find in a mod, or if the mod was paid (which is against the [Mojang TOS](https://account.mojang.com/documents/commercial_guidelines)).

<details>
<summary>Incompatibilites</summary>

## Incompatibilities
- Old Animations <2.6.4 - Frequent crashes
- Old Animations 2.6.4
  - Pet colors does not color slots
  - Catacombs F7 terminal solvers do not color slots
  - Enchanting solvers do not color slots
- Old tab display
  - Many features rely on using the location found in the new tab display
</details>

<details>
<summary>Current Features</summary>

## Current Features
- Guild party desktop notifications
- Coordinate and angle display
- Golden T10/T6/T4 enchant display
- Disable Spirit Sceptre messages
- Disable Midas Staff messages
- Disable Implosion messages
- Disable heal messages
- Disable ability cooldown messages
- Disable out of mana messages
- Disable kill combo messages
- Slayer item tracker
- Ghosts item tracker  
- RNGesus drop alerts
- Click anywhere on-screen to open Maddox
- Maddox menu keybind
- Block starting other slayer quests
- Slayer slain alert
- Fishing, jerry fishing, fishing festival, spooky fishing, crystal hollows fishing, lava fishing, trophy fishing trackers
- Expertise kills in fishing rod lore
- Gemstones applied in item lore
- Catacombs trackers
- Dungeons puzzle solver (Riddle, trivia, blaze, creeper, water, tic tac toe, boulder, silverfish, ice walk)
- Dungeons timer (similar to LiveSplit)
- Misc. dungeon info
- Watcher ready message
- Catacombs F7 Stage 3 solvers (Starts with letter, select all colour, ignore arrows on sea lanterns)
- Find correct Livid (with graphic display of HP)
- Catacombs F6 and F7 Giant HP display
- Use custom music in supported locations
- Experimentation solvers (Ultrasequencer, Chronomatron, Superpairs)
- Hide tooltips in experiment addons
- Hide tooltips in Melody's Harp
- Pet background colors based on level
- Golem spawning alerts + 20 second timer
- Skill xp/hour tracker
- Show total skill xp instead of progress to next level
- Show time until century cakes run out
- Mythological event (Diana) tracker
- Low health alert in dungeons
- API commands
- Update checker
- Reparty command
- Auto accept reparty
- Highlight Slayer Bosses
- Highlight Arachne
- Highlight Skeleton Masters
- Show teammates in 30 block radius
- Hide pet candy in pet tooltip
- Highlighting completed commissions
- Custom name colors
- Crystal Hollows waypoints (with SkyblockExtras support)
- Ability cooldowns display
- Custom alerts based on chat
- Predicted dungeon score display
- Hide player armour
- Automatically join skyblock
- Fire pillar display
- Chat aliases
- Thunder/Lord Jawbus spawn alerts
- Show when minion was last collected
- Show amount of Magmafish if trophy fish are filleted
- Show estimated time until bazaar order is filled
- Show timer until Crimson Isle minibosses respawn
- Automatically announce Vanquishers in chat
- Kuudra notifications (stun/ballista/cloak)
- Powder/hour tracker
- Fix drill animation resetting
- Highlight filled bazaar orders
- Dungeon RNG meter info display
- Optimize mining route
</details>

<details>
<summary>Commands</summary>

## Commands
- /dhelp - Returns this message in-game.
- /dsm - Opens the GUI for Danker's Skyblock Mod.
- /loot <zombie/spider/wolf/enderman/blaze/vampire/fishing/catacombs/mythological/> [winter/festival/spooky/ch/lava/trophy/f(1-7)/mm/session] - Returns loot received from slayer quests or fishing stats. /loot fishing winter returns winter sea creatures instead.
- /display <zombie/spider/wolf/enderman/blaze/vampire/fishing/catacombs/mythological/ghosts/auto/off> [winter/festival/spooky/ch/lava/trophy/f(1-7)/mm/session] - Text display for trackers. /display fishing winter displays winter sea creatures instead. /display auto automatically displays the loot for the slayer quest you have active.
- /resetloot <zombie/spider/wolf/enderman/blaze/vampire/fishing/catacombs/mythological/confirm/cancel> -  - Resets loot for trackers. /resetloot confirm confirms the reset.
- /slayer [player] - Uses API to get slayer xp of a person. If no name is provided, it checks yours.
- /skill [player] - Uses API to get skill levels of a person. If no name is provided, it checks yours.
- /lobbyskills - Uses API to find the average skills of the lobby, as well the three players with the highest skill average.
- /guildof [player] - Uses API to get guild name and guild master of a person. If no name is provided, it checks yours.
- /petsof [player] - Uses API to get pets of a person. If no name is provided, it checks yours.
- /bank [player] - Uses API to get bank and purse coins of a person. If no name is provided, it checks yours.
- /armor [player] - Uses API to get armor of a person. If no name is provided, it checks yours.
- /dungeons [player] - Uses API to get dungeon levels of a person. If no name is provided, it checks yours.
- /weight [player] [lily/farming] - Uses API to get weight of a person. If no name is provided, it checks yours. Adding lily uses lily's weight. Adding farming uses Kaeso's farming weight.
- /importfishing - Imports your fishing stats from your latest profile to your fishing tracker using the API.
- /sbplayers - Uses API to find how many players are on each Skyblock island.
- /reparty - Disbands and reparties all members in the party
- /fairysouls - Check the fairysouls of a player
- /skilltracker <start/stop/reset> - Text display for skill xp/hour.
- /lobbybank - Uses API to find the average bank total of the lobby, as well the three players with the highest total money in the bank (and purse).
- /player [player] - Uses API to find skills, slayers, coins and weight of a player.
- /reloadconfig - Reloads Danker's Skyblock Mod config.
- /reloaddsmrepo - Reloads Danker's Skyblock Mod repository.
- /hotmof [player] - Uses API to find total powder and HotM tree of a person. If no name is provided, it checks yours.
- /trophyfish [player] - Uses API to find trophy fish stats of a person. If no name is provided, it checks yours.
- /stoplobby - Stops currently running /lobbyskills or /lobbybank command.
- /powdertracker <start/stop/reset> - Text display for powder/hour.
</details>

<details>
<summary>Keybinds</summary>

## Keybinds
- Open Maddox menu - M by default.
- Regular Ability - Numpad 4 by default.
- Start/Stop Skill Tracker - Numpad 5 by default.
- Create Waypoint - Numpad 6 by default.
- Start/Stop Powder Tracker - Numpad 8 by default.
- Disable Mouse Movement - None by default.
- Disable Moving Forwards/Back - None by default.
- Disable Moving Left/Right - None by default.
</details>

<details>
<summary>Warps</summary>

## Warps
Shortcut commands that save you the time of typing the whole warp command.
- /deep - Warps you to the Deep Caverns.
- /nether - Warps you to the Crimson Isle.
- /isle - Warps you to the Crimson Isle.
- /crimson - Warps you to the Crimson Isle.
- /mines - Warps you to the Dwarven Mines.
- /forge - Warps you to the Dwarven Forge.
- /crystals - Warps you to the Crystal Hollows.
- /gold - Warps you to the Gold Mine.
- /desert - Warps you to the Desert.
- /spider - Warps you to the Spiders Den.
- /barn - Warps you to the Barn.
- /end - Warps you to the End.
- /park - Warps you to the Park.
- /castle - Warps you to the Hub Castle.
- /da - Warps you to the Dark Auction.
- /crypt - Warps you to the Crypt in the Hub.
- /nest - Warps you to the top of the Spider's Den.
- /void - Warps you to the Void Sepulture in the End.
- /drag - Warps you to the Dragons Nest in the End.
- /jungle - Warps you to the Jungle.
- /howl - Warps you to the Howling Cave in the Park.
- /dun - Warps you to the Dungeon Hub.
</details>

<details>
<summary>Custom Music</summary>

## Custom Music
1. Place a music file with the given name in the `.minecraft/config/dsmmusic` folder:
  - Dungeon: `dungeon.wav`
  - Blood room: `bloodroom.wav`
  - Dungeon boss: `dungeonboss.wav`
  - Dungeon hub: `dungeonhub.wav`
  - F7 Phase 2 (Storm): `phasetwo.wav`
  - F7 Phase 3 (Goldor): `phasethree.wav`
  - F7 Phase 4 (Necron): `phasefour.wav`
  - F7 Phase 5 (Wither King): `phasefive.wav`
  - Hub: `hub.wav`
  - Private Island: `island.wav`
  - Farming Islands: `farmingislands.wav`
  - Garden: `garden.wav`
  - Gold Mine: `goldmine.wav`
  - Deep Caverns: `deepcaverns.wav`
  - Dwarven Mines: `dwarvenmines.wav`
  - Crystal Hollows: `crystalhollows.wav`
  - Spider's Den: `spidersden.wav`
  - Crimson Isle: `crimsonisle.wav`
  - Kuudra: `kuudra.wav`
  - The End: `end.wav`
  - The Park: `park.wav`
2. Either run `/dsmmusic reload` or restart your game.
3. Enable the custom music in `/dsm`.
4. (Optional) Change the volume of the music with `/dsmmusic volume`.

#### Shuffling
By adding numbers to the end of the file, you can have multiple music files for the same area. One of them will be randomly selected (the same song could play twice in a row). For example:
- dungeon.wav
- dungeon1.wav
- dungeon2.wav
- dungeon99.wav
</details>

<details>
<summary>Alert Regex</summary>

## Alert Regex
To replace alert text with a captured group, add `$$x$$` to the alert text, with `x` being the number of the capture group. `$$0$$` will always be replaced with the entire trigger message.

For example, with the following alert

Regex: `From (.*) (.*): (.*)`  
Alert Text: `$$2$$ says $$3$$`  
Trigger Message: `From [ADMIN] Plancke: Nice autogg`  

the following alert text would appear

`Plancke says Nice autogg`.
</details>

### Installation

Download the newest Release and use it like every other forge mod.

### How to install a forge mod
- [Download the latest forge version](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.8.9.html "Download Forge")
- Run it to install forge  

- Open minecraft launcher and check if forge's profile is there, if not then you can create it ![image](https://user-images.githubusercontent.com/74936369/111808098-b8d7bf00-88e4-11eb-8a2d-60e93b1406a5.png)
- **Windows**: Press windows+r and type %appdata%/.minecraft/
- **Linux**: .minecraft is located in your home folder. ~/.minecraft
- **Mac**: do ⌘ (Command) + Space type "~/Library/Application Support/minecraft/
- Create a folder called "mods" if it isnt there already. then put the mods you download inside that folder and start minecraft.
                   
### Legal Disclaimer

This was made for educational purposes only, nobody which directly involved in this project is responsible for any damages caused.
**You are responsible for your actions.**
