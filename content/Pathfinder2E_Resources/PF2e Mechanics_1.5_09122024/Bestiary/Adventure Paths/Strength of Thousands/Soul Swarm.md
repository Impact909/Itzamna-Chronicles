---
title: "Soul Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w2ZcPXW6zbMKWPNL" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Soul Swarm"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Soul Swarm"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[ghost]]
trait_03: [[incorporeal]]
trait_04: [[spirit]]
trait_05: [[troop]]
trait_06: [[undead]]
trait_07: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Religion: +26, Stealth: +24"
abilityMods: [-5, 5, 3, 2, 5, 4]
speed: 30 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +18, __Will__ +23"
hp: 234
health:
  - name: ""
  - name: HP
    desc: "234, 16 squares (156 &#x3D; 12 squares, 78 &#x3D; 8 squares); __Weaknesses__ area damage 15, holy 15, splash damage 15; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 30 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 30, attack +22\n__Constant__  __(4th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Cosmic Explosion"
    desc: "`pf2:2`  The soul swarm unleashes a blast of burning sunlight or moonlight, dealing 4d8+6 fire damage to creatures in a 10-foot burst within 20 feet (DC 30 Reflex check save). When the soul swarm is reduced to 8 or fewer squares, this decreases to a 5-foot burst."

  - name: "Soul Grasp"
    desc: "`pf2:1`  `pf2:1` to `pf2:3` actions\n\n**Frequency** once per round\n* * *\n\n**Effect** The soul swarm reaches out and tries to tear at the spiritual energy of enemies within 5 feet (DC 32 Reflex check save). The soul swarm can choose to deal slashing damage as it cuts away at a creature, fire damage as it burns other souls away, or void damage as it attempts to unmake a soul. The damage depends on the number of actions.\n* * *\n\n`pf2:1` 2d6+1 untyped damage\n\n`pf2:2` 4d6+11 untyped damage\n\n`pf2:3` 6d6+11 untyped damage"

  - name: "Troop Movement"
    desc: "  Whenever the soul swarm Strides, the soul swarm first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves. This works just like a Gargantuan creature moving; for instance, if any square of the soul swarm enters difficult terrain, the extra movement cost applies to the whole soul swarm."
 
```

```encounter-table
name: Soul Swarm
creatures:
  - 1: Soul Swarm
```




