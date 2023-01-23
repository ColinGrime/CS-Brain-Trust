# CS Brain Trust: Minecraft SMP
Instead of you guys being forced to go through a bunch of links, here is a gist of everything you need to know.

## General Stuff:
- IP: **csbraintrust.com**
- Seed: **-5550122220331967276**
- Difficulty: **Hard**
- Max render distance: **24**
- Whitelisted: **Scill**, **EGG_R0LL**, **Reesedaman**, **AeroZombie03**, **Decrypted_**
- Gamerules:
  - **doInsomnia**: false (phantoms will not spawn)
  - **playersSleepingPercentage**: 0 (only 1 player is required to sleep)

## [Aurelium Skills](https://www.spigotmc.org/resources/aurelium-skills-advanced-skills-stats-abilities-and-more.81069/)

This plugin adds RPG-like skills to the game.  
Doing so will increase your stats and allow you to unlock abilities / mana abilities.

<details><summary>Skills</summary><p>

- **Farming**: Harvest crops to earn Farming XP
- **Foraging**:  Cut trees to earn Foraging XP
- **Mining**: Mine stone and ores to earn Mining XP  
- **Fishing**: Catch fish to earn Fishing XP  
- **Excavation**: Dig with a shovel to earn Excavation XP  
- **Archery**: Shoot mobs and players with a bow to earn Archery XP
- **Defense**: Take damage from entities to earn Defense XP
- **Fighting**: Fight mobs with melee weapons to earn Fighting XP
- **Endurance**: Walk and run to earn Endurance XP
- **Agility**: Jump and take fall damage to earn Agility XP
- **Alchemy**: Brew potions to earn Alchemy XP
- **Enchanting**: Enchant items and books to earn Enchanting XP
- **Sorcery**: Use mana abilities to earn Sorcery XP
- **Healing**: Drink and splash potions to earn Healing XP
- **Forging**: Combine and apply books in an anvil to earn Forging XP

</p></details>

<details><summary>Abilities (there are apparently 70, here are the examples they provide)</summary><p>

- **Bountiful Harvest**: Chance to get double drops from crops
- **Shredder**: Chance to deal triple durability damage with axes
- **Pick Master**: Deal more damage with pickaxes
- **Treasure Hunter**: Chance to get rare loot from fishing (customizable loot tables)
- **Piercing**: Chance for arrows to pierce through mobs
- **No Debuff**: Chance to negative a harmful potion effect from being applied
- **Bleed**: Chance to make the enemy bleed, dealing damage every few seconds
- **Meal Steal**: Chance to steal 1 hunger point when attacking a player
- **Thunder Fall**: When sneaking during a fall, you have a chance to deal a percentage of the fall damage expected to mobs in a 3 block radius
- **Alchemist**: Potions you brew have a longer duration
- **Life Steal**: Heal a percentage of the max HP of hostile mobs and players you kill

</p></details>

<details><summary>Mana Abilities (require mana to activate)</summary><p>

- **Replenish**: Replants crops automatically for a certain duration. Right-click with a hoe and break a crop to activate. Works with wheat, carrots, potatoes, nether wart, and beetroot.
- **Treecapitator**: Breaks entire trees instantly for a certain duration. Right-click with an axe and break a log to activate. Works best with oak, birch, and spruce trees (One block wide). The algorithm is not final and will be improved later on to work perfectly with all tree types.
- **Speed Mine**: Gives Haste 10 for a certain duration. Right-click with a pickaxe and break stone or an ore to activate.
- **Sharp Hook**: Deal damage to a hooked entity when left-clicking with a fishing rod'
- **Terraform**: Break blocks instantly in a 4 block radius in the same layer when digging. You must use a shovel and extra blocks broken must be the same type and in a single connected vein. Right click shovel and dig block to activate.
- **Charged Shot**: Arrows you shoot will deal more damage based on how far the bow was pulled back, consuming mana in the process. Does more damage per mana consumed. Left click a bow to toggle charged shot mode.
- **Absorption**: Incoming damage will decrease mana by 2x Minecraft damage instead of your health. Mana will not regenerate while Absorption is active. Left click shield and take damage to activate.
- **Lightning Blade**: Increases attack speed by _% for _ seconds. Right click sword and attack mob to activate.

