---
title: "Fen Mosquito Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WDorr4wdcR1cbO1I" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Fen Mosquito Swarm"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Fen Mosquito Swarm"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Stealth: +8"
abilityMods: [0, 4, 3, -5, 0, -5]
speed: 5 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +11, __Will__ +5"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Swarm Mind"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Pyrexic Malaria"
    desc: " (disease) The victim can't reduce its [[Conditions/Sickened|Sickened]] condition while it's affected by pyrexic malaria\n\n**Saving Throw** DC 20 Fortitude check\n\n**Onset** 4 days\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 5** dead"

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 1d6 piercing damage (DC 20 Reflex check save) and is exposed to pyrexic malaria. Creatures that fail the saving throw also take 1d4 bleed."
 
```

```encounter-table
name: Fen Mosquito Swarm
creatures:
  - 1: Fen Mosquito Swarm
```



When deadly fen mosquitoes gather in large numbers, they form into lethal swarms capable of draining blood at a truly alarming rate. Fen mosquito swarms are typically encountered only in tropical swamps or bogs, but during humid months in spring or summer they can drift into riverine areas or even through the waterfront reaches of settlements.
