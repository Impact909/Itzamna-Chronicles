---
title: "Cythnigot"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KqaqeiZs8xSVbtw0" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Cythnigot"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cythnigot"
level: "Creature 1"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[fiend]]
trait_02: [[qlippoth]]
trait_03: [[unholy]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Chthonian; Telepathy (Touch Only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Occultism: +7, Stealth: +6"
abilityMods: [1, 3, 4, 2, 2, 1]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +6, __Will__ +5"
hp: 14
health:
  - name: ""
  - name: HP
    desc: "14; __Immunities__  controlled,  fear effects; __Resistances__ mental 3, physical 3 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy (Touch Only)]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+8 (agile, finesse, magical, reach 0 feet, unholy)\n__Damage__  1d10 + 1 piercing plus tangle-spores"

  - name: "Occult Innate Spells"
    desc: "DC 17, attack +9; __4th __ (1 slots) _[[Spells/Read Omens|Read Omens]]_; __2nd __ (1 slots) _[[Spells/Paranoia|Paranoia]]_; __1st __ (1 slots) _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(1st)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Sickening Display"
    desc: "`pf2:1` (concentrate,emotion,fear,mental,occult,visual) The cythnigot presents its awful appearance fully, and creatures in a 10-foot emanation must attempt a DC 17 Will check save. Once a creature attempts this save, it's temporarily immune to further Sickening Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Off-Guard|Off-Guard]] until its next turn.\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 1]] and is off-guard for as long as it's sickened.\n\n**Critical Failure** As failure but [[Conditions/Sickened|Sickened 2]]."

  - name: "Tangle Spores"
    desc: " (disease) A creature bitten by a cythnigot becomes afflicted by fast-growing spores that swiftly grow into twitching spikes and hideous pallid growths of hairlike fibers. These growths erupt from the bite wound and writhe and wrap around the creature's limbs. Plant creatures take a –2 circumstance penalty to save against tangle spores\n\n**Saving Throw** DC 17 Fortitude check;\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** clumsy 1 and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** [[Conditions/Clumsy|Clumsy 2]], off-guard, and if you attempt a manipulate action, you must succeed at a DC 5 Flat check or it's lost; roll the check after spending the action, but before any effects are applied (1 round)."
 
```

```encounter-table
name: Cythnigot
creatures:
  - 1: Cythnigot
```



The cythnigot is a foul fungal parasite that grows and thrives in the corpses of small creatures. It wears these bodies like a suit, but also adjusts and tailors the fleshy covering to fit its needs, and the body ends up looking as alien as anything else spawned from the Chthonian depths. The cythnigot's most identifying feature is the long stalk of fungal material that extends from creature's body, ending in a surprisingly strong set of fanged jaws.

* * *

Long before the creatures known as demons came to be the dominant force in the Outer Rifts, qlippoth ruled the innumerable cracks of the Outer Sphere. These inimical creatures are a form of primordial and alien evil that predates mortal life, and most immortal life as well. Since the rise of mortal sin and the associated expansion of demonic life through the Outer Rifts, qlippoth have been driven to their deepest reaches, and they seethe with rancor at the loss of their realms. Yet, rather than directly oppose demons, qlippoth instead turn to the source—mortal sin—and wage an endless war to eradicate all creatures capable of sinful acts so that the demonic tide might be turned back. To ensure they do not bolster their foe's ranks, they enact horrific transformations on their targets, converting their victims into beings incapable of discerning right from wrong; this renders them unable to be judged by Pharasma's courts and thus incapable of becoming fiends. Most mortals consider the ministrations of a qlippoth to be far worse than any fate awaiting them in the afterlife.
