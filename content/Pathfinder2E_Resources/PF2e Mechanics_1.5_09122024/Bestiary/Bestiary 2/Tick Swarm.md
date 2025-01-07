---
title: "Tick Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zsBdLPcmKScXk5i3" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Tick Swarm"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Tick Swarm"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +16, Stealth: +19"
abilityMods: [1, 6, 4, -5, 3, -5]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +19, __Will__ +14"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ bludgeoning 5, piercing 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Swarm Mind"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Cling"
    desc: "`pf2:r`  **Trigger** A creature leaves the swarm's space\n* * *\n\n**Effect** The swarm takes 1d6 damage as ticks cling to the creature and continue biting, dealing 3d6 bleed. Immersion in water reduces the DC of the flat check to end this persistent damage to 5, and any area damage dealt to the creature destroys these clinging ticks."

attacks:
  - name: ""

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 3d6 piercing damage (DC 28 Reflex check save) plus Cling and exposure to tick fever."

  - name: "Tick Fever"
    desc: " (disease) **Saving Throw** DC 27 Fortitude check\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)."
 
```

```encounter-table
name: Tick Swarm
creatures:
  - 1: Tick Swarm
```



This swarm of thousands of fist-sized ticks forms a moving carpet of bloated insects-a nauseating and intimidating sight.
