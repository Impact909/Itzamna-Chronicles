---
title: "Hellknight Cavalry Brigade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t76xA9Uj7xBDQHm2" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Hellknight Cavalry Brigade"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Hellknight Cavalry Brigade"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
trait_05: [[troop]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common, Diabolic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +18, Intimidation: +17, Religion: +12, Society: +12, Hell Lore: +12"
abilityMods: [6, 1, 4, 2, 2, 3]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +13, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, troop defenses; __Weaknesses__ area damage 10, splash damage 5; __Resistances__ mental 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 90 (12 squares), 45 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Arrow Volley"
    desc: "`pf2:2`  The Hellknights draw or reload their longbows, then launch a ranged attack in the form of a volley. This volley is a 10-foot burst within 100 feet that deals 4d8 piercing damage (DC 23 Reflex check save).\n\nWhen the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Lance Charge"
    desc: "`pf2:3`  The brigade Forms Up, then Strides twice with a +10-foot circumstance bonus to its Speed.\n\nIf it moves at least 10 feet, the brigade deals 3d8+13 piercing damage (DC 26 Reflex check save) to each enemy within 10 feet of the brigade at the end of its movement."

  - name: "Mounted Troop"
    desc: "  Effects that target only animals or only humanoids may not work on the cavalry brigade, subject to the GM's discretion."

  - name: "Swing from the Saddle"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round.\n* * *\n\n**Effect** The brigade engages in a coordinated melee attack against each enemy within 10 feet (DC 23 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d6 slashing damage\n\n`pf2:2` 2d6+10 slashing damage\n\n`pf2:3` 3d6+13 slashing damage"

  - name: "Trailblazing Stride"
    desc: "  While moving on land, the Hellknight cavalry brigade ignores the effects of non-magical difficult terrain."

  - name: "Troop Movement"
    desc: "  Whenever the cavalry brigade Strides, the brigade first [[Bestiary Ability Glossary/Form Up|Forms Up]] as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves. This works just like a Gargantuan creature moving; for instance, if any square of the brigade enters difficult terrain, the extra movement cost applies to the whole brigade."
 
```

```encounter-table
name: Hellknight Cavalry Brigade
creatures:
  - 1: Hellknight Cavalry Brigade
```



A cavalry brigade consists of several Hellknights and a single field-maralictor, in the distinctive armor of their order and bearing lances; the maralictor speaks for the brigade, questioning travelers the brigade encounters and barking orders.

A Hellknight brigade is typically based at a keep or other fortification controlling an area measured by a day's ride in every direction-about 25 miles. Farther-ranging missions are possible but require substantial logistical support.
