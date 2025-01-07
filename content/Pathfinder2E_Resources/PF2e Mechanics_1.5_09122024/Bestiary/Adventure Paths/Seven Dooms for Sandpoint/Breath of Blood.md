---
title: Breath of Blood
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.37G0eVrNi0UE3SYB" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Breath of Blood"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 19
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A churning pool of blood bubbles and seethes, periodically venting noxious vapors into the air."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three DC 33 Nature check or DC 33 Occultism check checks to draw from the blood its magical nature, causing it to clot and become inert, a DC 36 Religion check check to offer prayers to sever the sacred link to Kabriri, or [[Spells/Dispel Magic|Dispel Magic]] (6th rank; counteract DC 29) to render the hazard inert for 10 minutes"
attacks:
  - name: ""

  - name: "Vent Toxins"
    desc: "`pf2:r` (divine, poison) **Trigger** A creature moves into the room beyond the northern stairs\n* * *\n\n**Effect** The blood on the floor bubbles vigorously, and as the bubbles burst, waves of toxic gas vent up around the triggering creature. The creature must attempt a DC 30 Fortitude check save unless they are holding their breath or don't need to breathe; the hazard then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Sickened|Sickened 1]] by the foul smelling gas.\n\n**Failure** As success, but the creature also becomes [[Conditions/Enfeebled|Enfeebled 1]] by the poison gas.\n\n**Critical Failure** As failure, but the creature becomes [[Conditions/Enfeebled|Enfeebled 2]]."

  - name: "Routine"
    desc: "(2 actions) The bubbles furiously sputter and burst on the hazard's first action, filling the air with toxic vapor that inflicts 6d6 poison damage (DC 30 Fortitude check save) to all creatures in area **J3b**. A creature that's holding its breath gains a +4 circumstance bonus to this save. On the hazard's second action, the bubbles Vent Toxins at a random target in area **J3b**."
  - name: "Reset"
    desc: "The hazard settles back down 1 round after all creatures leave the room and can trigger again at the start of the next round."
```

```encounter-table
name: Breath of Blood
creatures:
  - 1: Breath of Blood
```

