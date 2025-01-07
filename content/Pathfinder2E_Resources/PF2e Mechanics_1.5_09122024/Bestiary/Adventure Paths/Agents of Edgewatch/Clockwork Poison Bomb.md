---
title: Clockwork Poison Bomb
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - alchemical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #159: All or Nothing
aliases: "Actor.pVe2HDtiSaZsz9Qn" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Clockwork Poison Bomb"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[alchemical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 0
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +24, __Ref__ +26, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20, to ruin the nozzle (making it impossible to disable, in which case the only way to disarm the bomb is to destroy both its tanks); &lt;strong&gt;Tank Hardness&lt;/strong&gt; 15; &lt;strong&gt;Tank HP&lt;/strong&gt; 80 (BT 40) to destroy one of the tanks (both tanks must be destroyed to disarm the bomb; __Hardness__ 5; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 0" 
    desc: "The bomb uses Oggvurm's initiative roll as its Stealth roll"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A clockwork bomb releases gouts of poisonous smoke. The smoke issues forth from a single nozzle attached to two tanks of pressurized poison"
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three DC 31 Thievery check (expert) checks to [[Actions/Disable a Device|Disable a Device]] to disable the latches that lock the nozzle in place, then one DC 35 Thievery check (master) check to Disable a Device to turn off the nozzle; DCs decrease by 2 if Oggvurm is immobilized, paralyzed, unconscious, or dead"
attacks:
  - name: ""

  - name: "Poisonous Cloud"
    desc: "`pf2:r` (alchemical, poison) **Trigger** The bomb is Activated, which requires 3 actions\n* * *\n\n**Effect** The bomb releases a smoky cloud of [[Equipment/Blackfinger Blight|Blackfinger Blight]] in a 20-foot radius. Creatures within the smoke are [[Conditions/Concealed|Concealed]] from other creatures.\n\nAny creature that starts its turn in the smoke must roll a DC 32 Fortitude check saving throw to avoid being afflicted by blackfinger blight poison.\n\nThe cloud remains for 1 minute or until dispersed by strong winds."

  - name: "Routine"
    desc: "(1 action) On its turn, the bomb spews forth a smoky gout of airborne [[Equipment/Blackfinger Blight|Blackfinger Blight]] poison. The cloud fills a 20-foot radius, or a 10-foot radius if only one tank remains intact. If the bomb is already in the center of a blackfinger blight cloud, the radius of that cloud increases by 20 feet (or 10 feet, if only one tank remains intact) instead."
  - name: "Reset"
    desc: "The trap issues smoke for 3 minutes before its tanks run dry. The tanks must be replaced before the bomb can be reactivated."
```

```encounter-table
name: Clockwork Poison Bomb
creatures:
  - 1: Clockwork Poison Bomb
```

