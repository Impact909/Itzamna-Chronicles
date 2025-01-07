---
title: "Xulgath Ravening"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8cuZtPcBzE3wf7SS" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Xulgath Ravening"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Xulgath Ravening"
level: "Creature 4"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[troop]]
trait_05: [[xulgath]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +10, Stealth: +7"
abilityMods: [5, 1, 3, -1, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +12, __Will__ +8"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72, Thresholds 48 (12 squares), 24 (8 squares); __Weaknesses__ area damage 5, splash damage 2"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 21 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, the creature also takes a –5 status penalty to its Speeds for 1 round. While within the aura, the creature takes a –2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths stenches for 1 minute.\n\n[[Bestiary Effects/Effect_ Xulgath Stench|Effect: Xulgath Stench]]"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 48 (12 squares), 24 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Fang and Claw"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The xulgath ravening lashes out at enemies within 5 feet (DC 21 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d6 slashing damage\n\n`pf2:2` 1d6+5 slashing damage\n\n`pf2:3` 2d6+5 slashing damage"

  - name: "Infected Wounds"
    desc: " (poison) The xulgaths' Fang and Claw deals an additional 1d6 poison damage to any creature sickened by a xulgath's stench."

  - name: "Sharpened Advance"
    desc: "`pf2:2`  The troop fires a ranged attack in the form of a 5-foot burst within 50 feet that deals 3d6 piercing damage (DC 18 Reflex check save), then the troop either Steps or Strides up to 15 feet toward the area they attacked."

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by–20- foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Xulgath Ravening
creatures:
  - 1: Xulgath Ravening
```



Strength and hunger drive most xulgath societies, reinforced by the tenets of their abyssal patron Zevgavizeb. A powerful leader can seize control of a xulgath community and direct their followers to fight as a unit, but formation fighting isn't something most xulgaths practice. This mob mentality often results in overzealous warriors tripping over or even biting each other. Suitably, these mobs have earned the name "ravenings," a term also used when describing Zevgavizeb's carnivorous rampages and referring to the millennia of xulgath infighting and social decline.

## The Power of Suggestion

Xulgath ravening are most common in clutches controlled by spiritual leaders using some combination of cult behavior, group ritual, and even a little enchantment magic. By convincing participants that they're possessed by Zevgavizeb or a similar force, the leader then identifies a target and hopes for the best. Instilling secular doubt or incapacitating the leader can shatter a ravening's focus, causing its members to scatter or even turn on their leader.
