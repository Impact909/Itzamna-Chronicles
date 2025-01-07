---
title: "Marsh Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.R56o1Gq6LHL6VlPT" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Marsh Giant"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Marsh Giant"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[water]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Low-Light Vision"
languages: "Aklo, Common, Jotun, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +15, Nature: +15, Religion: +17"
abilityMods: [6, 3, 4, 0, 3, 1]
speed: 35 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +13, __Will__ +17"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Gaff|+1 Striking Gaff]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gaff"
    desc: "+20 (magical, reach 10 feet, trip, versatile p)\n__Damage__  2d6 + 14 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, reach 10 feet)\n__Damage__  2d6 + 14 bludgeoning"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+20 (primal, range 60 feet, water)\n__Damage__  5d6 bludgeoning"

  - name: "Occult Innate Spells"
    desc: "DC 23, attack +13; __5th __  _[[Spells/Mariner's Curse|Mariner's Curse]]_; __2nd __  _[[Spells/Augury|Augury]]_, _[[Spells/Mist|Mist]]_"

  - name: "Drowning Hook"
    desc: "`pf2:1` (primal,water) **Requirements** A creature is [[Conditions/Prone|Prone]] within the marsh giant's reach\n* * *\n\n**Effect** The marsh giant uses its gaff to push the creature down as water bubbles up below it. The target becomes submerged in water until they are no longer prone and must hold their breath if they cannot breathe water. They take 4d6 bludgeoning damage (DC 23 Fortitude check save) and lose 3 rounds worth of air if they fail the save."

  - name: "Twist the Hook"
    desc: "`pf2:2`  The marsh giant makes a melee Strike with its gaff. If it hits, it twists and yanks the gaff to knock the target [[Conditions/Prone|Prone]] and create an awful wound, dealing 2d6 persistent bleed damage to the creature."
 
```

```encounter-table
name: Marsh Giant
creatures:
  - 1: Marsh Giant
```



Dwellers of brackish coastal salt marshes and fetid bogs and swamps, marsh giants appear hideous to most airbreathers, with fishlike mouths, slimy graygreen skin, and dark, beady eyes. They prefer to eat the flesh of those they slay in battle, including other marsh giants, and guzzle stagnant water from cauldrons or directly from their swampy homes.

Marsh giant clans are insular, with each clan dedicating itself to zealous worship of a sea-dwelling deity, demon lord, or stranger entity. Whatever forces call to the marsh giants sometimes ensnare boggards and ogres as well, gathering in grim worship. Rather than favor these humanoid hangerson, marsh giants lavish attention on favored pets: krooths, giant octopuses, or primeval creatures like dinosaurs and the crocodilian deinosuchuses.

Barely topping 11 feet tall and 1,000 pounds, marsh giants are small for giants but make up for their stature with their zealotry.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
