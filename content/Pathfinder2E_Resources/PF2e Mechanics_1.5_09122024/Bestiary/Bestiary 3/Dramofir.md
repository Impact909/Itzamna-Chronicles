---
title: "Dramofir"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IVbftvps8gxdLVIc" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/dream
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Dramofir"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Dramofir"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[dream]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Greater Darkvision"
languages: "telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Diplomacy: +27, Occultism: +21, Stealth: +28, Dreamlands Lore: +23"
abilityMods: [3, 6, 4, 1, 8, 7]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +22, __Ref__ +26, __Will__ +30"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  sleep; __Weaknesses__ slashing 10; __Resistances__ critical hits 10, precision 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Surreal Anatomy"
    desc: "  A dramofir has resistance 10 to precision damage and the extra damage from critical hits. If the resistance is greater than the extra damage, it reduces the extra damage to 0 but doesn't reduce the attack's normal damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Needle"
    desc: "+27 (agile, finesse, reach 10 feet)\n__Damage__  3d6 + 9 piercing 2d6 mental"

  - name: "**Ranged** `pf2:1` Needle"
    desc: "+27 (agile, thrown 20 ft.)\n__Damage__  3d6 + 9 piercing 2d6 mental"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +28; __8th __  _[[Spells/Dream Council|Dream Council]]_; __7th __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Mask of Terror|Mask of Terror]]_, _[[Spells/Nightmare|Nightmare]]_, _[[Spells/Sleep|Sleep]]_, _[[Spells/Soothe|Soothe (x2)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Bittersweet Dreams"
    desc: "`pf2:2` (emotion,mental,occult,visual) The dramofir swishes their robes in a mesmerizing display that brings the dreams in the robes to life before the viewer's very eyes. Each creature within 30 feet must attempt a DC 34 Will check save or be filled with ennui.\n* * *\n\n**Critical Success** The creature is unaffected and temporarily immune for 24 hours.\n\n**Success** For 1 round, the creature takes a -1 status penalty to attack rolls, saving throws, and skill checks, and all other emotion effects on it are suppressed.\n\n**Failure** As success, but the creature is also [[Conditions/Slowed|Slowed 1]] and the duration is 1d4 rounds.\n\n**Critical Failure** As success, but the creature is also slowed 1, the status penalty is -2, and the duration is 1 minute.\n\n[[Bestiary Effects/Effect_ Bittersweet Dreams|Effect: Bittersweet Dreams]]"

  - name: "Pluck Dream"
    desc: "`pf2:3` (mental,occult) **Requirements** The dramofir is adjacent to an [[Conditions/Unconscious|Unconscious]] or sleeping creature\n* * *\n\n**Effect** The dramofir licks the creature's forehead, places their hand in the same spot, and siphons the creature's dreams to incorporate into their robes.\n\nIf the target is affected by any mental effect altering their dreams, such as an [[Bestiary 2/Animate Dream|Animate Dream's]] curse of endless nightmares or a [[Spells/Nightmare|Nightmare]] spell, the dramofir attempts to counteract that effect (counteract modifier +26). Otherwise, the dramofir plucks a benign dream from the creature, and the target must attempt a DC 36 Will check save.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Stupefied|Stupefied 1]] until the next time it gets a full night's rest.\n\n**Critical Failure** As failure, but [[Conditions/Stupefied|Stupefied 2]], and the dramofir casts a 6th-rank [[Spells/Rewrite Memory|Rewrite Memory]] spell on the target."
 
```

```encounter-table
name: Dramofir
creatures:
  - 1: Dramofir
```



Beings of inscrutable intent and incredible power, dramofirs hail from the Dreamlands and shamble across the multiverse in search of dreams to incorporate into their voluminous robes. Few people on the Material Plane dare trifle with dramofirs and instead treat them with respect, hoping that they'll simply take their chosen victims' dreams and then go away. Often, this is exactly what happens. Every now and then, however, in the process of siphoning an individual's dreams, the dramofir slays their victim without warning or apparent cause.
