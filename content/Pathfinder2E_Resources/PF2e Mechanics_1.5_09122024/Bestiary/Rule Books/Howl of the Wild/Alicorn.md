---
title: "Alicorn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CUERZVk2na8HqRDI" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fey
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Alicorn"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Alicorn"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[fey]]
trait_03: [[holy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Empyrean, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Arcana: +27, Athletics: +27, Diplomacy: +30, Stealth: +25"
abilityMods: [8, 7, 4, 6, 4, 6]
speed: 40 feet,  fly 80 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +26, __Will__ +29"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Immunities__  poison"
abilities_top:
  - name: ""

  - name: "Wild Empathy"
    desc: "  The alicorn has an empathic connection to the creatures of the natural world that. The alicorn can use Diplomacy to [[Actions/Make an Impression|Make an Impression]] on animals and to make very simple [[Actions/Request|Requests]] of them."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
  - name: "Draw in Magic"
    desc: "`pf2:r` (arcane,concentrate) **Trigger** A creature within 30 feet of the alicorn Casts a Spell\n* * *\n\n**Effect** The alicorn attempts to counteract the triggering spell (counteract modifier +28, counteract rank 8th). If successful, the alicorn can choose to gain the effects of the triggering spell as its sole target."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+29 (holy, magical)\n__Damage__  2d6 spirit 4d10 + 10 piercing"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+29 (holy, magical, reach 10 feet)\n__Damage__  4d6 + 10 piercing 2d6 spirit"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+29 (agile, magical, reach 10 feet)\n__Damage__  4d8 + 10 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 36, attack +0; __8th __  _[[Spells/Wall of Force|Wall of Force]]_; __6th __  _[[Spells/Telepathy|Telepathy]]_; __5th __  _[[Spells/Banishment|Banishment]]_; __1st __  _[[Spells/Gentle Landing|Gentle Landing (At-Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Light|Light]]_"

  - name: "Aerial Attack"
    desc: "`pf2:2`  The alicorn Flies and Strikes twice with their wings at any points during their movement. Each attack counts toward the alicorn's multiple attack penalty, but the penalty doesn't increase until after they make all the attacks."

  - name: "Beam of Light"
    desc: "`pf2:2` (arcane,concentrate,fire,holy,light) The alicorn harnesses a powerful burning ray of light from their horn. Creatures in a 120-foot line take 16d6 fire damage (DC 36 Fortitude check save). An unholy creature in the area takes an additional 8d6 spirit damage. If the light passes through an area of magical darkness or targets a creature affected by magical darkness, the beam attempts to counteract the darkness (counteract modifier +28, counteract rank 8th). The alicorn can't use its Beam of Light again for 1d4 rounds."

  - name: "Ghost Touch"
    desc: "  An alicorn's Strikes have the effects of a ghost touch property rune."
 
```

```encounter-table
name: Alicorn
creatures:
  - 1: Alicorn
```




