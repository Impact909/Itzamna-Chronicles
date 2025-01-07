---
title: "Duergar Slave Lord"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UgLW731bBijzHeyL" 
tags:
  - pf2e/creature/type/duergar
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Duergar Slave Lord"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Duergar Slave Lord"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[duergar]]
trait_02: [[dwarf]]
trait_03: [[evil]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +23, Intimidation: +22, Society: +21, Stealth: +27, Survival: +26"
abilityMods: [4, 8, 3, 2, 5, 3]
speed: 25 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +21, __Ref__ +28, __Will__ +23; +2 status to all saves vs. magic"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|+2 Striking Composite Longbow]], 2x [[Equipment/Hatchet|+1 Striking Hatchet]], [[Equipment/Studded Leather Armor|+1 Resilient Studded Leather Armor]], Key to the Temple of All Gods, 100x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Improved Evasion"
    desc: "  When a duergar slave lord rolls a success on a Reflex save, they get a critical success instead. When they roll a critical failure on a Reflex save, they get a failure instead. Finally, when they fail a Reflex save against a damaging effect, they take half damage."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+28 (agile, finesse, magical, versatile s)\n__Damage__  2d6 + 10 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+29 (deadly d10, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  2d8 + 8 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __2nd __  _[[Spells/Enlarge|Enlarge (Self Only)]]_, _[[Spells/Invisibility|Invisibility (Self Only)]]_"

  - name: "Hunt Prey"
    desc: "`pf2:1`  The slave lord designates as its prey a single creature that they can see or hear or that they are Tracking. They gain a +2 circumstance bonus to Perception checks when they [[Actions/Seek|Seek]] their prey and a +2 circumstance bonus to [[Actions/Track|Track]] their prey. They also ignore the penalty for making ranged attacks within their second range increment against their prey.\n\nThe first time a slave lord hits their hunted prey in a round, they deal 2d8 additional precision damage. A slave lord can have only one prey designated at a time."

  - name: "Hunter's Flurry"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The slave lord makes two bow Strikes or two melee Strikes, each using a different weapon. These Strikes must target the slave lord's prey. If both Strikes hit, combine their damage for the purpose of resistances and weaknesses."
 
```

```encounter-table
name: Duergar Slave Lord
creatures:
  - 1: Duergar Slave Lord
```




