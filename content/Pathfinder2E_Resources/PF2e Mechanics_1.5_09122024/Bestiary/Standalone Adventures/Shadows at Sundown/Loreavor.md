---
title: "Loreavor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.chdQzr1k0Hi15LjX" 
tags:
  - pf2e/creature/type/astral
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Loreavor"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Shadows at Sundown"
name: "Loreavor"
level: "Creature 9"
rare_03: [[Rare]]
alignment: ""
size: "Small"
trait_01: [[astral]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Thoughtsense (Imprecise) 60 Feet"
languages: "Common; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Arcana: +17, Occultism: +21, Society: +17, Stealth: +19"
abilityMods: [3, 6, 4, 6, 4, 3]
speed: 20 feet,  fly 20 feet
sourcebook: "_Pathfinder Adventure: Shadows at Sundown_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +15, __Ref__ +21, __Will__ +19"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Resistances__ mental 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Thoughtsense|Thoughtsense (Imprecise) 60 feet]]"
    desc: "  Thoughtsense allows a monster to sense all non-mindless creatures at the listed range."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Reconstruct Spell"
    desc: "`pf2:r` (mental,occult) **Trigger** A creature within 30 feet attempts and fails to [[Actions/Cast a Spell|Cast a Spell]] while stupefied\n* * *\n\n**Effect** The loreavor gains use of the failed spell as an occult innate spell. It can cast that spell once; if the spell is of a higher level than half the loreavor's level (5th level or higher for most loreavors), the loreavor must succeed at a flat check with a DC equal to 5 + the rank of the spell it is attempting to cast; on a failure, the spell fails, and the loreavor becomes [[Conditions/Stupefied|Stupefied 1]] for 1 minute. If the spell isn't cast within 24 hours, or if the loreavor uses Reconstruct Spell again before casting the spell, the spell is lost. No more than one loreavor can reconstruct a given spell this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Touch"
    desc: "+19 (agile, finesse)\n__Damage__  2d10 + 7 mental plus search-memory"

  - name: "**Ranged** `pf2:1` Mind Bolt"
    desc: "+21 (range 60 feet)\n__Damage__  2d12 + 4 mental"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __4th __  _[[Spells/Rewrite Memory|Modify Memory (AT Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Telekinetic Hand|Mage Hand]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Redact"
    desc: " (occult) By spending an hour in contact with a non-magical document or piece of artwork no larger than 1 Bulk, a loreavor can consume either a few words from the text or render the artistry of the work more mundane. Doing so heals the loreavor of 4d8 HP. Words fade from the text, leaving an obvious blank space behind, while artwork is reduced in worth by 10% of its original value. A loreavor can consume incidental text in this manner from a spellbook but cannot consume actual spells recorded in the book. The loreavor can't use Redact for 24 hours."

  - name: "Search Memory"
    desc: " (mental,occult) When the loreavor damages a creature with its touch Strike, the creature must succeed at a DC 28 Will check save or become [[Conditions/Stupefied|Stupefied 1]], or [[Conditions/Stupefied|Stupefied 2]] on a critical failure."
 
```

```encounter-table
name: Loreavor
creatures:
  - 1: Loreavor
```



Rarely, when an ioton leeches a particularly secretive thought, it can choke to death on the secret, only to be born from its previous body into that of a loreavor: an ennosite whose existence is shaped around the consumption of secrets and artistry.

Loreavors sip at secrets throughout their lives and are instinctively drawn to obscure information. Their hunger places them firmly at odds with scholars and historians alike. Living victims lose memories; written texts become blank books. Loreavors' favorite sites are ruins and ancient libraries, but they can also survive on banal secrets of everyday life as well. While the creatures are secretive, typically staying out of sight and fleeing danger, they become aggressive when their favored food sources are threatened.

A loreavor appears as a 3-foot-long, pale, wormlike creature with dozens of half-formed faces growing from its segmented body. Trapped in an area without secrets to eat, a loreavor won't starve and can live for years.
