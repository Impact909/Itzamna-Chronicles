---
title: Etward's Nightmare
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #189: Dreamers of the Nameless Spires
aliases: "Actor.onn0tksQlTf9OjHL" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #189: Dreamers of the Nameless Spires"
name: "Etward's Nightmare"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 30
sourcebook: "_Pathfinder #189: Dreamers of the Nameless Spires_"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The incense burners begin to smoke, filling the air with strangely nostalgic scents."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Occultism check (expert) to enter a state akin to lucid dreaming so as to unweave the nightmare from within, or DC 30 Intimidation check (master) to stand resolute against the nightmares and turn the fear back upon itself"
attacks:
  - name: ""

  - name: "Light Incense Burners"
    desc: "`pf2:r` (incapacitation, mental, occult, sleep) **Trigger** A creature lies down on the bed, or a living creature spends more than 3 rounds inside this room\n* * *\n\n**Effect** Incense swiftly fills the room (even if the incense burners have been removed or were destroyed). All creatures in area **A12** must attempt a DC 32 Fortitude check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]] by the incense's scent.\n\n**Failure** The creature falls [[Conditions/Unconscious|Unconscious]]. If it's still unconscious after 1 minute, it wakes up automatically.\n\n**Critical Failure** As failure, but if it's still unconscious after 1 hour, it wakes up automatically."

  - name: "Routine"
    desc: "(2 actions; cold, enchantment, mental, occult) The haunt uses its first action to light incense burners again, forcing any creature that isn't already [[Conditions/Unconscious|Unconscious]] to save against that effect once more. Its second action is to cause any unconscious creatures in the room to experience horrific, vivid dreams about being lost in the arctic during a blizzard, while enormous furred figures— saumen kar—lunge at them through the snow to attack repeatedly. Each unconscious creature must attempt a DC 28 Fortitude check saving throw. If at the end of the round there are no unconscious creatures in the room, Etward's nightmare ends and the trap deactivates.\n* * *\n\n**Critical Success** The creature is unaffected and wakes up.\n\n**Success** The creature remains unconscious and takes 1d10 cold and 1d10 mental. This damage does not wake the creature, and those who are awake can see the unconscious creature thrash as if in the throes of a nightmare while their body rimes over with layers of frost. The creature can fight against the bitter cold and monstrous shapes by attempting a DC 28 Will check save as a three-action activity on its turn— on a success, the creature wakes up.\n\n**Failure** As success, but 1d10+6 cold and 1d10+6 mental, and with a DC 32 Will check save to wake up.\n\n**Critical Failure** The creature remains unconscious and takes 2d10+12 cold and 2d10+12 mental."
  - name: "Reset"
    desc: "The hazard resets when Etward dreams in this room."
```

```encounter-table
name: Etward's Nightmare
creatures:
  - 1: Etward's Nightmare
```

