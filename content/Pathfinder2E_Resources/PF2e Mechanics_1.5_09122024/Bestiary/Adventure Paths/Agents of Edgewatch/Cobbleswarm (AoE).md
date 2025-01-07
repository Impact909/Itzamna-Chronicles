---
title: "Cobbleswarm (AoE)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.056M638iv6r3BhEA" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/earth
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Cobbleswarm (AoE)"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Cobbleswarm (AoE)"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[earth]]
trait_03: [[swarm]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Tremorsense (Precise) 40 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +13"
abilityMods: [1, 4, 2, -3, 3, 0]
speed: 20 feet,  burrow 10 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +10, __Ref__ +12, __Will__ +7"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 3, splash damage 3; __Resistances__ piercing 6, slashing 6"
abilities_top:
  - name: ""

  - name: "Precise Tremorsense 40 feet"
    desc: "  The cobbleswarm's tremorsense is a precise sense out to 40 feet and an imprecise sense out to 80 feet. The cobbleswarm can't sense anything beyond the range of its tremorsense.\n* * *\n\nTremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Clutching Cobbles"
    desc: "  The cobbleswarm's space is difficult terrain."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "Grasping Bites"
    desc: "`pf2:2` (attack) The cobbleswarm attempts an Athletics check check and compares the result to the Fortitude DC of all creatures in its space.\n* * *\n\n**Critical Success** The creature falls [[Conditions/Prone|Prone]] and takes 1d6 bludgeoning damage, and is [[Conditions/Restrained|Restrained]] by the cobbleswarm until the end of the cobbleswarm's next turn.\n\n**Success** The creature falls prone, and is [[Conditions/Grabbed|Grabbed]] by the cobbleswarm until the creature until the end of the cobbleswarm's next turn."

  - name: "Pummeling Assault"
    desc: "`pf2:1`  Each enemy in the cobbleswarm's space takes 2d4 bludgeoning damage (DC 17 Reflex check save)."
 
```

```encounter-table
name: Cobbleswarm (AoE)
creatures:
  - 1: Cobbleswarm (AoE)
```




