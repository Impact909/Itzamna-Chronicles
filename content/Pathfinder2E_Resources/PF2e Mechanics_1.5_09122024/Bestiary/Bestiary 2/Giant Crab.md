---
title: "Giant Crab"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KsTNywCKVv1QSlAr" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Giant Crab"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Crab"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Stealth: +7"
abilityMods: [4, 3, 1, -4, 2, -3]
speed: 25 feet,  swim 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +9, __Will__ +8"
hp: 24
health:
  - name: ""
  - name: HP
    desc: "24; __Resistances__ physical 3 (except bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Scuttle"
    desc: "`pf2:r`  **Trigger** A creature that the giant crab can see targets the crab with an attack\n* * *\n\n**Effect** The giant crab scuttles to the side and gains a +2 circumstance bonus to AC against the triggering attack. After the attack resolves, the crab can Stride up to its speed in a straight line as part of the reaction."

  - name: "Vulnerable to Prone"
    desc: "  If a creature critically succeeds on a check to [[Actions/Trip|Trip]] the giant crab, the crab is flipped over onto its back in addition to the usual effects. A giant crab that is flipped onto its back has a particularly hard time defending itself; instead of taking the normal -2 circumstance penalty to AC for being [[Conditions/Off-Guard|Off-Guard]], it takes a -4 circumstance penalty to AC."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 ()\n__Damage__  1d10 + 4 slashing plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6+4 bludgeoning damage, DC 18 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Crab
creatures:
  - 1: Giant Crab
```



Crabs are scavenging crustaceans known for their hard shells and iconic sideways gait. They use their claws to defend themselves, hunt, and fight other crabs for territory. When confronted with threats from outside their species, most crabs prefer to flee, but when retreat isn't possible, they clamp on to their foes as tightly as they can.

The statistics presented here represent giant crabs that live close to the water's surface. Crabs that live deeper underwater often exhibit more extreme adaptations to their environment. Crabs who live in the depths where little light reaches gain darkvision and cold resistance, and those adapted to the most hostile reaches of the deep sea can detect nearby creatures through subtle shifts in ocean currents.

These skittering creatures are prized for their delicious meat, but their size makes them dangerous targets for harvesting.
