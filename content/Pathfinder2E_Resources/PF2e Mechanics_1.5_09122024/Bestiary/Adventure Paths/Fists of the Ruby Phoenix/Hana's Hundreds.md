---
title: "Hana's Hundreds"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ni8NZ6Rgsm5AS4WL" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Hana&#x27;s Hundreds"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Hana's Hundreds"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; "
languages: "Taldane, Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +30, Intimidation: +27"
abilityMods: [8, 6, 6, 1, 2, 4]
speed: 30 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +29, __Ref__ +23, __Will__ +23"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, troop defenses (180/90); __Weaknesses__ area damage 20, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Troop Movement"
    desc: "  Whenever Hana's Hundreds Strides, the team first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the team enters difficult terrain, the extra movement cost applies to the whole team."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 180 (12 squares), 90 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Rain of Knives"
    desc: "`pf2:2`  Hana's Hundreds launch a volley of throwing knives in a 10-foot burst within 50 feet that deals4d6+13 piercing damage (DC 33 Reflex check). When the team is reduced to 8 or fewer squares, this area decreases to a 5-foot burst"

  - name: "Run Them Over!"
    desc: "`pf2:3`  Hana's Hundreds attempt to trample all foes in their way. The team Forms Up and Strides twice, moving through the space of Medium or smaller creatures. Each creature the team moves through takes4d8+14 bludgeoning damage (DC 33 Reflex check save). On a critical failure, the creature is also knocked [[Conditions/Prone|Prone]]."

  - name: "Whirlwind of Blades"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n\nHana's Hundreds flail their swords wildly at each enemy adjacent to the team (DC 33 Reflex check save). The damage depends on the number of actions.\n* * *\n\n`pf2:1` 2d8 slashing damage\n\n`pf2:2` 3d8+13 slashing damage\n\n`pf2:3` 4d8+16 slashing damage"
 
```

```encounter-table
name: Hana's Hundreds
creatures:
  - 1: Hana's Hundreds
```




