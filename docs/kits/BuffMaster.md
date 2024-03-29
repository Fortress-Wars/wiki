
# Buff Master

***

#### ![buff-master-icon](../assets/kits/buff_master/buff-master-icon.jpg)

# Overview
***
- **Introduced:** v1.7.0
- **Description:** A support kit that gives potion effects to teammates. Selectable buffs include Regeneration, Absorption, Speed, and Resistance.
- **Role:** Support
- **How to Unlock:** Purchase for 500 Credits

<br />  

# Gear
***
- Iron Chestplate
- Leather Leggings
- Iron Boots
- Wooden Sword
- Buff
- Select Buff
- {{ kits.buff_master.data.MAX_HEALING_POTIONS }} Healing Potions

<br />  

## Abilities
***
### Actives
<!-- tabs:start -->
#### **Buff**
## Buff
Right click to buff all allies in a certain radius (including self). The buff applied will be determined by the currently selected buff. The cooldown will increase the more allies that are buffed.

<!-- ![_image_1_](../assets/kits/buff_master/_image_1_.jpg_) -->

#### **Select Buff**
## Select Buff
Right click to cycle between buffs forwards. Left click to cycle between buffs backwards. Available effects are Regeneration, Absorption, Speed, and Resistance.

![Regeneration](../assets/kits/buff_master/buff-master-regeneration.jpg)

![Absorption](../assets/kits/buff_master/buff-master-absorption.jpg)

![Speed](../assets/kits/buff_master/buff-master-speed.jpg)

![Resistance](../assets/kits/buff_master/buff-master-resistance.jpg)

<!-- tabs:end -->
<br /> 

# Achievements
***

| Achievement | Description | Reward |
| ----------- | ----------- | ------ |
| Family Practice | Buff 4 teammates with one activation. | 20 Credits |
| Stronk Creeper | Buff a creeper with buff master. | 20 Credits |
| The True Buff Master | Buff 1,000 teammates. | 100 Credits |

<br />  

# Kit Data
***

| Property | Value | Description |
|----------|-------|-------------|
| MAX_HEALING_POTIONS | `{{ kits.buff_master.data.MAX_HEALING_POTIONS }}`  | Maximum number of healing potions the player can carry. |
| BUFF_MASTER_BUFF_BASE_COOLDOWN | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_BASE_COOLDOWN }}` | The base cooldown, in ticks, of the Buff ability. |
| BUFF_MASTER_BUFF_MAX_COOLDOWN | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_MAX_COOLDOWN }}` | The max cooldown, in ticks, of the Buff ability. |
| BUFF_MASTER_BUFF_PER_MOB_COOLDOWN | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_PER_MOB_COOLDOWN }}` | The cooldown per mob affected, in ticks, added to the base cooldown. |
| BUFF_MASTER_BUFF_PER_PLAYER_COOLDOWN | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_PER_PLAYER_COOLDOWN }}` | The cooldown per player affected, in ticks, added to the base cooldown. |
| BUFF_MASTER_BUFF_RADIUS | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_RADIUS }}` | The radius of the Buff ability. |
| BUFF_MASTER_BUFF_SWITCH_ICD | `{{ kits.buff_master.data.BUFF_MASTER_BUFF_SWITCH_ICD }}` | The cooldown, in ticks, for switching effects. |
| BUFF_MASTER_REGENERATION_DURATION | `{{ kits.buff_master.data.BUFF_MASTER_REGENERATION_DURATION }}` | The duration of the regeneration effect. |
| BUFF_MASTER_REGENERATION_LEVEL | `{{ kits.buff_master.data.BUFF_MASTER_REGENERATION_LEVEL }}` | The level of the regeneration effect. |
| BUFF_MASTER_ABSORPTION_DURATION | `{{ kits.buff_master.data.BUFF_MASTER_ABSORPTION_DURATION }}` | The duration of the absorption effect. |
| BUFF_MASTER_ABSORPTION_LEVEL | `{{ kits.buff_master.data.BUFF_MASTER_ABSORPTION_LEVEL }}` | The level of the absorption effect.  |
| BUFF_MASTER_SPEED_DURATION | `{{ kits.buff_master.data.BUFF_MASTER_SPEED_DURATION }}` | The duration of the speed effect. |
| BUFF_MASTER_SPEED_LEVEL | `{{ kits.buff_master.data.BUFF_MASTER_SPEED_LEVEL }}` | The level of the speed effect. |
| BUFF_MASTER_RESISTANCE_DURATION | `{{ kits.buff_master.data.BUFF_MASTER_RESISTANCE_DURATION }}` | The duration of the resistance effect. |
| BUFF_MASTER_RESISTANCE_LEVEL | `{{ kits.buff_master.data.BUFF_MASTER_RESISTANCE_LEVEL }}` | The level of the resistance effect. |
| BUFF_MASTER_SWORD_DAMAGE | `{{ kits.buff_master.data.BUFF_MASTER_SWORD_DAMAGE }}` | The base melee damage of the sword. |
| BUFF_MASTER_SWORD_SPEED | `{{ kits.buff_master.data.BUFF_MASTER_SWORD_SPEED }}` | The base melee speed of the sword. |
