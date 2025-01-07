---
title: "Salamander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.T2lt22MjQ1VXsf0Q" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Salamander"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Salamander"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[elemental]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Pyric"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +17, Crafting: +15, Deception: +12, Intimidation: +14, Society: +13"
abilityMods: [4, 3, 4, 2, 2, 1]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +15, __Ref__ +16, __Will__ +13"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125; __Immunities__  bleed,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ranseur|+1 Ranseur]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ranseur"
    desc: "+18 (disarm, magical, reach 10 feet)\n__Damage__  2d10 + 7 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+17 (agile, reach 10 feet)\n__Damage__  1d8 + 7 bludgeoning plus grab 1d6 fire plus grab"

  - name: "Armor of Flames"
    desc: "`pf2:1`  The salamander stokes its internal flames. Until the start of its next turn, it gains a +2 circumstance bonus to AC, and when an adjacent creature touches it or hits it with a physical attack, that creature takes 2d6 persistent fire damage unless it succeeds at a DC 25 Reflex check save."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+4 bludgeoning plus 1d6 fire, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Salamander
creatures:
  - 1: Salamander
```



Salamanders have serpentine lower torsos, but humanoid upper bodies with toothy reptilian snouts. Their affinity for cruelty and violence puts them in close alliance with the demons of the Abyss.

* * *

Fire elementals are destructive manifestations of the scorching Plane of Fire.
