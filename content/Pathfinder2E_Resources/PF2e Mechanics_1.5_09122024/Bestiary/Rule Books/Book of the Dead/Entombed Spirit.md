---
title: Entombed Spirit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Book of the Dead
aliases: "Actor.ua3NqyEsV9NaFjKm" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Entombed Spirit"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 11
sourcebook: "_Pathfinder Book of the Dead_"
ac: 15
armorclass:
  - name: AC
    desc: "15; "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 9; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The wall bulges out in the shape of a howling humanoid face as it twists and forms tendrils reaching for nearby creatures. This haunt is formed when a murder victim is entombed within a wall before or after their death."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 17 Occultism check (trained) to weaken the spirit, DC 18 Athletics check (trained) to force the spirit's face back inside the wall, or DC 19 Diplomacy check (trained) to talk down the spirit; two total successes across all skills are required to disable the haunt"
attacks:
  - name: ""

  - name: "Gasp"
    desc: "`pf2:r` (fear, mental, occult) **Trigger** A creature moves adjacent to the wall where the corpse is entombed\n* * *\n\n**Effect** The spirit gasps and wails for aid while the wall takes on the shape of its face and roils, growing tendrils. All creatures within 10 feet must succeed at a DC 18 Will check save or be [[Conditions/Frightened|Frightened 1]] for as long as the haunt remains active. The haunt then rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The spirit attempts to [[Actions/Grapple|Grapple]] up to two creatures within 10 feet with a +14 Athletics modifier, then squeezes each creature it has [[Conditions/Grabbed|Grabbed]], dealing 1d10+4 damage damage. The haunt doesn't apply a multiple attack penalty to the second attempt to Grapple."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all creatures leave the area and resets immediately thereafter. If disabled, the haunt resets after 1 day. The haunt is permanently destroyed if the remains of the deceased are removed from the wall."
```

```encounter-table
name: Entombed Spirit
creatures:
  - 1: Entombed Spirit
```

