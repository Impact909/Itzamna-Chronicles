---
title: "Last Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WWqMCl1e7tgPFdRt" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Last Guard"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Last Guard"
level: "Creature 20"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[incorporeal]]
trait_02: [[lawful]]
trait_03: [[spirit]]
trait_04: [[troop]]
trait_05: [[undead]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Lifesense 60 Feet"
languages: "Common, Elven, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +38, Stealth: +38, Warfare Lore: +35"
abilityMods: [-5, 10, 10, 7, 7, 6]
speed:  fly 40 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +34, __Ref__ +36, __Will__ +31"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330, void healing, rejuvenation, troop defenses; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ area damage 20, splash damage 20; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Battlefield Bound"
    desc: "  Without a call to war, a last guard can stray only a short distance from the location they failed to defend, typically 120 feet. Some last guards are instead bound to a province, kingdom, or nation, rather than a specific location."

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a last guard is destroyed, they re-form after 2d4 days within the location they're bound to, fully healed. A last guard can be permanently destroyed and move on to the afterlife only if they successfully defend the location they're bound to from large-scale attack, or fulfill a call to war."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 220 (12 squares), 110 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Frightful Battle Cry"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental,sonic) The last guards unleash a soul-shaking bellow in unison. All creatures in a 60-foot cone take 7d6 sonic damage (DC 42 Will check). Any creature that fails its save is also [[Conditions/Frightened|Frightened 3]] (or [[Conditions/Frightened|Frightened 4]] on a critical failure).\n\nIf the troop occupies 8 or fewer squares, this area decreases to a 30-foot cone."

  - name: "Ghostly Blades"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The last guards engage in a coordinated attack with their spectral curve blades against each enemy within 5 feet (DC 40 Reflex check). The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 slashing and 1d8 void damage\n\n`pf2:2` 2d8+14 slashing and 2d8 void damage\n\n`pf2:3` 3d8+14 slashing and 3d8 void damage"

  - name: "Spectral Charge"
    desc: "`pf2:3`  The last guards charge, swarming through their foes. The troop Flies up to double its Speed, dealing 4d8 void damage to each creature whose space it moves through (DC 40 Reflex check). Any creature that fails its save is also [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] on a critical failure). The troop can affect each creature only once in a single use of Spectral Charge."

  - name: "Troop Movement"
    desc: "  Whenever the troop Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving."
 
```

```encounter-table
name: Last Guard
creatures:
  - 1: Last Guard
```




