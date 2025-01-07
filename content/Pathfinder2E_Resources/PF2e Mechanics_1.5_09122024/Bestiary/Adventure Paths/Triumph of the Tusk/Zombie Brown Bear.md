---
title: "Zombie Brown Bear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SZAbHPgZY3gbrx9u" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Zombie Brown Bear"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Zombie Brown Bear"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[undead]]
trait_03: [[zombie]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10"
abilityMods: [5, 1, 4, -5, 0, -1]
speed: 30 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +9, __Will__ +6"
hp: 92
health:
  - name: ""
  - name: HP
    desc: "92, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A zombie brown bear is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 ()\n__Damage__  2d8 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 ()\n__Damage__  1d10 + 5 slashing plus grab"

  - name: "Ripping Maul"
    desc: "`pf2:1`  **Requirements** The zombie brown bear has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The zombie chews and rips at the target, dealing 2d8+5 piercing damage with a DC 17 Reflex check save.\n\n_Note: A DC was not provided for this ability by Paizo. The DC present here is a moderate DC for the creature level according to the GM Core creature building Tables._"

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zombie Brown Bear
creatures:
  - 1: Zombie Brown Bear
```




