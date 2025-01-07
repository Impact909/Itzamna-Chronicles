---
title: "Twigjack Bramble"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YIHhGGhe055wmAsz" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/plant
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Twigjack Bramble"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Twigjack Bramble"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[fey]]
trait_02: [[plant]]
trait_03: [[troop]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +13, Nature: +11, Stealth: +16"
abilityMods: [3, 5, 3, 1, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +16, __Will__ +12"
hp: 102
health:
  - name: ""
  - name: HP
    desc: "102, (16 squares) Thresholds 68 (12 squares), 34 (8 squares); __Weaknesses__ area damage 10, splash damage 5, fire 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 68 (12 squares), 34 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Clear Cut"
    desc: "`pf2:3`  The twigjack bramble swarms over any creatures in their path, shredding their foes with razor-sharp thorns. The bramble Forms Up and Strides twice, moving through the space of any Medium or smaller creatures. Each creature whose space the bramble moves through takes 4d6 slashing damage (DC 21 Reflex check save). On a critical failure, the creature is also knocked [[Conditions/Prone|Prone]]."

  - name: "Mass Bramble Jump"
    desc: "`pf2:3` (plant,primal,teleportation) The twigjack bramble uses Form Up to redistribute its squares into any configuration wherein all squares are in undergrowth, then instantly teleports to another square within 60 feet, using Form Up again on the target square. The configuration of the second Form Up must also place all of the bramble's squares in undergrowth. This movement doesn't trigger reactions."

  - name: "Rain of Splinters"
    desc: "`pf2:2`  The twigjack bramble launches a volley of splinters and brambles in a 10-foot burst within 30 feet that deals 4d6 piercing damage (DC 21 Reflex check save). When the bramble is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Troop Movement"
    desc: "  Whenever the twigjack bramble Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the bramble enters difficult terrain, the extra movement cost applies to the whole group."
 
```

```encounter-table
name: Twigjack Bramble
creatures:
  - 1: Twigjack Bramble
```



A single twigjack is a dangerous and unpredictable creature with a capacity for sudden violence. A group of twigjacks united by shared purpose is a substantive force for destruction. The impetus behind the formation of a twigjack group, colloquially known as a "bramble," can be almost anything, although they nearly always form around a particularly charismatic or demagogic individual. Religious fanaticism is another common factor; notably, however, twigjacks rarely worship established deities and instead devote themselves to strange new gods of their own imagining who, inevitably, demand that their worshippers purge the twigjacks' territory of those whose presence displeases them.

## Proactive Vigilantes

Twigjacks frequently justify their violent and antisocial tendencies by declaring themselves the guardians of the forests in which they dwell, and that their duty is to keep those protected lands free of non-fey intruders by any means necessary. Rarely patient enough to wait for opportunities to come to them, roving brambles of twigjacks often seek out what they consider to be impending conflicts between forest-folk and outside threats in order to impose their "assistance," nearly always resulting in brutality and bloodshed that benefits neither side and only serves to escalate the situation.
