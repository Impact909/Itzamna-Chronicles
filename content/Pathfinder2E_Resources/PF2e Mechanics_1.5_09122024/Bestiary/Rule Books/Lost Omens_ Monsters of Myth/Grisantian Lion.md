---
title: "Grisantian Lion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BJD2ZDYwav6ufIE1" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/primal
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Grisantian Lion"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Grisantian Lion"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[primal]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +25, Intimidation: +25, Stealth: +22, Survival: +22"
abilityMods: [7, 5, 7, -3, 4, -2]
speed: 35 feet,  climb 20 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +25, __Ref__ +22, __Will__ +19"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  disease; __Resistances__ fire 10, physical 10 (except bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 ()\n__Damage__  3d10 + 14 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile)\n__Damage__  3d8 + 12 slashing"

  - name: "Dual Pounce"
    desc: "`pf2:2`  The grisantian lion Strides and makes two claw Strikes against the same creature at the end of that movement. Each attack counts against the grisantian lion's multiple attack penalty, but the penalty doesn't increase until after the grisantian lion makes both attacks. If both attacks hit, combine their damage for the purpose of resistances and weaknesses."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  claw.\n\nIf the grisantian lion Rends after a successful Dual Pounce, combine the Rend's damage with that from the Dual Pounce for the purpose of resistances and weaknesses.\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Vicious Rend"
    desc: "`pf2:r`  **Trigger** The grisantian lion uses Rend\n* * *\n\n**Effect** The target's armor takes damage equal to the damage from Rend. The target can attempt a DC 29 Reflex check save to reduce this damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Grisantian Lion
creatures:
  - 1: Grisantian Lion
```




