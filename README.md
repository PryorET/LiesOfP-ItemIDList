![LiesOFPLogo](https://www.liesofp.com/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F150395%2F1737984357-image-2-2.png&w=256&q=100)
## 🧭 Item ID Compendium
_Every relic has a name. Every name has a code. Welcome to the vault._

**This repository contains a categorized list of Item IDs used in-game. Click on the titles below to skip to a category:**
> 🔑[Key Items](#key-items) 🔁[Exchange Materials](#exchange-materials) ⚔️[Weapons](#weapons) 🦾[Legion Arms](#legion-arms) 💝[Amulets](#amulets)🛡️[Defense Parts](#defense-parts) <br>
> 📀[Records](#records) 🌙[Upgrade Materials](#upgrade-materials) 💎[Ergo](#ergo) 🧥[Costumes](#costumes) 📜[Quest Items](#quest-items)
---

### ⚠️IMPORTANT: Read before proceeding
- This list is **incomplete**, especially in the Quest Items section which only has base game items.
- Some category headings have a note below them. Make sure to read it before using Item IDs from that category!
---

### ⚙️Note on Commands
- If you're using this ID list to give yourself items, read carefully.
- All **command syntaxes** given in this file are based on **[this tool](https://fearlessrevolution.com/viewtopic.php?f=4&t=25815) by [sunbeam](https://fearlessrevolution.com/memberlist.php?mode=viewprofile&u=12587&sid=7e28eac477c840641d12dc752638bac1)**. You need to install it to use the given Commands.

  > Command Syntax to getting Items: `OnGainItem <ItemId> <ItemCount>`<br>
  > Example: `OnGainItem Quartz 10` will give **10 Quartz**
- Command to give Weapons are different, refer to **Weapon Category Notes**. For more info on commands refer to the original tool linked above.
---

## So Without Further Ado...
### 🔑Key Items
| Sl.| Item Name                    | Item ID                           | Notes |
|----|------------------------------|-----------------------------------|-------|
| 1  | Monad's Lamp                 | `Consume_Monard_Lamp`             |       |
| 2  | Guide's Hourglass            | `Consume_ReturnClock`             |       |
| 3  | Moonphase Pocket Watch       | `Consume_ReturnClockE`            |       |
| 4  | Last Resort                  | `Consume_giveup`                  |       |
| 5  | Pulse Cell                   | `Consume_Rechargeable_1`          |       |
| 6  | Grinder                      | `Consume_Buff_sharpness_recovery` |       |
| 7  | Cube                         | `Consume_Monard_bless`            |       |
| 8  | Core                         | `P_Organ_CorePart`                |       |
| 9  | Upgrade Core                 | `P_Organ_CorePart_Advance`        | DLC   |
| 10 | Enigma Assembly Tool         | `Weapon_combine`                  |       |
| 11 | Grinder Modification Unit    | `Grinder_Unit_Unlock`             |       |
| 12 | Overcharged Storage Battery  | `Collection_Core_Electronic`      |       |
| 13 | High Powered Flame Amplifier | `Collection_Core_Fire`            |       |


#### Missing: Star Chrysalis
---

### 🔁Exchange Materials
| Sl.| Item Name                           | Item ID                       | Notes |
|----|-------------------------------------|-------------------------------|-------|
| 1  | Quartz                              | `Quartz`                      |       |
|‎‎‎||
| 2  | Legion Plug                         | `Exchange_SlaveArm_Parts_4`   |       |
| 3  | Genius' Legion Plug                 | `DLC_Exchange_SlaveArm_Parts` | DLC   |
| 4  | Legion Caliber                      | `Reinforce_SlaveArm_G1`       |       |
|‎‎‎||
| 5  | Motivity Crank                      | `Handle_InfusionStone_Type1`  |       |
| 6  | Technique Crank                     | `Handle_InfusionStone_Type2`  |       |
| 7  | Advance Crank                       | `Handle_InfusionStone_Type3`  |       |
| 8  | Balance Crank                       | `Handle_InfusionStone_Type4`  |       |
|‎‎‎||
| 9  | Hidden Moonstone                    | `Reinforce_Blade_Common_G1`   |       |
| 10 | Crescent Moonstone                  | `Reinforce_Blade_Common_G2`   |       |
| 11 | Half Moonstone                      | `Reinforce_Blade_Common_G3`   |       |
| 12 | Full Moonstone                      | `Reinforce_Blade_Common_G4`   |       |
| 13 | Dark moon Moonstone of the Covenant | `Reinforce_Hero_G1`           |       |
| 14 | Full Moonstone of the Covenant      | `Reinforce_Hero_G2`           |       |

---

### ⚔Weapons

<details>
<summary><strong>📝NOTE! Click to Expand</strong></summary>
  
#### IMPORTANT! Given Item IDs in this category **do not give the entire weapon** but only the `Blade` part of the weapon. 
To get a Complete Weapon you need to get both the `Blade` and the `Handle` part of the weapon. For every weapon the blade part is represented by `BLD` and the handle part is represented by `HND` in the Item ID.
#### Command Syntax:
> To get a complete weapon: `giveweapon <Handle ID> <Blade ID> <quantity>` <br>
> To get a particular weapon part: `giveitem <Handle ID OR Blade ID> <quantity>`
  
#### Example:
> Item ID `WP_PC_BLD_Saber` will give the `Puppet's Saber Blade` <br>
> Item ID `WP_PC_HND_Saber` will give the `Puppet's Saber Handle`
> 
> Therefore to get a complete Puppets Saber the command is: `giveweapon WP_PC_HND_Saber WP_PC_BLD_Saber 1`

This is also true for special weapons that do not allow splitting the blade and the handle. But using commands it is possible to get only one part thus allowing Weapon Assembly with special weapon parts too.

#### Example:
>	Item ID `WP_PC_BLD_RoseSword` will give the `Monad's Sword` _(The name will be `Monad's Sword` but it will only be the Blade)_ <br>
> Item ID `WP_PC_HND_RoseSword` will give the `Monad's Sword` _(The name will be `Monad's Sword` but it will only be the Handle)_
>
>	Therefore to get a complete Monads Sword the command is: `giveweapon WP_PC_HND_RoseSword WP_PC_BLD_RoseSword 1`

Which basically means that whenever you select a Item ID from this list, replace `BLD` in it with `HND` to get its corresponding Handle Part.
</details>

> ### DLC Weapons
| Sl.| Weapon Name                   | Blade Item ID            | Type  |
|----|-------------------------------|--------------------------|-------|
| 1  | Pale Knight                   | `WP_PC_BLD_Gunblade`     | BOSS  |
| 2  | Death's Talon                 | `WP_PC_BLD_IronClaw`     | BOSS  |
|||
| 3  | Monad's Sword                 | `WP_PC_BLD_RoseSword`    |SPECIAL|
| 4  | Royal Horn Bow                | `WP_PC_BLD_Gakgung`      |SPECIAL|
|||
| 5  | Maniac's Pinwheel             | `WP_PC_BLD_Pinwheel`     |       |
| 6  | La Vendetta                   | `WP_PC_BLD_Guardbat`     |       |
| 7  | Lorenzini Bolt                | `WP_PC_BLD_Ballista`     |       |
| 8  | Silent Evangelist's Mace      | `WP_PC_BLD_AcidHammer`   |       |
| 9  | Arche's Guardian              | `WP_PC_BLD_ThunderSword` |       |
| 10 | Puppet of the Future's Welder | `WP_PC_BLD_FireRapier`   |       |

> ### Base Game Weapons
| Sl.| Weapon Name                    | Blade Item ID                   | Type  |
|----|--------------------------------|---------------------------------|-------|
| 1  | Seven-Coil Spring Sword        | `WP_PC_BLD_SevenSword`          | BOSS  |
| 2  | Etiquette                      | `WP_PC_BLD_UmbrellaSword`       | BOSS  |
| 3  | Holy Sword of the Ark          | `WP_PC_BLD_TransformGreatSword` | BOSS  |
| 4  | Trident of the Covenant        | `WP_PC_BLD_Trident`             | BOSS  |
| 5  | Puppet Ripper                  | `WP_PC_BLD_ChainScythe`         | BOSS  |
| 6  | Frozen Feast                   | `WP_PC_BLD_CrystalSword`        | BOSS  |
| 7  | Two Dragons Sword              | `WP_PC_BLD_Hwando`              | BOSS  |
| 8  | Uroboros's Eye                 | `WP_PC_BLD_Charkram`            | BOSS  |
| 9  | Noblesse Oblige                | `WP_PC_BLD_KkabiClub`           | BOSS  |
| 10 | Proof of Humanity              | `WP_PC_BLD_ScissorSword`        | BOSS  |
|||
| 11 | Golden Lie                     | `WP_PC_BLD_NoseStaff`           |SPECIAL|
| 12 | Azure Dragon Crescent Glaive   | `WP_PC_HND_DragonGlaive`        |SPECIAL|
|||
| 13 | Puppet's Saber                 | `WP_PC_BLD_Saber`               |       |
| 14 | Wintry Rapier                  | `WP_PC_BLD_Rapier`              |       |
| 15 | Greatsword of Fate             | `WP_PC_BLD_Bayonet`             |       |
|||
| 16 | Bramble Curved Sword           | `WP_PC_BLD_Kukri`               |       |
| 17 | Military Shovel                | `WP_PC_BLD_Shovel`              |       |
| 18 | Exploding Pickaxe              | `WP_PC_BLD_FirePickaxe`         |       |
| 19 | Blind Man's Double-Sided Spear | `WP_PC_BLD_ShieldSpear`         |       |
| 20 | Big Pipe Wrench Head           | `WP_PC_BLD_ClockworkBlunt`      |       |
| 21 | City Longspear                 | `WP_PC_BLD_GreatSpear`          |       |
| 22 | Spear of Honor                 | `WP_PC_BLD_SwordLance`          |       |
| 23 | Master Chef's Knife            | `WP_PC_BLD_Cleaver`             |       |
| 24 | Dancer's Curved Sword          | `WP_PC_BLD_Shamshir`            |       |
| 25 | Booster Glaive                 | `WP_PC_BLD_Glaive`              |       |
| 26 | Bone-Cutting Sawblade          | `WP_PC_BLD_GreatSaw`            |       |
| 27 | Acidic Crystal Spear           | `WP_PC_BLD_CrystalSpear`        |       |
| 28 | Acidic Great Curved Sword      | `WP_PC_BLD_AcidGreatsword`      |       |
| 29 | Live Puppet's Axe              | `WP_PC_BLD_GreatAxe`            |       |
| 30 | Salamander Dagger              | `WP_PC_BLD_FlameDagger`         |       |
| 31 | Fire Axe                       | `WP_PC_BLD_FireAxe`             |       |
| 32 | Clock Sword                    | `WP_PC_BLD_ClockSword`          |       |
| 33 | Circular Electric Chainsaw     | `WP_PC_BLD_ElectricCutter`      |       |
| 34 | Cursed Knight's Halberd        | `WP_PC_BLD_Halberd`             |       |
| 35 | Electric Coil Stick Head       | `WP_PC_BLD_CoilRod`             |       |
| 36 | Carcass Crystal Axe            | `WP_PC_BLD_CrystalAxe`          |       |
| 37 | Coil Mjolnir Head              | `WP_PC_BLD_ElectricHammer`      |       |
| 38 | Krat Police Baton Head         | `WP_PC_BLD_Baton`               |       |
| 39 | Tyrant Murderer's Dagger       | `WP_PC_BLD_Dagger`              |       |
| 40 | Pistol Rock Drill              | `WP_PC_BLD_RockDrill`           |       |
| 41 | Black Steel Cutter             | `WP_PC_BLD_FlameSword`          |       |

---

### 🦾Legion Arms
| Item ID                     | Name             |
|-----------------------------|------------------|
| `SlaveArm_Normal`           | Left Arm of Steel|
| `SlaveArm_PuppetString`     | Puppet String    |
| `SlaveArm_Fulminis`         | Fulminis         |
| `SlaveArm_Flamberge`        | Flamberge        |
| `SlaveArm_AcidLuncher`      | Pandemonium      |
| `SlaveArm_PileBunker`       | Deus Ex Machina  |
| `SlaveArm_Aegis`            | Aegis            |
| `SlaveArm_SniperCannon`     | Falcon Eyes      |
| `SlaveArm_Boomerang`        | Icarus           |
| `SlaveArm_ChargeShotGun`    | Cataclysm        |
---

### 💝Amulets

<details>
<summary><strong>📝NOTE! Click to Expand</strong></summary>

#### IMPORTANT! Given Item IDs in this category only give the base versions of the Amulets. 
To get the +1/+2/+3 versions of the Amulets you need to append _1/_2/_3 respectively

#### Example:
> Item ID `AC_mgmt_equip_L1_1` will give the `Strength Amulet` <br>
> Item ID `AC_mgmt_equip_L1_1_2` will give the `Strength Amulet+2` <br>
> Item ID `AC_mgmt_equip_L1_1_3` will give the `Strength Amulet+3`
>
> Therefore to get a `Strength Amulet +3` the command is `OnGainItem AC_mgmt_equip_L1_1_3 1`

Not all Amulets have a +1/+2/+3 version. Appending _1/_2/_3 to those Item IDs will create an invalid Item ID and give nothing.<br>
I have written the max upgrade versions of upgradeable amulets in the `Max Lv` column.
</details>

> ### DLC Amulets
| Sl.| Amulet Name              | Item ID          |Max Lv.|
|----|--------------------------|------------------|-------|
| 1  | Morbid Ambition's Amulet | `DLC_AC_Boss_01` |       |
| 2  | Nightmare's Amulet       | `DLC_AC_Boss_02` |       |
|||
| 3  | Duelist's Amulet         | `DLC_AC_01`      |       |
| 4  | Plundering Amulet        | `DLC_AC_03`      |       |
| 5  | Survival Amulet          | `DLC_AC_02`      |       |
| 6  | Solutionist's Amulet     | `DLC_AC_04`      |       |
| 7  | Legion Amulet            | `DLC_AC_07`      |       |
| 8  | Giant's Amulet           | `DLC_AC_08`      |       |
| 9  | Shepherd's Amulet        | `DLC_AC_09`      |       |
| 10 | Strategist's Amulet      | `DLC_AC_10`      |       |
| 11 | Courage Amulet           | `DLC_AC_11`      |       |
| 12 | Frenzied Amulet          | `DLC_AC_12`      | +1    |
| 13 | Winter's Sleep Amulet    | `DLC_AC_13`      | +3    |
| 14 | Whirlwind Amulet         | `DLC_AC_14`      |       |
| 15 | Storyteller's Amulet     | `DLC_AC_15`      |       |
| 16 | Tenacious Amulet         | `DLC_AC_16`      |       |

> ### Base Game Amulets
| Sl.| Amulet Name                   | Item ID               |Max Lv.|
|----|-------------------------------|-----------------------|-------|
| 1  | Dancing One's Amulet          | `AC_boss_L1_1`        |       |
| 2  | Extreme Modification Amulet   | `AC_boss_L1_2`        |       |
| 3  | Conquering Amulet             | `AC_resist_L3_9`      |       |
| 4  | Nameless One's Amulet         | `AC_mgmt_stat_L2_6`   |       |
| 5  | Triumvirate Amulet            | `AC_mgmt_equip_L3_10` |       |
| 6  | Arm of God Amulet             | `AC_mgmt_equip_L3_11` |       |
| 7  | Ghost Walk Amulet             | `AC_boss_L1_3`        |       |
| 8  | Impregnable Fortress Amulet   | `AC_boss_L1_4`        |       |
| 9  | Awakened God's Amulet         | `AC_boss_L1_5`        |       |
| 10 | Piercing Hatred Amulet        | `AC_boss_L1_6`        |       |
|||
| 11 | Black Cat's Amulet            | `AC_def_L1_3`         |       |
| 12 | Veteran's Amulet              | `AC_mgmt_stat_L2_5`   |       |
| 13 | Red Fox's Amulet              | `AC_mgmt_equip_L2_4`  |       |
| 14 | Assassin's Amulet             | `AC_atk_L2_4`         |       |
| 15 | Swordsmanship Master's Amulet | `AC_mgmt_stat_L2_7`   |       |
| 16 | Puppet Destroyer's Amulet     | `AC_atk_L2_3`         |       |
| 17 | Carcass Butcher's Amulet      | `AC_atk_L2_1`         |       |
| 18 | Murderer Puppet's Amulet      | `AC_atk_L2_2`         |       |
|||
| 19 | Blue Guardianship Amulet      | `AC_mgmt_stat_L1_10`  | +3    |
| 20 | Strength Amulet               | `AC_mgmt_equip_L1_1`  | +3    |
| 21 | Technique Amulet              | `AC_mgmt_equip_L1_2`  | +3    |
| 22 | Transformation Amulet         | `AC_mgmt_equip_L1_3`  | +3    |
|||
| 23 | Leaping Amulet                | `AC_mgmt_stat_L1_3`   | +1    |
| 24 | Indomitable Amulet            | `AC_resist_L2_1`      | +1    |
| 25 | Hunter's Amulet               | `AC_mgmt_stat_L1_11`  | +1    |
| 26 | Life Amulet                   | `AC_mgmt_stat_L1_1`   | +1    |
| 27 | Carrier's Amulet              | `AC_mgmt_equip_L3_5`  | +1    |
| 28 | Patience Amulet               | `AC_mgmt_stat_L2_9`   | +1    |
| 29 | Recharged Amulet              | `AC_mgmt_stat_L2_8`   | +1    |
| 30 | Iron Wall Amulet              | `AC_def_L3_1`         | +1    |

### 🛡Defense Parts
### 📀Records
### 🌙Upgrade Materials
### 💎Ergo
### 🧥Costumes
### 📜Quest Items
---

### ✍️Creator Notes
This list primarily is for players who aren’t deep in the modding or game-unpacking scene but still want to spawn items in-game. Before the Overture DLC, [this list](https://fearlessrevolution.com/viewtopic.php?p=317058#p317058) by [NarcolepticIBS](https://fearlessrevolution.com/memberlist.php?mode=viewprofile&u=170917&sid=b8be7d1e0c54b7505bfc7fd4f9a6fb06) was the go-to resource — but it never got updated after the DLC dropped.<br>
So when I started digging for Item IDs myself, I figured I can build a fresh, updated, centralized version. And host it on Github so others can contribute.<br>
Hope it’s as useful to others as it’s been for me. Happy spawning! 🎮

### 📈Future Plans
- I plan to complete - Missing Item names & DLC Quest Items
- I do not plan to complete - DLC Collectibles
- If you want to expand the list or spot any mistakes, contributions via Pull Requests will be much appreciated! Kindly [EMail me](mailto:pryor.e.t.x100@gmail.com) if you have any questions!

