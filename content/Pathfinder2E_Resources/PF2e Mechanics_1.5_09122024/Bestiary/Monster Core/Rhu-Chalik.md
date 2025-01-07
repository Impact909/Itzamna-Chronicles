---
title: "Rhu-Chalik"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rhaNG6J9D1TR9YeF" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Rhu-Chalik"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Rhu-Chalik"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[aberration]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Greater Darkvision, Tremorsense (Precise) 60 Feet"
languages: "Aklo; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Deception: +13, Diplomacy: +13, Intimidation: +13, Stealth: +15"
abilityMods: [3, 3, 4, 2, 5, 3]
speed: 5 feet,  fly 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23 all-around vision; __Fort__ +14, __Ref__ +11, __Will__ +17"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Thoughtsense 60 feet"
    desc: "  The rhu-chalik senses a creature's mental essence as a precise sense with the listed range; it cannot sense mindless creatures with thoughtsense."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "No Breath"
    desc: "  A rhu-chalik doesn't breathe and is immune to effects that require breathing (such as inhaled poisons)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+15 (agile)\n__Damage__  2d4 + 6 bludgeoning plus excruciating-enzyme 1d6 mental plus excruciating-enzyme"

  - name: "Occult Innate Spells"
    desc: "DC 24, attack +16; __5th __  _[[Spells/Mind Probe|Mind Probe]]_; __4th __  _[[Spells/Rewrite Memory|Rewrite Memory]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_"

  - name: "Excruciating Enzyme"
    desc: " (occult,poison) A rhu-chalik's tendrils secrete an enzyme that causes intense pain. A living creature hit by a tendril Strike must succeed at a DC 24 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] from the pain."

  - name: "Label Memories"
    desc: "`pf2:2` (mental,occult) The rhu-chalik invades the mind of a target within 100 feet, sorting the memories into alien structures for transmission. The target must attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The target creature is unaffected and temporarily immune to Label Memories for 1 minute.\n\n**Success** The target is unaffected.\n\n**Failure** The target becomes [[Conditions/Stupefied|Stupefied 2]] for 1 minute as its mind is reorganized to fit the rhu-chalik's needs. If it's already stupefied by this effect, the target instead becomes [[Conditions/Confused|Confused]] for 1 minute or until it recovers due to taking damage.\n\n**Critical Failure** As failure, but if the target is already stupefied by Label Memories, they become [[Conditions/Paralyzed|Paralyzed]] for 1 minute instead of confused."

  - name: "Transmit Memories"
    desc: "`pf2:3` (concentrate,mental,occult) **Requirements** The rhu-chalik is adjacent to a creature [[Conditions/Paralyzed|Paralyzed]] due to Label Memories\n* * *\n\n**Effect** The rhu-chalik copies the creature's consciousness and mentally sends this copied consciousness through the void of space to their waiting masters. The target creature is deeply disoriented by this procedure, becoming [[Conditions/Stupefied|Stupefied 2]] for 1 day afterward."
 
```

```encounter-table
name: Rhu-Chalik
creatures:
  - 1: Rhu-Chalik
```



Also called void wanderers, rhu-chaliks can survive the depths of space indefinitely, passing between worlds over the eons and scouting those planets for the Dominion of the Black. Rhu-chaliks prefer to work alone in order to reduce potential overlap in their mental predations, but sometimes receive assistance from those who believe the transmission of memories is transcendent. The furtive beings are calculating and infinitely patient, seeking only the most exceptional minds to cast beyond the stars to their masters.

* * *

The Dominion of the Black is a conglomeration of deep-space conquerors with a strong presence on Aucturn, the most remote planet in Golarion's solar system. The Dominion has secret outposts all over Golarion; most of its members on the planet are scouts, using their skills to steal brains and identities, gathering information without any consideration for the inhabitants of the worlds they infiltrate.
