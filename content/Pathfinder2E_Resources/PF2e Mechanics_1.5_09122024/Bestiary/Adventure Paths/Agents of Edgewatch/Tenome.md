---
title: "Tenome"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IYoTNiwTf33Q3zlZ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Tenome"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Tenome"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +11, Deception: +10, Intimidation: +10, Stealth: +12, Survival: +8"
abilityMods: [4, 5, 3, 0, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +15, __Will__ +12"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Obscuring Grab"
    desc: "  While the tenome is Grabbing a creature, all other creatures are [[Conditions/Concealed|Concealed]] to the tenome."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__ "

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile)\n__Damage__  2d6 + 4 slashing plus grab"

  - name: "Bone Drink"
    desc: "`pf2:2` (healing,occult) **Requirement** The tenome has a creature grabbed or restrained\n* * *\n\n**Effect** The tenome makes a jaws Strike against the grabbed or restrained creature. If the Strike hits, the creature must succeed at a DC 18 Fortitude check save or become [[Conditions/Drained|Drained 1]] (or the value of the creature's drained condition increases by 1 if it already has a drained value, to a maximum of drained 4).\n\nThe tenome regains 1d8 healing Hit Points each time it uses Bone Drink."

  - name: "Burst of Speed"
    desc: "`pf2:1`  The tenome Strides twice, Steps twice, or Steps and Strides (in either order).\n\nIt cannot use Burst of Speed again for 1d4 rounds."

  - name: "Terrifying Gaze"
    desc: "`pf2:1` (emotion,fear,incapacitation,mental,occult,visual) 1 or 2 actions\n\nA tenome can gaze at a creature within 30 feet by presenting one of its eyes. The target must succeed at a DC 21 Will check save or become [[Conditions/Frightened|Frightened 1]]. If the tenome uses 2 actions and presents both of its eyes, the target is also [[Conditions/Paralyzed|Paralyzed]] if it fails the save.\n\nA creature that successfully saves is temporarily immune for 24 hours."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tenome
creatures:
  - 1: Tenome
```




