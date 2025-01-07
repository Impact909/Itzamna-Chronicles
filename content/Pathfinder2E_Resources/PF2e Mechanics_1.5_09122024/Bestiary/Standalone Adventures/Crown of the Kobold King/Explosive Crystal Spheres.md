---
title: Explosive Crystal Spheres
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Crown of the Kobold King
aliases: "Actor.MQFtq4E6tjcR7o3v" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Explosive Crystal Spheres"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 5
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +11, __Ref__ +17, "
hp: 54
health:
  - name: ""
  - name: "HP"
    desc: "54, BT 27; __Hardness__ 13; __Immunities__  object immunities,  critical hits,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 5" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Shimmering, glyph-graven, two-foot-diameter crystalline spheres shimmer and condense in the air, launching with explosive force at intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Thievery check (expert) to locate and deface tiny activation runes located at one of the six locations that spawn crystal spheres, or DC 28 Arcana check (expert) or DC 28 Occultism check (expert) to manipulate the magical energy at one of those locations to render the spheres inert, or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 22) to counteract one of the crystal sphere spawn points"
attacks:
  - name: ""

  - name: "Manifest Crystal Sphere"
    desc: "`pf2:r` **Trigger** Three or more creatures remain in the Outer Ring for 6 seconds or longer;\n\n**Effect** Six spheres of crystal, each measuring 2 feet in diameter, manifest from thin air and begin quickly floating toward intruders. A sphere manifests at each of the points on the map indicated with a small numeral (labeled 1 through 6); the trap then rolls initiative."

  - name: "Routine"
    desc: "(6 actions) On each of the trap's actions, a crystal sphere that hasn't yet taken an action during the turn either flies 25 feet toward the closest creature in the Outer Ring (if no creature is within 25 feet), or it attacks a visible creature within 25 feet (the crystal spheres can sense targets via darkvision). If a crystal sphere attacks a target, that target takes 1d6 force damage (DC 24 Reflex check) as the sphere hits them and bursts. A creature can be attacked by multiple spheres in a turn, but a sphere always targets the closest target. Once a sphere attacks and bursts, it vanishes but respawns at its spawn point at the start of the next turn and continues its routine. A sphere that has been destroyed or had its spawn point disabled vanishes and doesn't continue to respawn and attack, and the trap loses 1 action for each sphere destroyed or disabled in this way."

```

```encounter-table
name: Explosive Crystal Spheres
creatures:
  - 1: Explosive Crystal Spheres
```

