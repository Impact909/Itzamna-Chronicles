---
title: The Putrid Rise
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.MGJHqD9Ks1Ozl4w8" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "The Putrid Rise"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 28
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
perception:
  - name: ""
  - name: "Stealth DC 28" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The stink of bile suddenly grows as the myriad mouths carved into the walls begin to vomit forth a deluge of acidic slurry."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) to disrupt the trap's magical network of sensors and effectively \"blind\" it to targets to react to, DC 38 Religion check (master) to recognize the carvings and recall one of the mantras needed to pass safely, or [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 32) to counteract the trap."
attacks:
  - name: ""

  - name: "Vomit"
    desc: "`pf2:r` **Trigger** The trap's sensors notice a creature on the stairs north of the entrance to area **D4**\n* * *\n\n**Effect** The myriad mouths on the walls spew out a foul-smelling acidic slurry along the entire stairwell. The stairs in areas **D3** become difficult terrain, and all creatures in area **D3** must attempt a DC 34 Reflex check saving throw. A creature that is [[Conditions/Fatigued|Fatigued]] by hunger takes a -2 circumstance penalty to this saving throw. The trap then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d6 acid damage and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes 8d6 acid damage, is [[Conditions/Sickened|Sickened 2]], and is knocked [[Conditions/Prone|Prone]].\n\n**Critical Failure** The creature takes 16d6 acid damage, is [[Conditions/Sickened|Sickened 3]], is knocked prone, and then tumbles down the stairs. The fall ends once the creature reaches the next lowest landing (note that a creature falling at the lowest flight tumbles into the carrion pit at area **D2**, but can attempt to [[Actions/Grab an Edge|Grab an Edge]] as detailed in that room). A creature that falls down the steps takes an additional 4d6 bludgeoning damage (DC 32 Reflex check) from the tumble, regardless of the total distance traveled."

  - name: "Routine"
    desc: "On its turn, the trap Vomits as its action. As long as the Putrid Rise is active, the stairs in area **D3** are difficult terrain."
  - name: "Reset"
    desc: "The trap deactivates 1 round after no targets can be sensed, but resets immediately."
```

```encounter-table
name: The Putrid Rise
creatures:
  - 1: The Putrid Rise
```

