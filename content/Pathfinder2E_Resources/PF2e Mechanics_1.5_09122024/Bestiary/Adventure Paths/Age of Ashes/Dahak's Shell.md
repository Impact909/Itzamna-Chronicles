---
title: Dahak's Shell
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #146: Cult of Cinders
aliases: "Actor.v0DvGXzWrI8UyzOG" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Dahak's Shell"
level: "Hazard 12"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 0
sourcebook: "_Pathfinder #146: Cult of Cinders_"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "or [[Spells/Detect Magic|Detect Magic]]"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A ring of eight dragon pillar replicas mark the border of a dome of magical prismatic energy that entirely contains the Fortress of Sorrow."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Each dragon pillar that is destroyed removes the corresponding color's effect from Dahak's shell; as long as even one color remains active, the pillars marking the shell's border cannot be damaged themselves, but a successful DC 32 Thievery check (master) check or a successful [[Spells/Dispel Magic|Dispel Magic]] (6th level; counteract DC 30) against one of the eight pillars can cause a randomly determined active color in the shell defense (below) to become deactivated for 1d4 rounds."
attacks:
  - name: ""
  - name: "Melee"
    desc: "Eye Beam +20 (range 120 feet) The target suffers an effect corresponding to the eye beam's color. On a critical hit, the target's save result is one degree worse."

  - name: "Prismatic Beam"
    desc: "`pf2:r` (divine, light) **Trigger** a creature attempts and fails to disable one of the shell colors via Thievery or [[Spells/Dispel Magic|Dispel Magic]]\n* * *\n\n**Effect** Dahak's shell Strikes the triggering creature with a random eye beam. Roll 1d8 to determine the color:\n\n1.  Red\n2.  Orange\n3.  Yellow\n4.  Green\n5.  Blue\n6.  Indigo\n7.  Violet\n8.  Black"

  - name: "Shell Defense"
    desc: "passive (divine, light) When a creature physically passes through the shell, the creature is affected simultaneously by all colors of energy currently active in the shell; apply these effects in the following order: red, orange, yellow, green, blue, indigo, violet, black. These effects are the same as that of the eye beams. Each effect requires its own save."

  - name: "Black Eye Beam"
    desc: "passive (divine, incapacitation, light) DC 32 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Failure** The target is blinded for 1 hour.\n\n**Critical Failure** The target is blinded for 24 hours."

  - name: "Blue Eye Beam"
    desc: "passive (divine, incapacitation, light) DC 32 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Petrified|Petrified]] for 1 round.\n\n**Failure** The target is petrified for 1 hour.\n\n**Critical Failure** The target is petrified permanently."

  - name: "Green Eye Beam"
    desc: "passive (divine, light, poison) 6d6 poison damage (DC 32 Reflex check save)."

  - name: "Indigo Eye Beam"
    desc: "passive (incapacitation, light) DC 32 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The target is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The target is controlled by the dragon pillar and remains within 60 feet of it at all times, defending the dragon pillar from all non-Cinderclaws. While a target is controlled, it is treated as a Cinderclaw ally by the dragon pillar. The dragon pillar can control up to 3 targets at a time; any targets in excess who critically fail this saving throw are instead confused for 1d4+1 rounds. A controlled creature can attempt a new Will save once every 24 hours to escape control, but doing so automatically causes the dragon pillar to attack it with a new eye beam to attempt to re-establish control. The control ends if the pillar is destroyed."

  - name: "Yellow Eye Beam"
    desc: "passive (divine, electricity, light) 6d6 electricity damage (DC 32 Reflex check save)."

  - name: "Orange Eye Beam"
    desc: "passive (acid, divine, light) 6d6 acid damage (DC 32 Reflex check save)."

  - name: "Red Eye Beam"
    desc: "passive (divine, fire, light) 6d6 fire damage (DC 32 Reflex check save)."

  - name: "Violet Eye Beam"
    desc: "passive (divine, incapacitation, light) DC 32 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The target is [[Conditions/Stunned|Stunned 3]].\n\n**Critical Failure** The target is [[Conditions/Stunned|Stunned 7]]."



```

```encounter-table
name: Dahak's Shell
creatures:
  - 1: Dahak's Shell
```

