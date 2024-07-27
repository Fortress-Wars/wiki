_Release Date: TBD_

# v2.0.0
- Health Bars
- NEW_FEATURE_2
- NEW_FEATURE_3
- Kit Changes
- Technical Changes
- Other Changes
- Bug Fixes

### Health Bars
Health bars show appear above ally player models. They show the player's Kit, Name, Health Bar, Numberic Health Value, and number of potions. Absorption and other status effects will also be reflected in the health bar. Enemies only see the player's name and nothing else!

### NEW_FEATURE_2

### NEW_FEATURE_3

### Kit Changes

Aquaman
- Added new death message for trident melee kills in water
- Melee trident kills now count towards the trident kills stat
- Base trident melee damage reduced from **7** to **4**
- Base trident throw damage reduced from **6** to **5**
- Water synergy damage bonus now also applies to melee trident attacks

Bomber
- Increased bomber knockback multiplier from **1.25** to **0.75**
- Bombs now consider line of sight when damaging enemies.

Brute
- Berserk passive now stacks. Each time the health drops to or below **10.0**, **1** stack will be gained (max **2** stacks) the speed level is determined by the number of berserk stacks
- Axe damage increased from **5.3** to **6**
- Axe swirl ability now considers line of sight when damaging enemies.

Buff Master
- Speed effect duration increased from **160** ticks to **320** ticks.
- Max cooldown for buff ability is now **300** ticks.

Builder
- Increased bricks and ladders final blow and assist reward counts.

Crusher
- Anvil ability now considers line of sight when damaging enemies.
- Getting hit by an anvil will stun targets for **60** ticks.

Demolitionist
- Demolition Radius is explodes all blocks in the radius instead of using Minecraft's tnt block logic.
- Bombs now consider line of sight when damaging enemies.

Engineer
- Added sentry fire sound
- Updated repair sound
- Pickup block metal refund is now based on the the percentage of current hp.
- Metal reward for a final blow and assist ("Metal Scrapper") are now **50** metal (was **75** and **25** respectively).
- Damage to engineer blocks (from abilities) now scale off of the **base** damage they would do to an enemy.
- Dispenser refreshes cooldowns by **20%** per dispense.
- Sentry now shoots from the center of the block. This means it can shoot an enemy from any direction.
- Dispenser no longer dispenses mana potions for Kit Priest and Kit Aquarius.

Fish
- Tropical Fish now heals only after hitting a target with it.
- Fishplosion and Fish Bow now summon tropical fish.
- OP fish now keeps the fish ability.
- Fish throw is now faster in OP fish mode.

Hitman:
- Bow now has infinity, but the max tags a hitman can have at once is still 6.
- Replaced chainmail leggings with black leather leggings.
- Replaced chainmail boots with black leather boots.
- Bow damage is now set to **5**.
- Decreased weakness effect duration from **200** ticks to **150** ticks.
- Decreased glowing effect duration from **400** ticks to **300** ticks.
- Decreased darkness effect duration from **400** ticks to **300** ticks.
- Harming effect damage is now set to **4**.
- Harming effect ignores no damage ticks.

Illusionist
- Divination Star damage bonus multiplier now only triggers when the owner of the Divination Star is the source of the damage.
- If the player attacks an enemy to uncloak from fake death, they will also hack them for **60** ticks.

Jumper
- Added ability to destroy the translocator manually with **left click**.
- Cooldown for scenario above is **80** ticks.
- Reduced cooldown of translocator after picking it up off the ground from **300** ticks to **40** ticks.
- Life duration of translocator increased from **6000** ticks to **24000** ticks.

Kangaroo
- Stomp ability now considers line of sight when damaging enemies.
- Increased stomp cooldown from **180** ticks to **210** ticks.
- Decreased stomp impact radius from **5** meters to **3** meters.

Knight
- Removed Pull ability
- New Fortify Ability: Increases shield strength, refreshes shield durability, and converts all damage types that would normally break or ignore the shield to damage the shield.
- Royal guard is now effective for all allies and only triggers when fortify is active and when the player is blocking.
- Damage Deflect from the shield is only active during the fortify duration.

Mathematician:
- Changed wooden sword to stone sword.
- Changed how math worksheets are distributed; The player now holds a max of **20** worksheets that regenerate **1** every **15** ticks. Worksheets can be dispensed by dispensers and rewarded for eliminations. Allies and enemies can hold a maximum of **15** worksheets. For every problem answered by the mathematician, one worksheet will be removed from all affected players.
- Increased the duration that allies and enemies hold practice problems from **600** ticks to **12000** ticks.
- Decreased cooldown for generating math problems from **600** ticks to **100** ticks.
- A random buff will now also be given after getting an elimination.

Medic
- Healing rate decreased from **5** ticks to **2** ticks.
- Healing Stone Capacity resource renamed to Electrolytes and is now displayed on the player's action bar.
- Medic's potions are now visually different than normal healing potions.

Mercy
- Mercy staff no longer casts a fishing line, instead it is now particle based.
- Players can target themselves by sneaking.
- Staff beam will now disconnects if out of line of sight for too long.
- Removed left-click to attach beam.

Miner
- Decreased Miner's Fervor ability cooldown from **400** ticks to **200** ticks

Soldier
- Grenade radius increased from **2** to **3** 
- Grenades now consider line of sight when damaging enemies.

## Technical Changes
- Reimplemented all kits
- Players can now be hacked. Hacked players will not be able to use their abilities (active and passive) and any active abilities will be terminated.
- Players can now be stunned. Stunned players will not be able to use their abilities.
- Added an interface to refresh ability cooldowns.
- Normalized shields taking damage based on the incoming damage.
- Added Line of sight checks for explosions and other AOE abilities.
- Refactor healing and mana potions. (Auto-pot no triggers in the same game tick (faster))
- Absorption hearts now count towards "Damage Dealt" stats and "Damage Taken" stats.

## Other Changes
-

## Bug Fixes
- Aquaman trident now returns to the item slot the user is on if it's empty.
- Bomber no longer blocks redstone events.
- Fixed issue where if an engineer died, the sentry would do more damage.
- Fixed engineer teleporter not able to be used if on soul sand and other partially lowered blocks moved.