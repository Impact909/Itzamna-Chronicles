---
title: "Goblin Shark"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RLF99E50FxwRWCPT" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Goblin Shark"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Goblin Shark"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Scent (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +15, Survival: +10"
abilityMods: [6, 4, 5, -4, 3, -3]
speed:  swim 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +16, __Ref__ +11, __Will__ +10"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85"
abilities_top:
  - name: ""

  - name: "Blood Scent"
    desc: "  The shark can smell blood in the water from up to 1 mile away."

  - name: "Camouflage"
    desc: "  The goblin shark's coloration blends in with the water. It doesn't need cover to attempt to [[Actions/Hide|Hide]] with a Stealth check while underwater."

  - name: "Electrolocation"
    desc: "  A goblin shark can sense minute electrical charges in living creatures, which it can use as a precise sense at a range of 20 feet."

abilities_mid:
  - name: ""
  - name: "Grasping Jaws"
    desc: "  Creatures that successfully [[Actions/Escape|Escape]] from the goblin shark's jaws take 1d6 bleed as the shark's hold tears flesh away."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d8 + 6 piercing plus grab"

  - name: "Lunging Bite"
    desc: "`pf2:2`  The goblin shark dashes forward and extends its jaws bite a creature. It swims up to 10 feet in a straight line and makes a jaws Strike with a reach of 10 feet."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Goblin Shark
creatures:
  - 1: Goblin Shark
```




