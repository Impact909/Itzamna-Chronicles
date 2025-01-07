---
title: "Cursed Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xZKxnMwF1eb8yfRV" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Cursed Guardian"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Cursed Guardian"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[chaotic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common, Fey; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Survival: +8"
abilityMods: [6, 3, 5, -3, 0, 3]
speed: 35 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +11, __Will__ +6"
hp: 58
health:
  - name: ""
  - name: HP
    desc: "58, Deadeye&#x27;s Shame; __Weaknesses__ Deadeye&#x27;s Shame 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Deadeye's Shame"
    desc: "  The cursed guardian has weakness 5 to all damage inflicted upon it by a worshipper of Erastil, and it takes a -2 circumstance penalty to all saving throws to resist effects caused by worshippers of Erastil. If it ever suffers a critical hit from or critically fails a save against an effect caused by a worshipper of Erastil, the cursed guardian is [[Conditions/Stunned|Stunned 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d6 + 8 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile)\n__Damage__  2d4 + 8 slashing plus grab"

  - name: "Mauler"
    desc: "  The cursed guardian gains a +2 circumstance bonus to damage rolls against creatures it Grabs."

  - name: "Rush"
    desc: "`pf2:2`  The cursed guardian Strides and makes a Strike at the end of that movement. During the Stride, it gains a +10-foot circumstance bonus to its Speed."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cursed Guardian
creatures:
  - 1: Cursed Guardian
```




