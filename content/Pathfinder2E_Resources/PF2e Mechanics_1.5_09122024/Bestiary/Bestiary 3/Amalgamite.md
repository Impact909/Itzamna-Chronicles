---
title: "Amalgamite"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.n63Y7U7ED0ASsg9c" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Amalgamite"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Amalgamite"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Low-Light Vision"
languages: "Aklo, Common, Draconic"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Athletics: +22, Occultism: +27, Lore (Any One Subcategory): +27"
abilityMods: [5, 6, 4, 8, 6, -1]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +22, __Ref__ +22, __Will__ +26"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, Regeneration 10 (deactivated by piercing); __Immunities__  controlled,  mental; __Weaknesses__ piercing 10; __Resistances__ bludgeoning 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Piercing)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Destabilizing Field"
    desc: " (aura) 40 feet. A creature that begins its turn within the area feels its body begin to stretch and must succeed at a DC 33 Fortitude check save or become destabilized.\n\nA destabilized creature emits a 10-foot destabilizing field aura and becomes [[Conditions/Sickened|Sickened 1]]. The destabilization ends when the creature is no longer sickened.\n\nA creature that succeeds at its saving throw against the aura is temporarily immune to all destabilizing fields for 1 minute."

  - name: "Displace"
    desc: "`pf2:r`  **Trigger** The amalgamite is hit by a Strike.\n* * *\n\n**Effect** The amalgamite Repositions itself or Transposes itself with another creature. If the amalgamite successfully changes its location, it and any Transposed creature take half damage from the triggering Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Limb"
    desc: "+24 ()\n__Damage__  3d10 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Warping Ray"
    desc: "+27 (deadly 2d8, magical, range 100 feet)\n__Damage__  3d8 + 8 force"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Ethereal Jaunt|Ethereal Jaunt]]_, _[[Spells/Warp Mind|Warp Mind]]_; __4th __  _[[Spells/Flicker|Blink (x2)]]_"

  - name: "Reposition"
    desc: "`pf2:2` (concentrate,occult,teleportation) The amalgamite teleports into an unoccupied space it can see within 50 feet."

  - name: "Transpose"
    desc: "`pf2:2` (occult,teleportation) The amalgamite chooses up to two destabilized creatures they can see within 50 feet and swaps their positions, or moves a single such creature to an unoccupied space they can see within range. If the amalgamite chooses two creatures, they can choose their self as one of these creatures, but both targets must be the same size.\n\nAn unwilling creature can attempt a DC 33 Will check save. If either target succeeds at this saving throw, both are unaffected."
 
```

```encounter-table
name: Amalgamite
creatures:
  - 1: Amalgamite
```



Teleportation magic can prove a difficult undertaking, even for experienced spellcasters. It requires precise calculation and timing, knowledge of the intended destination, and meticulous control over surging conjuration magics. A mistake in even the most minute element of such a spell can lead to disastrous results for those involved. When a particularly powerful spellcaster makes an error of this kind, either through arrogance or simple misjudgment, they might transform into an amalgamite.

A mass of flesh and misaligned limbs, an amalgamite is the warped body of a former spellcaster, sometimes joined with another version of itself to incorporate additional limbs or other irregularities. They're still alive, but they have become aberrants mentally and physically, with only the vaguest memories of their previous existence, which makes them a dangerous and bewildering foe. Their weird, warped anatomy constantly shifts and regrows, allowing the creatures to shrug off physical blows save those that pierce through its flesh and into its core being.

The magical residue of an amalgamite's creation radiates from it, seeping into and destabilizing any living beings that get too close. Infected creatures then further spread the amalgamite's aura among larger groups of allies and foes alike. The amalgamite uses this power to manipulate and confuse their enemies, whom they can teleport into traps, force into confrontations with other enemies, or draw close into striking range with their own odd appendages.
