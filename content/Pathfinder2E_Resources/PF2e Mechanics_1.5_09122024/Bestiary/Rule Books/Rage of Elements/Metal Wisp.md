---
title: "Metal Wisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9kNnMR5sfmp7xGrM" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Metal Wisp"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Metal Wisp"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Mining Lore: +4, Plane of Metal Lore: +4"
abilityMods: [2, 1, 3, 0, 2, 0]
speed:  fly 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +7, __Ref__ +3, __Will__ +6"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Immunities__  bleed,  electricity,  paralyzed,  poison,  sleep; __Resistances__ electricity 2"
abilities_top:
  - name: ""

  - name: "Rust Vision"
    desc: "  A metal wisp ignores the concealed condition from rust clouds."

abilities_mid:
  - name: ""
  - name: "Accord Essence"
    desc: "`pf2:r` (plant) **Trigger** An ally within 30 feet that benefited from the wisp's resonance in the last hour is targeted by an attack\n* * *\n\n**Effect** The wisp detonates itself in a small elemental explosion. Allies within 30 feet that have benefited from the wisp's resonance in the last hour gain temporary Hit Points equal to half the wisp's current Hit Points. These temporary Hit Points last 1 hour.\n\nA wisp that uses this reaction is permanently destroyed, and it can be restored only by a [[Spells/Wish|Wish]] ritual or similarly powerful effect. If an ability would prevent the wisp's destruction (for instance, if the wisp is summoned and would merely be dismissed), Accord Essence has no effect."

  - name: "Resonance"
    desc: " (aura,metal) 30 feet.\n\nAll wisps vibrate at a frequency attuned to their element, resonating with and empowering all creatures and effects sharing that trait. Creatures in the area gain a +1 status bonus to attack and damage rolls made with metal weapons or effects with the metal trait; a creature with the elemental and metal traits gains this bonus to all attack and damage rolls."

  - name: "Rust Cloud"
    desc: "  A metal wisp is constantly surrounded by a cloud of rust flakes that cause it to be [[Conditions/Concealed|Concealed]] from creatures more than 5 feet away from it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+6 (reach 10 feet)\n__Damage__  1 bleed 1d4 piercing"

  - name: "In Concert"
    desc: "  When a metal wisp rolls a critical failure on a check to Aid, they get a failure instead, and when they roll a success, they get a critical success instead."
 
```

```encounter-table
name: Metal Wisp
creatures:
  - 1: Metal Wisp
```



A metal wisp is a roiling sphere of rust particles and sharp metal fragments, all furiously orbiting a liquid metal core that resembles the skull of a mortal creature—usually a humanoid, but animal and even more fantastical skulls are not uncommon. They don't form attachments as easily as wisps from other elemental planes, which tend to view metal wisps as too morose, although they retain a certain curiosity since their return from the planar severance.
