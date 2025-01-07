---
title: "Living Waterfall"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.81fN8cltsU87ypAp" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Living Waterfall"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Living Waterfall"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +12"
abilityMods: [4, 3, 3, -2, 1, 0]
speed: 20 feet,  swim 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +12, __Will__ +10"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 5"
abilities_top:
  - name: ""

  - name: "Waterbound"
    desc: "  When not touching water, the living waterfall is [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Vortex"
    desc: " (aura,water) 30 feet.\n\nWater in the area that is in the same body of water as the living waterfall is difficult terrain for Swimming creatures that don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+15 (reach 10 feet)\n__Damage__  2d8 + 7 bludgeoning plus push-or-pull"

  - name: "Drench"
    desc: "`pf2:1` (primal,water) The elemental puts out all fires in a 5-foot emanation.\n\nIt extinguishes all non-magical fires automatically and attempts to counteract magical fires (+14 counteract modifier)."

  - name: "[[Bestiary Ability Glossary/Push|Push or Pull 5 feet]]"
    desc: "`pf2:1`  The living waterfall can choose whether to push or pull the creature on a succesful hit.\n* * *\n\n**Push** `pf2:1`\n\n**Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance.\n* * *\n\n**Pull** `pf2:1`\n\n**Requirements** The monster's last action was a success with a Strike that lists Pull in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Reposition|Reposition]] the creature, moving it closer to the monster. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Pull lists a distance, change the distance the creature is pulled on a success to that distance."
 
```

```encounter-table
name: Living Waterfall
creatures:
  - 1: Living Waterfall
```



Living waterfalls are humanoid-shaped columns of churning water. They see the water as their natural domain and even aquatic animals as interlopers. When summoned, they are surly, but will grudgingly guard all forms of aquatic sites.

* * *

Water elementals can be very destructive, but often not intentionally so; just as water can bring life to mortals in need, its waves can pound shores and rains can flood cities. Water elementals are similarly difficult to predict.
