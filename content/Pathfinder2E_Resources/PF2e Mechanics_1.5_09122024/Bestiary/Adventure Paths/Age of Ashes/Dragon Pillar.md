---
title: Dragon Pillar
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #146: Cult of Cinders
aliases: "Actor.YVKnchGkd56JZx6L" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Dragon Pillar"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 0
sourcebook: "_Pathfinder #146: Cult of Cinders_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +8, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56; __Hardness__ 14; __Immunities__  object immunities,  critical hits,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 0" 
    desc: "or [[Spells/Detect Magic|Detect Magic]]"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 10-foot-tall wooden pole topped by a wooden carving of Dahak's head. Each dragon pillar's head has been treated with something to give it a distinct color, as indicated in the specific encounter, but regardless of color, plumes of smoke waft up from the mouth."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Athletics check (expert) to push the pillar over, or DC 26 Thievery check (expert) on the pillar to erase the magic runes that power it, or [[Spells/Dispel Magic|Dispel Magic]] (4th level; counteract DC 22) to dispel the pillar's magic."
attacks:
  - name: ""

  - name: "Recognize Ally"
    desc: "passive A dragon pillar can see through its empty eye sockets, and it can recognize Cinderclaws and their allies. A character disguised as a Cinderclaw can trick a dragon pillar into perceiving it as a Cinderclaw ally by using Deception to [[Actions/Impersonate|Impersonate]]. A dragon pillar always uses Perception for initiative."

  - name: "Perception and Vision"
    desc: "passive **Perception** +16, [[Bestiary Ability Glossary/Darkvision|Darkvision]] 60 feet"

  - name: "Dragon Pillar Glance"
    desc: "`pf2:r` **Trigger** The dragon pillar sees a creature within 120 feet who isn't a recognized Cinderclaw or Cinderclaw ally.\n* * *\n\n**Effect** The dragon pillar makes an eye beam Strike against the triggering creature, then rolls initiative."

  - name: "Black Eye Beam"
    desc: "passive (divine, incapacitation) DC 24 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Failure** The target is blinded for 1 hour.\n\n**Critical Failure** The target is blinded for 24 hours."
  - name: "Melee"
    desc: "Eye Beam +20 (divine, range 120 feet) **Effect** The target is subjected to an effect determined by the pillar's color and summarized in the passive actions. On a critical hit, the target's save result is one degree worse."

  - name: "Blue Eye Beam"
    desc: "passive (divine, incapacitation) DC 24 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Petrified|Petrified]] for 1 round.\n\n**Failure** The target is petrified for 1 hour.\n\n**Critical Failure** The target is petrified permanently."

  - name: "Green Eye Beam"
    desc: "passive (divine, poison) 6d6 poison damage (DC 24 Reflex check save.)"

  - name: "Indigo Eye Beam"
    desc: "passive (incapacitation) DC 24 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The target is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The target is controlled by the dragon pillar and remains within 60 feet of it at all times, defending the dragon pillar from all non-Cinderclaws. While a target is controlled, it is treated as a Cinderclaw ally by the dragon pillar. The dragon pillar can control up to 3 targets at a time; any targets in excess who critically fail this saving throw are instead confused for 1d4+1 rounds. A controlled creature can attempt a new Will save once every 24 hours to escape control, but doing so automatically causes the dragon pillar to attack it with a new eye beam to attempt to re-establish control. The control ends if the pillar is destroyed."

  - name: "Yellow Eye Beam"
    desc: "passive (divine, electricity) 6d6 electricity damage (DC 24 Reflex check save.)"

  - name: "Orange Eye Beam"
    desc: "passive (acid, divine) 6d6 acid damage (DC 24 Reflex check save.)"

  - name: "Red Eye Beam"
    desc: "passive (divine, fire) 6d6 fire damage (DC 24 Reflex check save.)"

  - name: "Violet Eye Beam"
    desc: "passive (divine, incapacitation) DC 24 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The target is [[Conditions/Stunned|Stunned 3]].\n\n**Critical Failure** The target is [[Conditions/Stunned|Stunned 7]]."

  - name: "Routine"
    desc: "(1 action) On its initiative, the dragon pillar fires an eye beam at the closest target within 120 feet."
  - name: "Reset"
    desc: "The dragon pillar deactivates and resets as soon as it perceives no appropriate targets in range."
```

```encounter-table
name: Dragon Pillar
creatures:
  - 1: Dragon Pillar
```

