---
title: "Jackal Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Z6ByDfjzSBbZsVaz" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Jackal Guard"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Jackal Guard"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common, Mzunu"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +23, Religion: +18, Society: +17, Stealth: +18"
abilityMods: [5, 4, 3, 1, 2, -1]
speed: 30 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +18, __Will__ +18"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|+1 Striking Returning Spear]], [[Equipment/Sturdy Shield (Lesser)|Sturdy Shield (Lesser)]], [[Equipment/Chain Shirt|Chain Shirt]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol of Walkena]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+23 (magical)\n__Damage__  2d8 + 13 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+22 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 13 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+22 (magical, thrown 20 ft.)\n__Damage__  2d8 + 13 piercing"

  - name: "Impaling Strike"
    desc: "`pf2:2`  **Frequency** once per round\n* * *\n\n**Effect** The Jackal Guard lunges forward with their spear and delivers a piercing blow. The Jackal Guard Steps and then makes a melee spear Strike. On a hit, the target also takes 1d6 bleed."

  - name: "Knocking Sweep"
    desc: "`pf2:2`  **Frequency** once per round\n* * *\n\n**Effect** The Jackal Guard swings their weapon with a sweeping spin. They attempt separate Athletics checks to Trip any number of creatures within their reach. Each attempt counts toward the Jackal Guard's multiple attack penalty, but the multiple attack penalty doesn't increase until after they make all the attacks."

  - name: "Spear Vault"
    desc: "`pf2:2`  **Frequency** once per round\n* * *\n\n**Effect** The Jackal Guard uses their spear to jump over or around a creature and create an opening. The Jackal Guard Strides up to half their Speed. This movement doesn't trigger reactions. During this movement, they can move through the space of one creature, and when the Jackal Guard moves through a creature's space in this way, that creature becomes [[Conditions/Off-Guard|Off-Guard]] until the end of the Jackal Guard's turn. If the Jackal Guard ends their movement within melee reach of at least one enemy, they can make a melee Strike against that enemy."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Jackal Guard
creatures:
  - 1: Jackal Guard
```




