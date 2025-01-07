---
title: "Behir"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4PRDeo47CGAR4oTk" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/electricity
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Behir"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Behir"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[electricity]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +19, Intimidation: +18, Stealth: +18, Survival: +15"
abilityMods: [7, 4, 5, -2, 3, 4]
speed: 30 feet,  climb 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +16, __Will__ +15"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  electricity"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (reach 15 feet)\n__Damage__  2d12 + 10 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (agile)\n__Damage__  2d6 + 10 slashing"

  - name: "Breath Weapon"
    desc: "`pf2:2` (electricity,primal) The behir breathes lightning that deals 9d6 electricity damage in an 60-foot line (DC 27 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Claw Storm"
    desc: "`pf2:3`  The behir Strides up to its Speed, during which it can walk on air as if it were solid ground, ascending or descending at up to a 45-degree angle. It can make up to four claw Strikes at any point during this movement, each against a different target within reach, and it deals an extra 1d6 electricity damage with each Strike. These attacks count toward the behir's multiple attack penalty, but the multiple attack penalty doesn't increase until after the behir makes all of its attacks. If the behir moves half its Speed or less during a Claw Storm, that movement doesn't trigger reactions. The behir can't use Claw Storm if it has a creature wrapped in its coils. At the end of Claw Storm, it drifts downward up to 60 feet to the ground, landing softly and taking no damage from the fall. If it descends further than 60 feet, it takes damage normally from the remaining fall."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+7 bludgeoning damage, DC 27 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d12+7 bludgeoning damage, Rupture 21\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Wrap in Coils"
    desc: "`pf2:1`  **Requirements** The behir has a creature either [[Conditions/Restrained|Restrained]] or [[Conditions/Grabbed|Grabbed]] in its jaws\n* * *\n\n**Effect** The behir moves the creature into its coils, freeing its jaws. The creature remains grabbed and takes 1d6+6 slashing damage. The behir's coils can hold as many creatures as will fit in its space."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Behir
creatures:
  - 1: Behir
```



The behir is a massive, serpentine beast with never fewer than a dozen short legs, each ending in three hooked talons. A behir can live to 80 years, but most perish far younger to violence. Fully grown, a behir is 40 feet long and weighs 4,000 pounds.
