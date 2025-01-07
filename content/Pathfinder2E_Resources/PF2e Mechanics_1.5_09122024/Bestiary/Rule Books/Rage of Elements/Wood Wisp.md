---
title: "Wood Wisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RqC1lFqeRbbnp5LX" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Wood Wisp"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Wood Wisp"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Muan"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Stealth: +6, Plane of Wood Lore: +4"
abilityMods: [3, 1, 2, 0, 3, 0]
speed:  climb 40 feet,  fly 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +2, __Will__ +8"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ axe vulnerability 2, fire 2"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Accord Essence"
    desc: "`pf2:r` (plant) **Trigger** An ally within 30 feet that benefited from the wisp's resonance in the last hour is targeted by an attack\n* * *\n\n**Effect** The wisp detonates itself in a small elemental explosion of leaves and pollen. This gives temporary Hit Points equal to half the wisp's current HP to all allies within 30 feet that have benefited from the wisp's resonance aura in the past hour. These temporary Hit Points last 1 hour.\n\nA wisp that uses this reaction is permanently destroyed and can be restored only by a [[Spells/Wish|Wish]] ritual or similarly powerful effect. If an ability would prevent the wisp's destruction (for instance, if the wisp is summoned and would merely be dismissed), Accord Essence has no effect."

  - name: "Resonance"
    desc: " (aura,plant,wood) 30 feet.\n\nAll wisps vibrate at a frequency attuned to their element, resonating with and empowering all creatures and effects sharing that trait. A creature in the area gains a +1 status bonus to attack and damage rolls for effects with the plant or wood trait; a creature with the elemental trait and either plant trait or wood trait gains this bonus to all attack and damage rolls. For wood wisps, this bonus also applies to nonmagical wooden weapons, such as staves and clubs."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Thorny Vine"
    desc: "+5 (reach 10 feet)\n__Damage__  1 piercing 1d4 bludgeoning"

  - name: "In Concert"
    desc: "  When a wood wisp rolls a critical failure on a check to Aid, they get a failure instead, and when they roll a success, they get a critical success instead."
 
```

```encounter-table
name: Wood Wisp
creatures:
  - 1: Wood Wisp
```



Like other wisps, wood wisps roam their plane and attune to other wisps, wandering with them in symphonies. Because of their willingness to bond, wood wisps appear outside their home plane more than other wood elementals, though they're still relatively rare compared to other wisps.

Wood wisps resemble coconuts trailed by thick nests of branches that cover and conceal even deeper webs of thorny vines. They are, unfortunately, both unaware of the pain these thorns can cause fleshy creatures and very physically affectionate in their eagerness to offer assistance.
