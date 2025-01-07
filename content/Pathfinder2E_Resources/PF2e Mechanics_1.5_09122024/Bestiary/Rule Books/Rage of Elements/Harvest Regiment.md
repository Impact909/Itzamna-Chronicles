---
title: "Harvest Regiment"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cxCWO0csqBSN6Vv6" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/troop
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Harvest Regiment"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Harvest Regiment"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[troop]]
trait_04: [[wood]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision"
languages: "Fey, Muan"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Survival: +17"
abilityMods: [6, 1, 3, -1, 3, -2]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +14, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, Thresholds: 90, 45; __Weaknesses__ area damage 10, fire 10, splash damage 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Juice Shower"
    desc: "  When a harvest regiment is critically hit or critically fails a save against a damaging effect, sticky fruit juices splash out. This affects all creatures in a 5-foot emanation. A splashed creature takes a –10-foot status penalty to its Speeds and everything is [[Conditions/Concealed|Concealed]] to it. A creature can Interact to clear off the juice."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Raise Shells"
    desc: "`pf2:1`  The troop raises fragments of their shells shaped like shields to gain a +2 circumstance bonus to AC until the start of their next turn."

  - name: "Seed Volley"
    desc: "`pf2:2`  The harvest regiment spits an orderly volley of hard seeds drawn from within their bodies. This volley is a 10-foot burst within 120 feet that deals 3d10 bludgeoning damage (DC 23 Reflex check save). When the harvest regiment is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Shell Smash"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round;\n* * *\n\n**Effect** The harvest regiment engages in a coordinated melee attack against each enemy within 5 feet, with a DC 23 Reflex check save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+3 bludgeoning damage\n\n`pf2:2` 2d8+9 bludgeoning damage\n\n`pf2:3` 2d8+12 bludgeoning damage"

  - name: "Troop Movement"
    desc: "  Whenever the harvest regiment Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving."
 
```

```encounter-table
name: Harvest Regiment
creatures:
  - 1: Harvest Regiment
```



Great fruiting trees grow in massive orderly rows in a region of the Plane of Wood called Armory Grove. Over the course of decades, a regiment tree's branches grow heavy, laden with fruits uncannily shaped like people. They're cultivated by retired warriors whose tireless work ensures that these fruits grow into a form suitable for battle. Their efforts instill tactical knowledge in these fruit warriors so they're prepared to fight as soon as they fall from the tree—which they do simultaneously, forming one battle-ready unit. Each soldier is equal in skill and similar in form, with a wooden outer shell that splits into portions as the flesh of the fruit inside ripens. A slain warrior contains seeds within its body that can slowly germinate in rich soil with enough water—or blood. Every battlefield can become a new garden.
