---
title: Blood of Belcorra
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #163: Ruins of Gauntlight
aliases: "Actor.xkCjeHTakIXyhfVf" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Blood of Belcorra"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 13
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +9, __Will__ +12"
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 5; __Resistances__ physical 5 (except ghost touch)"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A bloody image of Belcorra arises, emits a soul‑draining light, then inhales blood from living creatures in the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Thievery check (trained) to wipe away enough of the bloodstain to disrupt the haunt's necromantic energies, or DC 20 Religion check (trained) to exorcise the haunt"
attacks:
  - name: ""

  - name: "Gauntlight Beam"
    desc: "`pf2:r` (light) **Trigger** A living creature ends its turn in area **A11** at night\n* * *\n\n**Effect** A ghastly image of Belcorra, seemingly composed of fresh blood, rises from the bloodstain on the floor and rotates in place like a lighthouse. Beams of cold blue light shine from Belcorra's eyes and open mouth, causing blisters and decay to spread across flesh. Living creatures within a 30-foot burst from the center of area **A11** must attempt a DC 20 Fortitude check save.\n\nThe haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d8 void damage.\n\n**Failure** The creature takes 1d8+6 void damage and is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Critical Failure** The creature takes 2d8+6 void damage and is [[Conditions/Blinded|Blinded]] for 1 round then dazzled for 1 round."

  - name: "Routine"
    desc: "(1 action) The bloody image opens its mouth and appears to inhale, drawing blood from the body of one creature in its line of sight within 90 feet from the center of area **A11**. The creature targeted must attempt a DC 20 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d10 bleed.\n\n**Failure** The creature takes 1d10+6 bleed damage.\n\n**Critical Failure** The creature takes 2d10+6 bleed damage and is [[Conditions/Enfeebled|Enfeebled 2]] as long as it's bleeding."
  - name: "Reset"
    desc: "If the haunt is disabled or destroyed through damage, the bloody phantom of Belcorra sprays upward in a spiral, dousing the trap door leading to area **A25** before draining upward through the keyhole, which reduces the Thievery DC to [[Actions/Pick a Lock|Pick the Lock]] to DC 20 Thievery check.\n\nAt the next sunrise, the blood drains back down to this room and the haunt resets. The haunt is destroyed permanently once Lasda Venkervale is rescued from area **D9**."
```

```encounter-table
name: Blood of Belcorra
creatures:
  - 1: Blood of Belcorra
```

