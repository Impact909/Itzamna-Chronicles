---
title: "Elemental Hurricane"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JyjhnmgusvqJ1rIW" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Elemental Hurricane"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Elemental Hurricane"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +21, Stealth: +22"
abilityMods: [6, 7, 4, 0, 3, 0]
speed:  fly 100 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +19, __Ref__ +24, __Will__ +18"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Disperse"
    desc: "`pf2:r`  **Trigger** The elemental hurricane takes damage from a hostile action.\n* * *\n\n**Effect** The elemental hurricane disperses.\n\nUntil the end of the current turn, it can't be attacked or targeted, doesn't take up space, and any auras or emanations it has are suppressed. At the end of the turn, the elemental hurricane reforms in any space in which it can fit within 100 feet of where it dispersed and any auras or emanations it has are restored as long as their duration didn't run out while it was dispersed."

  - name: "High Winds"
    desc: " (air,aura) 40 feet.\n\nAir within the emanation is difficult terrain for Flying creatures that don't have the air trait."

  - name: "Swiftness"
    desc: "  The elemental's movement doesn't trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+24 (finesse, reach 20 feet)\n__Damage__  2d10 + 12 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Lightning Lash"
    desc: "+24 (range increment 75 feet)\n__Damage__  2d12 + 6 electricity"

  - name: "Gale Breath"
    desc: "`pf2:2` (air) The elemental exhales a 30-foot cone of air. Creatures in the cone must succeed at a DC 29 Fortitude check save or be knocked away from the elemental.\n\nA creature knocked into a solid object stops moving and takes 10d6 bludgeoning damage (roll the damage once for all creatures).\n\nThe elemental hurricane can't use Gale Breath again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is pushed 20 feet.\n\n**Failure** The creature is pushed 40 feet.\n\n**Critical Failure** The creature is pushed 40 feet and knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Elemental Hurricane
creatures:
  - 1: Elemental Hurricane
```



Elemental hurricanes embody the ferocity of violent windstorms.

* * *

Hailing from the Plane of Air, these beings appear in a variety of sizes and shapes. They're noted for being elusive, swift, and often difficult to detect due to being composed primarily of air.
