![LiesOFPLogo](https://www.liesofp.com/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F150395%2F1737984357-image-2-2.png&w=256&q=100)
## 🧭 Item ID Compendium
_Every relic has a name. Every name has a code. Welcome to the vault._

**This repository contains a categorized list of Item IDs used in-game. Click on the titles below to skip to a category:**
> 🔧[Equipment](#equipment) ⚔️[Weapons(+Upgrades)](#weaponsupgrades) 🦾[Legion Arms(+Upgrades)](#legion-arms) <br>
> ⚙️[Grindstones](#grindstones) 💝[Amulets](#amulets)🛡️[Defense Parts](#defense-parts) 🔷[Wishstones](#wishstones)<br>
> 🔑[Key Items](#key-items) ✨[Special Items](#special-items) 🧪[Consumables](#consumables) 👜[Shops(+Currency)](#shopscurrency) 💎[Ergo](#ergo) 🧩[Encoded Messages](#encoded-messages)<br>
> 💿[Records](#records) 💬[Gestures](#gestures) 🥼[Costumes](#costumes) 📜[Collectibles](#collectibles)
---

### ⚠️IMPORTANT: Read before proceeding
- Some category headings have a note below them. Make sure to read it before using Item IDs from that category!
- The Commands and Item IDs are tested in Game **version 1.8.0.0** with Overture DLC and Bonus Content installed.
---

### ⚙️Note on Commands
- If you're using this ID list to give yourself items, read carefully.
- All **command syntaxes** given in this file are based on **[this tool](https://fearlessrevolution.com/viewtopic.php?f=4&t=25815) by [sunbeam](https://fearlessrevolution.com/memberlist.php?mode=viewprofile&u=12587&sid=7e28eac477c840641d12dc752638bac1)**. You need to install it to use the given Commands.

  > Command Syntax to getting Items: `OnGainItem <ItemId> <ItemCount>`<br>
  > Example: `OnGainItem Quartz 10` will give **10 Quartz**
- Command to give Weapons are different, refer to **Weapon Category Notes**. For more info on commands refer to the original tool linked above.
---

## So Without Further Ado...
### 🔧Equipment
> ### Basic Items
| Sl.| Item Name                    | Item ID                           | Notes |
|----|------------------------------|-----------------------------------|-------|
| 1  | Monad's Lamp                 | `Consume_Monard_Lamp`             |       |
| 2  | Moonphase Pocket Watch       | `Consume_ReturnClockE`            |       |
| 3  | Last Resort                  | `Consume_giveup`                  |       |
| 4  | Pulse Cell                   | `Consume_Rechargeable_1`          |       |
| 5  | Grinder                      | `Consume_Buff_sharpness_recovery` |       |
| 6  | Cube                         | `Consume_Monard_bless`            |       |
| 7  | Core                         | `P_Organ_CorePart`                |       |

> ### Advanced Items
| Sl.| Item Name                    | Item ID                           | Notes |
|----|------------------------------|-----------------------------------|-------|
| 8  | Upgrade Core                 | `P_Organ_CorePart_Advance`        | DLC   |
| 9  | Enigma Assembly Tool         | `Weapon_combine`                  |       |
| 10 | Grinder Modification Unit    | `Grinder_Unit_Unlock`             |       |
| 11 | Overcharged Storage Battery  | `Collection_Core_Electronic`      |       |
| 12 | High Powered Flame Amplifier | `Collection_Core_Fire`            |       |

---

### ⚔Weapons(+Upgrades)

<details>
<summary><strong>📝NOTE! Click to Expand</strong></summary>
  
#### IMPORTANT! Given Item IDs in this category **do not give the entire weapon** but only the `Blade` part of the weapon. 
To get a Complete Weapon you need to get both the `Blade` and the `Handle` part of the weapon. For every weapon the blade part is represented by `BLD` and the handle part is represented by `HND` in the Item ID.
#### Command Syntax:
> To get a complete weapon: `OnGiveWeapon <Handle ID> <Blade ID> <upgrade level>` <br>
> To get a particular weapon part: `OnGiveWeapon <Handle ID OR Blade ID> <upgrade level>`

#### Example:
> Item ID `WP_PC_BLD_Saber` will give the `Puppet's Saber Blade` <br>
> Item ID `WP_PC_HND_Saber` will give the `Puppet's Saber Handle`
> 
> Therefore to get a complete Puppets Saber the command is: `OnGiveWeapon WP_PC_HND_Saber WP_PC_BLD_Saber`

This is also true for special weapons that do not allow splitting the blade and the handle. But using commands it is possible to get only one part thus allowing Weapon Assembly with special weapon parts too.

#### Example:
>	Item ID `WP_PC_BLD_RoseSword` will give the `Monad's Sword` _(The name will be `Monad's Sword` but it will only be the Blade)_ <br>
> Item ID `WP_PC_HND_RoseSword` will give the `Monad's Sword` _(The name will be `Monad's Sword` but it will only be the Handle)_
>
>	Therefore to get a complete Monads Sword the command is: `OnGiveWeapon WP_PC_HND_RoseSword WP_PC_BLD_RoseSword`

Which basically means that whenever you select a Item ID from this list, replace `BLD` in it with `HND` to get its corresponding Handle Part.<br>
Additionally, command to give a `Monad's Sword +5` will be `OnGiveWeapon WP_PC_HND_RoseSword WP_PC_BLD_RoseSword 4`
</details>

> ### DLC Weapons
| Sl.| Weapon Name                    | Blade Item ID                   | Type  |
|----|--------------------------------|---------------------------------|-------|
| 1  | Pale Knight                    | `WP_PC_BLD_Gunblade`            | BOSS  |
| 2  | Death's Talon                  | `WP_PC_BLD_IronClaw`            | BOSS  |
||||
| 3  | Monad's Sword                  | `WP_PC_BLD_RoseSword`           |SPECIAL|
| 4  | Royal Horn Bow                 | `WP_PC_BLD_Gakgung`             |SPECIAL|
||||
| 5  | Maniac's Pinwheel              | `WP_PC_BLD_Pinwheel`            |       |
| 6  | La Vendetta                    | `WP_PC_BLD_Guardbat`            |       |
| 7  | Lorenzini Bolt                 | `WP_PC_BLD_Ballista`            |       |
| 8  | Silent Evangelist's Mace       | `WP_PC_BLD_AcidHammer`          |       |
| 9  | Arche's Guardian               | `WP_PC_BLD_ThunderSword`        |       |
| 10 | Puppet of the Future's Welder  | `WP_PC_BLD_FireRapier`          |       |

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
||||
| 11 | Golden Lie                     | `WP_PC_BLD_NoseStaff`           |SPECIAL|
| 12 | Azure Dragon Crescent Glaive   | `WP_PC_HND_DragonGlaive`        |SPECIAL|
||||
| 13 | Puppet's Saber                 | `WP_PC_BLD_Saber`               |       |
| 14 | Wintry Rapier                  | `WP_PC_BLD_Rapier`              |       |
| 15 | Greatsword of Fate             | `WP_PC_BLD_Bayonet`             |       |
||||
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

> ### Cranks
| Sl.| Item Name                           | Item ID                      | Notes |
|----|-------------------------------------|------------------------------|-------|
| 1  | Motivity Crank                      | `Handle_InfusionStone_Type1` |       |
| 2  | Technique Crank                     | `Handle_InfusionStone_Type2` |       |
| 3  | Advance Crank                       | `Handle_InfusionStone_Type3` |       |
| 4  | Balance Crank                       | `Handle_InfusionStone_Type4` |       |

> ### Moonstones
| Sl.| Item Name                           | Item ID                      | Notes |
|----|-------------------------------------|------------------------------|-------|
| 1  | Hidden Moonstone                    | `Reinforce_Blade_Common_G1`  |       |
| 2  | Crescent Moonstone                  | `Reinforce_Blade_Common_G2`  |       |
| 3  | Half Moonstone                      | `Reinforce_Blade_Common_G3`  |       |
| 4  | Full Moonstone                      | `Reinforce_Blade_Common_G4`  |       |
| 5  | Dark moon Moonstone of the Covenant | `Reinforce_Hero_G1`          |       |
| 6  | Full Moonstone of the Covenant      | `Reinforce_Hero_G2`          |       |

---

### 🦾Legion Arms
Little advice if you want multiple Legion Arms - Just get Legion Plugs in bulk and craft the Arms.
> ### Arms
| Sl.| Legion Arm        | Item ID                  | Notes |
|----|-------------------|--------------------------|-------|
| 1  | Icarus            | `SlaveArm_Boomerang`     | DLC   |
| 2  | Cataclysm         | `SlaveArm_ChargeShotGun` | DLC   |
||||
| 3  | Left Arm of Steel | `SlaveArm_Normal`        |       |
| 4  | Puppet String     | `SlaveArm_PuppetString`  |       |
| 5  | Fulminis          | `SlaveArm_Fulminis`      |       |
| 6  | Flamberge         | `SlaveArm_Flamberge`     |       |
| 7  | Pandemonium       | `SlaveArm_AcidLuncher`   |       |
| 8  | Deus Ex Machina   | `SlaveArm_PileBunker`    |       |
| 9  | Aegis             | `SlaveArm_Aegis`         |       |
| 10 | Falcon Eyes       | `SlaveArm_SniperCannon`  |       |

> ### Arm Upgrades
| Sl.| Item Name                    | Item ID                           | Notes |
|----|------------------------------|-----------------------------------|-------|
| 1  | Legion Caliber               | `Reinforce_SlaveArm_G1`           |       |
| 2  | Legion Plug                  | `Exchange_SlaveArm_Parts_4`       |       |
| 3  | Genius' Legion Plug          | `DLC_Exchange_SlaveArm_Parts`     | DLC   |

---

### ⚙Grindstones
| Sl.| Item Name                    | Item ID                           | Notes |
|----|------------------------------|-----------------------------------|-------|
| 1  | Flame Grindstone             | `Grinder_Unit_01`                 |       |
| 2  | Electric Blitz Grindstone    | `Grinder_Unit_02`                 |       |
| 3  | Acid Grindstone              | `Grinder_Unit_03`                 |       |
| 4  | Indomitable Grindstone       | `Grinder_Unit_04`                 |       |
| 5  | Destruction Grindstone       | `Grinder_Unit_05`                 |       |
| 6  | Satisfaction Grindstone      | `Grinder_Unit_06`                 |       |
| 7  | Durability Grindstone        | `Grinder_Unit_07`                 |       |
| 8  | Perfection Grindstone        | `Grinder_Unit_08`                 |       |
||||
| 9  | Cutting Grindstone           | `DLC_Grinder_Unit_01`             |DLC    |
| 10 | Piercing Grindstone          | `DLC_Grinder_Unit_02`             |DLC    |

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
| Sl.| Amulet Name                   | Item ID               |Max Lv.|
|----|-------------------------------|-----------------------|-------|
| 1  | Morbid Ambition's Amulet      | `DLC_AC_Boss_01`      |       |
| 2  | Nightmare's Amulet            | `DLC_AC_Boss_02`      |       |
||||
| 3  | Duelist's Amulet              | `DLC_AC_01`           |       |
| 4  | Plundering Amulet             | `DLC_AC_02`           |       |
| 5  | Survival Amulet               | `DLC_AC_03`           |       |
| 6  | Solutionist's Amulet          | `DLC_AC_04`           |       |
| 7  | Legion Amulet                 | `DLC_AC_07`           |       |
| 8  | Giant's Amulet                | `DLC_AC_08`           |       |
| 9  | Shepherd's Amulet             | `DLC_AC_09`           |       |
| 10 | Strategist's Amulet           | `DLC_AC_10`           |       |
| 11 | Courage Amulet                | `DLC_AC_11`           |       |
| 12 | Frenzied Amulet               | `DLC_AC_12`           | +1    |
| 13 | Winter's Sleep Amulet         | `DLC_AC_13`           | +3    |
| 14 | Whirlwind Amulet              | `DLC_AC_14`           |       |
| 15 | Storyteller's Amulet          | `DLC_AC_15`           |       |
| 16 | Tenacious Amulet              | `DLC_AC_16`           |       |

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
||||
| 11 | Black Cat's Amulet            | `AC_def_L1_3`         |       |
| 12 | Veteran's Amulet              | `AC_mgmt_stat_L2_5`   |       |
| 13 | Red Fox's Amulet              | `AC_mgmt_equip_L2_4`  |       |
| 14 | Assassin's Amulet             | `AC_atk_L2_4`         |       |
| 15 | Swordsmanship Master's Amulet | `AC_mgmt_stat_L2_7`   |       |
| 16 | Puppet Destroyer's Amulet     | `AC_atk_L2_3`         |       |
| 17 | Carcass Butcher's Amulet      | `AC_atk_L2_1`         |       |
| 18 | Murderer Puppet's Amulet      | `AC_atk_L2_2`         |       |
||||
| 19 | Blue Guardianship Amulet      | `AC_mgmt_stat_L1_10`  | +3    |
| 20 | Strength Amulet               | `AC_mgmt_equip_L1_1`  | +3    |
| 21 | Technique Amulet              | `AC_mgmt_equip_L1_2`  | +3    |
| 22 | Transformation Amulet         | `AC_mgmt_equip_L1_3`  | +3    |
||||
| 23 | Leaping Amulet                | `AC_mgmt_stat_L1_3`   | +1    |
| 24 | Indomitable Amulet            | `AC_resist_L2_1`      | +1    |
| 25 | Hunter's Amulet               | `AC_mgmt_stat_L1_11`  | +1    |
| 26 | Life Amulet                   | `AC_mgmt_stat_L1_1`   | +1    |
| 27 | Carrier's Amulet              | `AC_mgmt_equip_L3_5`  | +1    |
| 28 | Patience Amulet               | `AC_mgmt_stat_L2_9`   | +1    |
| 29 | Recharged Amulet              | `AC_mgmt_stat_L2_8`   | +1    |
| 30 | Iron Wall Amulet              | `AC_def_L3_1`         | +1    |

---

### 🛡Defense Parts

<details>
<summary><strong>📝NOTE! Click to Expand</strong></summary>

#### IMPORTANT! Given Item IDs in this category only give the base versions of the Defense Parts. 
To get the +1/+2 versions of the Defense Parts you need to append _1/_2 respectively

#### Example:
> Item ID `part_assembly_curse_3` will give the `LADA Disruption Cartridge`<br>
>	Item ID `part_assembly_curse_3_2` will give the `LADA Disruption Cartridge+2`
>
> Therefore to get a `LADA Disruption Cartridge+2` the command is `OnGainItem part_assembly_curse_3_2 1`

All Defense Parts except **DLC** and **Basic** have a +1/+2 version.
</details>

> ### One for All Parts
| Sl.| Item Name                                              | Item ID                     | Notes |
|----|--------------------------------------------------------|-----------------------------|-------|
| 1  | Workshop Union Composite Armor Liner                   | `part_skin_all_4`           | DLC   |
| 2  | Workshop Union Auto Adaptive Converter                 | `part_underskin_all_3`      | DLC   |
| 3  | Workshop Union Finished Cartridge                      | `part_assembly_all_3`       | DLC   |
||||
| 4  | Workshop Union Basic Frame                             | `part_bone_00`              |BASIC  |
| 5  | Workshop Union Certified Liner                         | `part_skin_strike_0`        |BASIC  |
| 6  | Workshop Union Old Generation Converter                | `part_underskin_0`          |BASIC  |
| 7  | Workshop Union Cartridge Prototype                     | `part_assembly_0`           |BASIC  |

> ### Frames
| Sl.| Item Name                                              | Item ID                     | Notes |
|----|--------------------------------------------------------|-----------------------------|-------|
| 1  | Workshop Union Lightweight Frame                       | `part_bone_0`               |       |
| 2  | LADA F150 Frame                                        | `part_bone_1`               |       |
| 3  | Workshop Union Strengthening Frame                     | `part_bone_2`               |       |
| 4  | Arch Heavyweight Frame                                 | `part_bone_3`               |       |
| 5  | LADA F250 Frame                                        | `part_bone_4`               |       |
| 6  | Arch Extra Heavyweight Frame                           | `part_bone_5`               |       |
| 7  | LADA F350 Frame                                        | `part_bone_6`               |       |

> ### Liners
| Sl.| Item Name                             | Item ID              | Notes |
|----|---------------------------------------|----------------------|-------|
| 1  | Workshop Union Fiber-Reinforced Liner | `part_skin_slash_1`  |       |
| 2  | Belford Fiber-Reinforced Liner        | `part_skin_slash_2`  |       |
| 3  | Arch Fiber-Reinforced Liner           | `part_skin_slash_3`  |       |
| 4  | LADA Fiber-Reinforced Liner           | `part_skin_slash_4`  |       |
||||
| 5  | Workshop Union Spaced Armor Liner     | `part_skin_strike_1` |       |
| 6  | Belford Spaced Armor Liner            | `part_skin_strike_2` |       |
| 7  | Arch Spaced Armor Liner               | `part_skin_strike_3` |       |
| 8  | LADA Spaced Armor Liner               | `part_skin_strike_4` |       |
||||
| 9  | Workshop Union Multi-Layer Liner      | `part_skin_pierce_1` |       |
| 10 | Belford Multi-Layer Liner             | `part_skin_pierce_2` |       |
| 11 | Arch Multi-Layer Liner                | `part_skin_pierce_3` |       |
| 12 | LADA Multi-Layer Liner                | `part_skin_pierce_4` |       |

> ### Converter
|Sl.| Item Name                                              | Item ID                     | Notes |
|---|--------------------------------------------------------|-----------------------------|-------|
| 1 | Workshop Union Standard Radiation Converter            | `part_underskin_fire_1`     |       |
| 2 | Belford Superior Radiation Converter                   | `part_underskin_fire_2`     |       |
| 3 | LADA Large Capacity Radiation Converter                | `part_underskin_fire_3`     |       |
||||
| 4 | Workshop Union Standard Insulation Converter           | `part_underskin_electric_1` |       |
| 5 | Belford Superior Insulation Converter                  | `part_underskin_electric_2` |       |
| 6 | LADA Large Capacity Insulation Converter               | `part_underskin_electric_3` |       |
||||
| 7 | Workshop Union Standard Corrosion Resistance Converter | `part_underskin_acid_1`     |       |
| 8 | Belford Superior Corrosion Resistance Converter        | `part_underskin_acid_2`     |       |
| 9 | LADA Large Capacity Corrosion Resistance Converter     | `part_underskin_acid_3`     |       |

> ### Cartridge
|Sl.| Item Name                    | Item ID                  | Notes |
|---|------------------------------|--------------------------|-------|
| 1 | Belford Break Cartridge      | `part_assembly_break_1`  |       |
| 2 | Arch Break Cartridge         | `part_assembly_break_2`  |       |
| 3 | LADA Break Cartridge         | `part_assembly_break_3`  |       |
||||
| 4 | Belford Shock Cartridge      | `part_assembly_impact_1` |       |
| 5 | Arch Shock Cartridge         | `part_assembly_impact_2` |       |
| 6 | LADA Shock Cartridge         | `part_assembly_impact_3` |       |
||||
| 7 | Belford Disruption Cartridge | `part_assembly_curse_1`  |       |
| 8 | Arch Disruption Cartridge    | `part_assembly_curse_2`  |       |
| 9 | LADA Disruption Cartridge    | `part_assembly_curse_3`  |       |

---

### 🔷Wishstones
| Sl.| Item Name             | Item ID         | Function                                                   |
|----|-----------------------|-----------------|------------------------------------------------------------|
| 1  | Recovery Wishstone    | `Monad_Unit_01` | Temporarily restores HP                                    |
| 2  | Patience Wishstone    | `Monad_Unit_02` | Increases max Stamina over a set period of time            |
| 3  | Advance Wishstone     | `Monad_Unit_03` | Temporarily restores Legion                                |
| 4  | Friendship Wishstone  | `Monad_Unit_04` | Temporarily restores Specter HP                            |
| 5  | Explosive Wishstone   | `Monad_Unit_05` | Explodes when Specter is hit                               |
| 6  | Protection Wishstone  | `Monad_Unit_06` | Reduces Specter's received damage                          |
| 7  | Frenzy Wishstone      | `Monad_Unit_07` | Increases Specter's destructive power                      |
| 8  | Indomitable Wishstone | `Monad_Unit_08` | Specter avoids death once and HP is restored               |
| 9  | Flame Wishstone       | `Monad_Unit_09` | Specter's Fire ATK/Reduces damage received                 |
| 10 | Lightning Wishstone   | `Monad_Unit_10` | Specter's Electric Blitz ATK/Reduces damage received       |
| 11 | Poison Wishstone      | `Monad_Unit_11` | Specter's Acid ATK/Reduces damage received                 |
| 12 | Courage Wishstone     | `Monad_Unit_12` | Increases Fable's charge amount when attacking             |
| 13 | Provocation Wishstone | `Monad_Unit_13` | Specter attracts enemy's attention/Reduces damage received |

---
### 🔑Key Items
> ### Keys
| Sl.| Item Name                              | Item ID                        | Notes |
|----|----------------------------------------|--------------------------------|-------|
| 1  | Trinity Key                            | `Epic_key_riddle`              |       |
| 2  | The Chosen One’s Trinity Key           | `Epic_key_riddle_final`        |       |
| 3  | Black Rabbit Hole Key                  | `Epic_key_rabbit`              | DLC   |
||||
| 4  | Krat Central Station Main Entrance Key | `Key_1`                        | DLC   |
| 5  | Secret Room Key                        | `Epic_key_hotel_VIP`           | DLC   |
| 6  | Zoo Tram Station Key                   | `Epic_key_zoo_tram`            | DLC   |
| 7  | Markiona’s Key                         | `Epic_key_zoo_play`            | DLC   |
| 8  | Coolant Control Room Console Key       | `Epic_key_lab_control_room`    | DLC   |
| 9  | Secret Ruins Key                       | `Epic_key_Ruin_BossRoom`       | DLC   |
| 10 | Fisherman’s Weathered Key              | `Epic_key_sea_Fisherman`       | DLC   |
| 11 | Monad Family’s Master Key              | `Epic_key_lab_monad`           | DLC   |
| 12 | Rose Garden Key                        | `Epic_key_RoseGarden`          | DLC   |
||||
| 13 | Cable Railway Key                      | `Epic_key_cath_funicular`      |       |
| 14 | Elysion Boulevard Apartment Key        | `Epic_key_hidden1`             |       |
| 15 | Krat City Hall Key                     | `Epic_key_cityhall`            |       |
| 16 | Krat City Hall Courtyard Key           | `Epic_key_ftr`                 |       |
| 17 | Venigni Works Back Door Key            | `Epic_key_factory_to_cath`     |       |
| 18 | Slum Shack Key                         | `Epic_key_SlumHouse`           |       |
| 19 | Rosa Isabelle Street Entrance Key      | `Epic_key_hotel_to_cult`       |       |
| 20 | Lorenzini Arcade 1st Floor Key         | `Epic_key_arcadecross`         |       |
| 21 | Arcade Underground Passage Key         | `Epic_key_arcade_tunnel`       |       |
| 22 | Saintess of Mercy Statue Gallery Key   | `Epic_key_pieta`               |       |
| 23 | High-level Alchemist Badge             | `Epic_key_Monastery_entry`     |       |
| 24 | Arche Abbey Passageway Key             | `Epic_key_MonasteryB_6F`       |       |
| 25 | Letter with the Refuge’s Address       | `Epic_key_dottedpaper_room_01` |       |
| 26 | Robbers’ Shack Key                     | `Epic_key_dottedpaper_room_03` |       |

> ### Main Quest Items
| Sl.| Item Name                         | Item ID                             | Notes |
|----|-----------------------------------|-------------------------------------|-------|
| 1  | Portrait of a Boy                 | `Epic_boy_paint`                    |       |
| 2  | Golden Ergo                       | `Epic_GoldenErgo`                   |       |
| 3  | Golden lead-acid battery          | `Epic_GoldenBattery`                |       |
| 4  | Ergo Wavelength Decoder           | `Epic_ErgoWave_Interpreter`         |       |
| 5  | Completed Ergo Wavelength Decoder | `Epic_Second_Life`                  |       |
| 6  | King of Puppets’ Message          | `Epic_PuppetKing_Message`           |       |
| 7  | Someone’s Necklace                | `Epic_OrphanageNecklace`            |       |
| 8  | A cure for Antonia                | `Epic_Remedy`                       |       |
| 9  | A cure no more effective          | `Epic_DiscoloredRemedy`             |       |
| 10 | Arm of God                        | `Epic_ArmOfGod`                     |       |
| 11 | Echo Player                       | `DLC_Quest_EchosPlayer`             | DLC   |
| 11 | Bloodstained Locket               | `DLC_Collection_Epic_Romeo_Locket`  | DLC   |

> ### Side Quest Items
| Sl.| Item Name                       | Item ID                              | Notes |
|----|---------------------------------|--------------------------------------|-------|
| 1  | Faded Whistle                   | `Consume_Instrument_01`              |       |
| 2  | Daylight Wreathed Horn          | `Consume_Nabal`                      | DLC   |
| 3  | Carnival Coin                   | `DLC_Consume_Carnival_Coin`          | DLC   |
||||
| 4  | Broken Baby Puppet              | `Epic_babydoll`                      |       |
| 5  | Small Wooden Officer Puppet     | `Epic_PoliceDoll`                    |       |
| 6  | Archbishop’s Holy Mark          | `Epic_Poison_for_rest`               |       |
| 7  | Smiling Bunny Mark              | `Epic_blackrabbit`                   |       |
| 8  | Wedding Ring                    | `Epic_ring`                          |       |
| 9  | Bloody Wedding Ring             | `Epic_ring_blood`                    |       |
| 10 | Venigni Commemorative Coin      | `Epic_Venigni_Coin`                  |       |
| 11 | Moon World Warrior Toy          | `Epic_Riddleking_Evidence`           |       |
| 12 | Bright Red Apple                | `Epic_RedApple`                      |       |
| 13 | Red Actress’s Locket            | `Epic_RedLadyLocket`                 |       |
| 14 | The White Lady’s Locket         | `Epic_WhiteLadyLocket`               |       |
| 15 | La Bleiwies                     | `Epic_WineCollection`                |       |
| 16 | Four-fingered Glove             | `Epic_Glove`                         |       |
| 17 | King of Riddles’ Surprise Box   | `Epic_riddle_box_01`                 |       |
| 18 | King of Riddles’ Surprise Box   | `Epic_riddle_box_02`                 |       |
| 19 | Golden Seed                     | `DLC_Quest_Gold_Seed`                | DLC   |
| 20 | Golden Rose                     | `DLC_Quest_Gold_Rose`                | DLC   |
| 21 | Bell Collar                     | `DLC_Quest_CatNecklace`              | DLC   |
| 22 | Rose Shoes                      | `DLC_Quest_Rosaura_Parts_06`         | DLC   |
| 23 | Old Bottle of Beer              | `DLC_Collection_Epic_Beer`           | DLC   |
| 24 | Empty Painkiller Bottle         | `DLC_Collection_Epic_Painkiller`     | DLC   |
| 25 | Blank Canvas                    | `DLC_Collection_Epic_Canvas`         | DLC   |
| 26 | Goddard’s Art Supplies          | `DLC_Collection_Epic_Goldeyes`       | DLC   |
| 27 | Painter’s Sky                   | `DLC_Collection_Poster_SelfPortrait` | DLC   |


---

### ✨Special Items
|Sl.| Item Name                     | Item ID             | Notes |
|---|-------------------------------|---------------------|-------|
| 1 | Quartz                        | `Quartz`            |       |
||||
| 2 | Star Fragment                 | `Helpmate_Material` |       |
||||
| 3 | Alchemical Booster            | `goldTree_Booster1` |       |
| 4 | Stabilized Alchemical Booster | `goldTree_Booster2` |       |
| 5 | Enhanced Alchemical Booster   | `goldTree_Booster3` |       |

---
### 🧪Consumables
> ### Consumable Items
| Sl.| Item Name                      | Item ID                         | Notes |
|----|--------------------------------|---------------------------------|-------|
| 1  | Anti-Freeze Ampoule            | `Consume_CancelBuff_Frozen`     | DLC   |
| 2  | Miraculous Enhancement Ampoule | `Consume_Buff_Body_Enhance`     | DLC   |
| 3  | Miraculous Recovery Ampoule    | `Consume_Recovery_Full`         | DLC   |
| 4  | Grindstone Coating Capsule     | `Consume_Recovery_Grinder`      | DLC   |
| 5  | Gemini's Enhanced Detection    | `Consume_Buff_Gain_Exp`         | DLC   |
||||
| 6  | Gemini's Iron Protection       | `Consume_Drop_Ergo_save`        |       |
| 7  | Recirculating Catalyst         | `Consume_Buff_stamina_regain`   |       |
| 8  | Venigni's Urgent Repair Tool   | `Consume_Buff_sharpness_regain` |       |
| 9  | Cat Dust                       | `Consume_cat_dust`              |       |
||||
| 10 | Fable Catalyst                 | `Consume_Buff_Frenzy`           |       |
| 11 | Legion Magazine                | `Consume_Buff_SlaveMagazine`    |       |
||||
| 12 | Fire Abrasive                  | `Consume_Buff_sharpness_Fire`   |       |
| 13 | Acid Abrasive                  | `Consume_Buff_sharpness_Acid`   |       |
| 14 | Electric Blitz Abrasive        | `Consume_Buff_sharpness_Elec`   |       |
||||
| 15 | Attribute Resistance Ampoule   | `Consume_Buff_Elemental`        |       |
| 16 | Attribute Purification Ampoule | `Consume_Cancel_Elemental`      |       |
| 17 | Special Resistance Ampoule     | `Consume_Buff_Special`          |       |
| 18 | Special Purification Ampoule   | `Consume_Cancel_Special`        |       |

> ### Throwing Items
| Sl.| Item Name                 | Item ID                         | Notes |
|----|---------------------------|---------------------------------|-------|
| 1  | Sawtoothed Wheel          | `Consume_Throw_Gear`            |       |
| 2  | Saw Blade                 | `Consume_Throw_sawtooth`        |       |
| 3  | Sharp Pipe                | `Consume_Throw_bignail`         |       |
| 4  | Cluster Grenade           | `Consume_Throw_Granade_Cluster` |       |
| 5  | Shot Put                  | `Consume_Throw_shotput`         |       |
| 6  | Chain                     | `Consume_Throw_toughness_break` |       |
||||
| 7  | Throwing Cell             | `Consume_Throw_Granade_Elec`    |       |
| 8  | Carcass Body Fluid Bottle | `Consume_Throw_Granade_Acid`    |       |
| 9  | Thermite                  | `Consume_Throw_Granade_Fire`    |       |
||||
| 10 | Fire Canister             | `Consume_Area_Fire`             |       |
| 11 | Acid Canister             | `Consume_Area_acid`             |       |
| 12 | Electric Blitz Canister   | `Consume_Area_Elec`             |       |

---

### 👜Shops(+Currency)
> ### Shop Upgrades
|Sl.| Item Name                     | Item ID                | Notes |
|---|-------------------------------|------------------------|-------|
| 1 | Krat Supply Box               | `Krat_BlackBox_2`      |       |
| 2 | Sturdy Krat Supply Box        | `Krat_BlackBox_3`      |       |
| 3 | Special Krat Supply Box       | `Krat_BlackBox_4`      |       |
||||
| 4 | Incredible Venigni Collection | `Venigni_BlackBox_2`   |       |
| 5 | Fancy Venigni Collection      | `Venigni_BlackBox_3`   |       |
| 6 | Great Venigni Collection      | `Venigni_BlackBox_4`   |       |
||||
| 7 | Klaus's Luxury Bag            | `DLC_Klaus_BlackBox_1` |       |
| 8 | Klaus's Premium Luxury Bag    | `DLC_Klaus_BlackBox_2` |       |

> ### Special Currency
|Sl.| Item Name       | Item ID                | Notes |
|---|-----------------|------------------------|-------|
| 1 | Gold Coin Fruit | `Exchange_GoldenFruit` |       |
| 2 | Ancient Disk    | `Exchange_SpecialCoin` |       |

---

### 💎Ergo
> ### Generic Hard Ergo
| Sl.| Ergo Crystal Name           | Item ID                       | Amount |
|----|-----------------------------|-------------------------------|--------|
| 1  | Dim Ergo Fragment           | `Consume_ProtectDropErgo_1`   | +100   |
| 2  | Vivid Ergo Fragment         | `Consume_ProtectDropErgo_2`   | +300   |
| 3  | Radiant Ergo Fragment       | `Consume_ProtectDropErgo_3`   | +500   |
| 4  | Resplendent Ergo Fragment   | `Consume_ProtectDropErgo_4`   | +700   |
||||
| 5  | Dim Ergo Chunk              | `Consume_ProtectDropErgo_1M`  | +1000  |
| 6  | Vivid Ergo Chunk            | `Consume_ProtectDropErgo_1MP` | +1500  |
| 7  | Radiant Ergo Chunk          | `Consume_ProtectDropErgo_2M`  | +2000  |
| 8  | Resplendent Ergo Chunk      | `Consume_ProtectDropErgo_3M`  | +3000  |
||||
| 9  | Dim Ergo Crystal            | `Consume_ProtectDropErgo_1L`  | +5000  |
| 10 | Vivid Ergo Crystal          | `Consume_ProtectDropErgo_2L`  | +7000  |
| 11 | Radiant Ergo Crystal        | `Consume_ProtectDropErgo_3L`  | +10000 |
| 12 | Resplendent Ergo Crystal    | `Consume_ProtectDropErgo_4L`  | +15000 |
| 13 | Ergo Crystal of the Eternal | `Consume_ProtectDropErgo_5L`  | +25000 |
| 14 | Angel's Ergo Crystal        | `Consume_ProtectDropErgo_6L`  | +35000 |
| 15 | Forgotten God's Ergo Crystal| `Consume_ProtectDropErgo_7L`  | +50000 |

> ### Boss Ergo
| Sl.| Ergo Crystal Name                    | Item ID              | Related Boss                                             |
|----|--------------------------------------|----------------------|----------------------------------------------------------|
| 1  | Parade Leader's Ergo                 | `CH01_Boss_Ergo`     | Parade Master                                            |
| 2  | Broken Hero's Ergo                   | `CH02_Boss_Ergo`     | Scrapped Watchman                                        |
| 3  | King's Flame Ergo                    | `CH03_Boss_Ergo`     | King's Flame, Fuoco                                      |
| 4  | Twisted Angel's Ergo                 | `CH04_Boss_Ergo`     | Fallen Archbishop Andreus                                |
| 5  | Burnt-White King's Ergo              | `CH06_Boss_Ergo`     | Romeo, King of Puppets                                   |
| 6  | Reborn Champion's Ergo               | `CH07_Boss_Ergo`     | Champion Victor                                          |
| 7  | Puppet-Devouring Green Hunter's Ergo | `CH08_Boss_Ergo`     | Puppet-Devouring Green Monster                           |
| 8  | Sad Zealot's Ergo                    | `CH12_Boss_Ergo`     | Laxasia the Complete                                     |
| 9  | Fallen One's Ergo                    | `CH13_Boss_Ergo`     | Simon Manus, Awakened God                                |
| 10 | Nameless Puppet's Ergo               | `CH00_Boss_Ergo`     | Nameless Puppet                                          |
| 11 | Macabre Puppeteer's Ergo             | `DLC_CH01_Boss_Ergo` | Markiona, Puppeteer of Death                             |
| 12 | Tortured Guardian's Ergo             | `DLC_CH03_Boss_Ergo` | Anguished Guardian of the Ruins                          |

> ### Hidden Ergo (Unobtainable without Commands)
| Sl.| Ergo Crystal Name                    | Item ID              | Related Boss                                             |
|----|--------------------------------------|----------------------|----------------------------------------------------------|
| 1  | Brother Avenger's Ergo               | `CH09_Boss_Ergo`     | Black Rabbit Brotherhood                                 |
| 2  | Sad Clown's Ergo                     | `CH11_Boss_Ergo`     | Corrupted Parade Master                                  |

---

### 🧩Encoded Messages
> ### Cryptic Vessels
|Sl.| Item Name                 | Item ID                                    | Notes |
|---|---------------------------|--------------------------------------------|-------|
| 1 | Crafted Cryptic Vessel    | `Collection_Dottedpaper_01`                |       |
| 2 | Jeweled Cryptic Vessel    | `Collection_Dottedpaper_02`                |       |
| 3 | Old Cryptic Vessel        | `Collection_Dottedpaper_03`                |       |
| 4 | Rusty Cryptic Vessel      | `Collection_Dottedpaper_04`                |       |
| 5 | Mechanical Cryptic Vessel | `Collection_Dottedpaper_05`                |       |
| 6 | Alidoro's Cryptic Vessel  | `Collection_Dottedpaper_06`                |       |

> ### Cipher Machines
|Sl.| Item Name                 | Item ID                                    | Notes |
|---|---------------------------|--------------------------------------------|-------|
| 1 | Bloody Cipher Machine     | `DLC_Collection_Letter_StrangeStory_01_01` |DLC    |
| 2 | Corroded Cipher Machine   | `DLC_Collection_Letter_StrangeStory_02_01` |DLC    |
| 3 | Frosted Cipher Machine    | `DLC_Collection_Letter_StrangeStory_03_01` |DLC    |

---

### 💿Records
> ### Base Game Records
| Sl.| Item Name                             | Item ID                       | Type  |
|----|---------------------------------------|-------------------------------|-------|
| 1  | Shadow Flower                         | `Collection_Record_1`         |       |
| 2  | Misty E'ra                            | `Collection_Record_2`         |       |
| 3  | Fascination                           | `Collection_Record_3`         |       |
| 4  | Feel                                  | `Collection_Record_4`         |       |
| 5  | Someday                               | `Collection_Record_5`         |       |
| 6  | Divine Service                        | `Collection_Record_6`         |       |
| 7  | Far East Princess                     | `Collection_Record_7`         |       |
| 8  | Memory of Beach                       | `Collection_Record_8`         |       |
| 9  | Quixotic                              | `Collection_Record_9`         |       |
| 10 | Why                                   | `Collection_Record_11`        |       |
| 11 | Proposal, Flower, Wolf Part 1         | `Collection_Record_10_Normal` |       |
||||
| 12 | Shadow Flower                         | `Collection_Record_1_Golden`  |GOLDEN |
| 13 | Quixotic                              | `Collection_Record_2_Golden`  |GOLDEN |
| 14 | Fascination                           | `Collection_Record_3_Golden`  |GOLDEN |
| 15 | Memory of Beach                       | `Collection_Record_8_Golden`  |GOLDEN |
| 16 | Proposal, Flower, Wolf Part 1         | `Collection_Record_10`        |GOLDEN |

> ### DLC Records
|Sl.| Item Name                  | Item ID                   | Type  |
|---|----------------------------|---------------------------|-------|
| 1 | Lisrim                     | `DLC_Collection_Record_1` |       |
| 2 | SURVIVOR                   | `DLC_Collection_Record_2` |       |
| 3 | Nightmare                  | `DLC_Collection_Record_3` |       |
| 4 | The Clear Blue Sky         | `DLC_Collection_Record_4` |       |
||||
| 5 | The Clear Blue Sky         | `DLC_Collection_Record_5` |GOLDEN |
| 6 | Lisrim                     | `DLC_Collection_Record_6` |GOLDEN |
| 7 | SURVIVOR                   | `DLC_Collection_Record_7` |RED    |
| 8 | Nightmare                  | `DLC_Collection_Record_8` |GOLDEN |

---

### 💬Gestures
| Sl.| Gesture            | Item ID                      | Note  |
|----|--------------------|------------------------------|-------|
| 1  | Play Dead          | `DLC_Gesture_FeignDeath`     | DLC   |
| 2  | Shiver             | `DLC_Gesture_Shivering`      | DLC   |
| 3  | Peer into Distance | `DLC_Gesture_LookAhead`      | DLC   |
| 4  | Cheer              | `DLC_Gesture_Cheer`          | DLC   |
| 5  | Heart              | `DLC_Gesture_Heart`          | DLC   |
| 6  | Doubt              | `DLC_Gesture_Doubt`          | DLC   |
| 7  | Tap Dance          | `DLC_Gesture_Dance`          | DLC   |
| 8  | Deep Bow           | `DLC_Gesture_DeepBow`        | DLC   |
||||
| 9  | Stalker's Promise  | `Gesture_SwordSalute`        |       |
| 10 | Pray               | `Gesture_Pray`               |       |
| 11 | Remembrance        | `Gesture_Test_Apology`       |       |
| 12 | Beg                | `Gesture_Test_Beg1`          |       |
| 13 | Entreat            | `Gesture_Test_Beg2`          |       |
| 14 | Show Off Clothes   | `Gesture_Show_Cloth`         |       |
| 15 | Fear               | `Gesture_Fear`               |       |
| 16 | Swagger            | `Gesture_Boast`              |       |
| 17 | Clap               | `Gesture_Clap`               |       |
| 18 | Sad                | `Gesture_Sad`                |       |
| 19 | Respect            | `Gesture_Praise`             |       |
| 20 | Greet              | `Gesture_Hi`                 |       |
| 21 | Sit                | `Gesture_Sitdown`            |       |
| 22 | Taunt              | `Gesture_Provoke`            |       |
| 23 | Anger              | `Gesture_Anger`              |       |
| 24 | Check Ground       | `Gesture_Interaction_Bottom` |       |
| 25 | Happy              | `Gesture_Joy`                |       |

---

### 🧥Costumes
> ### Body
| Sl.| Item Name                          | Item ID                          | Type  |
|----|------------------------------------|----------------------------------|-------|
| 1  | Treasure Hunter's Hunting Apparel  | `Costume_Alidoro`                | BONUS |
| 2  | Armor of the Honorable             | `Costume_GuanYu`                 | BONUS |
||||
| 3  | Winter's Hunting Apparel           | `DLC_Costume_WarmSuit`           | DLC   |
| 4  | Reddened Tailcoat                  | `DLC_Costume_Romeo`              | DLC   |
| 5  | Blue Sheep's Battle Apparel        | `DLC_Costume_Stalker_Goat`       | DLC   |
| 6  | Golden Snail's Tailcoat            | `DLC_Costume_Stalker_Snail`      | DLC   |
| 7  | Famed Detective's Coat             | `DLC_Costume_Detective`          | DLC   |
| 8  | Black Death's Protective Apparel   | `DLC_Costume_Rabbit1`            | DLC   |
| 9  | Blazing Death's Hunting Apparel    | `DLC_Costume_Rabbit2`            | DLC   |
| 10 | Piercing Death's Hunting Apparel   | `DLC_Costume_Rabbit3`            | DLC   |
| 11 | Permeating Death's Hunting Apparel | `DLC_Costume_Rabbit4`            | DLC   |
| 12 | Leader's Battle Apparel            | `DLC_Costume_Lea`                | DLC   |
||||
| 13 | White Shirt                        | `Costume_01`                     |       |
| 14 | Blue Blood's Tailcoat              | `Costume_02`                     |       |
| 15 | Workshop Master's Workwear         | `Costume_03`                     |       |
| 16 | Workshop Master's Workwear         | `Costume_Factory_Meister`        |       |
| 17 | Mischievous Puppet's Clothes       | `Costume_Naughty_Boy`            |       |
| 18 | Someone's Memory                   | `Costume_Someone_Memory`         |       |
| 19 | Puppet Prince's Formal Dress       | `Costume_Prince_Robes`           |       |
| 20 | Alchemist's Cape                   | `Costume_Alchemist_Cape`         |       |
| 21 | The Great Venigni's Signature Coat | `Costume_Venigni_Coat`           |       |
| 22 | Monster Sweeper's Hunting Apparel  | `Costume_Stalker_Monster_Hunter` |       |
| 23 | Mad Donkey's Hunting Apparel       | `Costume_Stalker_Madman`         |       |
| 24 | Survivor's Hunting Apparel         | `Costume_Stalker_Survivor`       |       |
| 25 | Black Cat's Hunting Apparel        | `Costume_Stalker_Cat`            |       |
| 26 | The Atoned's Hunting Apparel       | `Costume_Stalker_Pilgrim`        |       |
| 27 | Robber Weasel's Hunting Apparel    | `Costume_Stalker_Weasel`         |       |
| 28 | Red Fox's Hunting Apparel          | `Costume_Stalker_Fox`            |       |
| 29 | Owl Doctor's Hunting Apparel       | `Costume_Stalker_Army_Surgeon`   |       |
| 30 | The White Lady's Hunting Apparel   | `Costume_Stalker_WhiteLady`      |       |

> ### Masks and Hats
| Sl.| Item Name                                     | Item ID                        | Type  |
|----|-----------------------------------------------|--------------------------------|-------|
| 1  | Treasure Hunter's Mask                        | `HatCostume_Alidoro`           | BONUS |
| 2  | Bandana of the Honorable                      | `HatCostume_GuanYu`            | BONUS |
| 3  | Alchemist's Hat                               | `HatCostume_AlchemistHat`      | BONUS |
| 4  | Winter Festival Peaked Hat                    | `HatCostume_RedHat`            | BONUS |
| 5  | Earnest Reindeer's Antlers                    | `HatCostume_ReindeerHorn`      | BONUS |
||||
| 6  | Winter's Hunting Hat                          | `DLC_HatCostume_WarmSuit`      | DLC   |
| 7  | Blue Sheep's Mask                             | `DLC_HatCostume_Stalker_Goat`  | DLC   |
| 8  | Golden Snail's Mask                           | `DLC_HatCostume_Stalker_Snail` | DLC   |
| 9  | Puppet Prince's Imperial Crown                | `DLC_HatCostume_Prince_Crown`  | DLC   |
| 10 | Famed Detective's Hat                         | `DLC_HatCostume_Detective`     | DLC   |
| 11 | The Eldest's Gas Mask                         | `DLC_HatCostume_Rabbit1`       | DLC   |
| 12 | The Battle Maniac's Mask                      | `DLC_HatCostume_Rabbit2`       | DLC   |
| 13 | The Eccentric's Mask                          | `DLC_HatCostume_Rabbit3`       | DLC   |
| 14 | The Youngest's Mask                           | `DLC_HatCostume_Rabbit4`       | DLC   |
| 15 | Leader's Mask                                 | `DLC_HatCostume_Lea`           | DLC   |
||||
| 16 | Mask Worn by those Preparing for the Festival | `Mask_Festival_Eve`            |       |
| 17 | Mad Donkey's Mask                             | `Mask_Stalker_Madman`          |       |
| 18 | Survivor's Mask                               | `Mask_Stalker_Survivor`        |       |
| 19 | Black Cat's Mask                              | `Mask_Stalker_Cat`             |       |
| 20 | The Atoned's Mask                             | `Mask_Stalker_Pilgrim`         |       |
| 21 | Robber Weasel's Mask                          | `Mask_Stalker_Weasel`          |       |
| 22 | Red Fox's Mask                                | `Mask_Stalker_Fox`             |       |
| 23 | Owl Doctor's Mask                             | `Mask_Stalker_ArmySurgeon`     |       |
| 24 | The White Lady's Mask                         | `Mask_Stalker_WhiteLady`       |       |

> ### Accessories
|Sl.| Item Name                       | Item ID                       | Type  |
|---|---------------------------------|-------------------------------|-------|
| 1 | Illusory Emerald Glasses        | `Head_Glassess_Emerald`       | BONUS |
| 2 | Midwinter Nights Red Nose       | `Head_Glassess_RudolfNose`    | BONUS |
| 3 | The Great Venigni's Glasses     | `Head_Glassess_Venigni2`      | BONUS |
||||
| 4 | Great Adventure Mask            | `DLC_Head_Glassess_Zoo`       | DLC   |
| 5 | Veteran's Eyepatch              | `DLC_Head_Glassess_Eyepatch`  | DLC   |
| 6 | Famous Detective's Mustache     | `DLC_Head_Glassess_Detective` | DLC   |
| 7 | Genius Meister's Monocle        | `DLC_Head_Glassess_Monocle`   | DLC   |
||||
| 8 | Mischievous Puppet's Parade Hat | `Head_Naughty_Boy`            |       |
| 9 | The Great Venigni's Glasses     | `Head_Glassess_Venigni`       |       |

---
### 📜Collectibles
```
I do not plan to curate and complete this section!
I have pasted the existing Base Game Item IDs in NarcolepticIBS' ID List, but I will not categorize it or add the DLC Items.
Please contribute if you want to complete this section of the list.
```
| Sl.| Item Name                                                    | Item ID                                                | Notes                     |
|----|--------------------------------------------------------------|--------------------------------------------------------|---------------------------|
| 1  | Black Rabbit Brotherhood Ledger                              | `Collection_Letter_22`                                 |                           |
| 2  | High-powered Flame Amplifier                                 | `Collection_Core_Fire`                                 |                           |
| 3  | Primer for Workshop Technicians                              | `Collection_CentralStation_07`                         |                           |
| 4  | Fairytale of the Three Brothers of the Workshop Tower        | `Collection_CentralStation_11`                         |                           |
| 5  | Factory Manager’s Report                                     | `Collection_Letter_17`                                 |                           |
| 6  | Overcharged Storage Battery                                  | `Collection_Core_Electronic`                           |                           |
| 7  | Crumpled Baptist’s Doodle                                    | `Collection_Letter_56`                                 |                           |
| 8  | Mechanical Cryptic Vessel                                    | `Collection_Dottedpaper_05`                            |                           |
| 9  | Mechanical Cryptic Vessel Decryption                         | `Collection_Databox_Interpretation_05`                 |                           |
| 10 | Guillaume’s Ballad                                           | `Collection_Letter_10`                                 |                           |
| 11 | Miracle Cure                                                 | `Collection_Letter_02`                                 |                           |
| 12 | Old Cryptic Vessel                                           | `Collection_Dottedpaper_03`                            |                           |
| 13 | Rusty Cryptic Vessel                                         | `Collection_Dottedpaper_04`                            |                           |
| 14 | Rusty Cryptic Vessel Decryption                              | `Collection_Databox_Interpretation_04`                 |                           |
| 15 | Someone’s Report Notes Notebook                              | `Collection_Letter_InterviewNote`                      |                           |
| 16 | A Letter that cannot arrive                                  | `Collection_CentralStation_03`                         |                           |
| 17 | Archbishop's Diary                                           | `Collection_Letter_15`                                 |                           |
| 18 | Descartes’s Note                                             | `Collection_Letter_11`                                 |                           |
| 19 | Have a taste of La Bleiwies, the greatest wine in the world! | `Collection_Letter_18`                                 |                           |
| 20 | The Witch's Tower and Princess Poster                        | `Collection_Letter_23`                                 |                           |
| 21 | Letter from Someone Who Has Gone Ahead                       | `Collection_Letter_SMMockery`                          |                           |
| 22 | Monad Charity House Guide                                    | `Collection_Letter_21`                                 |                           |
| 23 | Monad Charity House Concert                                  | `Collection_Letter_MonadCharity`                       |                           |
| 24 | Doctor’s Confessions                                         | `Collection_Letter_04`                                 |                           |
| 25 | Venigni’s Guide                                              | `Collection_Letter_08`                                 |                           |
| 26 | Venigni's Krat Landmark Guide I                              | `Collection_Letter_KratNotedGuide1`                    |                           |
| 27 | Venigni's Krat Landmark Guide II                             | `Collection_Letter_KratNotedGuide2`                    |                           |
| 28 | Venigni's Krat Landmark Guide IV                             | `Collection_Letter_34`                                 |                           |
| 29 | Jeweled Cryptic Vessel                                       | `Collection_Dottedpaper_02`                            |                           |
| 30 | Jeweled Cryptic Vessel Decryption                            | `Collection_Databox_Interpretation_02`                 |                           |
| 31 | Resurrection! Champion Victor has returned!                  | `Collection_Letter_MonsterCityLegend`                  |                           |
| 32 | Scribbles of Slum Resident                                   | `Collection_Letter_SlummerScrawl`                      |                           |
| 33 | Crafted Cryptic Vessel                                       | `Collection_Dottedpaper_01`                            |                           |
| 34 | Crafted Cryptic Vessel Decryption                            | `Collection_Databox_Interpretation_01`                 |                           |
| 35 | Have you seen this eccentric?!                               | `Collection_Letter_05`                                 |                           |
| 36 | Cecile’s Written Confession                                  | `Collection_Letter_20`                                 |                           |
| 37 | Wanted:Black Rabbit Brotherhood                              | `Collection_Letter_52`                                 |                           |
| 38 | Wanted:Alidoro                                               | `Collection_Letter_43`                                 |                           |
| 39 | King of Riddles’ Hint                                        | `Collection_Letter_RiddleKingHint`                     |                           |
| 40 | Scandal! V, the Tragedy Behind the Flamboyance               | `Collection_Letter_TragedyofV`                         |                           |
| 41 | Passenger’s Note                                             | `Collection_Letter_passenger_note`                     |                           |
| 42 | Simon Manus’s Confession                                     | `Collection_Letter_49`                                 |                           |
| 43 | Experiment Report of Order - Test Subject 890                | `Collection_Letter_Remedy_TestRecord`                  |                           |
| 44 | Alidoro’s Cryptic Vessel                                     | `Collection_Dottedpaper_06`                            |                           |
| 45 | Alidoro’s Cryptic Vessel Decryption                          | `Collection_Databox_Interpretation_06`                 |                           |
| 46 | Atkinson’s Letter                                            | `Collection_Letter_DearBell`                           |                           |
| 47 | Notes from an Experiment                                     | `Collection_Letter_26`                                 |                           |
| 48 | Stained Choir Sheet Music                                    | `Collection_Letter_Score`                              |                           |
| 49 | Frozen Man’s Letter                                          | `Collection_Letter_Frozenman`                          |                           |
| 50 | Woman’s Prayer                                               | `Collection_Letter_12`                                 |                           |
| 51 | Lover’s Letter                                               | `Collection_CentralStation_06`                         |                           |
| 52 | The Letter of the Eternal                                    | `Collection_Letter_55`                                 |                           |
| 53 | Artist’s Doodle                                              | `Collection_Letter_Artist_Scribble`                    |                           |
| 54 | Bundle of Old Letters                                        | `Collection_Letter_39`                                 |                           |
| 55 | Moonlight Town Guide                                         | `Collection_Letter_Cathedral_Vil_History`              |                           |
| 56 | The Great Venigni and Pistris the Submarine                  | `Collection_Letter_51`                                 |                           |
| 57 | [This month’s trend: Stalker masks]                          | `Collection_Letter_StalkerMask`                        |                           |
| 58 | Rose Estate Incident, left as a mystery                      | `Collection_Letter_25`                                 |                           |
| 59 | Geppetto’s Letter                                            | `Collection_Letter_53`                                 |                           |
| 60 | The greatest show on Earth is coming!                        | `Collection_Letter_KratGrandExposition_SpecialArticle` |                           |
| 61 | Torn Doodle                                                  | `Collection_Letter_doodle`                             |                           |
| 62 | Ripped Venigni's Krat Landmark Guide III                     | `Collection_Letter_CatFake`                            |                           |
| 63 | Sweepers Branch Office Newspaper Archives                    | `Collection_Letter_19`                                 |                           |
| 64 | Cherry-Scented Letter                                        | `Collection_Letter_40`                                 |                           |
| 65 | Sentry’s Notebook                                            | `Collection_Letter_33`                                 |                           |
| 66 | First Discovery, Camille                                     | `Collection_Letter_FirstDiscovery`                     |                           |
| 67 | Note Left at the Counter                                     | `Collection_Letter_50`                                 |                           |
| 68 | Order of Kroud Report                                        | `Collection_Letter_concierge_note`                     |                           |
| 69 | Krat News Issue 1124                                         | `Collection_Letter_KratTimes1124`                      |                           |
| 70 | Krat Times Issue 183                                         | `Collection_Letter_KratTimes183`                       |                           |
| 71 | Special Report! Foreigner’s Confession                       | `Collection_Letter_StrangerConfession`                 |                           |
| 72 | Introducing the Parade Puppet!                               | `Collection_Letter_Introduce_ParadeDoll`               |                           |
| 73 | The Blue Butterfly’s Letter                                  | `Collection_Letter_54`                                 |                           |
| 74 | Bloody Letter                                                | `Collection_CentralStation_05`                         |                           |
| 75 | So Said Pistris I                                            | `Collection_Letter_41`                                 |                           |
| 76 | So Said Pistris II                                           | `Collection_Letter_42`                                 |                           |
| 77 | So Said Pistris III                                          | `Collection_Letter_47`                                 |                           |
| 78 | Frayed Notebook                                              | `Collection_Letter_AlidoroNote`                        |                           |

---

### ✍️Creator Notes
This list is for anybody tinkering with the commands, be it simple cheaters like me or serious modders. Before the Overture DLC, [this list](https://fearlessrevolution.com/viewtopic.php?p=317058#p317058) by [NarcolepticIBS](https://fearlessrevolution.com/memberlist.php?mode=viewprofile&u=170917&sid=b8be7d1e0c54b7505bfc7fd4f9a6fb06) was the go-to resource — but it never got updated after the DLC dropped. It also lacks some stuff like Cryptic Vessels & Bonus Costumes.<br>
So when I started digging for Item IDs myself, I figured I can build a fresh, updated, centralized version. And host it on Github so others can contribute.<br>
Hope it’s as useful to others as it’s been for me. Happy spawning! 🎮

### 📈Future Plans
- I do not plan to complete the Collectibles Section
- If you have suggestions or spot any mistakes, please report it via the [issue tracker](https://github.com/PryorET/LiesOfP-ItemIDList/issues)! Contributions via Pull Requests will also be much appreciated! Kindly [EMail me](mailto:pryor.e.t.x100@gmail.com) if you have any questions!

---

### ☕ Support
This project has been another one of my ways to avoid coursework. If it saved you some time, feel free to fuel my ergo addiction:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/pryoret)

---
