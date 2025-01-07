---
title: Shoanti Ancestor Storm
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - haunt
  - occult
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #208: Hoof, Cinder, and Storm
aliases: "Actor.6rUiK83za6vb2o7O" 
level: 8
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Shoanti Ancestor Storm"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[haunt]]
trait_03: [[occult]]
modifier: 12
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
perception:
  - name: ""
  - name: "Stealth DC 12" 
    desc: "(trained) to notice the smoke intensifying and filling with the tortured faces of lost souls"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Smoke and fire explode up around the boundaries of the storm, accusatory screams and threats of violence echoing over the winds and crackling of flames. Broken weapons and shields litter the ground and Shoanti warriors emerge from the smoke, blood running down their faces as they prepare for battle."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Occultism check to redirect the anger of the haunt back onto itself, DC 28 Intimidation check to goad the Shadefield spirits into attacking someone outside of the ritual circle, or DC 28 Religion check to assuage the spirits in the area. Four successes are needed to disable the haunt long enough for the ritual to be completed."
attacks:
  - name: ""

  - name: "Ancestors' Wrath"
    desc: "`pf2:r` (mental, occult, spirit) **Trigger** The ritual begins\n* * *\n\n**Effect** The ancestor storm howls in fury and pain. This deals 2d10+11 spirit damage to all non-Shoanti creatures in the area, who must attempt a DC 28 Fortitude check save. The haunt then rolls initiative."

  - name: "Calling the Blood"
    desc: "action (auditory, mental) The ancestor storm randomly chooses a Shoanti ritualist to distract. The ritualist must attempt a DC 26 Will check save or become [[Conditions/Fascinated|Fascinated]] by the voices of their ancestors for 1 round, increasing the DCs to Disable the haunt by 2 for the duration."
  - name: "Melee"
    desc: "Arrows of Rage +20 (fire, magical, occult, range increment 60 feet) "

  - name: "Arrows of Rage"
    desc: "action The hazard makes an arrows of rage Strike against all non-Shoanti creatures within 60 feet of the cairn."

  - name: "Routine"
    desc: "(4 actions) The ancestor storm uses 1 action to release a pulse of void energy, restoring 10 healing Hit Points to each Shadefield spirit in the area, before using its next 2 actions to make an arrows of rage Strike against all non-Shoanti creatures within 60 feet of the cairn. The haunt then uses its 4th action to use Calling the Blood on one random leader participating in the ritual. The haunt loses an action for each Shadefield spirit killed, and when there are no Shadefield spirits remaining, the haunt uses its next action to summon a new Shadefield spirit into the battle."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all creatures leave the Shadefields but resets immediately. The haunt is only permanently disabled when Diskah Night Watcher is put to rest. Otherwise, the haunt reforms within 24 hours of being Disabled."
```

```encounter-table
name: Shoanti Ancestor Storm
creatures:
  - 1: Shoanti Ancestor Storm
```

