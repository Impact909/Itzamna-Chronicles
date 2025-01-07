---
title: "Tooth Fairy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6MS4p4dlv1IKG4nA" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Tooth Fairy"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tooth Fairy"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[fey]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Stealth: +5, Thievery: +6"
abilityMods: [-2, 3, 0, -1, 2, 1]
speed: 10 feet,  fly 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +2, __Ref__ +7, __Will__ +4"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8; __Weaknesses__ cold iron 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Pliers"
abilities_mid:
  - name: ""
  - name: "Plaque Burst"
    desc: "  When killed, a tooth fairy bursts into sticky, foul-smelling white dust. Each creature in a 5-foot emanation must succeed at a DC 16 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pliers"
    desc: "+7 (disarm, finesse, reach 0 feet)\n__Damage__  1d6 bludgeoning plus tooth-tug"

  - name: "Primal Innate Spells"
    desc: "DC 13, attack +5; __1st __  _[[Spells/Sleep|Sleep]]_\n__Cantrips__  __(1st)__ _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "Tooth Tug"
    desc: "`pf2:1` (manipulate) **Requirements** The tooth fairy's last action was a successful pliers Strike against a creature with teeth\n* * *\n\n**Effect** The tooth fairy attempts a Thievery check check against the creature's Fortitude DC, dealing 2 bleed damage on any result but a critical failure. On a critical success, it also pulls out one of the target's teeth.\n\nIf the creature loses a tooth, it takes a –1 status penalty to Charisma-based skill checks and must succeed at a DC 5 Flat check to Cast a Spell unless that spell has the subtle trait. These effects last for 1 day, or until the stolen tooth is returned and the target regains at least 1 Hit Point."
 
```

```encounter-table
name: Tooth Fairy
creatures:
  - 1: Tooth Fairy
```



Lone fairies usually need several minutes of elbow grease and a sleeping or restrained subject to extract a tooth.

* * *

Tooth fairies spawn when a child's tooth (or, less commonly, an entire child) is buried in terrain rife with fey energies. Hatching from the buried teeth like larvae from an egg, tooth fairies build crude pliers from whatever they can find, then go hunting for more teeth—regardless of the owners' willingness.
