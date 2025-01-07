---
title: "Angry Townsfolk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M4N3H8n0kgVW6Xy4" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Angry Townsfolk"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Angry Townsfolk"
level: "Creature 5"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
trait_04: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Intimidation: +11, Settlement Lore: +9"
abilityMods: [5, 0, 3, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +9, __Will__ +11"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, troop defenses; __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Seek Quarry"
    desc: "  Angry townsfolk can spend 1 minute to designate a single creature for whom they have a physical description as their quarry. They gain a +2 circumstance bonus to Perception against their quarry."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 50 (12 squares), 25 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Pitchforks and Torches"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round.\n* * *\n\n**Effect** The angry townsfolk engage in a coordinated melee attack against each enemy within 10 feet, with a DC 19 Reflex check save. The damage depends on the number of actions.\n\n`pf2:1` 1d10 piercing damage or 1d10 fire damage\n\n`pf2:2` 1d10+7 piercing damage or 1d10+7 fire damage\n\n`pf2:3` 1d10+10 piercing damage or 1d10+10 fire damage"

  - name: "Troop Movement"
    desc: "  Whenever the city guards Stride, they first [[Bestiary Ability Glossary/Form Up|Form Up]] as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed.\n\nThis works just like a Gargantuan creature moving; for instance, if any square of the guards enters difficult terrain, the extra movement cost applies to all the guards."

  - name: "Urban Chasers"
    desc: "  Angry townsfolk ignore difficult terrain (but not greater difficult terrain) caused by crowds or from movement through narrow spaces such as alleyways."
 
```

```encounter-table
name: Angry Townsfolk
creatures:
  - 1: Angry Townsfolk
```


variant city guard squadron


