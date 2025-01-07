---
title: "Tooth Fairy Leader"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OqFvuzH6D4pXu3Rs" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Tooth Fairy Leader"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Tooth Fairy Leader"
level: "Creature 2"

alignment: ""
size: "tiny"
trait_01: [[fey]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Stealth: +6, Thievery: +8"
abilityMods: [1, 5, 1, 0, 3, 2]
speed: 10 feet,  fly 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +11, __Will__ +5"
hp: 35
health:
  - name: ""
  - name: HP
    desc: "35"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Tuskblade, Pliers"
abilities_mid:
  - name: ""
  - name: "Plaque Burst"
    desc: "  When killed, a tooth fairy bursts into sticky, foul-smelling white dust. Each creature in a 5-foot emanation must succeed at a DC 19 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pliers"
    desc: "+11 (disarm, finesse, reach 0 feet)\n__Damage__  1d6 + 5 bludgeoning plus tooth-tug"

  - name: "**Melee** `pf2:1` Tuskblade"
    desc: "+10 (forceful, reach 0 feet, two-hand d10)\n__Damage__  1d6 + 5 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 18, attack +10; __1st __  _[[Spells/Sleep|Sleep]]_\n__Cantrips__  __(1st)__ _[[Spells/Daze|Daze]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "Tooth Tug"
    desc: "`pf2:1` (manipulate) **Requirements** The tooth fairy's last action was a successful pliers Strike against a creature with teeth\n* * *\n\n**Effect** The tooth fairy attempts a Thievery check check against the creature's Fortitude DC, dealing 2 bleed damage on any result but a critical failure. On a critical success, it also pulls out one of the target's teeth.\n\nIf the creature loses a tooth, it takes a –1 status penalty to Charisma-based skill checks and must succeed at a DC 5 Flat check to Cast a Spell unless that spell has the subtle trait. These effects last for 1 day, or until the stolen tooth is returned and the target regains at least 1 Hit Point."
 
```

```encounter-table
name: Tooth Fairy Leader
creatures:
  - 1: Tooth Fairy Leader
```


Variant tooth fairy

Lone fairies usually need several minutes of elbow grease and a sleeping or restrained subject to extract a tooth.

* * *

Tooth fairies spawn when a child's tooth (or, less commonly, an entire child) is buried in terrain rife with fey energies. Hatching from the buried teeth like larvae from an egg, tooth fairies build crude pliers from whatever they can find, then go hunting for more teeth—regardless of the owners' willingness.
