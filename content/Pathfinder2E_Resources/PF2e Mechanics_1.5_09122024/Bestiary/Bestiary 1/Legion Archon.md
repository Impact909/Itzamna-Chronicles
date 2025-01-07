---
title: "Legion Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.j9rFRoTixKKx3eHQ" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Legion Archon"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Legion Archon"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +14, Diplomacy: +16, Intimidation: +16, Religion: +14, Survival: +14"
abilityMods: [5, 2, 4, 1, 2, 5]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +11, __Will__ +15; +1 status to all saves vs. magic"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Weaknesses__ unholy 10; __Resistances__ fire 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Full Plate|Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Menacing Guardian"
    desc: " (aura,divine) 30 feet. Enemies that start their turn in the area or enter it must attempt a DC 23 Will check save.\n\nOn a failure, they take a -1 status penalty to attack rolls, spell rolls, and damage rolls against any other target while in the aura for 24 hours or until they damage the archon, whichever comes first. On a critical failure, they can't use hostile actions against any other target while in the area for 24 hours or until they damage the archon, whichever comes first.\n\nRegardless of the result, a creature is then temporarily immune to further menacing guardian auras for 24 hours."

  - name: "Retributive Strike"
    desc: "`pf2:r`  **Damage Reduction** 9\n\nA legion archon can also make a Retributive Strike by throwing its flame of justice.\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flame Of Justice"
    desc: "+18 (holy, magical, versatile p)\n__Damage__  2d10 + 5 slashing 1d6 spirit"

  - name: "**Ranged** `pf2:1` Flame Of Justice"
    desc: "+15 (holy, magical, range increment 30 feet, versatile p)\n__Damage__  2d10 + 5 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +16; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __  _[[Spells/Sure Strike|True Strike (x3)]]_\n__Cantrips__  __(4th)__ _[[Spells/Light|Light]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast [[Spells/Translocate|Translocate]], it can cast an innate _dimension door_ (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's _dimension door_.\n\nIf the archon's _dimension door_ has enough distance, the archon appears the same distance and direction from the creature as before either used _dimension door_."

  - name: "Flame of Justice"
    desc: " (divine) A legion archon's spirit of righteousness manifests in its hands as a mighty two-handed sword called the flame of justice.\n\nA legion archon can throw its flame of justice as a ranged weapon. If disarmed or thrown, the flame of justice vanishes after landing or dealing damage and reappears in the legion archon's hands again instantly.\n\nOn a critical hit, the fire damage from the flame of justice deals maximum damage (6 on the d6) before being doubled for the critical hit, and the target takes 1d10 persistent fire damage."
 
```

```encounter-table
name: Legion Archon
creatures:
  - 1: Legion Archon
```



Despite their flaming blades and heavy armor, legion archons are the diplomats of peace among the archons, preferring justice via compromise and mutual benefit rather than justice by the sword. Nonetheless, when forced to fight against fiendish powers-especially fiends that embody the sin of wrath-legion archons don't hesitate in battle, mounting offensives under divine commanders like Iomedae.

* * *

Archons are guardians of Heaven and enemies of chaos and evil. They openly fight back the spread of fiends but also quietly nurture the seeds of virtue within mortals, teaching the denizens of the Material Plane how to act with honor and integrity, enact just laws, and cast off sin and temptation.

Archons live in the immense seven-tiered mountain of Heaven. They manifest in the Garden at the mountain's peak from mortal souls who answer a mysterious voice. There they swear to forever serve the cause of justice and transform into their new archon forms. Intensely orderly in their metamorphosis, new archons begin as lantern archons or other lesser forms, transforming into ever-greater archons as their virtue and achievements grow. Each archon represents a particular virtue, such as hope, charity, justice, or courage, and they gain strength in the presence of mortals who exemplify this virtue. Due to their extremely lawful nature, archons sometimes find themselves at odds with azatas.
