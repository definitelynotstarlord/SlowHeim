![Valheim Modpack Landscape](https://raw.githubusercontent.com/definitelynotstarlord/SlowHeim/refs/heads/main/config/SlowHeimBase-Complete_806x460.png)

**Should be compatible and working with the April 1st 0.220.5 update**
Do NOT update ANY mods except for the main modpack!

### SlowHeim, Take It Easy!
Welcome to SlowHeim! A modpack focused on a vanilla+ experience that offers a much slower pace and a lot more of a challenge than normal, especially when it comes to surviving, exploring, and the environment. 

I made this modpack for my young children and I for a family server playthrough. I uploaded this to Thunderstore to make it easier to manage updates for us. Before playing this modpack, please keep in mind it was made solely for my family's vision of what Valheim should be, with mods.

- NoMap playthrough! The map has been moved to the Cartography table and you must plan ahead
- Riverheim creates a much better world to explore -- do NOT ever upgrade Riverheim!
- New raids (thanks Majestic!)
- Portals have been disabled but are replaced with craftable Waystones which act very similar, but add a cooldown based on your travel distance
- Access to magic much earlier through Therzie's Wizardry
- Southsil armor adds alternatives to Therzie's armory additions - find a style you like!
- There are buffs and debuffs for each season
- You will not be able to repair any items until you get to bronze
- All creatures can now be 0-3 stars, with bosses being 2-5 stars
- Plants and trees will grow more slowly than normal, but expect the best growth in Spring and Summer
- Smelting ore and all conversions now take 5x longer
- A wandering trader will sometimes arrive, and he now buys a few more hunting and fishing related items and sells VES upgrade scrolls
- ValheimEnchantingSystem to further upgrade your weapons and armor
- Building pieces like Corewood and more vanilla pieces, etc. have been added
- A couple mods that attempt to help with network performance if you are playing with friends
- Lord of the Rings music overhaul (disable the LotR music mod AND the CustomAudio mod if you do not like this or want to reduce load times)

All of my changes are documented below.

## Performance Warning!
This modpack has 80+ mods. My goal was to add mods that I thought were necessary and that performed optimally as well. Still, it is a lot of mods and it does take a hit on performance.
- Game startup time for me is ~2m. Your screen may be white and even warn you that Valheim is not responding -- just click to "wait" for the program to respond, it will load!
- Remove/disable CustomAudio, Lord of the Rings Music to reduce load times
- Remove/disable RenderLimits for another boost to FPS
- Increased CPU utilization, 30%+ on a 12th gen i7-12700F
- 18-20GB memory utilization with under 5000 total instances
- 50% utilization on a 4070ti
- See the troubleshooting section below for additional performance enchancing tips

## World Modifiers
I would suggest you make the following changes on your world:
- Player-based raids
- Everything else default

## Detailed Changes - A Must Read!
These are the changes I have made to the game. I've added 80+ mods and configured quite a few of them as I see fit. Here you will find those changes and learn more details about this modpack.

- [KG's ValheimEnchantmentSystem](https://thunderstore.io/c/valheim/p/KGvalheim/Valheim_Enchantment_System/)
  - Disabled the VES crafting system
  - Item ugprade scrolls can now only be found or purchased from Haldor
  - Since crafting is no longer possible, chance to upgrade has been slightly increased
- [Mods by Therzie](https://thunderstore.io/c/valheim/p/Therzie/)
  - Therzie adds in so much content and has rounded out game completion
  - If you are unsure of how the Wizadry or Armor work, you need to read his Wiki, which can be found [here](https://docs.google.com/spreadsheets/d/1kxXS34lWO-MWGktSqcOaRE_4tiLZHjN8sV1hxv2GsEU/edit?pli=1&gid=0#gid=0)
  - Furthermore, I would suggest joining his Discord if you are stumped or have questions about the new magic and armory additions
- [Smoothbrain's CLLC](https://thunderstore.io/c/valheim/p/Smoothbrain/CreatureLevelAndLootControl/)
  - Creatures can be 0-3 stars, roughly 50% chance for a star. Bosses can be 3-6 stars, weighted heavily at 3 and 4 stars
    - All bosses and creatures have a chance to spawn with special affixes and prefixes
- [Smoothbrain's Skills](https://thunderstore.io/c/valheim/p/Smoothbrain/)
  - Farming: Increases yield and regrowth time as you level. You can ignore biome for planting at level 65, can plant more crops at once every 15 levels, and at level 40 you can see growth %
  - Foraging: Increase yield and regrowth time as you level
  - Lumberjacking: Increasing damage to trees and yield as you level 
  - Mining: Starting at level 35 you have a very small chance of an ore exploding in one hit, this chance incrases as you level 
  - PackHorse: Increases carry weight as you level
- [Smoothbrain's TimedItemDestruction](https://thunderstore.io/c/valheim/p/Smoothbrain/TimedItemDestruction/)
  - Items on the ground are removed in one hour, excluding player bases
- [Smoothbrain's Backpack](https://thunderstore.io/c/valheim/p/Smoothbrain/Backpacks/)
  - A backpack can be crafted which reduces the weight of items placed inside by 35% that starts with 3 inventory slots. This backpack can be upgraded in each biome until a maximum of 20 slots are achieved
- [Smoothbain's PassivePowers](https://thunderstore.io/c/valheim/p/Smoothbrain/PassivePowers/)
  - The Forsaken Powers are now passive and you may have two at once. Use power one or two by holding `F` and tapping `1` or `2`. The active state lasts 60 seconds and has a 10 minute cooldown
- [Smoothbrain's Resurrection](https://thunderstore.io/c/valheim/p/Smoothbrain/Resurrection/)
  - Default settings - one SurtlingCore to resurrect your pal
- [Shudnal's ExtraSlots](https://thunderstore.io/c/valheim/p/shudnal/ExtraSlots/)
  - Two additional inventory rows, and slots for armor, food, arrows, and utilities
- [Shudnal's Waystones](https://thunderstore.io/c/valheim/p/shudnal/Waystones/)
  - You can craft a Waystone like you would a portal. Activate it, sit in front, click E, and look around to find other Waystones or your home
  - You can lower wait time by using neck, deer, troll, and boss trophies on a Waystone
- [Shudnal's Seasons](https://thunderstore.io/c/valheim/p/shudnal/Seasons/):
  - The Valheim "year" is 40 in-game days
  - You will freeze to death during winterstorms and during winter evenings, even inside. You will need a fire (torch works)
  - Wood burns fastest in the fall and winter but faster in spring and summer as well
  - Day length is doubled, nights in the winter are longer than the days
  - Winter bloom is brutal -- if you don't like it, disable bloom
- [Mods by ZenDragon](https://thunderstore.io/c/valheim/p/ZenDragon/)
  - Workbenches no longer prevent creature spawning. This is now accomplished by fire only. Each fire source will have a radius in which it prevents spawning. Be careful, as the more fire sources you have, the higher the odds of triggering a raid
  - Assign an item to a sign to see nearby resources
    - Simply "use" your item on a sign. Then, hit "E" (Find) when looking at your sign and it will highlight the chest where the resources are
  - Cartography table will explore a full 1000m radius over the course of 10 in-game days
    - Even though you are playing "NoMap", having multiple cartography tables throughout the world will slowly build a full map
    - Take note breaking the table destroys map data. If you would like to move your table, you must do so by taking advantage of the ZenRedecorate mod - instructions at the bottom of this section
  - You cannot place pins on the map like normal. You must craft a Map Pin and attach it to a sign
  - Item stands now acts like chests
  - Beehives now act as chests
  - You will not consume as much stamina on paths, so make paths, lots of paths
  - You can pick up and replace furniture, without destroying it
    - Hold Left Control and Left-Click your furniture piece. Move it and Left-Click to place it
    - Especially useful on the Cartography table...
  - Terrain can only be slightly modified to encourage proper base fortification
  - Obliterator picks one random item on destruction and gives you 50% mats back
  - Health now regenerates when resting, and seated
  - On death you will keep two randomly equipped items
- [Mods by Blacks7ar](https://thunderstore.io/c/valheim/p/blacks7ar/)
  - You will get much more resources as your Hunting skill increases, 2x at level 100
  - Added in corewood, collectors (guck, tar, resin), new hip location for one handed weapons, and the Herbalist skill
    - Crafting costs lowered for the collectors and they hold 50 items instead of 10
  - New Herbalist skill with potions and tonics and new plants
- [Mods by Azumatt](https://thunderstore.io/c/valheim/p/Azumatt/)
  - You can only repair your items by crafting a RepairStation -- make sure to bring one with you! This also means no reparing until bronze!
  - All of your gold is stored in your "currency pocket"
  - You can add Resin and Tar to prevent weathering of your build pieces
- [FactoriaTeam's MakeTowerShieldsGreatAgain](https://thunderstore.io/c/valheim/p/FactoriaTeam/Make_Tower_Shields_Great_Again/)
  - All vanilla shields and then I added in all of Therzie's tower shields
  - Tower shields are legitimate now and will far exceed a buckler's worth if you're truly just trying to block
- [OdinPlus' Mods](https://thunderstore.io/c/valheim/p/OdinPlus/)
  - OdinHorse (Raelaziel)
    - Chance to find and tame a horse. Invaluable on this new map with hardcore exploration difficulty
  - Campsite (Raelaziel)
    - You can craft a Small Campfire, Sleeping Bag, Small Tent, and Big Tent. The Sleeping Bag and Tents require Campfire Resources. These recipes are changed from the original mod -- you will want to make sure you have plenty of Campfire Resources with you while traveling
  - TrainingPlace (Raelaziel, KG, and Gravebear)
    - Adds the ability to train your skills up, but all "vitamins" have been disabled
    - I feel like this offers massive potential for abuse, but 5% experience on death is a pretty big deal afterall!
  - Traveling Haldor (Gravebear)
    - Traveling Haldor has a 50% chance to spawn every 5 days, after you have defeated Eikthyr. Once spawned, you can trade with him for 10 minutes before he leaves
  - Basements
    - Since we cannot modify terrain anymore, this mod will allow you build a pretty expensive basement to help store your goods
- [Mods by VentureValheim](https://thunderstore.io/c/valheim/p/VentureValheim/Sea_Of_Noodles/)
  - All locations are reset every 20 in-game days unless you have built something inside
  - More Serpents
  - MiningCaves
- [Kam1goroshi's BetterFishing](https://thunderstore.io/c/valheim/p/Kam1goroshi/BetterFishing/)
  - Fishing progresses much faster and starting at level 30 you will boost your chance of better quality fish
  - Maybe a great way to make extra money from Haldor
- [Advize's PlantEverything](https://thunderstore.io/c/valheim/p/Advize/PlantEverything/)
  - Crops, mushrooms, and trees now grow much more slowly. The longest item growth will be 8 hours with the shortest being 3 hours. Biome enforcement is on until your farming gets to level 65
- [ThisModpack]
  - You can now build a Shield Generator with tin, copper, and surtling cores to help protect you from storms
  - Haldor now buys fish, neck meat, deer meat, serpent meat, and more! Hunting and fishing could be lucrative
  - Stonecutter no longer requires iron and can be crafted with resources from the Black Forest

## Troubleshooting
- You can modify these mods in-game by pressing `F1` or by opening the config files themselves locally. I would recommend [vscode](https://code.visualstudio.com/download) if you're wanting to edit config files locally, but Notepad++ and even Notepad do work
- This modpack was tested primarily on a 12th Gen i7-12700F, 4070ti, 48GB memory, and a Kingston SNV2S1000G with max graphics setting, and it runs perfectly fine. My kids played on older i7/i5s with an RTX 2060 and 16/32GB of memory and slightly lower graphics settings, and not a single issue either 
- Memory consumption issues can be a thing
  - Disable CustomAudio and Lord of the Rings Music to lower memory usage 7-8GB. You must disable both
- Remove/disable RenderLimits for a small boost to FPS
- Poor performance
  - Though terraforming is restricted, excessive flattening can cause lag
  - Use `F2` to monitor your instances and stay as low as you can. Anything over 10,000 is definitely going to be a bad time
  - See the `Section 2: Optimize Boot Configuration for Better FPS` section at the [RobThePCGuy's Performance Mod Guide](https://github.com/RobThePCGuy/Performance-Mod-Guide-For-Valheim/blob/main/README.md). We see considerable boost in performance when using these options
- If you do not like the UI I put together, disable the "MinimalUI" mod. Alternatively, you can press "F7" at any time and use right-click to cycle through the various screens in which you can drag-and-drop how you'd like
- When installing on a server, make sure you're not adding the client-side mods. Use WinSCP to upload the mods via FTP

## Server Installation
- Disable SmoothSave on clients if you are uploading these mods to a server as SmoothSave needs to only be server-side
- Copy everything to your server except for these mods:
  - StartupAccelerator
  - ClearSkies
  - LocalizationCache
  - MinimalUI
  - CustomAudio
  - Lord of the Rings Music
  - BepInEx Configuration Manager
- Once the above mods have been removed, shut your server down and copy your entire BepInEx folder to the server
- Watch [Stoned Prophet's Complete Starter's Guide](https://www.youtube.com/watch?v=JEqIvO_uJMw) as an excellent resource for setting up your server!
 
## Contact
If you enjoy this modpack and want to provide any feedback or have questions, feel free to reach out!
- `config_this` on Discord
- [Filthy Casual Discord](https://discord.gg/yPcZKgtXJv), [CookieMilk](https://valheim.cookiemilk.se/index.html), and [ZenDragon](https://github.com/ZenDragonX/ZenMods_Valheim/wiki),
