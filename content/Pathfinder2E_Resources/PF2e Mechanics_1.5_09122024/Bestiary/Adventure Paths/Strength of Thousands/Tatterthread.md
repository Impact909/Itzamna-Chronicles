---
title: "Tatterthread"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.x4oNrCT0MaooGWyJ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Tatterthread"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Tatterthread"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fey]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Greater Darkvision, Lifesense 120 Feet, Truesight"
languages: "Common, Jotun; tongues"
skills:
  - name: "Skills"
    desc: "Deception: +35, Intimidation: +37, Occultism: +38, Religion: +32, Stealth: +36, Thievery: +34, Lore (all): +32"
abilityMods: [7, 6, 7, 10, 6, 7]
speed: 35 feet,  fly 35 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +35, __Ref__ +30, __Will__ +36; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400, regeneration 15 (deactivated by cold iron); __Immunities__  off-guard,  void; __Weaknesses__ cold iron 20; __Resistances__ acid 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Deny Fate"
    desc: " (misfortune) When Tatterthread rolls initiative, enemies she can see within 120 feet that are also rolling initiative automatically roll a 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Caustic Shears"
    desc: "+38 (deadly 2d12, magical, reach 10 feet, versatile p)\n__Damage__  4d6 + 15 slashing plus shadow-corrosion 5d6 acid plus shadow-corrosion"

  - name: "**Melee** `pf2:1` Acid Stream"
    desc: "+38 (agile, magical, reach 10 feet)\n__Damage__  4d10 + 15 acid plus shadow-corrosion"

  - name: "Occult Innate Spells"
    desc: "DC 42, attack +32; __10th __ (7 slots) _[[Spells/Shadow Blast|Shadow Blast (Acid Only)]]_, _[[Spells/Shadow Siphon|Shadow Siphon]]_, _[[Spells/Freeze Time|Time Stop]]_; __9th __ (2 slots) _[[Spells/Power Word Kill|Power Word Kill]]_, _[[Spells/Weird|Weird]]_; __8th __ (2 slots) _[[Spells/Quandary|Maze]]_, _[[Spells/Migration|Wind Walk]]_; __7th __ (3 slots) _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Read Omens|Read Omens (At Will)]]_, _[[Spells/Spellwrack|Spellwrack (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(10th)__ _[[Spells/Hidden Mind|Mind Blank]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Geas_, _Legend Lore_"

  - name: "Fated"
    desc: "  When a creature is subject to a fortune effect from a norn and a misfortune effect from any source other than a norn (or vice versa), the norn's effect automatically counteracts the other effect and then takes place normally, rather than the two effects canceling each other out. If both the fortune and misfortune effect are from a norn, then the two cancel each other out as normal. At the GM's discretion, powerful entities related to fate or luck, like Desna, Magdh, or Pharasma, count as a norn for the purpose of this ability."

  - name: "Shadow Corrosion"
    desc: " (acid,occult) When Tatterthread deals acid damage with a Strike, she regains 10 healing Hit Points. The target must succeed at a DC 39 Fortitude check save or become [[Conditions/Doomed|Doomed 1]] ([[Conditions/Doomed|Doomed 2]] on a critical failure)."

  - name: "Shadow Snip"
    desc: "`pf2:2` (acid,death,manipulate,occult) **Frequency** three times per day\n* * *\n\n**Effect** Tatterthread produces a scrap of shadow linked to the fate of a creature within 100 feet of her, then snips it with her caustic shears. The target takes 100 acid damage (DC 42 Fortitude check). If the target is reduced to 0 Hit Points from this damage, it melts into a puddle of fetid acid and dies immediately. If the target failed the saving throw, it loses any acid resistance it has for 1 minute (1 day on a critical failure). A creature slain by Shadow Snip can't be restored to life except by miracle, wish, or similarly powerful magic, or by divine intervention. Regardless of the outcome of its save, a creature targeted by Shadow Snip becomes temporarily immune for 24 hours. The norn can't use Shadow Snip again for 1d4 rounds."

  - name: "Shift Fate"
    desc: "`pf2:r` (occult) **Trigger** A creature within 120 feet attempts a saving throw\n* * *\n\n**Effect** The creature rolls the save twice, and then Tatterthread decides which result applies. If she chooses the lower roll, this is a misfortune effect; if she chooses the higher roll, it's a fortune effect; if they're the same, she decides which trait to apply."
 
```

```encounter-table
name: Tatterthread
creatures:
  - 1: Tatterthread
```


Variant norn


