---
title: "Ixirizmid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OMYgxDvpdrfe1TSs" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Ixirizmid"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Ixirizmid"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fungus]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision, Tremorsense (Precise) 30 Feet"
languages: "Aklo, Common, Migo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +18, Athletics: +15, Deception: +17, Medicine: +21, Occultism: +18, Religion: +17, Stealth: +16, Thievery: +16"
abilityMods: [3, 6, 4, 6, 5, 3]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +18, __Will__ +17"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  cold; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Precise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Clever Disguises"
    desc: "  Ixirizmid can use Deception to impersonate any Medium humanoid creature, although creating such a disguise takes 1 hour. They can't impersonate a specific individual with this ability."

  - name: "No Breath"
    desc: "  Ixirizmid doesn't breathe and is immune to effects that require breathing (such as an inhaled poison)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (agile, finesse)\n__Damage__  2d8 + 5 slashing plus grab"

  - name: "Rituals"
    desc: "_Extract Brain_"

  - name: "Eviscerate"
    desc: "`pf2:1` (manipulate) Ixirizmid performs a swift and painful surgery on a creature it has grabbed or restrained, or who's otherwise immobilized. They roll a Medicine check check against the target's Fortitude DC. Regardless of the result, the target then becomes temporarily immune to Eviscerate for 24 hours.\n* * *\n\n**Critical Success** The target takes 8d6 slashing damage, is [[Conditions/Slowed|Slowed 1]] for 1 round, and becomes [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Enfeebled|Enfeebled 1]], or [[Conditions/Stupefied|Stupefied 1]] (the mi-go chooses) for 24 hours.\n\n**Success** The target takes 5d6 slashing damage and is [[Conditions/Slowed|Slowed 1]] for 1 round by the pain.\n\n**Failure** The target takes 3d6 slashing damage.\n\n**Critical Failure** The target takes no damage."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  Ixirizmid deals an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ixirizmid
creatures:
  - 1: Ixirizmid
```




