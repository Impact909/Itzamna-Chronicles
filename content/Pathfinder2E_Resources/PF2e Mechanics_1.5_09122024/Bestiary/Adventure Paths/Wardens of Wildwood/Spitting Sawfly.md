---
title: "Spitting Sawfly"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xS11LedovGIeijm8" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/mutant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Spitting Sawfly"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Spitting Sawfly"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[mutant]]
trait_03: [[wood]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +20"
abilityMods: [4, 6, 5, -5, 3, 1]
speed: 20 feet,  climb 20 feet,  fly 40 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +19, __Ref__ +22, __Will__ +16"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  acid; __Resistances__ poison 10"
abilities_top:
  - name: ""

  - name: "Wood Scent (Precise) 30 feet"
    desc: "  A spitting sawfly can smell plants and wood as a precise scent at the listed range."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+22 (finesse, poison)\n__Damage__  2d12 + 10 piercing plus seizing-venom"

  - name: "**Ranged** `pf2:1` Acid Spit"
    desc: "+22 (poison, range increment 30 feet)\n__Damage__  4d8 acid plus seizing-venom"

  - name: "Consume Essence"
    desc: "`pf2:1` (healing,manipulate,primal) **Frequency** once per day;\n\n**Requirements** The spitting sawfly is adjacent to a creature with the wood trait or to a coiled conifer\n* * *\n\n**Effect** The sawfly feasts upon the targeted creature or the coiled conifer's sap, regaining 5d6 Hit Points. A targeted creature must attempt a DC 29 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure)."

  - name: "Creeping Sprout"
    desc: " (disease) A creature afflicted with creeping sprout is treated by the spitting sawfly as if it has the wood trait\n\n**Saving Throw** DC 29 Fortitude check;\n\n**Stage 1** carrier with no ill effect (1d4 days)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1d4 days);\n\n**Stage 3** 12d6 acid damage, creeping cone swarm emerges (disease ends)"

  - name: "Plant Spores"
    desc: "`pf2:1`  The spitting sawfly plants spores in an adjacent creature that's [[Conditions/Paralyzed|Paralyzed]] or [[Conditions/Unconscious|Unconscious]], exposing it to creeping sprout disease."

  - name: "Seizing Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 29 Fortitude check;\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Off-Guard|Off-Guard]] and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 2** off-guard and [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] (1 round)"
 
```

```encounter-table
name: Spitting Sawfly
creatures:
  - 1: Spitting Sawfly
```



Spitting sawflies are enormous, bloated insects covered in tumor-like knots of spores. These ravenous pests sow disease and spores wherever they go, heralding the infestation of creeping cones.

* * *

The Plane of Wood contains many unique ecosystems formed around species of wondrous trees; when Ayrzul's Blight mutates one of these trees rather than killing it, it can have a cascading effect on the tree's biome. Multiple species often mutate in tandem, becoming warped mockeries and a vector for Ayrzul's Blight. These "blight bonded" creature families are parasites and predators and typically form twisted symbiotic relationships.
