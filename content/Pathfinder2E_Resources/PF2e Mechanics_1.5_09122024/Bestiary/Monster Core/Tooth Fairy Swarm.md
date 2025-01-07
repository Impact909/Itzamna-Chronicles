---
title: "Tooth Fairy Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MS1uNqHMCbBhWZka" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Tooth Fairy Swarm"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tooth Fairy Swarm"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[fey]]
trait_02: [[swarm]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Stealth: +10, Thievery: +12"
abilityMods: [-2, 3, 0, -1, 2, 2]
speed: 10 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +5, __Ref__ +10, __Will__ +7"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, cold iron 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Plaque Burst"
    desc: "  When killed, a tooth fairy swarm bursts into sticky, foul-smelling white dust. Each creature in a 15-foot emanation must succeed at a DC 20 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."

attacks:
  - name: ""

  - name: "Pinch"
    desc: "`pf2:1`  Tooth fairies pinch their victims' fingers, noses, ears, or similar protruding body parts. Each enemy in the swarm's space takes 2d6 bludgeoning damage (DC 20 Reflex check save). Creatures that critically fail this save are [[Conditions/Sickened|Sickened 1]] from the pain."

  - name: "Pry"
    desc: "`pf2:3`  The tooth fairies try to pry out one of their target's teeth. One enemy in the swarm's space takes 4d6 bludgeoning damage with a DC 20 Reflex check save. On a failed save, the target takes 2 bleed damage and loses a tooth.\n\nIf the creature loses a tooth, it takes a –1 status penalty to Charisma-based skill checks and must succeed at a DC 5 Flat check to Cast a Spell unless that spell has the subtle trait. These effects last for 1 day, or until the stolen tooth is returned and the target regains at least 1 Hit Point."
 
```

```encounter-table
name: Tooth Fairy Swarm
creatures:
  - 1: Tooth Fairy Swarm
```



A mob of tooth fairies working together can conduct forced dentistry in seconds.

* * *

Tooth fairies spawn when a child's tooth (or, less commonly, an entire child) is buried in terrain rife with fey energies. Hatching from the buried teeth like larvae from an egg, tooth fairies build crude pliers from whatever they can find, then go hunting for more teeth—regardless of the owners' willingness.
