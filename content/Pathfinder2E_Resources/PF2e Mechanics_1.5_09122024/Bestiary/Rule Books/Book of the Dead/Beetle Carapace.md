---
title: "Beetle Carapace"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.h8Ge7yxCQddk7b88" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Beetle Carapace"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Beetle Carapace"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[skeleton]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +15"
abilityMods: [5, 3, 4, -5, 2, -2]
speed: 20 feet,  fly 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +16, __Ref__ +13, __Will__ +10"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandible"
    desc: "+15 ()\n__Damage__  2d8 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+15 ()\n__Damage__  2d6 + 7 bludgeoning"

  - name: "Abdomen Cache"
    desc: "  The abdomen of a beetle carapace can be fitted with a simple hinge, allowing it to open and be used as storage. The abdomen can hold up to one Medium or smaller creature, a Large or smaller swarm, or a similar amount of cargo. The beetle or a creature stored in it can Interact to open the hatch. If the beetle carapace takes a critical hit by a bludgeoning weapon, roll a DC 10 Flat check. If the check fails, the cache is breached, and its contents spill out of the beetle. The hatch can also be Forced Open (DC 22 Athletics check)."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+2 piercing, DC 24 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Beetle Carapace
creatures:
  - 1: Beetle Carapace
```



Created from the exoskeleton of a giant stag beetle, this mindless husk can cut a foe in half using its powerful mandibles. The abdomen of this crawling undead is empty, and more than one necromancer has used this space to hide valuable cargo.

* * *

Among the ranks of the dead, none are so numerous, nor so varied, as the skeleton. While most are almost entirely made from bone, some maintain a few scraps of flesh to aid them in movement, such as wing membranes.
