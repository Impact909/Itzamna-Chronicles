---
title: "Titanosaur"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2WbpPjQqgxEYngjz" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Titanosaur"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Titanosaur"
level: "Creature 16"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +34"
abilityMods: [10, 4, 9, -4, 5, 6]
speed: 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +33, __Ref__ +28, __Will__ +29"
hp: 370
health:
  - name: ""
  - name: HP
    desc: "370"
abilities_top:
  - name: ""

  - name: "Majestic Presence"
    desc: " (aura,emotion,visual) 90 feet. Creatures of Huge size or smaller that enter the aura must attempt a DC 38 Will check save. Regardless of the result of the saving throw, the creature is temporarily immune to the titanosaur's Majestic Presence for 1 hour.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Fascinated|Fascinated]] by the titanosaur for 1 round.\n\n**Failure** The creature is fascinated for 2 rounds.\n\n**Critical Failure** The creature is fascinated for 1 minute."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (reach 30 feet)\n__Damage__  3d8 + 16 bludgeoning plus improved-knockdown"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+32 (reach 15 feet)\n__Damage__  3d12 + 16 bludgeoning"

  - name: "Seismic Slam"
    desc: "`pf2:2`  **Frequency** once per minute\n* * *\n\n**Effect** The titanosaur rears up on its hind legs before slamming its forelegs back on the ground with a thunderous crash, creating a localized tremor with the effects of an [[Spells/Earthquake|Earthquake]] spell centered on itself, though the effect is non-magical. Fissures do not form under the titanosaur."

  - name: "Sweeping Tail"
    desc: "`pf2:2`  The titanosaur lashes its tail in a 30-foot cone. Creatures in the area take 8d10 bludgeoning damage (DC 38 Reflex check save). The momentum of the titanosaur's swing then makes it [[Conditions/Off-Guard|Off-Guard]] until the beginning of its next turn."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 38 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Titanosaur
creatures:
  - 1: Titanosaur
```



Titanosaurs are some of the largest land animals ever to walk the surface of Golarion, massive sauropods that can reach over 100 feet in length and weigh more than 80 tons. While typically content to focus on consuming vast quantities of vegetation and ignore the presence of smaller creatures, titanosaurs that feel threatened can unleash destruction rivaling natural disasters.
