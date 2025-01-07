---
title: "Castoroides"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.czss07MEvXWR8Hle" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Castoroides"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Castoroides"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Crafting: +7, Survival: +8"
abilityMods: [4, 1, 3, -4, 3, 1]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +6, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Deep Breath"
    desc: "  A castoroides can hold its breath for 1 hour."

  - name: "Slap"
    desc: "`pf2:r`  **Trigger** The castoroides is targeted by a physical ranged Strike from an attacker it can see\n* * *\n\n**Effect** The castoroides swats at the projectile with its wide tail, gaining a +2 circumstance bonus to its AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  2d6 + 4 piercing plus grab"

  - name: "Construct Shelter"
    desc: "`pf2:3`  The castoroides rapidly constructs a simple mound along one side of its space, which can be used to Take Cover."

  - name: "Gouge"
    desc: "`pf2:1`  The castoroides deals 2d8 piercing damage to a creature it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] (DC 20 Fortitude check). A creature that fails its save also takes 1d4 bleed."

  - name: "Penetrating Bite"
    desc: "`pf2:2`  As beaver, but the castoroides's jaws Strike ignores the first 10 Hardness instead of the first 5 Hardness."

  - name: "Prop"
    desc: "`pf2:1`  The castoroides stabilizes itself with its tail, gaining a +1 circumstance bonus to its Fortitude and Reflex DCs against Shove and Trip attempts until it next takes an action with the move trait."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Castoroides
creatures:
  - 1: Castoroides
```



Beavers are stocky, herbivorous rodents that live in freshwater ecosystems throughout Avistan. They live in lodges, which they construct from logs, grass, rocks, and mud.

Castoroides are bear-sized beavers that build their lodges on land near a water source rather than in the water.
