---
title: "Sphinx"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UcyycONQSD1zVpl3" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Sphinx"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sphinx"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, See the Unseen"
languages: "Common, Draconic, Sphinx; Truespeech"
skills:
  - name: "Skills"
    desc: "Arcana: +17, Athletics: +18, Deception: +16, Diplomacy: +16, Intimidation: +18, Occultism: +17, Bardic Lore: +19"
abilityMods: [6, 1, 3, 5, 4, 4]
speed: 35 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +14, __Will__ +19"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""

  - name: "Bardic Lore"
    desc: "  Sphinxes are naturally curious, and their love of puzzles and mysteries leads them to gather information on a broad range of topics. Sphinxes have Bardic Lore, a special Lore skill that can be used only to Recall Knowledge, but on any topic."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d6 + 9 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 27, attack +19; __4th __  _[[Spells/Clairaudience|Clairaudience (At Will)]]_, _[[Spells/Clairvoyance|Clairvoyance (At Will)]]_, _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Read Omens|Read Omens]]_; __3rd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Locate|Locate]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_ __(2nd)__ _[[Spells/See the Unseen|See the Unseen]]_"

  - name: "Claw Rake"
    desc: "`pf2:3`  The sphinx rears back on their hind legs and makes two claw Strikes at the same target, using the same attack bonus as their highest melee attack. If both attacks deal damage, the target takes extra damage equal to one claw Strike."

  - name: "Pounce"
    desc: "`pf2:1`  The sphinx Strides and makes a Strike at the end of that movement. If the sphinx began this action [[Conditions/Hidden|Hidden]], they remain hidden until after the attack."

  - name: "Riddler's Rune"
    desc: "  Once per week, a Sphinx can create a magical symbol as the [[Spells/Rune Trap|Rune Trap]] ritual. The sphinx usually shapes it to take the form of a written riddle and sets the password to the answer.\n\nA creature that gives the wrong answer or tries to pass without answering must succeed at a DC 26 Will check save or be affected by one of the following spells, chosen by the sphinx when creating the symbol: [[Spells/Synaptic Pulse|Synaptic Pulse]] (5th), [[Spells/Charm|Charm]] (4th), [[Spells/Fear|Fear]] (4th), [[Spells/Phantom Pain|Phantom Pain]] (4th), [[Spells/Sleep|Sleep]] (4th). The sphinx learns the identity of any creature that answers the riddle and tends to be friendly to them if they answered correctly."
 
```

```encounter-table
name: Sphinx
creatures:
  - 1: Sphinx
```



Sphinxes are mystical beings with the body of a lion, the wings of a great bird, and the upper torso and head of a human. They are often maligned in legends as nothing more than monsters, and though they are quick to anger and are capable of exacting deadly retribution for perceived slights, they are also very intelligent.

Sphinxes are often associated with desert regions, but they can dwell in more moderate climates as well. They form small groups consisting of a single, extended family that hunts and works together to protect and teach their young. As they mature, sphinxes develop a wanderlust, a drive to gather hidden lore and solve the world's greatest riddles-the trait that is perhaps most often identified with their kind.

While sometimes bound into service as guardians for powerful spellcasters, lone sphinxes may also be encountered on journeys of discovery and as purveyors of esoteric lore. If treated with the proper respect-and fed well-a sphinx can demonstrate a willingness to exchange information. Their favorite currency is, of course, riddles and secrets. One who can trade knowledge for knowledge has a much better chance of succeeding while bargaining with a sphinx. However, a sphinx's insatiable thirst for new riddles as well their extensive collection of secrets accumulated over hundreds of years of life-makes it difficult to offer them something they don't already know. Those who attempt to trade petty insight and stale riddles may invoke a sphinx's ire and will not live long enough to regret it.
