![LiesOFPLogo](https://www.liesofp.com/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F150395%2F1737984357-image-2-2.png&w=256&q=100)
## 🧭 Item ID Compendium
_Every relic has a name. Every name has a code. Welcome to the vault._

**This repository contains a categorized list of item IDs used in-game. Click on the titles below to skip to a category:**
> 🔑[Key Items](#key-items) ⚔️[Weapons](#weapons) 🦾[Legion Arms](#legion-arms) ♥️[Amulets](#amulets)🛡️[Defense Parts](#defense-parts) <br>
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
</details>

### 🦾Legion Arms
### ♥Amulets
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
- Contributions via Pull Requests will be much appreciated! Kindly [EMail me](mailto:pryor.e.t.x100@gmail.com) if you have any questions!

