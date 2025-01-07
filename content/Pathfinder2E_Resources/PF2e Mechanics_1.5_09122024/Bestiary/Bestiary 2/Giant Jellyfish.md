---
title: "Giant Jellyfish"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hHYRSegm83oOLYtP" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Giant Jellyfish"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Jellyfish"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
trait_03: [[mindless]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Stealth: +15"
abilityMods: [6, 4, 6, -5, 0, -5]
speed:  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +17, __Ref__ +15, __Will__ +1"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165; __Immunities__  precision,  mental; __Weaknesses__ piercing 5, slashing 5; __Resistances__ bludgeoning 10, poison 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+18 (agile, reach 20 feet)\n__Damage__  2d8 + 8 bludgeoning plus jellyfish-venom"

  - name: "Jellyfish Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d8 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "Squeeze"
    desc: "  A giant jellyfish can fit into tight spaces as if it were a Medium creature. It can move at its full Speed while [[Actions/Squeeze|Squeezing]]."
 
```

```encounter-table
name: Giant Jellyfish
creatures:
  - 1: Giant Jellyfish
```



Unlike its smaller cousins, the giant jellyfish is an active predator that chases down its prey through reefs or open water. It can even squeeze its enormous bell-shaped body into the tight confines of shipwrecks to drape its mane of tentacles across the exposed flesh of its prey.
