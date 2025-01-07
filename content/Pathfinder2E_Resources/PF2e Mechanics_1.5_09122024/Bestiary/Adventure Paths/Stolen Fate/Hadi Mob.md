---
title: "Hadi Mob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YjalS4g2wRp1ywq1" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/ratfolk
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Hadi Mob"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Hadi Mob"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[ratfolk]]
trait_04: [[troop]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Common, Daemonic; ratspeak"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Stealth: +29"
abilityMods: [6, 8, 6, 4, 4, 2]
speed: 25 feet,  climb 10 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +29, __Will__ +23"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, (16 squares); Thresholds 180 (12 squares), 90 (8 squares); __Weaknesses__ area damage 15, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Ratspeak"
    desc: "  A hadi mob can communicate with rodents."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Gnaw and Chew"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** the hadi mob bites and tears into the flesh of each enemy adjacent to the troop (DC 33 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8+8 slashing damage plus hadi pestilence\n\n`pf2:2` 4d8+12 slashing damage plus hadi pestilence\n\n`pf2:3` 6d8+12 slashing damage plus hadi pestilence"

  - name: "Hadi Pestilence"
    desc: " (disease,divine) This daemonic disease turns the victim into a hadi.\n\n**Saving Throw** DC 19 Fortitude check\n\n**Stage 1** carrier (1 day)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 5** [[Conditions/Drained|Drained 3]] (1 week)\n\n**Stage 6** transform into a hadi (1 year). For a PC, the best way to model this is to replace ancestry Hit Points, size, Speeds, ability boosts, ability flaws, traits, and special abilities with those of the ratfolk ancestry. The character loses previous ancestry feats, selecting replacements from the ratfolk ancestry."

  - name: "Troop Movement"
    desc: "  Whenever the hadi mob Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Hadi Mob
creatures:
  - 1: Hadi Mob
```



aemons, including leukodaemons, once ruled over part of the fallen city of Kho. While they did, they created the first hadis.

Hadis look more fiendish and sinister than typical ratfolk. In hadi society, those who foster and cultivate blights and sickness are alchemists known as "tafens". Others, known as "rajwans," focus their training on brutal combat and barbarian rages.

Individually, most hadis are no match for a high level group, but when confronted in their lair, they can gather together into a dangerous mob.

## Hadi Evil

Although the original hadis created by daemons in ages past were ascended from rats infused with fiendish qualities that tempered their sapience with an engineered evil, over the generations the hadi people have formed their own society. They cling to evil ways largely out of tradition or fear, but there are an increasing number of hadis who admire Kho's derhiis and seek their own paths. Others, particularly those who have traveled far from Kho, have come to understand the plight of their folk under the weight of a fiendish past. Non-evil hadi thus exist, but they are viewed by those in positions of power in Kho as dangers to the social order. These hadi do not carry the pestilence their more sinister kin do and many actively work to suppress the spread of illnesses.
