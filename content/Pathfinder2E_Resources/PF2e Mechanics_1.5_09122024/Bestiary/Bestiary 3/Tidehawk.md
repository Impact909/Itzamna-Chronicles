---
title: "Tidehawk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5R2TKUnBpOoN2hhd" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Tidehawk"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Tidehawk"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[beast]]
trait_03: [[water]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision, Wavesense (Imprecise) 120 Feet"
languages: "Common, Sussuran, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +21, Nature: +24"
abilityMods: [5, 7, 5, 4, 6, 4]
speed: 25 feet,  fly 50 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +21, __Ref__ +25, __Will__ +22"
hp: 213
health:
  - name: ""
  - name: HP
    desc: "213, regeneration 20 (deactivated by fire), self-resurrection; __Weaknesses__ fire 15; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 120 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Self-Resurrection"
    desc: " (healing,primal) When a tidehawk dies, it melts into a torrent of rainwater. If this rain falls into a body of water, such as an ocean or lake, the tidehawk returns to life fully healed 1d4 rounds later, as if subject to a 6th-rank [[Spells/Resurrect|Resurrect]] ritual. Self-resurrection happens only if there are remains to resurrect; for instance, a tidehawk killed by a [[Spells/Disintegrate|Disintegrate]] spell can't use this ability. A tidehawk that dies while above land must wait until its rainwater runs or seeps into an appropriate body of water to self-resurrect. A tidehawk can self-resurrect only once per year."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+26 (finesse, magical, reach 15 feet)\n__Damage__  3d12 + 11 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+26 (agile, finesse, magical, reach 15 feet)\n__Damage__  3d8 + 11 slashing"

  - name: "**Ranged** `pf2:1` Break Swell"
    desc: "+26 (range increment 30 feet)\n__Damage__  3d8 + 11 bludgeoning plus knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Control Water|Control Water]]_, _[[Spells/Heal|Heal (x2)]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Oceanic Armor"
    desc: "`pf2:1` (primal,water) **Requirements** The tidehawk is within 120 feet of a body of water at least as large as it is\n* * *\n\n**Effect** The tidehawk draws water to itself, wrapping its feathers like a suit of armor. The tidehawk gains a +2 circumstance bonus to AC until the start of its next turn. If the tidehawk takes damage from a melee Strike while under this effect, this water armor explodes outward, dealing 4d8 bludgeoning damage (DC 32 Reflex check save) to the attacking creature and ending the circumstance bonus to AC.\n\n[[Bestiary Effects/Effect_ Oceanic Armor|Effect: Oceanic Armor]]"

  - name: "Typhoon Dive"
    desc: "`pf2:2` (primal,water) **Requirements** The tidehawk is Flying\n* * *\n\n**Effect** The tidehawk Flies up to its Speed, diving below the surface of deep water (such as a sea or ocean), causing a surging wave that deals 6d6 bludgeoning damage (DC 32 Reflex check save) to each creature within a 60-foot emanation of where the tidehawk entered the water. The area becomes difficult terrain until the start of the tidehawk's next turn while the water surges and runs off."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Tidehawk
creatures:
  - 1: Tidehawk
```



Tidehawks, avian embodiments of the sea and rain, nest in deep underwater crevasses and glide among waves. They feed mostly on large sea life and rise above the surface during or in the aftermath of a rainstorm to bask in the fresh moisture of the air.

Though tidehawks hail from the same mystical family as the legendary phoenix, the two rarely interact due to their different outlooks and elemental affiliations. Phoenixes see tidehawks as flighty and unreliable, while tidehawks view their fiery kin as self-righteous do-gooders who can't resist meddling in mortal affairs. Only particularly evil threats to natural environments can bring them together.
