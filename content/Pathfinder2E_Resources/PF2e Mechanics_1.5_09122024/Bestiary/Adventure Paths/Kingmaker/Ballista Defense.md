---
title: Ballista Defense
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.LEDUOFTtS1qP4sDa" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Ballista Defense"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[mechanical]]
modifier: 23
sourcebook: "_Pathfinder Kingmaker_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +18, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A ballista armed with a massive bolt fires on a creature approaching the Palace."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 36 Thievery check (master) to sabotage the ballista by reaching through the firing slit from outside (this DC is reduced by 10 if the PCs are in the room with the ballista, DC 26 Thievery check), or DC 33 Intimidation check to frighten off the Pitax Warden operating the ballista."
attacks:
  - name: ""

  - name: "Ready and Load"
    desc: "`pf2:r` **Trigger** The alarm is raised while the PCs are approaching the Palace\n* * *\n\n**Effect** The guards ready and load the ballista. The ballista defense then rolls Initiative."
  - name: "Melee"
    desc: "Ballista Bolt +24 (range 300 feet) "

  - name: "Routine"
    desc: "(3 actions) The ballista takes 1 action to fire a ballista bolt and 2 actions to reload. After ten rounds, the ballista is out of ammunition and can no longer function."
  - name: "Reset"
    desc: "(1 day) If the PCs haven't reached 30 Liberation Points, additional ammunition for a ballista can be secured in a day, but if the PCs have reached 30 Liberation Points, a ballista that runs out of ammo cannot be reset."
```

```encounter-table
name: Ballista Defense
creatures:
  - 1: Ballista Defense
```

