---
title: "Spriggan Bully"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NvAkhMGPlJrA72Ij" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/spriggan
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Spriggan Bully"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Spriggan Bully"
level: "Creature 3"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[gnome]]
trait_04: [[humanoid]]
trait_05: [[spriggan]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +8, Intimidation: +10, Society: +8, Stealth: +11, Survival: +10, Thievery: +9"
abilityMods: [3, 4, 2, 1, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +9, __Ref__ +11, __Will__ +8"
hp: 48
health:
  - name: ""
  - name: HP
    desc: "48"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Morningstar|Morningstar]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Enraged Growth"
    desc: "`pf2:r` (polymorph,primal) **Trigger** The spriggan bully takes damage\n* * *\n\n**Effect** The spriggan bully grows to Large size, along with their equipment (which returns to natural size if removed). The spriggan bully's reach increases by 5 feet. They regain 5 healing Hit Points and gain a +2 status bonus to melee attacks and damage rolls. This effect continues until the end of the spriggan bully's next turn, but on any turn in which the spriggan bully deals damage to another creature and is not [[Conditions/Fatigued|Fatigued]], the effect extends until the end of the following turn.\n\nWhen Enraged Growth ends, the spriggan bully is fatigued for 1 hour."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Morningstar"
    desc: "+10 (versatile p)\n__Damage__  1d6 + 6 bludgeoning"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+11 (range increment 120 feet, reload 1)\n__Damage__  1d8 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 20, attack +10; __2nd __  _[[Spells/Shatter|Shatter]]_; __1st __  _[[Spells/Fear|Fear]]_\n__Cantrips__  __(2nd)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "Bully's Bludgeon"
    desc: "`pf2:1` (nonlethal) The spriggan bully makes a morningstar Strike with a +2 circumstance bonus to its attack roll. This attack is nonlethal."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The spriggan bully's Strikes deal an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Spriggan Bully
creatures:
  - 1: Spriggan Bully
```



The typical spriggan is a bully who prefers to take live prisoners in fights, but only to ensure that they have a large stock of living victims to torment, tease, and abuse. They train to use weapons in nonlethal ways that inflict the maximum amount of pain even as they guard against accidental death. When not bullying prisoners or hunting for new victims, spriggan bullies enjoy drinking, watching others fight, and fighting among themselves.
