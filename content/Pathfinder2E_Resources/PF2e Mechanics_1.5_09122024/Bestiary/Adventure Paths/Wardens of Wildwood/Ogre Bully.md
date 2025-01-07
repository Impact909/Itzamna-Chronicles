---
title: "Ogre Bully"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NKbfalJgD20VtJS3" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Ogre Bully"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Ogre Bully"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Jotun, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Intimidation: +14, Survival: +13"
abilityMods: [6, 3, 5, -1, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +14, __Will__ +12"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Resistances__ bludgeoning 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ogre Hook|+1 Ogre Hook]], 3x [[Equipment/Hatchet|Hatchet]], [[Equipment/Chain Shirt|Chain Shirt]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ogre Hook"
    desc: "+18 (deadly d10, reach 10 feet, trip)\n__Damage__  1d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+16 (agile, sweep)\n__Damage__  1d6 + 13 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+16 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 13 slashing"

  - name: "Hooking Hurl"
    desc: "`pf2:1`  **Requirements** The ogre's last action was a successful ogre hook Strike\n* * *\n\n**Effect** The ogre latches the hook into the target and attempts to [[Actions/Reposition|Reposition]] the target with a sudden flick, even if the ogre doesn't have a free hand. This attempt doesn't apply the ogre's multiple attack penalty. If the target ends its movement adjacent to an obstacle or adjacent to a creature of equal or greater size, the target also takes 1d10 bludgeoning damage and is [[Conditions/Off-Guard|Off-Guard]] for 1 round."

  - name: "Stomp the Small"
    desc: "  The ogre's melee and ranged Strikes deal an additional 2 damage to Medium creatures. This additional damage increases to 1d6+2 damage to Small or smaller creatures."
 
```

```encounter-table
name: Ogre Bully
creatures:
  - 1: Ogre Bully
```


Variant ogre warrior

The simplest of ogres are slabs of muscle with hateful eyes, misshapen visages, and malformed bodies. Always eager for mayhem and murder, ogre warriors are quick to turn on their kin when there's a shortage of smaller folk to torment, so those who lead ogres do their best to keep them constantly distracted with new opportunities for raids and ruin.

* * *

For many societies, ogres embody brutish, amoral violence and greedy cruelty. Standing 10 feet tall and densely muscled, ogres are usually as strong as they are vicious. The worst ogres are sadists, enjoying remorseless murder, torture, and violence in all of its forms. Although they prefer to vent their violent urges on other humanoids—the smaller the better—ogre captivity can end in a horrifying fate for anyone unlucky enough to fall within their meaty grasp: becoming dinner. But for all their creativity in inflicting pain, ogres often forget that their playthings lack their own robust fortitude and high pain tolerance, and many of their captives die sooner than the ogres might prefer. Meanwhile, those who manage to survive captivity in an ogre's larder often emerge with lasting mental scars. A captive able to keep their wits about them, however, can sometimes trick the brutes by promising treasure, more plentiful food sources, or other crude amusements, taking advantage of an ogre's often-limited intellect to engineer opportunities to escape or gain revenge.

Ogres are social creatures only in the most debased sense. They gather together in groups called families, though members are not always related by blood. The most powerful ogre in any family is the "boss"—usually the family's patriarch or matriarch—whom the other ogres in the family learn to quickly obey or risk being brutalized by the boss's loyal kin. Ogres lair in caves, crumbling ruins, or dilapidated shacks close enough to humanoid settlements or animal trails to make raiding easy. Their lairs are filthy and frequently contain all-too-recognizable evidence of their depravity, along with assorted treasures stolen from past captives.