</p></details>

## [McMMO Horses](https://www.spigotmc.org/resources/mcmmohorses.46301/)

This plugins adds new abilities to horses.  
You can claim, name, summon, and level up abilities for your horse.

<details><summary>Skills</summary><p>

- **Swiftness**: Increases the speed of your horse
- **Agility**: Increases the change of dodging attacks
- **Vitality**: Increases the health of your horse
- **Wrath**: Temporarily disables damage and increases speed

</p></details>

<details><summary>Getting Started</summary><p>

- To get started, claim a horse by taming it and giving it a saddle. Then, while riding it, use **/h claim**.
- To level up your horse stats, ride for long distances for a Swiftness increase. To increase it's health, wrath, or agility, let your horse take damage.
- To heal your horse, give them sugar, apples, carrots, golden apples, or golden carrots.
- To view your horses stats, use **/h stats**.
- To protect your horse from damage when you are not riding it, use **/h protect**.
- When you disconnect from the server, your horse will despawn to protect it. When you join the server again, use **/h summon** to summon your horse again.
- If you wish to rename your horse, use **/h set name [name]**.

</p></details>

## [Levelled Mobs](https://www.spigotmc.org/resources/levelledmobs.74304/)

This plugin applies a level to each mob *(I don't think it effects mobs spawned with spawners)*.  
It will be on **average** difficulty in the beginning, but we can change this later on if we get too strong.

## [Mine Tweaks](https://www.spigotmc.org/resources/minetweaks.96757/)

This plugin adds numerous quality of life changes.

<details><summary>Notable Additions (you can read more about it if you want)</summary><p>

- Most crops can be **grown with bonemeal** (cactus, sugarcane, netherwart).
- You can **harvest crops by right clicking them**, reverting them back to stage 1.
- **Trowel tool**: Places a random block from your hotbar (so you can put like all cobblestone if you need to use a lot of it).
- **Middle click** a crafting table in your inventory to **open it**. You no longer have to place 1 million crafting tables (*ahem* Reese).
- Water bucket + infinity book = **infinite water bucket**.
- You can **color code** items with anvils.
- You can **dye the name of named mobs**.
- Withers spawn **skeleton minions** when it reaches half health.
- Prevents any non-player entity from **trampling farmland**.
- Wandering traders aren't **completely useless**.
- **Announces the location** of wandering trader spawns to all players.
- And more (check out the page about if you're interested).
  
</p></details>

## [Xp Bottler](https://www.spigotmc.org/resources/xp-bottler-1-15-2-1-19-3.75989/)

This plugin allows you to convert your XP into regular XP bottles.  
To do so, all you have to do is right click an **emerald block** with an **empty bottle**.  

Conversion rate: **9 XP** = **1 XP bottle** (little worse than what the XP bottle should give you)

## [Mineable Spawners](https://www.spigotmc.org/resources/mineablespawners-1-8-1-18-silkspawners-alternative.59921/)

This plugin allows you to mine and pickup spawners.  
To do so, all you need is a **diamond silk touch pickaxe**.

Chance to drop: **20%**

## [AFK+](https://www.spigotmc.org/resources/afk.35065/)

This plugin allows you to become AFK.  
While AFK, it will indicate it in the tab and your nametag.  

You cannot be moved / hurt by mobs while AFK, but players can still hurt you.

## [Dynmap](https://www.spigotmc.org/resources/dynmap%C2%AE.274/)

This plugin allows you to view the world in a 'Google Maps' style.  
Link: **http://csbraintrust.com:8123/**

---

### Don't like something? Want to add something? DM me.
