---
title: Endless Elven Aging
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #149: Against the Scarlet Triad
aliases: "Actor.YCZ8Bynvgh1dsmbf" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Endless Elven Aging"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[haunt]]
trait_02: [[magical]]
modifier: 33
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30, per square (6 squares must be destroyed to disable the haunt); __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A haunted mural fascinates characters and swiftly drains their vitality."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 38 Occultism check (master) or DC 38 Religion check (master) to calm the restless energies and suppress the haunt for 1 hour; a critical success deactivates the haunt permanently."
attacks:
  - name: ""

  - name: "Lifelike Scintillation"
    desc: "`pf2:r` (occult) **Trigger** A living creature examines the mural or enters the room\n* * *\n\n**Effect** The haunt activates and rolls initiative."

  - name: "Captivate"
    desc: "action (incapacitation, mental, occult) The faintly moving images compel one creature within 30 feet of the room to move into the room. The creature attempts a DC 38 Will check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target must spend all its actions on its next turn moving into the room, and is then [[Conditions/Paralyzed|Paralyzed]] until the end of its next turn.\n\n**Critical Failure** As failure, and the target is also [[Conditions/Stupefied|Stupefied 2]] for 1 minute."

  - name: "Live a Thousand Lives"
    desc: "action (mental, occult) The haunt causes a living creature in the room to experience a full elven life, weathering every wound, misfortune, loss, and consequence of aging centuries in a matter of seconds. The target must attempt a DC 38 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target becomes [[Conditions/Fatigued|Fatigued]].\n\n**Failure** The target becomes [[Conditions/Drained|Drained 1]] (or its drained value increases by 1, to a maximum of drained 3), and it is [[Conditions/Paralyzed|Paralyzed]] until the end of its next turn.\n\n**Critical Failure** As failure, but the target also becomes [[Conditions/Doomed|Doomed 1]] (or its doomed value increases by 1)."

  - name: "Routine"
    desc: "(2 actions) The haunt lures creatures into area A2 using Captivate. Any actions it hasn't used to Captivate are used to drain a living creature in the room with Live a Thousand Lives."
  - name: "Reset"
    desc: "The haunt continues its routine until there are no targets within 30 feet of the room. It then resets over the course of 1 minute and is able to activate again."
```

```encounter-table
name: Endless Elven Aging
creatures:
  - 1: Endless Elven Aging
```

