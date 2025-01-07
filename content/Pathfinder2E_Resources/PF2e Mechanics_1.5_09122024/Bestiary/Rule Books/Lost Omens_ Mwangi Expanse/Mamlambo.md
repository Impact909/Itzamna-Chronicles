---
title: "Mamlambo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yVNt7F1NsPhsVLeX" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Mamlambo"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: The Mwangi Expanse"
name: "Mamlambo"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[aquatic]]
trait_02: [[beast]]
trait_03: [[evil]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +21, Stealth: +19, Survival: +17"
abilityMods: [7, 4, 5, -3, 4, 0]
speed: 10 feet,  swim 40 feet
sourcebook: "_Pathfinder Lost Omens: The Mwangi Expanse_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +20, __Will__ +15"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Luminous Lure"
    desc: " (aura,emotion,incapacitation,light,mental,primal) 30 feet. The mamlambo emits dim light from its skin. A creature that enters or begins its turn in the aura must attempt a DC 23 Will check save. Humanoids take a -2 penalty to this saving throw.\n\nRegardless of the save's result, the creature is temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]], and for as long as it is in the aura it must spend at least 1 of its actions on each of its turns to move closer to the mamlambo as expediently as possible, while avoiding obvious dangers. If the creature ends its movement or turn adjacent to the mamlambo, it is Slowed 1 until it is out of the aura or until the mamlambo makes a Strike against it.\n\nThe target can attempt a new Will save at the beginning of each of their subsequent turns, and on a success, the effect ends.\n\n**Critical Failure** As failure, but the creature must spend each of its actions moving closer to the mamlambo, and if it ends its movement or turn adjacent to the mamlambo, it is [[Conditions/Paralyzed|Paralyzed]] until it is out of the aura or until the mamlambo makes a Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (reach 10 feet)\n__Damage__  2d8 + 11 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+21 (agile, reach 15 feet)\n__Damage__  2d6 + 11 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  50 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Face Eater"
    desc: "`pf2:1`  **Requirements** The mamlambo has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]], or there is a [[Conditions/Dying|Dying]], [[Conditions/Immobilized|Immobilized]], or [[Conditions/Unconscious|Unconscious]] creature within the mamlambo's reach\n* * *\n\n**Effect** The mamlambo deals 2d8+11 piercing damage to the creature (DC 28 Fortitude check save).\n\nOn a failure, the creature also takes an additional 2d6 bleed, or 4d6 bleed on a critical failure."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mamlambo
creatures:
  - 1: Mamlambo
```



Mamlambos are river predators with hypnotic, bioluminescent skin. They appear similar to crocodiles, but the narrow head at the end of their long necks resembles a horse's skull, and their four legs are stubby and inefficient for land movement. Their skin's green glow is only barely visible in daylight or when underwater, though the glow is difficult to resist. As a result, they're frequently trailed by fish, birds, or other river creatures ensnared by the alluring radiance.

Humanoids are mamlambos' favorite prey, particularly humans, although they strangely prefer to only eat their victims' faces and brains. Mamlambos are dim-witted but sly, and sometimes hide their victims under submerged rocks or logs to make their discovery less likely. A mamlambo might be active in a region for days or even weeks before its presence is discovered.
