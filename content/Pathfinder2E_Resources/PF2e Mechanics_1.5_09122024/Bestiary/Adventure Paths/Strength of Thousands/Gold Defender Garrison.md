---
title: "Gold Defender Garrison"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.on54Y8kZn52h7u1C" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Gold Defender Garrison"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Gold Defender Garrison"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[mindless]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [7, 2, 6, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +26, __Ref__ +22, __Will__ +22"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, 16 squares (160 &#x3D; 12 squares, 80 &#x3D; 8 squares); __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 15, bludgeoning 10, splash damage 8; __Resistances__ physical 15 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|(Golem) Golem Antimagic]]"
    desc: "  harmed by _cold_(2d8 damage from areas or persistent damage); healed by _fire_ (area 2d8 healing Hit Points); slowed by _acid_\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Death Throes"
    desc: "  As the garrison's numbers dwindle, gold defenders melt away into worthless slag. Every time that the garrison is reduced to a threshold, it leaves behind a 10-foot radius cloud of fumes and a 10-foot radius puddle of molten metal. Creatures that breathe fumes are exposed to gold defender poison. Creatures that move through the puddle take 10d6 fire damage. The fumes dissipate after 1 round and the puddle completely evaporates after 1 minute."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Gold Defender Poison"
    desc: " (poison) Any [[Conditions/Drained|Drained]] value from this poison is reduced by 1 every hour\n\n**Saving Throw** DC 33 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6 poison and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 4d6 poison and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 8d6 poison and [[Conditions/Drained|Drained 3]] (1 round)."

  - name: "Golden Strike"
    desc: "`pf2:1`  `pf2:1` to `pf2:3` actions\n\n**Frequency** once per round\n* * *\n\n**Effect** The garrison makes a melee attack against each enemy within 5 feet (DC 30 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8+2 bludgeoning damage\n\n`pf2:2` 3d8+12 bludgeoning damage\n\n`pf2:3` 4d8+15 bludgeoning damage"

  - name: "Light Reflection"
    desc: "`pf2:2` (primal) **Requirements** The gold defender garrison is not in darkness\n* * *\n\n**Effect** The gold defender garrison reshapes its skin into a reflective surface that magnifies ambient light into a precise beam that burns all creatures in a 30-foot cone, dealing 14d6 fire damage (DC 31 Reflex check save if the gold defender is in dim light, DC 33 Reflex check save if it's in bright light). The size of the cone reduces to a 15-foot cone when the garrison is reduced to 8 or fewer squares. It can't use Light Reflection again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and catches fire, taking 1d6 persistent fire damage.\n\n**Critical Failure** As failure, but the persistent fire damage is 5d6 persistent fire."

  - name: "Troop Movement"
    desc: "  Whenever the garrison Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Gold Defender Garrison
creatures:
  - 1: Gold Defender Garrison
```




