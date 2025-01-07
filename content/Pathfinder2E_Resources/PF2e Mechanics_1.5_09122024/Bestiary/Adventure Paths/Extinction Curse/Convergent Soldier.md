---
title: "Convergent Soldier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vLMeLENLNbfahyjO" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Convergent Soldier"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Convergent Soldier"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Common, Fey, Utopian; convergent link"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +32, Survival: +28"
abilityMods: [6, 5, 9, 2, 4, 2]
speed: 25 feet
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +28, __Will__ +25"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|+1 Striking Bastard Sword]], [[Equipment/Longbow|Longbow]], [[Equipment/Studded Leather Armor|+1 Studded Leather Armor]], Eagle Garrison Badge, 20x [[Equipment/Arrows|Arrows]]"
  - name: "Convergent Link"
    desc: "  Creatures with this ability can communicate with each other by manifesting an aura of wispy Utopian runes.\n\nThis has the effects of [[Bestiary Ability Glossary/Telepathy|Telepathy]] with a range of 300 feet, but requires line of sight."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Disrupted Link"
    desc: "  While a convergent soldier is [[Conditions/Confused|Confused]], [[Conditions/Fascinated|Fascinated]], or [[Conditions/Frightened|Frightened]], they loses their convergent link and convergent tactics abilities."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+31 (magical, two-hand d12)\n__Damage__  2d8 + 12 slashing plus convergent-tactics"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+29 (deadly d10, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 9 piercing plus convergent-tactics"

  - name: "Convergent Tactics"
    desc: "  The convergent soldier's attacks deal an extra 4d8 damage to creatures within reach of one of their allies with convergent tactics."

  - name: "Force Communication"
    desc: "`pf2:1` (divine,illusion,mental,visual) Utopian runes burst from the convergent soldier.\n\nAny creature [[Conditions/Stupefied|Stupefied]] by the [[Extinction Curse/Convergence Lattice|Convergence Lattice]] who is within 100 feet of the convergent soldier and can see the runes must attempt a DC 34 Will check save.\n* * *\n\n**Failure** For 1 round, the creature is [[Conditions/Off-Guard|Off-Guard]] to creatures with the convergent link ability and counts as an ally with convergent tactics for the purposes of activating the convergent tactics ability.\n\n**Critical Failure** As failure, and the creature is also [[Conditions/Slowed|Slowed 1]] for 1 round due to the information overload."
 
```

```encounter-table
name: Convergent Soldier
creatures:
  - 1: Convergent Soldier
```




