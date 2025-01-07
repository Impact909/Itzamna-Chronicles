---
title: "Phoenix"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0sYhViQDTxaFHLek" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Phoenix"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Phoenix"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[fire]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, See the Unseen"
languages: "Common, Empyrean, Pyric, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +27, Diplomacy: +31, Intimidation: +27, Nature: +25"
abilityMods: [6, 7, 5, 7, 6, 6]
speed: 25 feet,  fly 70 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +31, __Will__ +28; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, regeneration 20 (deactivated by cold or unholy), self-resurrection; __Immunities__  fire; __Weaknesses__ cold 10, unholy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold or Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Self-Resurrection"
    desc: " (healing,primal) When a phoenix dies, they collapse into a pile of smoldering ashes before returning to life fully healed 1d4 rounds later, as if subject to a 7th-rank [[Spells/Resurrect|Resurrect]] ritual. Self-resurrection happens only if there are some remains to resurrect; for instance, a phoenix killed by a [[Spells/Disintegrate|Disintegrate]] spell can't use this ability.\n\nA phoenix whose remains rest within an area devoted to an unholy deity by [[Spells/Consecrate|Consecrate]] can't self-resurrect until their remains are no longer in that area. A phoenix can self-resurrect only once per year."

  - name: "Shroud of Flame"
    desc: " (aura,fire,primal) 20 feet. 4d6 fire, DC 37 Reflex check save.\n\nWhile this aura is active, any adjacent creature that hits the phoenix with a melee attack or otherwise touches them takes 2d6 fire damage. The phoenix can activate or deactivate the aura with a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+30 (finesse, fire, magical, reach 20 feet)\n__Damage__  1d12 + 9 piercing 3d8 fire 2d10 fire"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+30 (agile, finesse, fire, magical, reach 20 feet)\n__Damage__  1d6 + 6 piercing 3d8 fire 2d10 fire"

  - name: "**Ranged** `pf2:1` Flame Jet"
    desc: "+30 (fire, range increment 40 feet)\n__Damage__  6d6 fire 2d10 fire"

  - name: "Primal Innate Spells"
    desc: "DC 39, attack +31; __8th __  _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Dispel Magic|Dispel Magic (x3)]]_, _[[Spells/Divine Immolation|Divine Immolation]]_, _[[Spells/Everlight|Everlight (At Will)]]_, _[[Spells/Heal|Heal (x3)]]_, _[[Spells/Wall of Fire|Wall of Fire (x3)]]_; __7th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_; __6th __  _[[Spells/Cleanse Affliction|Cleanse Affliction (x3)]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_\n__Constant__  __(6th)__ _[[Spells/See the Unseen|See the Unseen]]_"

  - name: "Flaming Strafe"
    desc: "`pf2:1` (fire,primal) The phoenix blazes with superheated flame and Flies up to their Speed. They deal 6d6 fire damage to each creature within 20 feet of each square they move through (DC 37 Reflex check save)."
 
```

```encounter-table
name: Phoenix
creatures:
  - 1: Phoenix
```



The phoenix is a primordial bird made of heat and flame that dwells in the most inhospitable regions of the desert. Though highly intelligent and brimming with compassion, the phoenix is best-known for its iconic ability to resurrect itself when slain, emerging reborn from the ashes of its own corpse. Phoenixes are often sought out for their knowledge or healing abilities, as they cannot abide the sight of suffering and deny their succor only to the most foul and irredeemable of creatures.

Phoenixes enjoy the company of metallic dragons, and when the two dwell in close proximity, they can forge lifelong friendships, sharing their resources and words of wisdom while keeping each other updated on regional news.

While most phoenixes are benevolent, they are not infallible. When a phoenix loses its way or falls under the influence of evil, it still retains its strong appetite for knowledge. Evil phoenixes are known to assault universities and libraries in their pursuit for power-not only to gain new information, but also to set fire to the texts and thus hoard that knowledge for themselves.
