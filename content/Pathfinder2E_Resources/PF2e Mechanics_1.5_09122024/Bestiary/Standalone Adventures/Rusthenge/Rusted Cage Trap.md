---
title: Rusted Cage Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: Rusthenge
aliases: "Actor.MZmfD4o5KvNYcNQC" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Rusted Cage Trap"
level: "Hazard 1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +4, "
hp: 24
health:
  - name: ""
  - name: "HP"
    desc: "24; __Hardness__ 5; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: " +7"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A rusty cage embedded in the ceiling drops down with a clang to try to entrap a creature that steps onto the pressure plate in the middle of the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 13 Thievery check to harmlessly trigger the trap by nudging the pressure plate, DC 20 Thievery check to stabilize the pressure plate so it doesn't trigger, or DC 20 Athletics check to [[Actions/Escape|Escape]] from the cage or [[Actions/Force Open|Force Open]] the cage once it falls"
attacks:
  - name: ""

  - name: "Slam Down"
    desc: "`pf2:r` **Trigger** A creature walks under the cage and steps on the pressure plate\n* * *\n\n**Effect** The cage drops from the ceiling to trap the triggering creature, who must attempt a DC 17 Reflex check save.\n* * *\n\n**Critical Success** The creature avoids the trap, and returns to the space it just left rather than entering the trap's space.\n\n**Success** As Critical Success, but the falling trap delivers a glancing blow and 1d6+3 bludgeoning damage to the creature as it stumbles back.\n\n**Failure** The falling trap lands on the triggering creature. A Medium or smaller creature becomes trapped inside the cage ([[Actions/Escape|Escape]] DC 20). A Large or larger creature takes 2d6+5 bludgeoning damage and is knocked [[Conditions/Prone|Prone]] as the cage bounces off the creature's body, becoming destroyed in the process.\n\n**Critical Failure** As Failure, but a Medium or smaller creature is also struck by the cage, knocked prone, and then takes 2d6+5 bludgeoning damage and is [[Conditions/Immobilized|Immobilized]] by the cage as it lands on a limb."


  - name: "Reset"
    desc: "The mechanism to manually reset this trap is located in area **D15**."
```

```encounter-table
name: Rusted Cage Trap
creatures:
  - 1: Rusted Cage Trap
```

