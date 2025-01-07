---
title: "Magma Scorpion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EdqgLOBbP3IdyZgU" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Magma Scorpion"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Magma Scorpion"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[fire]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [6, 3, 5, -4, 4, 0]
speed: 40 feet,  climb 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +14, __Will__ +16"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Immunities__  bleed,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 10"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  The magma scorpion ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+20 (agile, reach 10 feet)\n__Damage__  2d6 + 9 bludgeoning plus grab 1d6 fire plus grab"

  - name: "**Melee** `pf2:1` Tail Sting"
    desc: "+20 (reach 10 feet)\n__Damage__  1d10 + 9 piercing plus magma-scorpion-venom 1d6 fire plus magma-scorpion-venom"

  - name: "**Ranged** `pf2:1` Magma Spit"
    desc: "+17 (fire, range increment 40 feet)\n__Damage__  1d6 + 9 fire 1d6 fire"

  - name: "Magma Scorpion Venom"
    desc: " (fire,injury,poison) **Saving Throw** DC 26 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 fire damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 fire damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Magma Scorpion
creatures:
  - 1: Magma Scorpion
```



Whether skittering through Abyssal wastelands or basking in the searing sand of the deepest deserts, magma scorpions have charred carapaces constantly emitting vision-warping waves of heat.
