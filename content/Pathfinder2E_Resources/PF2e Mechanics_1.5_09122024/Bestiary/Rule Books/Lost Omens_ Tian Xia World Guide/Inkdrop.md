---
title: "Inkdrop"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8gpPjzNOIqkcLU72" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Inkdrop"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Inkdrop"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +2, Stealth: +3"
abilityMods: [0, -3, 2, -5, 0, -5]
speed: 10 feet,  climb 10 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 7
armorclass:
  - name: AC
    desc: "7; __Fort__ +2, __Ref__ +6, __Will__ +5"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Immunities__  critical hits,  precision,  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ cold 5, fire 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Perfect Memory"
    desc: "  An inkdrop remembers the exact pattern of any ink it moves over physically."

abilities_mid:
  - name: ""
  - name: "Blotting"
    desc: "  While a creature has the inkdrop grabbed or pinned, it can destroy the inkdrop by smudging the inkdrop out with an Interact action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+6 ()\n__Damage__  1d4 bludgeoning plus blinding-ink"

  - name: "Blinding Ink"
    desc: "  A creature critically struck by the inkdrop's pseudopod is [[Conditions/Blinded|Blinded]] by the ink until it clears its eyes using an Interact action."

  - name: "Ink Blot"
    desc: "`pf2:1`  The inkdrop leaves a pattern it remembers over a square foot of surface. If there's existing non-magical ink on the surface, the inkdrop erases the nonmagical ink."
 
```

```encounter-table
name: Inkdrop
creatures:
  - 1: Inkdrop
```



Not all handcrafts are intended for war. The inkdrop is an infiltrator used by spellcasters to learn secrets or alter documents. Embodied in a single fist-sized drop of ink, the inkdrop can glide across a page, changing characters or removing them altogether, with devastating consequences for statecraft.
