---
title: "Woodweave Caterpillar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2WRjdGlxccxtdFB2" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Woodweave Caterpillar"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Woodweave Caterpillar"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[wood]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +25, Survival: +20"
abilityMods: [7, 4, 6, -5, 4, -4]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +20, __Will__ +22"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Weaknesses__ axe vulnerability 10, fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Special)]]"
    desc: "`pf2:r`  Bristles only. The woodweave caterpillar gains an extra reaction at the start of each of its turns that it can use only to make a Reactive Strike. It can't use more than one Reactive Strike triggered by the same action. In addition to the normal trigger, the caterpillar can make a Reactive Strike against a creature that touches it or an adjacent creature that attempts a melee Strike against it.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+25 (reach 10 feet)\n__Damage__  3d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Bristles"
    desc: "+25 ()\n__Damage__  3d8 + 13 piercing plus penetrating-bristles"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+23 ()\n__Damage__  3d10 + 11 bludgeoning"

  - name: "Penetrating Bristles"
    desc: "  On a critical hit with a bristles Strike, a woodweave caterpillar's bristles lodge in the target's body, causing severe pain and blood loss. They deal 3d6 bleed damage, and the target is [[Conditions/Off-Guard|Off-Guard]] as long as the persistent damage continues."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or Smaller, foot, DC 32 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Woodweave Caterpillar
creatures:
  - 1: Woodweave Caterpillar
```




