---
title: "Prospecti Statue"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bOEP2WqWzWLypYm0" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/earth
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Prospecti Statue"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Prospecti Statue"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[construct]]
trait_02: [[earth]]
trait_03: [[mindless]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17"
abilityMods: [6, -1, 6, -5, 0, -5]
speed: 30 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 26
armorclass:
  - name: AC
    desc: "26 (22 when broken); construct armor; __Fort__ +17, __Ref__ +10, __Will__ +9"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Hardness__ 10; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+1 Longsword (Huge)]]"
abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 10)"
    desc: "  Like normal objects, a giant animated statue has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once a giant animated statue is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 22."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stone Fist"
    desc: "+19 (magical)\n__Damage__  2d12 + 6 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+18 (magical, versatile p)\n__Damage__  1d8 + 10 slashing"

  - name: "Stone Robes"
    desc: "`pf2:1`  The Prospecti statue turns suddenly, causing its robes, which flow like fabric despite being as hard as stone, to swing about and damage opponents.\n\nCreatures adjacent to the animated statue take 2d6+6 bludgeoning damage (DC 25 Reflex check save; on a critical failure, the creature is also knocked [[Conditions/Prone|Prone]])."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Prospecti Statue
creatures:
  - 1: Prospecti Statue
```



As with any humanoid animated statues of Medium size, giant animated statues are used to guard locations of importance, but their increased size and power make them most useful in large vaults, spacious chambers, or outdoor locations. Animated objects of this strength and size are ideal for tasks and responsibilities usually performed by golems, and more powerful animated objects are thus all but unheard of.
