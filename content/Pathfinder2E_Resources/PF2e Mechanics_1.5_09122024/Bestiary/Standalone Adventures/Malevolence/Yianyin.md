---
title: "Yianyin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.m4xtxzjouWw5ehvh" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Yianyin"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Yianyin"
level: "Creature 7"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[monitor]]
trait_03: [[psychopomp]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 120 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Diplomacy: +17, Intimidation: +17, Medicine: +16, Occultism: +14, Religion: +16, Boneyard Lore: +16"
abilityMods: [0, 6, 5, 3, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +14, __Ref__ +17, __Will__ +16; +1 status to all saves vs. magic"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  death effects,  disease; __Resistances__ void 7, poison 7"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 120 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Unnerving Presence"
    desc: " (aura,divine,emotion,fear,incapacitation) 30 feet. A creature that begins its turn within the aura must attempt a DC 22 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and becomes temporarily immune to unnerving presence for 24 hours.\n\n**Success** The creature's attack rolls take a -1 status penalty for 1 round.\n\n**Failure** The creature feels Yianyin's eyeless gaze upon them but knows that something far more dangerous and monstrous watches them through those empty sockets. The overwhelming presence of this alien intelligence causes the creature to become [[Conditions/Slowed|Slowed 1]] for 1 round as they shake and tremble with fear.\n\n**Critical Failure** As failure, but the creature is instead [[Conditions/Stunned|Stunned 1]] and knows the name of what watches from those empty eyes: Tchekuth."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, finesse)\n__Damage__  2d8 + 2 bludgeoning plus corrupted-touch"

  - name: "Innate Occult Spells"
    desc: "DC 25, attack +17; __4th __ (2 slots) _[[Spells/Confusion|Confusion]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_; __3rd __ (1 slots) _[[Spells/Illusory Disguise|Illusory Disguise]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_\n__Cantrips__  __(4th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Compel Condemned"
    desc: "`pf2:1` (divine,incapacitation,mental) Yianyin telepathically compels a creature within 30 feet to approach and allow Yianyin to kiss them, in preparation for using Kiss of Death. The target must attempt a DC 25 Will check save.\n\n**Success** The creature is unaffected and is temporarily immune to Compel Condemned for 24 hours.\n\n**Failure** The creature must spend each of its actions to move closer to Yianyin as quickly as possible, while avoiding obvious dangers. If the compelled creature is adjacent to Yianyin, it stays still and doesn't act. If the creature takes any damage, the effect ends and the creature is temporarily immune to Compel Condemned for 24 hours. This effect lasts for 1 round, but if Yianyin uses this ability again on subsequent rounds, it extend the duration by 1 round for all affected creatures.\n\n**Critical Failure** As failure, but damage does not end the effect."

  - name: "Corrupted Touch"
    desc: "  Yianyin's Strikes deal 2d6 void damage to living creatures. A creature critically hit by Yianyin's Strike must attempt a DC 18 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure) as rot spreads throughout their flesh."

  - name: "Kiss of Death"
    desc: "`pf2:2` (death,divine,manipulate) Yianyin gives a long, passionate kiss to an [[Conditions/Unconscious|Unconscious]] or willing creature, dealing 4d6 void damage.\n\nAny creature damaged by Yianyin's Kiss of Death for 3 consecutive rounds becomes unconscious and is [[Conditions/Dying|Dying 1]]."
 
```

```encounter-table
name: Yianyin
creatures:
  - 1: Yianyin
```




