---
title: "Elemental Tsunami"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.g80XHm4LjHkwnKTm" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Elemental Tsunami"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Elemental Tsunami"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Stealth: +23"
abilityMods: [6, 6, 6, 0, 3, 0]
speed: 35 feet,  swim 100 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +22, __Will__ +19"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "Waterbound"
    desc: "  When not touching water, the elemental tsunami is [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Vortex"
    desc: " (aura,water) 50 feet.\n\nWater in the area that is in the same body of water as the elemental tsunami is difficult terrain for Swimming creatures that don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+24 (reach 20 feet)\n__Damage__  2d12 + 12 bludgeoning plus push-or-pull-10-feet"

  - name: "Drench"
    desc: "`pf2:1` (primal,water) The elemental puts out all fires in a 20-foot emanation.\n\nIt extinguishes all non-magical fires automatically and attempts to counteract magical fires (+20 counteract modifier)."

  - name: "Surge"
    desc: "`pf2:2`  The elemental tsunami momentarily expands to fill the area of its vortex. Creatures within the aura take 5d12+6 bludgeoning damage with a DC 31 Fortitude check save. A creature that fails this save is pushed 20 feet.\n\nThe elemental tsunami then shrinks to its normal space and can't Surge again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Push|Push or Pull 10 feet]]"
    desc: "`pf2:1`  The elemental tsunami can choose whether to push or pull the creature on a succesful hit.\n* * *\n\n**Push** `pf2:1`\n\n**Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance.\n* * *\n\n**Pull** `pf2:1`\n\n**Requirements** The monster's last action was a success with a Strike that lists Pull in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Reposition|Reposition]] the creature, moving it closer to the monster. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Pull lists a distance, change the distance the creature is pulled on a success to that distance."
 
```

```encounter-table
name: Elemental Tsunami
creatures:
  - 1: Elemental Tsunami
```



Elemental tsunamis are huge and destructive, having none of the caring or nurturing aspects of water.

* * *

Water elementals can be very destructive, but often not intentionally so; just as water can bring life to mortals in need, its waves can pound shores and rains can flood cities. Water elementals are similarly difficult to predict.
