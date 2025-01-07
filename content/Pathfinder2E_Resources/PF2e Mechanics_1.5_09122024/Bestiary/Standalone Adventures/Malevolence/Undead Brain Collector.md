---
title: "Undead Brain Collector"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Ux2QpcQPm8I2jItm" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Undead Brain Collector"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Undead Brain Collector"
level: "Creature 7"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Aklo, Chthonian, Common, Draconic, Protean, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +17, Occultism: +12, Stealth: +16"
abilityMods: [6, 3, 5, -1, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +12, __Will__ +15; +1 status to all saves vs. magic"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  paralyzed,  unconscious,  poison,  death effects,  disease"
abilities_top:
  - name: ""

  - name: "Absorb Phantom Brain"
    desc: "  **Trigger** The undead brain collector possesses at least 1 phantom brain after using Brainlash\n* * *\n\n**Effect** The undead brain collector absorbs 1d4 of its phantom brains, gaining 1d8 temporary Hit Points for each brain it absorbed."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 ()\n__Damage__  2d10 + 8 piercing plus mind-rotting-toxin"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+18 (agile)\n__Damage__  2d8 + 8 slashing"

  - name: "Brainlash"
    desc: "`pf2:2` (mental,occult) The undead brain collector extrudes a writhing tangle of ectoplasm from its bursted brain blisters. These ectoplasmic strands lash out at all living targets within 30 feet. Targets in this area must attempt a DC 25 Will check save.\n\nAfter the undead brain collector uses this ability, seven phantom brains glow and shimmer where its brain blisters once were. It can't use Brainlash again until all seven phantom brains are Absorbed.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d6 mental damage.\n\n**Failure** The creature takes 8d6 mental damage.\n\n**Critical Failure** The creature takes 8d6 mental damage and is [[Conditions/Confused|Confused]]."

  - name: "Mind-Rotting Toxin"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n* * *\n\n**Stage 1** 1d6 void and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 1d6 void, stupefied 1, and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 3** 2d6 void, [[Conditions/Stupefied|Stupefied 2]], and slowed 1 (1 round)"
 
```

```encounter-table
name: Undead Brain Collector
creatures:
  - 1: Undead Brain Collector
```




