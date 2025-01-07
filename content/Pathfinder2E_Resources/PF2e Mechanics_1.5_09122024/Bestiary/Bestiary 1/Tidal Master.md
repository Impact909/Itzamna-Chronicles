---
title: "Tidal Master"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.79YJ6FZlVcgQedhv" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Tidal Master"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Tidal Master"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Stealth: +19"
abilityMods: [5, 5, 5, -1, 3, 0]
speed: 30 feet,  swim 80 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +21, __Will__ +15"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "Water-Bound"
    desc: "  When not touching water, the tidal master is [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Vortex"
    desc: " (aura,water) 40 feet. Water in the area that is in the same body of water as the tidal master is difficult terrain for Swimming creatures that don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+21 (reach 15 feet)\n__Damage__  2d12 + 11 bludgeoning plus push-or-pull-10-feet"

  - name: "Drench"
    desc: "`pf2:1` (primal,water) The elemental puts out all fires in a 10-foot emanation.\n\nIt extinguishes all non-magical fires automatically and attempts to counteract magical fires (+20 counteract modifier)."

  - name: "[[Bestiary Ability Glossary/Push|Push or Pull 10 feet]]"
    desc: "`pf2:1`  The tidal master can also pull the creature.\n* * *\n\n**Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Tidal Master
creatures:
  - 1: Tidal Master
```



Tidal masters use their power over waves and water to drown their enemies.

* * *

Water elementals can be very destructive, but often not intentionally so; just as water can bring life to those in need on the Material Plane, its waves can pound shores and rains can flood cities. Water elementals are similarly difficult to predict.
