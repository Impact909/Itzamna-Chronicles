---
title: "Rooftop Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FJEdzpoTTnKuaT51" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dream
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Rooftop Guardian"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Rooftop Guardian"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[dream]]
trait_04: [[evil]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Aklo; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Athletics: +29, Crafting: +24, Deception: +24, Occultism: +28, Religion: +26, Stealth: +28"
abilityMods: [6, 7, 5, 7, 5, 5]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +28, __Will__ +26; +1 status to all saves vs. magic"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, (fast healing 10); __Immunities__  cold,  confused; __Resistances__ poison 15, sonic 15"
abilities_top:
  - name: ""

  - name: "Greater Web Sense"
    desc: "  While touching its webs, the Leng spider has precise [[Bestiary Ability Glossary/Tremorsense|Tremorsense]] to detect the vibrations of creatures touching its web."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Web War Flail"
    desc: "+27 (disarm, magical, reach 15 feet, sweep, trip)\n__Damage__  3d10 + 16 bludgeoning"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+27 (reach 10 feet)\n__Damage__  3d12 + 16 piercing plus leng-spider-venom"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+27 (agile, reach 10 feet)\n__Damage__  3d8 + 16 slashing"

  - name: "**Ranged** `pf2:1` Web Bola"
    desc: "+28 (magical, nonlethal, ranged trip, thrown 20 ft.)\n__Damage__  2d6 + 16 bludgeoning"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +23; __7th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Interplanar Teleport|Interplanar Teleport (To Leng or the Universe only)]]_, _[[Spells/Warp Mind|Warp Mind]]_; __6th __  _[[Spells/Mislead|Mislead]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_; __4th __  _[[Spells/Charm|Charm (x3)]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(7th)__ _[[Spells/Fly|Fly]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Create Web Weaponry"
    desc: "`pf2:1` (manipulate) The Leng spider creates a weapon by applying a cord of webbing to heavy objects, such as rocks or chunks of metal, either attaching two heavy objects together to create a web bola or fastening one to its leg to create a web war flail."

  - name: "Descend on a Web"
    desc: "`pf2:1` (move) The Leng spider moves straight down up to 120 feet, suspended by a web line. It can hang from the web or drop off. The distance it Descends on a Web doesn't count when calculating falling damage.\n\nThe web can be severed by a Strike that deals slashing damage (AC 30, Hardness 15, 25 HP), causing the Leng spider to fall."

  - name: "Lay Web Trap"
    desc: "`pf2:1` (manipulate) **Frequency** three times per day\n* * *\n\n**Effect** The Leng spider spins a web within 20 feet of itself to create a [[Equipment/Grasping Snare|Grasping Snare]], [[Equipment/Stunning Snare|Stunning Snare]], or [[Equipment/Warning Snare|Warning Snare]]. The Leng spider's web provides all the raw materials it needs. All save and [[Actions/Escape|Escape]] DCs associated with web traps use the Leng spider's Crafting DC for traps (DC 36). A web trap decays after 24 hours."

  - name: "Leng Spider Venom"
    desc: " (emotion,mental,poison) **Saving Throw** DC 33 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 2d6 poison damage, [[Conditions/Confused|Confused]], and [[Conditions/Drained|Drained 2]] (1 round); the confused effect has the emotion and mental traits."

  - name: "Ranged Trip"
    desc: "  A Leng spider can use a web bola to [[Actions/Trip|Trip]] a target with the Athletics skill. The skill check takes a -2 circumstance penalty. A web bola deals no damage when used to Trip."
 
```

```encounter-table
name: Rooftop Guardian
creatures:
  - 1: Rooftop Guardian
```


Variant elite Leng spider

The monstrous, bloated spiders from the windswept realm of Leng build eerie, dangerous lairs with the aid of magically compelled slaves. Leng spiders have anywhere from five to 13 legs, but never an even number.
