---
title: "Tar Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EtL5sraNXD421Bv9" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Tar Ooze"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Tar Ooze"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23, Stealth: +13"
abilityMods: [8, -3, 8, -5, 0, -5]
speed: 15 feet,  climb 10 feet
sourcebook: "_Pathfinder #177: Burning Tundra_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +22, __Ref__ +10, __Will__ +15"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Immunities__  critical hits,  precision,  unconscious,  visual,  mental; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A tar ooze can sense nearby motion through vibration and movement."

abilities_mid:
  - name: ""
  - name: "Sticky"
    desc: "`pf2:r`  **Trigger** The tar ooze is hit by a melee attack\n* * *\n\n**Effect** The ooze attempts to [[Actions/Grapple|Grapple]] the creature that hit it. The ooze must still spend an action to extend the duration of the Grab on subsequent rounds, as normal."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+23 (reach 10 feet)\n__Damage__  2d10 + 14 bludgeoning plus improved-grab"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 29 Reflex check, 6d6 bludgeoning, [[Actions/Escape|Escape]] DC 29, Rupture 17\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Viscous Sludge"
    desc: "  The tar ooze can have up to eight creatures grappled at the same time; doing so doesn't prevent it from making pseudopod Strikes. A tar ooze can climb on ceilings and other inverted surfaces, though such surfaces are difficult terrain."

  - name: "Zombification"
    desc: " (primal) A creature slain while engulfed by a tar ooze undergoes a horrifying transformation and crawls from the ooze a week later as a tar zombie."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tar Ooze
creatures:
  - 1: Tar Ooze
```




