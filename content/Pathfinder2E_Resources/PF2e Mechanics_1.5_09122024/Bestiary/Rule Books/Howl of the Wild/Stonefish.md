---
title: "Stonefish"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W0JkYvSXcbroRz7x" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Stonefish"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Stonefish"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4, Stealth: +9"
abilityMods: [2, 3, 2, -5, 1, -1]
speed:  swim 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +6, __Will__ +3"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Camouflage"
    desc: "  The stonefish can [[Actions/Hide|Hide]] in its natural environment even if it doesn't have cover."

  - name: "Defensive Spines"
    desc: "  When a creature moves into a space with one or more stonefish, that creature takes 1d4 piercing damage and is exposed to stonefish venom."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+7 (finesse)\n__Damage__  1d6 + 2 piercing"

  - name: "**Melee** `pf2:1` Spines"
    desc: "+6 ()\n__Damage__  1d4 + 2 piercing plus stonefish-venom"

  - name: "Stonefish Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n\n**Maximum Duration** 3 hours\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] (10 minutes)\n\n**Stage 3** 3d6 poison and clumsy 2 (1 hour)"
 
```

```encounter-table
name: Stonefish
creatures:
  - 1: Stonefish
```



Stonefish use their superior camouflage to lie in wait and devour small prey, becoming indistinguishable from the reefs they call home. Larger creatures are also at risk, although mostly through accidental contact with the stonefish's spines and their agonizing venom.
