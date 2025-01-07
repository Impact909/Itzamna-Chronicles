---
title: "Clockwork Shambler Horde"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Wgg6IujzoDwsjBdB" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Clockwork Shambler Horde"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Clockwork Shambler Horde"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[troop]]
trait_05: [[zombie]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: ""
abilityMods: [6, 0, 4, -5, 2, -2]
speed: 20 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +21, __Ref__ +16, __Will__ +17"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, troop defenses; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 10, slashing 10, splash damage 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Slow"
    desc: "  A shambler troop is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 160 (12 squares), 80 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Grave Tide"
    desc: "  The shambler troop is less organized than most troops. It can move into other creatures' spaces, and other creatures can move into its spaces. Its spaces are difficult terrain to other creatures."

  - name: "Shambling Onslaught"
    desc: "`pf2:1`  `pf2:1` to `pf2:2`\n\n**Frequency** once per round\n* * *\n\n**Effect** The shamblers lash out at any enemies in their squares or within 5 feet (DC 25 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 3d6+9 bludgeoning damage\n\n`pf2:2` 3d8+13 bludgeoning damage"

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Clockwork Shambler Horde
creatures:
  - 1: Clockwork Shambler Horde
```


Variant shambler troop

Necromancers most often create these mindless undead as obedient, expendable servitors. Left to its own devices, a zombie seeks only to consume the living, stopping only when its rotting body can no longer hold together.

* * *

This shuffling mass of decaying flesh moves with dull but singular focus.
