![Valheim Modpack Landscape](https://raw.githubusercontent.com/definitelynotstarlord/SlowHeim/refs/heads/main/config/SlowHeimBase-Complete_806x460.png)

### SlowHeim, Take It Easy! 
Welcome to SlowHeim! A nomap/noportal modpack!

This modpack is now designed for the SlowHeim server and includes FastLink with server/password - though you do need to be whitelisted to play. Feel free to disable FastLink. If you'd like to play, message me on Discord. I have included all of my configuration files that exist on the server. The goal of this modpack is to greatly increase the size of the world while enhancing some of Valheim's survival aspects. This playthrough is meant to be very slow. It is still a work in progress and I'll be updating as we find things that need to be changed.

If you choose to play with this modpack, please always review my changelog before updating and always backup your changes as my updates will overwite them!

## Warning!
This modpack has 70+ mods. My goal was to add mods that I thought were necessary and that performed optimally as well. Still, it is a lot of mods and they do take a hit on performance.
- If you are modifying settings for any of the mods included in this modpack, you must backup your config files as my future updates will overwrite your changes. You will need to restore your files/changes post-update.
- I have used a combination of Expand World Size and Riverheim for worldgen. Terrain is drastically smoother, mountains being not quite as mountainy, and a 4.5x size map.
  - Take note that depending on your PC specs, the first time you start a world it may take 30-60 minutes to generate. I have a pretty nice PC and I average 32 minutes.
  - Also note that you will notice Valheim's "dimply" terrain a lot more, especially on shores and in the mountains. It is very striking in the mountain and on shores. Disable Tessellation in your graphics menu to correct this.
- Memory consumption is ~12-14GB, so unless you have over 16GB of memory, you may have a bad time. One of my kids only has 16GB of memory and can play just fine, but your mileage may vary.
- I think most people will find my changes to be a little too much for them and that they have made the game way too grindy. One may even call this "BoringHeim" or "GrindHeim" as opposed to SlowHeim lol.

## Modpack Overview
This is an overview of the changes I have implemented into the game. At the end of this modpage are all the tweaks I made to the mods that are installed.
- The map is much larger with much less reliance on sailing. You should be able to complete everything up to the Mistlands without having to sail, unless you're bringing loot back to base on a river or sailing along the shores.
- You won't be able to repair your weapons until you get to the bronze age and build a Repair Station. And yes, you will need to bring Repair Station materials with you so that you can repair your items while on long journeys.
- To get boss rewards such as keys, you will need to sacrifice the trophy. Want more stuff? Keep sacrificing trophies.
- You will find that days and nights are longer and there are seasons that last 10 days each. You will freeze to death regardless of the biome unless you're warm. Campfires will burn through wood a lot faster in the Fall and Winter. Smelting is a bit slower. Your crops are not going to grow in the winter and grow more slowly overall.
- You don't get a map. Or a compass. Or portals. What you do get is a cartography table that will slowly explore a 7,500m radius over 40 in-game days (an entire in-game year). You can craft parchment and record the discoveries from the table to it and whilt it is in your inventory, press "M" to view it. Since you cannot add pins directly to the map, you can instead craft a Pin and attach this to a sign.
- You can upgrade your weapons and armor with enchanting scrolls you find or purchase from Traveling Haldor.
- Speaking of Haldor, he now travels and he will buy more things from you. There is a roughly 30% chance every three days that he may show up and hang around for 20 minutes.Hint: fishing and hunting could be lucrative. He will also sell you ingots and wood/stone from the previous biome once you have defeated the boss. At a premium, of course.
- You will see a bit more 1-3 star creatures and with CLLC, they may be imbued with properties such as frost damage, extra armor, or regenerating health. Best to avoid 3 star regenerating trolls for a while! Bosses now spawn with 3-5 stars with an equal chance of 2, 3, and 4 stars. Bosses will be imbued with special properties and do extra damage per star.
- You will notice almost no QoL changes. For me, the QoL mods just remove some of the only "true" survival challenges in the game such as inventory management and adventure preparedness.

## Troubleshooting and Tips
- You can modify these mods in-game by pressing `F1` or by opening the config files themselves locally. I would recommend [vscode](https://code.visualstudio.com/download) if you're wanting to edit config files locally, but Notepad++ and even Notepad do work. Some changes are best made while the server is offline.
- This modpack was tested primarily on a 12th Gen i7-12700F, 4070ti, 48GB memory, and a Kingston SNV2S1000G with max graphics setting, and it runs perfectly fine. My kids play on older i7/i5s with an RTX 2060 and 16/32GB of memory and slightly lower graphics settings, and they have not experiened any issues.
- Memory allocation:
  - I noticed that even though I have 48GB of memory, I was still having issues. The problem is that many of the Valheim mod dlls are loaded into Standby memory. This usually isn't a problem, but I quickly realized I had 14-20GB in Standby and Valheim was throwing errors. I would recommend using RAMMap to clear Standby memory. A guide can be found [here](https://www.partitionwizard.com/partitionmagic/window-10-standby-memory.html).
- Remove/disable RenderLimits for a small boost to FPS.
- Poor performance
  - Though terraforming is restricted, excessive flattening can cause lag
  - Use `F2` to monitor your instances and stay as low as you can. Anything over 10,000 is definitely going to be a bad time
  - See the `Section 2: Optimize Boot Configuration for Better FPS` section at the [RobThePCGuy's Performance Mod Guide](https://github.com/RobThePCGuy/Performance-Mod-Guide-For-Valheim/blob/main/README.md). We see considerable boost in performance when using these options.
- If you're hosting for friends, here are a few mods I'd recommend:
  - For improved networking (if the included NetworkTweaks doesn't help, be sure to disable it before trying these recommended networking mods), combine [Network by Smoothbrain](https://thunderstore.io/c/valheim/p/Smoothbrain/Network/) and [ReturnToSender by ComfyMods](https://thunderstore.io/c/valheim/p/ComfyMods/ReturnToSender/)
  - [Groups by Smoothbrain](https://thunderstore.io/c/valheim/p/Smoothbrain/Groups/) is cool because you can see your teammates' health. That is all the value it really adds. 
  - [Server devcommands by JereKuusela](https://thunderstore.io/c/valheim/p/JereKuusela/Server_devcommands/) is a great mod to help you administer your server.
- When installing on a server, make sure you're not adding any "client-side only" mods. Use WinSCP to upload the mods via FTP while the server is shutdown.

## Server Installation
- Shutdown your server.
- Copy everything to your server except for these mods:
  - BepInEx Configuration Manager
  - Render Limits
  - CurrencyPocket
  - BiomeObserver
  - ReliableBlock
- I would highly suggest creating your world locally, and uploading to your server. I would suggest following [these instructions](https://www.g-portal.com/wiki/en/how-to-upload-your-own-world-on-your-valheim-server).
- Watch [Stoned Prophet's Complete Starter's Guide](https://www.youtube.com/watch?v=JEqIvO_uJMw) as an excellent resource for setting up your server!
- There are a lot of opinions on which server host to use. I have used GTX for many years without issue. They have a very responsive staff as well. It is a bit of a premium price but I found it to be well worth it.
  - When setting up your server, do be mindful of the memory consumption. I have not tested this specific modpack on a dedicated server yet, but I would assume you would need 8GB of memory at a minimum.
 
## Contact
If you enjoy this modpack and want to provide any feedback or have questions, feel free to reach out!
- `config_this` on Discord
- I hangout in the following Discords: [Filthy Casual Discord](https://discord.gg/yPcZKgtXJv), [CookieMilk](https://valheim.cookiemilk.se/index.html), and [ZenDragon](https://github.com/ZenDragonX/ZenMods_Valheim/wiki).

## Detailed Changes
These are the changes I have made to the game. I've added 70+ mods and configured quite a few of them as I see fit. Here you will find those changes and learn more granular details about this modpack.

- [WackysDatabase by WackyMole](https://thunderstore.io/c/valheim/p/WackyMole/WackysDatabase/)
- [Mods by JereKuusela](https://thunderstore.io/c/valheim/p/JereKuusela/)
  - ExpandWorldSize: 4.5x world size with stretched biomes. This makes the initial loading screen look goofy.
  - RenderLimits: Increased render distance and distant details. This does not impact my PC but it may yours, disable for a boost in performance, or optionally, reconfigure it. Just know future updates will reset your personal settings.
- [KG's ValheimEnchantmentSystem](https://thunderstore.io/c/valheim/p/KGvalheim/Valheim_Enchantment_System/)
  - Disabled the VES crafting system.
  - Item ugprade scrolls can now only be found or purchased from Haldor.
  - Since crafting is no longer possible, chance to upgrade has been slightly increased.
- [Mods by Therzie](https://thunderstore.io/c/valheim/p/Therzie/)
  - All mods except for his DeepNorth collection. These add the most startup time, unfortunately, they're big.
  - If you are unsure of how the Wizadry or Armory mods work, you need to read the wiki, which can be found [here](https://docs.google.com/spreadsheets/d/1kxXS34lWO-MWGktSqcOaRE_4tiLZHjN8sV1hxv2GsEU/edit?pli=1&gid=0#gid=0).
  - Furthermore, I would suggest joining his Discord if you are stumped or have questions about the new magic and armory additions.
- [Mods by Smoothbrain](https://thunderstore.io/c/valheim/p/Smoothbrain/)
  - CLLC:
    - Difficulty set to "Medium".
    - Creatures spawn with 0-3 stars.
    - Bosses spawn with 3-5 stars.
    - CombatOwner: Hopefully improves latency during combat by making the attacking player the "owner" of the combat.
    - ServerCharacters: Characters are now saved server-side.
  - Backpacks: Allows you to build an expensive backpack that provides 3 slots and 25% reduced weight for items stored inside. This can be leveled up a total of 4 times and provides 3, 6, 8, 12, and 16 additional storage slots.
  - PassivePowers: These are much different than both vanilla and this mod.
    - You will be able to have two passive powers at any given time, that give a small buff similar to the active ability.
    - After killing the boss for the third time, you can then use the active ability of the boss power.
    - The cooldown on active boss powers is 40 minutes, but the power lasts a full 2 minutes.
    - To activate Power 1 or 2, hold "F" and press "1" or "2".
  - ConversionSizeAndSpeed: Increased time for various things like charcoal, smelting, etc.
  - Foraging: As you level up, increased yield and regrowth times. 5% exp loss on death, like vanilla skills.
  - Mining: As you level up, increased damage and yield with a 1% chance of a mining explosion at level 50. 5% exp loss on death, like vanilla skills.
  - Lumberjacking: As you level up, increased damage and yield with a slight speed buff in the Black Forest. 5% exp loss on death, like vanilla skills.
  - Raching: As you level up, increased yield and faster taming times with a calming effect at level 30. 5% exp loss on death, like vanilla skills.
  - PackHorse: Increase your carrying capacity as you level up. 5% exp loss on death, like vanilla skills.
  - Resurrection: Resurrect your friends when they die, for 100 coins.
  - StartupAccelerator: Helps the game load faster.
  - SmoothSave: Removes the annoying stutter every time the game saves.
- [Mods by Shudnal](https://thunderstore.io/c/valheim/p/shudnal/)
  - ExtraSlots: Two additional inventory rows, and slots for armor, food, arrows, and utilities.
  - Seasons:
    - The Valheim "year" is 40 in-game days.
    - You will freeze to death during winterstorms and during winter evenings, even inside. You will need a fire (torch works).
    - Wood burns fastest in the fall and winter but faster in spring and summer as well.
    - Day length is doubled, nights in the winter are longer than the days.
    - Winter bloom is brutal -- if you don't like it, disable bloom in your game.
    - Plants grow faster in the Spring and Summer months. Honey production drastically reduces in the winter.
  - TradersExtended: Haldor now sells and buys a lot more stuff. 
    - You can make significant gold by hunting and fishing.
    - After defeating a boss, you can now buy the ingots from that biome from Haldor. 
    - Prices will fluctuate based on how much gold Haldor currently has.
- [Mods by ZenDragon](https://thunderstore.io/c/valheim/p/ZenDragon/)
  - ZenMap: Cartography table will explore a full 10000m radius over the course of 25 in-game days.
    - Even though you are playing "NoMap", having multiple cartography tables throughout the world will slowly build a full map.
    - Take note breaking the table destroys map data. If you would like to move your table, you must do so by taking advantage of the ZenRedecorate mod - instructions at the bottom of this section.
    - You can craft a piece of parchment at a level 3 workstation and record the cartography tabledata  to that individual map and access it while traveling.
    - You cannot place pins on the map like normal. You must craft a Map Pin and attach it to a sign.
  - ZenBeehive: Beehives now act as chests and can hold 12 honey.
  - ZenPath: You will consume 0 stamina on a paved path, and 50% less stamina on a dirt path.
  - ZenTerrain: Terrain can only be slightly modified to encourage proper base fortification.
  - BossStone: Boss Stones are player-based, meaning, if you are not there with the Eikthyr trophy is placed, you will not see it.
  - ZenBreeding: Only wild-caught animals can reproduce. Their offspring are sterile.
  - ZenCombat: 
    - No more wood arrows.
    - Slower movement when drawing a bow.
    - Parrying a ranged attack no longer stuns them.
    - Dismount is now LeftAlt.
  - ZenConstruction: 
    - Trees no longer offer support. 
    - You can no longer build at Bonemass.
    - You can build sligthler further away from a workbench now.
  - ZenDistributor: Auto store items from a cart into nearby chest, if those items exist already.
  - ZenHoverItem: Will display items in chest with their icons, remaining smelting time, etc.
  - ZenItemStands: Item stands now function like a chest.
  - ZenRedecorate: Hold LeftControl to enter move mode. You can move furniture and chests up to 35m away but you will be encumbered while doing so.
  - ZenWorldSettings: Tree removed and progression spawning disabled - no more fulings in the meadows for new players.
  - ZenRecycle: The obliterator will select one recipe item from the recycle item and return 50% of the cost.
  - ZenPlayer: You can sleep in a bed without owning it, 
    - Regenerate healt while sitting with comfort increasing regen,.
    - Food no longer loses potency over time.
    - You keep 3 random equipped items on death.
    - Improved riding skill reduces stamina drain.
    - Other ZenPlayer options reverted back to vanilla in regards to skills and skill loss.
- [Mods by Blacks7ar](https://thunderstore.io/c/valheim/p/blacks7ar/)
  - CookingAdditions: Adds new food. Salt can generate in Meadows, BlackForest, and Plains.
  - Hunting: Get progressive bonuses as you hunt more animals.
  - OneHandWeaponOnTheHip: Just adds your one handed weapons to your hip.
  - ResinCollector: Will collect 60 total resin, producing one every five minutes. Costs SurtlingCores, Copper, Leather, and Finewood.
  - GuckCollector: Will collect 60 total guck, producing one every two minutes. Costs SurtlingCores, Tin, Leather, and Finewood.
  - CrystalCollector: Will collect 60 total crystals, producing one every two minutes. Costs SurtlingCores, Iron, Stone, and ElderBark.
  - TarCollector: Will collect 60 total tar, producing one every two minutes. Costs SurtlingCores, Silver, Stone, and FineWood.
  - SapExtractor: Will collect 60 total sap, producing one every two minutes. Vanilla Recipe.
- [SouthsilArmor by Southsil](https://thunderstore.io/c/valheim/p/southsil/SouthsilArmor/)
  - Adds over 30 new armor sets, fairly well-balanced.
- [Loyal Spears Auto Pickup and Return to Owner by Goldenrevolver](https://thunderstore.io/c/valheim/p/Goldenrevolver/Loyal_Spears_Auto_Pickup_And_Return_To_Owner/)
  - Spears are no longer automatically picked up by your friends, and they return to you 6 seconds after hitting the ground.
- [Mods by CookieMilk](https://thunderstore.io/c/valheim/p/CookieMilk/)
  - Leash: Allows you to leash animals to a wood post. This is used only to help control OdinHorse.
  - YouGotMail: When playing with friends on such a big world, you can now build a mailbox (BlackForest materials) to send items to one another. One day wait time on sent mail.
- [NetworkTweaks by Searic](https://thunderstore.io/c/valheim/p/Searica/NetworkTweaks/)
  - Hopefully improved latency in multiplayer.
- [HoneyPlus by OhhLoz](https://thunderstore.io/c/valheim/p/OhhLoz/HoneyPlus/)
  - New foods and build items based around honey but tar/royal jelly recipes removed.
- [Mods by Azumatt](https://thunderstore.io/c/valheim/p/Azumatt/)
  - RepairStation: You can only repair your items by crafting a RepairStation, which requires Bronze.
  - BiomeObserver: 60s cooldown, always display when moving into a new biome.
  - CurrencyPocket: Coins are added to a new slot in your inventory that stay with the player.
  - WardIsLove: Recharged with GreyDwarfEyes, can be built with BlackForest materials.
  - FastLink: Preconfigured to connect to SlowHeim. If not playing on our server, ignore this or disable it.
- [FactoriaTeam's MakeTowerShieldsGreatAgain](https://thunderstore.io/c/valheim/p/FactoriaTeam/Make_Tower_Shields_Great_Again/)
  - All vanilla shields, including Therzie's, have been significantly buffed and compete with the buckler.
- [Chatter by ComfyMods](https://thunderstore.io/c/valheim/p/ComfyMods/Chatter/)
  - A more elegant chat window with some configuration settings.
- [Mods by OdinPlus](https://thunderstore.io/c/valheim/p/OdinPlus/)
  - OdinHorse:
    - Horses on spawn in the BlackForest during the night.
    - Horse speed and health has been slightly increased while decreasing it's stamina.
    - Armor from this mod has been removed.
    - This mod is kind of goofy. The horse AI is pretty bad and will run off. So, always have the horse follow you before riding or have it follow right when dismounting. Then place a single wood post in the ground and "leash it". Voila!
  - Campsite:
    - You can craft a Small Campfire, Sleeping Bag, Small Tent, and Big Tent. 
    - The Sleeping Bag and Tents require Campfire Resources. These recipes are changed from the original mod -- you will want to make sure you have plenty of Campfire Resources with you while traveling
  - Traveling Haldor (Gravebear)
    - Traveling Haldor has a 30% chance to spawn every 3 days, during the daytime. He will remain for 20 minutes and vanish. He can be a little wild!
  - OdinsFoodBarrels: Just cool barrels to store some items in.
- [Venture Location Reset by VentureValheim](https://thunderstore.io/c/valheim/p/VentureValheim/Venture_Location_Reset/)
  - All locations are reset every 25 in-game days unless you have built something inside.
- [Reely SpecTackleLure by Neobotics](https://thunderstore.io/c/valheim/p/Neobotics/Reely_SpecTackleLure/)
  - Upgraded fishing rods add to your fishing skill.
  - 5% chance to catch biome specific fish without using special bait.
  - Fish spawn near player structures.
  - Chance to spawn a serpent when ocean fishing.
- [Advize's PlantEverything](https://thunderstore.io/c/valheim/p/Advize/PlantEverything/)
  - Crops, mushrooms, and trees now grow much more slowly. Biome enforcement is on until your farming gets to level 65.
- [ThisModpack]
  - Stonecutter no longer requires iron and can be crafted with resources from the Black Forest.
