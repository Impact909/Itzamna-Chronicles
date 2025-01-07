---
title: "Cultist Troop"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PiMF2dd0JfUaCUKO" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Cultist Troop"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Cultist Troop"
level: "Creature 5"

alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[fey]]
trait_03: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +14"
abilityMods: [5, 1, 4, 1, 0, 3]
speed: 25 feet
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +12, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, (16 squares); Thresholds 60 (12 squares), 30 (8 squares);; __Weaknesses__ area damage 5, cold iron 5, splash damage 2"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by–20-foot area (minus any missing squares), then moves up to its Speed. See _Bestiary 3_ for further details."

  - name: "Wild Swing"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The cultists chaotically swing their weapons—from pixies' tiny rapiers to redcaps' scythes—at each enemy adjacent to the troop (DC 22 Reflex check save), dealing a small amount of damage to the troop at the same time. The damage depends on the number of actions.\n\n`pf2:1` 1d12+1 slashing damage to enemies and 1d4 slashing damage to the troop\n\n`pf2:2` 2d12+1 slashing damage and 1d4+2 slashing damage to the troop\n\n`pf2:3` 2d12+5 slashing damage and 2d4 slashing damage to the troop"
 
```

```encounter-table
name: Cultist Troop
creatures:
  - 1: Cultist Troop
```




