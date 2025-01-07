---
title: "Anitoli Nostraema"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AZNXNPy4E0aO7HeD" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Anitoli Nostraema"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Anitoli Nostraema"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Deception: +14, Occultism: +13, Stealth: +15"
abilityMods: [0, 5, 2, 3, 5, 4]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +17, __Will__ +15"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95; __Immunities__  paralyzed,  unconscious,  poison,  death effects,  disease"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Whispered Despair"
    desc: "`pf2:r` (emotion) **Trigger** A creature with an active emotion effect enters an attic whisperer's aura of sobs\n* * *\n\n**Effect** The attic whisperer attempts to counteract the emotion effect, with a counteract modifier of +13."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (agile, finesse)\n__Damage__  3d8 piercing plus steal-breath"

  - name: "**Melee** `pf2:1` Bony Hand"
    desc: "+17 (agile)\n__Damage__  2d12 void plus steal-voice"

  - name: "Aura of Sobs"
    desc: " (auditory,aura,emotion,mental,occult) 10 feet. Anitoli Nostreaema enshrouds itself in a tapestry of stolen voices. Each living creature that enters or starts their turn in the aura must succeed at a DC 21 Will check save or the unnerving, bitter sobs render them distraught and they become [[Conditions/Stupefied|Stupefied 1]] for as long as they remain within the aura. A creature that succeeds is temporarily immune for 1 hour.\n\nAnitoli Nostreaema can activate or deactivate the aura with a single free action, which has the concentrate trait."

  - name: "Steal Breath"
    desc: " (curse,incapacitation,occult) Anitoli Nostreaema siphons the breath from living creatures, sapping their strength. A living creature hit by a jaws Strike must attempt a DC 24 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Enfeebled|Enfeebled 1]] for 1 round.\n\n**Failure** The target is [[Conditions/Enfeebled|Enfeebled 1]] for 24 hours and [[Conditions/Fatigued|Fatigued]].\n\n**Critical Failure** The target is enfeebled 1 for 24 hours, is fatigued, and falls [[Conditions/Unconscious|Unconscious]]."

  - name: "Steal Voice"
    desc: " (auditory,curse,occult) When Anatoli Nostraema hits a living creature with a bony hand Strike, it tries to pull the victim's voice into its aura. The victim must attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target's voice is weak for 1 minute. Anytime it attempts an action with the auditory trait, it must succeed at a DC 5 Flat check check or the action is lost.\n\n**Failure** The target loses the ability to speak for 1 hour, until the curse is removed, or until the attic whisperer is destroyed, whichever comes first. During this time, the attic whisperer can perfectly mimic the target's voice, and the target takes a -2 circumstance penalty to saving throws against that attic whisperer's aura of sobs.\n\n**Critical Failure** As failure, but the effects lasts until the attic whisperer is destroyed or the curse is removed."
 
```

```encounter-table
name: Anitoli Nostraema
creatures:
  - 1: Anitoli Nostraema
```




