---
title: "Drow Shootist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YScZPdk92rktLIxy" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/drow
  - pf2e/creature/type/elf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Drow Shootist"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Drow Shootist"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[drow]]
trait_03: [[elf]]
trait_04: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Elven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +16, Deception: +16, Intimidation: +14, Stealth: +17, Thievery: +17"
abilityMods: [2, 5, 1, 0, 4, 2]
speed: 30 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +15, __Ref__ +17, __Will__ +16; +1 status to all saves vs. magic, +2 status to all saves vs. mental"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  sleep"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Repeating Hand Crossbow|+1 Repeating Hand Crossbow]], [[Equipment/Rapier|Rapier]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Shootist Bandolier|Shootist Bandolier]], 4x [[Equipment/Stupor Poison|Stupor Poison]], 4x [[Equipment/Repeating Hand Crossbow Magazine|Repeating Hand Crossbow Magazine]]"
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

abilities_mid:
  - name: ""
  - name: "Shootist's Luck"
    desc: "`pf2:r` (fortune) **Trigger** The shootist fails a save\n\n**Frequency** once per day\n* * *\n\n**Effect** The shootist rerolls the save and uses the better result."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+18 (deadly d8, disarm, finesse)\n__Damage__  1d6 + 9 piercing"

  - name: "**Ranged** `pf2:1` Repeating Hand Crossbow"
    desc: "+20 (range increment 60 feet, reload 0, repeating)\n__Damage__  1d6 + 9 piercing plus stupor-poison"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +16; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Faerie Fire|Faerie Fire (At Will)]]_\n__Cantrips__  __(4th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "Distracting Shot"
    desc: "`pf2:2`  The shootist takes aim and makes a ranged Strike. If the attack hits and deals damage, the target is [[Conditions/Off-Guard|Off-Guard]] until the end of the shootist's turn, or until the end of the shootist's next turn on a critical hit."

  - name: "Reloading Trick"
    desc: "`pf2:2`  **Requirements** The shootist is holding an unloaded repeating hand crossbow\n* * *\n\n**Effect** The shootist Interacts to reload the repeating hand crossbow and Strikes with it."

  - name: "Shootist's Draw"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The shootist Interacts to draw a repeating hand crossbow and Strikes with it, or Strikes with a loaded repeating hand crossbow they're holding then Interacts to stow it."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The shootist deals an extra 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Drow Shootist
creatures:
  - 1: Drow Shootist
```



The rare few drow who specialize in the repeating hand crossbow command respect not only for their skills but for their luck and swagger.

* * *

Drow have a reputation for evil due to demon worship in their major settlements. However, like members of any ancestry, drow can have any alignment, especially when removed from the demon lords' sinister influence.
