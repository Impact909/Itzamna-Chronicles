---
title: "Cataclysm Beetle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DreEwz50mYPabEvp" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Cataclysm Beetle"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Cataclysm Beetle"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +36, Intimidation: +31, Survival: +30"
abilityMods: [10, 2, 9, -3, 6, 5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +35, __Ref__ +26, __Will__ +30"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340; __Immunities__  acid"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+35 (reach 10 feet)\n__Damage__  3d12 + 16 slashing plus grab"

  - name: "Bombardier's Spray"
    desc: "`pf2:2` (acid,primal) The cataclysm beetle sprays a 60-foot cone of acid from its abdomen that deals 12d10 acid damage (DC 40 Reflex check). It can't use Bombardier's Spray or Burning Pool for 1d4 rounds."

  - name: "Burning Pool"
    desc: "`pf2:2` (acid,primal) The cataclysm beetle spills acid directly from its abdomen, creating a wave of acid that deals 10d12 acid damage to all creatures in a 30-foot emanation (DC 40 Fortitude check). Creatures that fail this save are pushed back 10 feet from the cataclysm beetle (30 feet on a critical failure). It can't use Bombardier's Spray or Burning Pool for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cataclysm Beetle
creatures:
  - 1: Cataclysm Beetle
```




