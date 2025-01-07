---
title: Paralyzing Light Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #164: Hands of the Devil
aliases: "Actor.bT9nvhoxtwY6fw5e" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Paralyzing Light Trap"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #164: Hands of the Devil_"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "When any creature other than a devil enters the light, the magic interwoven in the light holds the creature in place and rings an alarm."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (master) to distort or diffuse the light, keeping the light cone intact but preventing the trap from triggering, or [[Spells/Dispel Magic|Dispel Magic]] (4th level; counteract DC 26) to dispel the light, leaving the room in darkness"
attacks:
  - name: ""

  - name: "Stasis Field"
    desc: "`pf2:r` (incapacitation, mental, occult) **Trigger** A non-devil creature moves into the light\n* * *\n\n**Effect** The light expands to fill the room, and each nondevil creature within the room must attempt a DC 26 Will check save. A high-pitched chime sounds in the barracks (area **D15**), audible in this room as well. The trap then rolls initiative.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Stunned|Stunned 2]].\n\n**Failure** The target is [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\n**Critical Failure** The target is [[Conditions/Stupefied|Stupefied 2]] for 1d4 rounds and paralyzed for 1 round."

  - name: "Routine"
    desc: "(1 action) All [[Conditions/Stunned|Stunned]] and [[Conditions/Paralyzed|Paralyzed]] creatures in the room take 1d10 mental damage (DC 26 Will check save). Creatures who fail also become paralyzed for 1 round but can use a reaction to mentally fight off this stasis; creatures who do so take 5d10 mental damage mental damage but are no longer paralyzed."
  - name: "Reset"
    desc: "The stasis magic in the light builds up over the course of an hour, after which the trap can trigger again."
```

```encounter-table
name: Paralyzing Light Trap
creatures:
  - 1: Paralyzing Light Trap
```

