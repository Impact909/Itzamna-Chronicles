---
title: Promise of Plagues
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.TqSP4Pz1ixeSpiA3" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Promise of Plagues"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 19
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +18, __Ref__ +26, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Immunities__  precision; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ bludgeoning 14, slashing 7, piercing 14"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Clouds of buzzing flies and a carpet of vermin fill a room strewn with decaying pieces of cast-off body parts and gobbets of rancid meat."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three DC 33 Arcana check or DC 33 Nature check checks to command the vermin to be silent or to cleanse away the filth and decay to make the hazard harmless, a DC 36 Religion check check to offer prayers to sever the sacred link to Kabriri, or [[Spells/Dispel Magic|Dispel Magic]] (6th rank; counteract DC 29) to render the hazard inert for 10 minutes"
attacks:
  - name: ""

  - name: "Swarming Bites"
    desc: "`pf2:r` **Trigger** A creature moves into the room beyond the northern stairs\n* * *\n\n**Effect** A combination of biting flies and ravenous creepy-crawlies swarm the triggering creature. The creature takes 6d6 piercing damage (DC 30 Reflex check save). If the creature took any damage, it's automatically exposed to ghast fever. The hazard then rolls initiative."

  - name: "Ghast Fever"
    desc: "passive (disease) **Saving Throw** DC 30 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "Routine"
    desc: "(2 actions) The clouds of vermin in the room fill the air, rain down from the walls and ceiling, and swarm up from the floor below. All creatures in the room are subjected to Swarming Bites on the hazard's first action. On the second action, the swarming vermin grow particularly dense and eager in their attentions to one randomly determined creature in area **J3c**. If that creature is suffering from ghast fever and is at stage 4 or lower, they must immediately attempt a DC 30 Fortitude check save. On a failure, the stage of their ghast fever advances one step."
  - name: "Reset"
    desc: "The hazard settles back down 1 round after all creatures leave the room and can trigger again at the start of the next round."
```

```encounter-table
name: Promise of Plagues
creatures:
  - 1: Promise of Plagues
```

