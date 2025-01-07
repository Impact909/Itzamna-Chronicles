---
title: "Echopsyvne"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.reTikV3QJlKi40Y5" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/palinthanos
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Echopsyvne"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Echopsyvne"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[palinthanos]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; "
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Deception: +32"
abilityMods: [-5, 9, 0, 6, 5, 6]
speed:  fly 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +24, __Ref__ +33, __Will__ +31"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Backward Speakers"
    desc: "  When a palinthanos vocalizes, the sounds it creates are reversed. For the egarhowl, this only results in unnerving backwards sounds of angry roars and bestial noises, but for those who can speak, it makes understanding them difficult. A palinthanos has no difficulty understanding any language it can speak, but when it speaks, listeners must succeed at a DC 30 Perception check check made as a free action with the concentrate trait each round to quickly decipher the reversed conversation. This prevents a palinthanos from being able to easily utilize linguistic actions."

abilities_mid:
  - name: ""
  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, finesse, magical)\n__Damage__  3d6 spirit 3d6 + 8 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Possession|Possession (x3)]]_"

  - name: "Distort Perception"
    desc: "`pf2:1` (incapacitation,mental,occult) **Frequency** once per round\n* * *\n\n**Effect** The echopsyvne targets a creature it can see within 30 feet and alters its perception of time. The target must attempt a DC 40 Will check save. Regardless of success or failure, the creature then becomes temporarily immune to this ability for 24 hours.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature perceives time to flow backward briefly and becomes [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** Time flows backward for the creature, leaving them unable to interact with the world around them. The creature is [[Conditions/Stunned|Stunned 3]], after which it is slowed 1 for 1 round.\n\n**Critical Failure** The creature's mind becomes stuck in a time loop, and it becomes [[Conditions/Paralyzed|Paralyzed]] by the disorienting sight for 1 minute. At the end of each of its turns, it can attempt a new Will save to reduce the remaining duration by 1 round or end it entirely on a critical success."

  - name: "Predestined Defeat"
    desc: "`pf2:r` (occult) **Trigger** The echopsyvne rolls initiative\n\n**Frequency** once per day\n* * *\n\n**Effect** At the start of combat, an inverted, reversed explosion of spiritual and void energy implodes in a 30-foot emanation centered on the echopsyvne—a reversal of the creature's spiritually explosive death. All creatures in the area take 15d8 spirit damage (DC 37 Fortitude check save); creatures that fail this save are also [[Conditions/Slowed|Slowed 1]] for 1 round as time seems to distort around them."

  - name: "Reaction Reversal"
    desc: "  Since an echopsyvne appears to move backwards in time and the results of its actions manifest slightly out of sync, its manipulate or move actions and Strikes don't trigger reactions normally. Whenever a reaction would be triggered by an echopsyvne in this way, the reacting creature must attempt a DC 11 Flat check. On a failure, their reaction does not trigger."

  - name: "Temporal Possession"
    desc: "  When the echopsyvne casts possession on a creature, that creature experiences time backward. When the echopsyvne controls the target, they function normally, but when the target takes their own actions while the echopsyvne is in partial control or riding along in their body, they become [[Conditions/Clumsy|Clumsy 3]] and take a –10-foot status penalty to all of their Speeds. When the echopsyvne stops possessing the target, willingly or otherwise, the target must succeed at a DC 37 Will check save or be [[Conditions/Stunned|Stunned 1]] as they readjust to a more familiar flow of time."
 
```

```encounter-table
name: Echopsyvne
creatures:
  - 1: Echopsyvne
```



Palinthanos formed from intelligent creatures tend to be scheming and envious opportunists who seek to possess mortal bodies. They appear as vortexes of twisted, misty faces from which ghostly limbs emerge, regardless of their appearance in life.

* * *

When a cosmic event like Godsrain disturbs all that exists, the River of Souls sometimes flows backward for a brief moment, literally, from the shockwave. Unwilling and confused souls that are forced back far enough can have the agonizing experience of enduring death in reversed time. Some of these souls manage to re-enter the river once the flow returns to normal, but those who are stranded on the metaphorical shores of the living can become palinthanos: powerful undead born from their reversed demise who struggle futilely until their predestined banishment back to the River.

## Backward Time

Palinthanos movements often feel counterintuitive to the senses, as if there is some invisible force from the unseen future acting upon them. For example, wounds created by palinthanos attacks tend to appear on bodies out of sync with the inflicting strike, manifesting a fraction of a section before the attack lands. Wherever they appear, it's as though two streams of time collide and flow opposite of one another, which the Universe does its best to make sense of.
