---
title: "Skeleton Infantry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rfvP2KQkaUQgySra" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Skeleton Infantry"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Skeleton Infantry"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[skeleton]]
trait_04: [[troop]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [5, 3, 4, -5, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +18, __Will__ +19"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, troop defenses; __Immunities__  mental; __Weaknesses__ area damage 15, splash damage 8; __Resistances__ cold 5, electricity 5, fire 5, piercing 10, slashing 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Form a Phalanx"
    desc: "`pf2:1`  Many of the skeletons raise their shields to protect others. The infantry gain a +2 circumstance bonus to AC until the start of their next turn.\n\n[[Bestiary Effects/Effect_ Form a Phalanx|Effect: Form a Phalanx]]"

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Threshold** 120 (12 squares), 60 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Hurl Javelins!"
    desc: "`pf2:2`  The troop's members throw a volley of javelins. Each creature in a 10-foot burst within 30 feet of the troop takes 2d6+10 piercing damage (DC 26 Reflex check save).\n\nWhen the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Lower Spears!"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The skeletons engage in a coordinated longspear attack against each enemy within 10 feet (DC 27 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8 piercing damage\n\n`pf2:2` 3d8+8 piercing damage\n\n`pf2:3` 4d8+8 piercing damage"

  - name: "Phalanx Charge"
    desc: "`pf2:2`  **Requirements** The infantry is in a phalanx\n* * *\n\n**Effect** The skeletons lower their longspears and charge. The troop Strides in a straight line until they're adjacent to an enemy then use Lower Spears!, dealing 3d8+8 piercing damage. Any creature that fails its save is also knocked [[Conditions/Prone|Prone]]."

  - name: "Troop Movement"
    desc: "  Whenever the skeleton infantry Stride, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the infantry enter difficult terrain, the extra movement cost applies to all the guards."
 
```

```encounter-table
name: Skeleton Infantry
creatures:
  - 1: Skeleton Infantry
```



This troop of skeletons was once a cohort of highly disciplined spear-and-shield infantry from an ancient empire.

* * *

Almost any creature that had bones in life and leaves them behind in death can become a shambling, undead skeleton-humanoids, beasts, aberrations, fey, and more.
