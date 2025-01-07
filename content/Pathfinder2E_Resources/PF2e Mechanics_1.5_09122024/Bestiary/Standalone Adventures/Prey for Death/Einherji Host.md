---
title: "Einherji Host"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BIYTLSwCBmCkMMsI" 
tags:
  - pf2e/creature/type/aesir
  - pf2e/creature/type/monitor
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Einherji Host"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Einherji Host"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[aesir]]
trait_02: [[monitor]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Hallit, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +28, Intimidation: +24"
abilityMods: [7, 4, 6, 0, 4, 3]
speed: 40 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 35
armorclass:
  - name: AC
    desc: "35 37 with shields raised; __Fort__ +29, __Ref__ +23, __Will__ +25; +4 to will vs. fear"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, Thresholds 180 (12 squares), 90 (8 squares); __Weaknesses__ area damage 18, splash damage 9; __Resistances__ piercing 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 180 (12 squares), 90 (8 squares)\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Dagger Volley"
    desc: "`pf2:2`  The einherji host launches a ranged attack in the form of a volley of thrown daggers. This volley fills a 30-foot cone; all creatures in the area take 5d4+15 piercing damage (DC 36 Reflex check save). When the troop is reduced to 8 or fewer squares, this area decreases to a 15-foot cone."

  - name: "Jotun Slayer"
    desc: "  An einherji host has a +4 circumstance bonus to Strike as One damage rolls made against giants and creatures that are Huge or larger."

  - name: "Pay For Every Inch"
    desc: "`pf2:3`  The einherji host Forms Up, Raises Shields, and prepares to counterattack. Until the start of the troop's next turn, each time an enemy takes an action to move through a space adjacent to the troop, they take 4d8+18 slashing damage (DC 36 Reflex check save)."

  - name: "Raise Shields"
    desc: "`pf2:1`  The troop raises their shields, increasing their Armor Class by 2 until the start of the troop's next turn."

  - name: "Song of Freedom"
    desc: "`pf2:1` (concentrate,mental) The troop sings of freedom, bolstering their conviction and morale. Until the start of the troop's next turn, their Will saves increase to +29 against all mental effects, not just against fear effects."

  - name: "Strike as One"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The einherji host makes melee attacks against each enemy within 5 feet (DC 36 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8+7 slashing damage\n\n`pf2:2` 3d8+14 slashing damage\n\n`pf2:3` 4d8+14 slashing damage"

  - name: "Troop Movement"
    desc: "  Whenever the einherji host Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares they may have as the result of having taken Hit Point damage), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Einherji Host
creatures:
  - 1: Einherji Host
```




