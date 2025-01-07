---
title: "Almiraj"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1jHPrkJQPLYYbGJY" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Almiraj"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Almiraj"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +10, Survival: +8"
abilityMods: [5, 3, 4, -4, 0, 3]
speed: 35 feet,  burrow 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +11, __Will__ +8"
hp: 63
health:
  - name: ""
  - name: HP
    desc: "63"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 5 feet DC 22 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]].\n\nCreatures that critically fail are also fleeing for 1 round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Horn only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike.\n\nFleeing creatures take an additional 1d6 bleed damage. On a critical hit, the target is knocked [[Conditions/Prone|Prone]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+13 ()\n__Damage__  2d8 + 7 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d6 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile)\n__Damage__  2d4 + 7 slashing"

  - name: "Final Shake"
    desc: "`pf2:1`  **Requirements** The almiraj has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The almiraj clamps its jaws down on the creature and shakes it vigorously, attempting to finish it off. The creature takes 2d6 bludgeoning damage and must succeed at a DC 20 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 1]]. Small or smaller creatures take a –2 circumstance penalty to their save."

  - name: "Goring Charge"
    desc: "`pf2:2`  The almiraj lowers its head and moves with ferocity toward its selected prey. The almiraj Strides twice. If it ends its movement within melee reach of at least one enemy, it makes a horn Strike against that enemy. This Strike deals an additional 1d6 persistent bleed damage."

  - name: "Into the Earth"
    desc: "`pf2:1`  **Requirements** The almiraj has a Medium or smaller creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The almiraj attempts to flee with its meal, burrowing into the ground. The grabbed creature must succeed at a DC 20 Reflex check save or be dragged beneath the ground as the almiraj Burrows up to its Speed. If the target succeeds at its save, it Escapes and the almiraj continues burrowing as normal; if it fails, the grabbed creature must hold its breath or begin suffocating under the dirt."
 
```

```encounter-table
name: Almiraj
creatures:
  - 1: Almiraj
```



An almiraj closely resembles a yellow hare in almost all ways... except for the 2-foot-long black horn jutting from its forehead. Though it shares this trait with the docile unicorn, that's where their similarities end. Almirajes are vicious creatures, known to slaughter much larger cattle and, in times of desperation, people. Its stare is said to send even the bravest warrior running for their life.

Unlike common hares, almirajes are solitary and intensely territorial. They're adaptable ambush hunters with the stamina and speed to chase down any prey. They attack with their jaws and claws but are primarily known for trying to gut their prey with a vicious stab from their horn. Many scholars believe that the terrifying magical aura the creatures exude originates from their horns. This line of thinking has led to an increase in almiraj attacks as local citizens try to capture the creature alive and remove the horn, hoping this will turn it into a more docile hare. These hopes have not proven fruitful, as an almiraj is just as aggressive, if not more so, after their horn has been removed.

Adventurers often think themselves lucky if they manage to avoid the terrifying horn of this ferocious predator, but it's a much better alternative than being caught in its jaws. Almirajes have a nasty habit of grabbing their prey and vigorously shaking them until they go limp. If this fails, they'll drag their prey underground until they suffocate deep in the earth. Few have ever escaped the burrow of an almiraj.
