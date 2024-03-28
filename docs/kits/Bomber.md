
# Bomber

***

#### ![bomber-icon](../assets/kits/bomber/bomber-icon.jpg)

# Overview
***
- **Introduced:** v1.7.0
- **Description:** A damage kit that places and detonates bombs.
- **Role:** Damage
- **How to Unlock:** Purchase for 500 Credits

<br />  

# Gear
***
- Chainmail Chestplate
- Chainmail Leggings
- Chainmail Boots
- Iron Sword
- 3 Bombs
- Detonator
- 7 Healing Potions

<br />  

# Active Abilities
***
## Bombs
Bombs are used to deal large area damage. Bombs can't be placed too close to others and only 3 can be placed at any one time. If there are 3 bombs set and another bomb is placed, then the oldest will be destroyed.

![Bombs](../assets/kits/bomber/Bomber%20-%20Bombs.gif)

## Detonator
Right click to detonate all of the player's bombs dealing damage to enemies and self. Bombs will ignore invulnerability frames. The player can also detonate bombs while respawning.

![Detonator 1](../assets/kits/bomber/Bomber%20-%20Detonate.gif)

Bombs destroy enemy builder bricks, enemy builder ladders, cobwebs and jumper translocators and damage engineer blocks.

![Detonator 2](../assets/kits/bomber/Bomber%20-%20Detonate%20Bricks.gif)

![Detonator 3](../assets/kits/bomber/Bomber%20-%20Detonate%20Engineer%20Blocks.gif)

Bombs will disable shields if the bomb hits a player that is blocking.

![Detonator 4](../assets/kits/bomber/Bomber%20-%20Detonate%20Shield.gif)

<br />  

# Achievements
***

| Achievement | Description | Reward |
| ----------- | ----------- | ------ |
| Aye, what just happened? | Blow up an enemy from far away. | 20 Credits |
| Couldn't ya see the bloody bombs! | Blow up a invisible enemy. | 20 Credits |
| The Destruction of Fort Knox! | Blow up enemy builder bricks as bomber! | 20 Credits |
| Ka-boooom! | Get a double bomb kill. | 30 Credits |
| Kablooie! | Get a triple bomb kill. | 50 Credits |
| And that's what ya get for touching that! | Get 1,000 bomb kills. | 250 Credits |

<br />  

# Kit Data
***

| Property | Value | Description |
|----------|-------|-------------|
| MAX_HEALING_POTIONS | 7 | Maximum number of healing potions the player can carry. |
| BOMBER_BOMB_PLACE_ICD | 5 | The internal cooldown, in ticks, for placing bombs. |
| BOMBER_BOMB_PLACE_MIN_DISTANCE | 3 | The minimum distance, in meters, for placing bomb near an already placed bomb. |
| BOMBER_BOMB_COUNT | 3 | The maximum number of placed and held bombs a player can have a once. |
| BOMBER_BOMB_DAMAGE | 6 | The damage that a single bomb does. |
| BOMBER_BOMB_SELF_DAMAGE_MULTIPLIER | 0.5 | The damage multiplier of bomb damage from the player's own bombs.|
| BOMBER_BOMB_RADIUS | 6 | The radius of the explosion effect. |
| BOMBER_BOMB_YIELD | 2.5 | The minecraft bomb yield value. (this isn't measured in meters/blocks) |
| BOMBER_BOMB_KNOCKBACK_MULTIPLIER | 0.75 | The multiplier of the knockback that is applied to entities after a bomb explosion. |
| BOMBER_BOMB_REGENERATION_TICKS | 160 | The interval, in ticks, for regenerating bombs. |
| BOMBER_BOMB_DISPENSER_NUM | 1 | The amount of bombs to receive from each engineer dispenser tick. |
| BOMBER_DETONATE_FUSE_TICKS | 30 | The duration, in ticks, it takes for bombs to explode. This is also sets the cooldown for the detonator ability. |
| BOMBER_SWORD_DAMAGE | 6 | The base damage of the sword. |
| BOMBER_SWORD_SPEED | 4 | The base speed of the sword. |
