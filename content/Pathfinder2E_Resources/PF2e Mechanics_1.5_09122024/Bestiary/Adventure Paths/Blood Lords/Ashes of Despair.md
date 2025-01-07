---
title: Ashes of Despair
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #185: A Taste of Ashes
aliases: "Actor.cLHqbuxxVDmhEbuU" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Ashes of Despair"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 39
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
perception:
  - name: ""
  - name: "Stealth DC 39" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Swirling ashes fill the room and form into the semblance of a massive predatory bird that swoops upon those in the chamber, draining their life force away."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 44 Occultism check (master) to disrupt and counteract the shadow magic animating the ashes, or DC 42 Religion check (master) to exorcise the animating spirit. Disabling the trap requires three successful checks, in any combination of Occultism and Religion checks."
attacks:
  - name: ""

  - name: "Shriek of Despair"
    desc: "`pf2:r` **Trigger** Two or more creatures enter area **F9**\n* * *\n\n**Effect** A terrifying shriek of pain and suffering deals 3d12+40 mental damage to each creature within area **F9**, and each creature must attempt a DC 42 Will check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature takes no damage and is [[Conditions/Frightened|Frightened 1]].\n\n**Success** The creature takes half damage and is frightened 1.\n\n**Failure** The creature takes full damage and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature takes double damage, is frightened 2, and [[Conditions/Doomed|Doomed 1]]."

  - name: "Routine"
    desc: "(1 action) The shadowy shape sends streams of scouring ash toward the mouth, eyes, and nose of each creature in the room, dealing 3d12+20 slashing damage and requiring a DC 42 Fortitude check save. Creatures that don't need breathe can't be sickened by the haunt and creatures that don't see can't be [[Conditions/Blinded|Blinded]] by it.\n* * *\n\n**Critical Success** The creature takes no damage and is blinded for 1 round.\n\n**Success** The creature takes half damage, is blinded for 1 round, and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes full damage, is blinded for 1 minute, and is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature takes full damage, is blinded for 1 minute, is sickened 2, and is unable to use any spells or abilities with the verbal trait while it is sickened."
  - name: "Reset"
    desc: "The haunt resets immediately when there are no creatures in area **F9**. Any previous successes from attempts to Disable the haunt persist when it's later triggered. After three successes, the haunt doesn't reset."
```

```encounter-table
name: Ashes of Despair
creatures:
  - 1: Ashes of Despair
```

