---
title: "Leng Envoy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MpgqZ5NpRlpBswZt" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dream
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Leng Envoy"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Leng Envoy"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[dream]]
trait_04: [[evil]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision"
languages: "Aklo; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +29, Deception: +35, Intimidation: +32, Occultism: +35, Stealth: +32, Thievery: +30, Sailing Lore: +38"
abilityMods: [5, 6, 5, 9, 5, 6]
speed: 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +27, __Ref__ +30, __Will__ +33"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, planar fast healing 15; __Immunities__  cold; __Resistances__ critical hits 20, precision 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Kukri|+2 Greater Striking Keen Kukri]], [[Equipment/Musical Instrument (Handheld)|Pipes]], 4x Leng Ruby"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Planar Fast Healing]]"
    desc: "  A denizen of Leng maintains a connection to Leng at all times, and when away from Leng, they have fast healing 15. They lose this ability on Leng or in areas where planar connections do not function. If killed, their body dissolves into nothingness in 1d4 rounds, leaving behind their equipment. A slain denizen reforms in Leng; they can be permanently killed only when their planar fast healing doesn't function.\n* * *\n\nA monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "No Breath"
    desc: "  The Leng envoy doesn't need to breathe."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Kukri"
    desc: "+34 (agile, finesse, magical, trip)\n__Damage__  3d6 + 13 slashing 3d6 bleed"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (agile, finesse)\n__Damage__  3d10 + 13 piercing plus debilitating-bite"

  - name: "Occult Innate Spells"
    desc: "DC 40, attack +34; __9th __  _[[Spells/Phantom Pain|Phantom Pain]]_, _[[Spells/Truespeech|Tongues (Tongues)]]_, _[[Spells/Unfathomable Song|Unfathomable Song]]_; __8th __  _[[Spells/Suggestion|Suggestion]]_, _[[Spells/Uncontrollable Dance|Uncontrollable Dance]]_; __7th __  _[[Spells/Warp Mind|Warp Mind]]_; __5th __  _[[Spells/Locate|Locate]]_, _[[Spells/Mind Probe|Mind Probe]]_; __4th __  _[[Spells/Outcast's Curse|Outcast's Curse]]_; __3rd __  _[[Spells/Hypnotize|Hypnotic Pattern]]_, _[[Spells/Levitate|Levitate]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image]]_\n__Cantrips__  __(9th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Debilitating Bite"
    desc: " (curse,occult) A creature that takes damage from a denizen's bite must succeed at a DC 40 Fortitude check save or become [[Conditions/Clumsy|Clumsy 1]]. Each time a target fails an additional save against this ability, the condition value increases by 1 (to a maximum of Clumsy 4). This condition value decreases by 1 every 24 hours."

  - name: "Leng Ruby"
    desc: " (occult) Many denizens of Leng carry strange rubies mined from quarries in Leng. As long as a creature holds a Leng ruby that it willingly accepted as a gift or payment from a denizen of Leng, any denizen of Leng can target that creature with [[Spells/Mind Reading|Mind Reading]], [[Spells/Outcast's Curse|Outcast's Curse]], [[Spells/Phantom Pain|Phantom Pain]], or [[Spells/Warp Mind|Warp Mind]] at a range of 1 mile, and the bearer uses an outcome one degree of success worse than the result of its saving throw against _Outcast's Curse_."

  - name: "Play the Pipes"
    desc: "`pf2:3` (auditory,primal) **Frequency** once per day\n\n**Requirements** The Leng envoy is holding a musical instrument\n* * *\n\n**Effect** The envoy plays a melody on its instrument to cast [[Spells/Uncontrollable Dance|Uncontrollable Dance]], [[Spells/Unfathomable Song|Unfathomable Song]], or [[Spells/Warp Mind|Warp Mind]] without expending the spell slot and using his music in place of providing the spell's component actions. The spell gains the auditory trait and targets all creatures in a 60-foot emanation instead of its usual targets. A creature that succeeds at its Will save against any spell is then temporarily immune from all spells played from the envoy's pipes for 1 minute. Aberrations are immune to this music."
 
```

```encounter-table
name: Leng Envoy
creatures:
  - 1: Leng Envoy
```


Variant denizen of Leng

Slavers and raiders from the cold, windswept dimension of Leng, these malevolent humanoids range across reality in ominous black ships capable of sailing beyond the borders of dimensions and planes. Although most denizens of Leng seek slaves and plunder like any pirate, others operate as self-styled ambassadors and merchants, sowing discord with far-ranging plots. While the inscrutable denizens dress themselves in flowing robes, veils, and broad turbans to appear human, their aberrant physiology, when glimpsed, is evident from their crown of stubby horns and tentacled jaws to their furry, goat-like legs.

Above the fierce captains who command the infamous black ships are an even higher caste of denizens of Leng. These cultists and musicians serve as high priests, laboring to appease the frightening gods who look down upon the Nightmare Realm with cold malice.
