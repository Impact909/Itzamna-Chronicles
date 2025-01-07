---
title: "Risen Nemesis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p8PY3DKdDdPZodgu" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/palinthanos
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Risen Nemesis"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Risen Nemesis"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[fiend]]
trait_02: [[incorporeal]]
trait_03: [[palinthanos]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Greater Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Deception: +35, Intimidation: +37"
abilityMods: [-5, 7, 7, 7, 7, 7]
speed:  fly 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +33, __Ref__ +33, __Will__ +33"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 20 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
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
    desc: "+35 (agile, finesse, magical)\n__Damage__  4d6 + 10 slashing 4d6 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 42, attack +34; __9th __  _[[Spells/Phantasmagoria|Phantasmagoria]]_; __8th __  _[[Spells/Vision of Death|Vision of Death]]_; __7th __  _[[Spells/Warp Mind|Warp Mind]]_\n__Cantrips__  __(10th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Come Out, You Cowards!"
    desc: "`pf2:3` (move,occult) In each round the Risen Nemesis does not have a PC to target, they go on a rampage, harming innocent bystanders and damaging the opera house structure. The Risen Nemesis Strides, then damages enough of their immediate surroundings at the end of this Stride to fill a 10-foot emanation with rubble that functions as difficult terrain (or greater difficult terrain where difficult terrain from rubble already existed). The PCs lose 1d4 Opera Points from their accumulated total."

  - name: "Distort Perception"
    desc: "`pf2:1` (incapacitation,mental,occult) **Frequency** once per round\n* * *\n\n**Effect** The risen nemesis targets a creature it can see within 30 feet and alters its perception of time. The target must attempt a DC 42 Will check save. Regardless of success or failure, the creature then becomes temporarily immune to this ability for 24 hours.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature perceives time to flow backward briefly and becomes [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** Time flows backward for the creature, leaving them unable to interact with the world around them. The creature is [[Conditions/Stunned|Stunned 3]], after which it is slowed 1 for 1 round.\n\n**Critical Failure** The creature's mind becomes stuck in a time loop, and it becomes [[Conditions/Paralyzed|Paralyzed]] by the disorienting sight for 1 minute. At the end of each of its turns, it can attempt a new Will save to reduce the remaining duration by 1 round or end it entirely on a critical success."

  - name: "Predestined Defeat"
    desc: "`pf2:r` (occult) **Trigger** The risen nemesis rolls initiative\n\n**Frequency** once per day\n* * *\n\n**Effect** At the start of combat, an inverted, reversed explosion of spiritual and void energy implodes in a 30-foot emanation centered on the risen nemesis—a reversal of the creature's spiritually explosive death. All creatures in the area take 16d8 spirit damage (DC 39 Fortitude check save); creatures that fail this save are also [[Conditions/Slowed|Slowed 1]] for 1 round as time seems to distort around them."

  - name: "Reaction Reversal"
    desc: "  Since an risen nemesis appears to move backwards in time and the results of its actions manifest slightly out of sync, its manipulate or move actions and Strikes don't trigger reactions normally. Whenever a reaction would be triggered by an risen nemesis in this way, the reacting creature must attempt a DC 11 Flat check. On a failure, their reaction does not trigger."

  - name: "Temporal Possession"
    desc: "  When the echopsyvne casts possession on a creature, that creature experiences time backward. When the echopsyvne controls the target, they function normally, but when the target takes their own actions while the echopsyvne is in partial control or riding along in their body, they become [[Conditions/Clumsy|Clumsy 3]] and take a –10-foot status penalty to all of their Speeds. When the echopsyvne stops possessing the target, willingly or otherwise, the target must succeed at a DC 37 Will check save or be [[Conditions/Stunned|Stunned 1]] as they readjust to a more familiar flow of time."

  - name: "Undo Destruction"
    desc: "`pf2:2` (occult) Destruction is the beginning, not the end! The Risen Nemesis rewinds time on a pile of rubble that they can see within 120 feet, causing the rubble in a 10-foot burst to restore itself to its pre-destroyed state and causing the area to no longer serve as difficult terrain. All creatures in the area must make a DC 42 Reflex check save. The Risen Nemesis cannot use Undo Destruction again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature avoids being harmed by the violence of the repairs.\n\n**Success** The creature takes 2d10 bludgeoning, 2d10 piercing, and 2d10 slashing damage as pieces of rubble bash, slice, and pierce them while it swirls through the air to rebuild.\n\n**Failure** As success but 4d10 bludgeoning, 2d10 piercing, and 2d10 slashing damage and the creature is knocked [[Conditions/Prone|Prone]].\n\n**Critical Failure** As failure but 8d10 bludgeoning, 8d10 piercing, and 8d10 slashing damage and the target is carried away with the rubble. They become [[Conditions/Restrained|Restrained]] by the rebuilt structure (usually the wall or floor within the rubble pile or closest to it; [[Actions/Escape|Escape]] DC 42). The restrained character might be so encased in rubble that they run the risk of suffocation."
 
```

```encounter-table
name: Risen Nemesis
creatures:
  - 1: Risen Nemesis
```


Variant echopsyvne

Palinthanos formed from intelligent creatures tend to be scheming and envious opportunists who seek to possess mortal bodies. They appear as vortexes of twisted, misty faces from which ghostly limbs emerge, regardless of their appearance in life.

* * *

When a cosmic event like Godsrain disturbs all that exists, the River of Souls sometimes flows backward for a brief moment, literally, from the shockwave. Unwilling and confused souls that are forced back far enough can have the agonizing experience of enduring death in reversed time. Some of these souls manage to re-enter the river once the flow returns to normal, but those who are stranded on the metaphorical shores of the living can become palinthanos: powerful undead born from their reversed demise who struggle futilely until their predestined banishment back to the River.

## Backward Time

Palinthanos movements often feel counterintuitive to the senses, as if there is some invisible force from the unseen future acting upon them. For example, wounds created by palinthanos attacks tend to appear on bodies out of sync with the inflicting strike, manifesting a fraction of a section before the attack lands. Wherever they appear, it's as though two streams of time collide and flow opposite of one another, which the Universe does its best to make sense of.
