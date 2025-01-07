---
title: "Attic Whisperer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ecJT0LZRhVtcj66s" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Attic Whisperer"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Attic Whisperer"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Deception: +11, Society: +10, Stealth: +13"
abilityMods: [0, 5, 0, 2, 4, 3]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +8, __Ref__ +13, __Will__ +12"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Aura of Sobs"
    desc: " (auditory,aura,concentrate,emotion,mental,occult) 10 feet. An attic whisperer enshrouds itself in a tapestry of stolen voices. Each living creature that enters or starts their turn in the aura must succeed at a DC 19 Will check save or the unnerving, bitter sobs render them distraught and they become [[Conditions/Stupefied|Stupefied 1]] for as long as they remain within the aura. A creature that succeeds is temporarily immune for 1 hour.\n\nThe attic whisperer can activate or deactivate the aura with a single free action, which has the concentrate trait."

  - name: "Whispered Despair"
    desc: "`pf2:r` (emotion) **Trigger** A creature with an active emotion effect enters an attic whisperer's aura of sobs\n* * *\n\n**Effect** The attic whisperer attempts to counteract the emotion effect, with a counteract modifier of +13."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (agile, finesse)\n__Damage__  2d8 piercing plus steal-breath"

  - name: "**Melee** `pf2:1` Bony Hand"
    desc: "+13 (agile)\n__Damage__  2d10 void plus steal-voice"

  - name: "Steal Breath"
    desc: " (curse,incapacitation,occult) The attic whisperer siphons the breath from living creatures, sapping their strength. A living creature hit by a jaws Strike must attempt a DC 21 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Enfeebled|Enfeebled 1]] for 1 round.\n\n**Failure** The target is [[Conditions/Enfeebled|Enfeebled 1]] for 24 hours and [[Conditions/Fatigued|Fatigued]].\n\n**Critical Failure** The target is enfeebled 1 for 24 hours, is fatigued, and falls [[Conditions/Unconscious|Unconscious]]."

  - name: "Steal Voice"
    desc: " (auditory,curse,occult) When an attic whisperer hits a living creature with a bony hand Strike, it tries to pull the victim's voice into its aura. The victim must attempt a DC 21 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target's voice is weak for 1 minute. Anytime it attempts an action with the auditory trait, it must succeed at a DC 5 Flat check check or the action is lost.\n\n**Failure** The target loses the ability to speak for 1 hour, until the curse is removed, or until the attic whisperer is destroyed, whichever comes first. During this time, the attic whisperer can perfectly mimic the target's voice, and the target takes a -2 circumstance penalty to saving throws against that attic whisperer's aura of sobs.\n\n**Critical Failure** As failure, but the effects lasts until the attic whisperer is destroyed or the curse is removed."
 
```

```encounter-table
name: Attic Whisperer
creatures:
  - 1: Attic Whisperer
```



Beware the haunting sobs of the attic whisperer, for they carry the pained wrath of an abandoned child who perished due to the neglect or absence of their caretakers. Animated by loneliness, the embittered spirit binds itself to the material world in a body made of bits and oddments of a lost childhood-wooden blocks, scraps of blankets, ratty dolls, buttons, carved trinkets, and glass marbles. To give themselves the semblance of a head, they top their patchwork bodies with a small animal's skull.

Attic whisperers most frequently lurk in old infirmaries, orphanages, and other such institutions where children were forgotten, and they lay dormant for decades in hopes that they might one day find a playmate to ease their eternal loneliness. When they sense the living, attic whisperers attempt to lure them into their clutches by calling out to them using the voice of a small child. Though attic whisperers intend only to play with those they encounter, they drain the breath and voice from living creatures as their dark impulses take over.
