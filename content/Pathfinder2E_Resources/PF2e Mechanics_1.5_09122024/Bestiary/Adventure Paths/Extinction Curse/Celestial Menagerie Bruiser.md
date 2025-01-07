---
title: "Celestial Menagerie Bruiser"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.c29aG0o1PQArWunN" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Celestial Menagerie Bruiser"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #152: Legacy of the Lost God"
name: "Celestial Menagerie Bruiser"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Intimidation: +16, Stealth: +13, Survival: +12, Thievery: +13, Circus Lore: +12"
abilityMods: [5, 1, 2, 0, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder #152: Legacy of the Lost God_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +15, __Will__ +13"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Greatclub|+1 Striking Greatclub]], [[Equipment/Chain Shirt|Chain Shirt]], Face Mask"
abilities_mid:
  - name: ""
  - name: "Opportunistic Brawler"
    desc: "`pf2:r`  **Trigger** A creature hits the bruiser with a melee Strike\n* * *\n\n**Effect** The bruiser attempts to [[Actions/Shove|Shove]] the creature. On a success or a critical success, the target is also knocked [[Conditions/Prone|Prone]]. The bruiser can't Stride after a target it successfully Shoves in this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+20 (backswing, magical, shove)\n__Damage__  2d10 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+19 (agile, nonlethal)\n__Damage__  1d4 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+15 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 8 piercing"

  - name: "Terrifying Sneer"
    desc: "`pf2:1`  **Frequency** once per turn\n\n**Requirements** The bruiser must target a creature they [[Actions/Shove|Shoved]] since the end of the bruiser's last turn\n* * *\n\n**Effect** The bruiser attempts to [[Actions/Demoralize|Demoralize]] the target. If the bruiser rolls a success, they get a critical success instead."
 
```

```encounter-table
name: Celestial Menagerie Bruiser
creatures:
  - 1: Celestial Menagerie Bruiser
```




