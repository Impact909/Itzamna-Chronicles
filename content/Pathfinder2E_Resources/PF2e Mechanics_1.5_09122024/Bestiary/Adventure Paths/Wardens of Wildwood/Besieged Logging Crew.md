---
title: "Besieged Logging Crew"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0fkeJ4wZWTwe4qPa" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Besieged Logging Crew"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Besieged Logging Crew"
level: "Creature 4"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; "
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +12, Nature: +8, Survival: +10, Lumber Lore: +10"
abilityMods: [3, 2, 2, 1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +9, __Will__ +10"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, Thresholds 40 (12 squares), 20 (8 squares);; __Weaknesses__ area damage 10, splash damage 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 40 (12 squares), 20 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Hurl Axes"
    desc: "`pf2:2`  The loggers draw their hatchets, then launch a ranged attack in the form of a volley. This volley is a 10-foot burst within 120 feet that deals 3d6 slashing damage (DC 18 Reflex check save). When the crew is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Tandem Chop"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The loggers engage in a coordinated axe attack against each enemy within 10 feet, with a DC 19 Reflex check save. The damage depends on the number of actions expended.\n\n`pf2:1` 1d10 slashing damage\n\n`pf2:2` 3d6+7 slashing damage\n\n`pf2:3` 3d6+10 slashing damage"

  - name: "Troop Movement"
    desc: "  Whenever the loggers Stride, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the logging crew enters difficult terrain, the extra movement cost applies to all the loggers."
 
```

```encounter-table
name: Besieged Logging Crew
creatures:
  - 1: Besieged Logging Crew
```




