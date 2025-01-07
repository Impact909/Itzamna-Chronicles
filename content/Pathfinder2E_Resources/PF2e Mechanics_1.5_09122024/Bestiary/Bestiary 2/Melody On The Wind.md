---
title: "Melody On The Wind"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5B6y55KpBhwA4xU6" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Melody On The Wind"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Melody On The Wind"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Performance: +22, Stealth: +22"
abilityMods: [4, 6, 2, 2, 5, 6]
speed:  fly 100 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +16, __Ref__ +22, __Will__ +19"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hostile Duet"
    desc: "`pf2:r` (auditory) **Trigger** A hostile creature within 30 feet creates an effect with the auditory trait that provides bonuses to itself or its allies\n* * *\n\n**Effect** The melody on the wind recreates the auditory effect, gaining the bonuses for itself and its allies as long as the original effect persists."

  - name: "Retune"
    desc: "`pf2:r` (auditory) **Trigger** The melody on the wind is targeted by a spell with the auditory trait\n* * *\n\n**Effect** The melody on the wind attempts to counteract the spell. If it succeeds, the spell effect is caught in a blast of wind that sweeps it back to its origin, affecting the caster. Targets of the triggering effect other than the melody on the wind are still affected normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wind Gust"
    desc: "+23 (agile, finesse)\n__Damage__  2d10 + 10 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Solid Refrain"
    desc: "+23 (range increment 70 feet)\n__Damage__  2d8 + 10 sonic"

  - name: "Mesmerizing Melody"
    desc: "`pf2:1` (auditory,concentrate,mental,primal) The melody on the wind sings in a sonorous chorus. Any creature in a 30-foot emanation must attempt a DC 30 Will check save to resist becoming fascinated by the melody on the wind. A creature that succeeds at its save is temporarily immune for 24 hours.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Fascinated|Fascinated]] for 1 round.\n\n**Failure** The creature is fascinated for 1d4 rounds."

  - name: "Swiftness"
    desc: "  The melody on the wind's movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Melody On The Wind
creatures:
  - 1: Melody On The Wind
```



This cloud of song and sound has been caught by the wind and carried across the air. While the melody on the wind might enjoy the beauty of music, it is by nature a destructive elemental force.
