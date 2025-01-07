---
title: "Polar Bear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GWm6mIdijPZJPePH" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Polar Bear"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Polar Bear"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +14, Stealth: +10, Survival: +10"
abilityMods: [5, 1, 5, -4, 1, -1]
speed: 35 feet,  swim 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +10, __Will__ +10"
hp: 73
health:
  - name: ""
  - name: HP
    desc: "73"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 ()\n__Damage__  2d8 + 7 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile)\n__Damage__  2d6 + 7 slashing plus grab"

  - name: "Mauler"
    desc: "  The polar bear gains a +3 circumstance bonus to damage rolls against creatures it has [[Conditions/Grabbed|Grabbed]]."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The polar bear's Strikes deal an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The bear's last action was a success with a Strike that lists Grab in its damage entry, or it has a creature grabbed using this action.\n* * *\n\n**Effect** The bear automatically Grabs the target until the end of the bear's next turn. The creature is [[Conditions/Grabbed|Grabbed]] by whichever body part the bear attacked with, and that body part can't be used to Strike creatures until the grab is ended. Using Grab extends the duration of the monster's Grab until the end of its next turn for all creatures grabbed by it. A grabbed creature can use the [[Actions/Escape|Escape]] action to get out of the grab, and the Grab ends for a grabbed creatures if the bear moves away from it."
 
```

```encounter-table
name: Polar Bear
creatures:
  - 1: Polar Bear
```



Polar bears are known for their pale fur, with black eyes, lips, and toe pads. They are aggressively predatory creatures, stalking prey for miles on land or across the icy waters of frozen oceans. They are also amazing ambush predators, leaping from the water to ambush seals resting on ice floes. If they are desperate, polar bears hunt not only other animals but also humanoids.
