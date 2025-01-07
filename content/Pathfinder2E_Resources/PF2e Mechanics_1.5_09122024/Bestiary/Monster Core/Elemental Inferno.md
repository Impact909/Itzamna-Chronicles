---
title: "Elemental Inferno"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BKtyEkLYbA8X7gWl" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Elemental Inferno"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Elemental Inferno"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[fire]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Pyric"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21"
abilityMods: [6, 6, 5, 0, 3, 0]
speed: 70 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +23, __Will__ +19"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, explosion; __Immunities__  bleed,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 15, water 10"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  The elemental inferno ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "Explosion"
    desc: " (fire) When the elemental inferno dies, it explodes, dealing 7d6 fire damage to each creature in a 10-foot emanation (DC 30 Reflex check save)."

  - name: "Intense Heat"
    desc: " (aura,fire) 10 feet. 7d6 fire damage DC 28 Reflex check"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+24 (reach 15 feet)\n__Damage__  2d10 + 12 fire 3d8 fire"

  - name: "**Ranged** `pf2:1` Fire Mote"
    desc: "+24 (range increment 60 feet)\n__Damage__  2d10 + 6 fire"

  - name: "Blue Flames"
    desc: "  When the elemental inferno scores a critical hit, its body surges with blue flames, increasing the damage of its intense heat and Inferno Leap by 3d6 until the start of its next turn."

  - name: "Inferno Leap"
    desc: "`pf2:2` (fire) The elemental inferno jumps horizontally and vertically with a maximum height and distance each equal to its Speed. Its intense heat is suppressed until the end of the jump. Instead, at any point during the jump, flames explode from the elemental in a 30-foot emanation, dealing 12d6 fire damage to each creature within the area (DC 30 Reflex check save).\n\nThe elemental inferno can't Inferno [[Actions/Leap|Leap]] again for 1d4 rounds."
 
```

```encounter-table
name: Elemental Inferno
creatures:
  - 1: Elemental Inferno
```



Walking conflagrations of unimaginably hot fire, elemental infernos are harbingers of destruction and heedless chaos. More tactical than many elementals, the infernos will set entire cities ablaze to confuse enemies.

* * *

Fire elementals are destructive manifestations of the scorching Plane of Fire. Although most fire elementals revel in the chance to experience new kinds of fires away from their home plane, even the most considerate fire elemental can be a danger to humanoids and their property.
