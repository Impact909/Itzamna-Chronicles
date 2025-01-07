---
title: "Melodic Squall"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yVQpST5Lcohi8pD4" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Melodic Squall"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Melodic Squall"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[chaotic]]
trait_03: [[elemental]]
trait_04: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "Sussuran, Tengu, Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Performance: +32, Stealth: +32"
abilityMods: [6, 8, 4, 2, 6, 8]
speed:  fly 100 feet
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +24, __Ref__ +32, __Will__ +28"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hostile Duet"
    desc: "`pf2:r` (auditory) **Trigger** A hostile creature within 30 feet creates an effect with the auditory trait that provides bonuses to itself or its allies\n* * *\n\n**Effect** The melodic squall recreates the auditory effect, gaining the bonuses for itself and its allies as long as the original effect persists."

  - name: "Retune"
    desc: "`pf2:r` (auditory) **Trigger** The melodic squall is targeted by a spell with the auditory trait\n* * *\n\n**Effect** The melodic squall attempts to counteract the spell. If it succeeds, the spell effect is caught in a blast of wind that sweeps it back to its origin, affecting the caster. Targets of the triggering effect other than the melody on the wind are still affected normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wind Gust"
    desc: "+32 (agile, finesse)\n__Damage__  3d10 + 14 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Solid Refrain"
    desc: "+32 (range increment 70 feet)\n__Damage__  3d8 + 14 sonic"

  - name: "Mesmerizing Melody"
    desc: "`pf2:1` (auditory,concentrate,mental,primal) The melodic squall sings in a sonorous chorus. Any creature in a 30-foot emanation must attempt a DC 36 Will check save to resist becoming fascinated by the melody on the wind. A creature that succeeds at its save is temporarily immune for 24 hours.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Fascinated|Fascinated]] for 1 round.\n\n**Failure** The creature is fascinated for 1d4 rounds."

  - name: "Subsonic Burst"
    desc: "`pf2:1` (emotion,fear,mental,primal,sonic) The melodic squall focuses intense sound at an inaudible frequency in a 100-foot line. Each creature in the line must attempt a DC 34 Fortitude check save.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Confused|Confused]] until the beginning of the melodic squall's next turn."

  - name: "Swiftness"
    desc: "  The melodic squall's movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Push|Push 10ft]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Melodic Squall
creatures:
  - 1: Melodic Squall
```


Variant melody on the wind

This cloud of song and sound has been caught by the wind and carried across the air. While the melody on the wind might enjoy the beauty of music, it is by nature a destructive elemental force.
