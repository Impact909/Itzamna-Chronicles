---
title: "Trumpet Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YHwhGLHr7k3lcL1y" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Trumpet Archon"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Trumpet Archon"
level: "Creature 14"

alignment: ""
size: "Medium"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Diplomacy: +29, Intimidation: +28, Nature: +23, Performance: +31, Religion: +23, Stealth: +25"
abilityMods: [7, 5, 5, 3, 6, 8]
speed: 35 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +24, __Will__ +27; +1 status to all saves vs. magic"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Weaknesses__ unholy 15; __Resistances__ sonic 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|+2 Striking Bastard Sword]], [[Equipment/Full Plate|+1 Resilient Full Plate]], [[Equipment/Musical Instrument (Virtuoso handheld)|Virtuoso Trumpet]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Retributive Strike|Retributive Strike]]"
    desc: "`pf2:r`  **Damage Reduction** 16\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+29 (holy, magical, versatile p)\n__Damage__  2d12 + 13 slashing 2d6 sonic 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +24; __7th __  _[[Spells/Heal|Heal (x2)]]_, _[[Spells/Noise Blast|Sound Burst]]_; __6th __  _[[Spells/Heroism|Heroism]]_, _[[Spells/Zealous Conviction|Zealous Conviction]]_; __5th __  _[[Spells/Banishment|Banishment]]_, _[[Spells/Breath of Life|Breath of Life]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __3rd __  _[[Spells/Circle of Protection|Circle of Protection (Against evil only) (x2)]]_\n__Cantrips__  __(7th)__ _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast [[Spells/Translocate|Translocate]], the archon can use dimension door (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's dimension door.\n\nIf the archon's dimension door has enough distance, the archon appears the same distance and direction from the creature as before either creature used dimension door."

  - name: "Kind Word"
    desc: "`pf2:1` (auditory,divine,emotion,linguistic,mental) The trumpet archon offers an ally praise or encouragement. The archon attempts to counteract one emotion effect on the ally (with a counteract modifier of +24), and the archon and the ally both gain a +1 status bonus to attack rolls and saving throws for 1 round."

  - name: "Trumpet Blast"
    desc: "`pf2:1` (auditory,divine,emotion,mental) The trumpet archon blows mightily on their horn, creating a tone of such beauty and grandeur those who hear it are paralyzed in awe. Non-archons within 100 feet must attempt a DC 34 Fortitude check save.\n\nThey are temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Off-Guard|Off-Guard]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 1]] and off-guard as long as it's stunned.\n\n**Critical Failure** The creature is [[Conditions/Paralyzed|Paralyzed]] for 1 round."
 
```

```encounter-table
name: Trumpet Archon
creatures:
  - 1: Trumpet Archon
```



Trumpet archons are messengers, emissaries, and storytellers-embodiments of the virtue of kindness. They use stories and allegories to prevent bloodshed, and among all archons they are the most likely to work together with angels, perhaps leading to the similarities in their forms. When diplomacy is impossible, trumpet archons rally the righteous to battle-one reassuring glance from a trumpet archon is often all it takes to instill a shaken ally with resounding courage once again.
