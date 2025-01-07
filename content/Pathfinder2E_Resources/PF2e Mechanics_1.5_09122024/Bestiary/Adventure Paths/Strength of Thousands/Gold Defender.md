---
title: "Gold Defender"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t3QjD0GtzSb6GiXe" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Gold Defender"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Gold Defender"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [8, -1, 4, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +21, __Will__ +22"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 15 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|(Golem) Golem Antimagic]]"
    desc: "  harmed by _cold_(6d10 damage, 2d8 damage from areas or persistent damage); healed by _fire_ (area 2d8 healing Hit Points); slowed by _acid_\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Death Throes"
    desc: "  When the gold defender is destroyed, it melts into worthless slag. As it melts, it releases a 10-foot burst cloud of fumes and a 10-foot radius puddle of molten metal. Creatures that breathe fumes are exposed to gold defender poison. Creatures that move through the puddle take 10d6 fire damage. The fumes dissipate after 1 round and the puddle cools after 1 minute."

  - name: "Malleable Shape"
    desc: "  The gold defender's body is made from soft gold, which is particularly pliable. If the gold defender is critically hit with an attack that deals bludgeoning damage, the attack partially bends and reshapes the gold defender. The gold defender becomes [[Conditions/Clumsy|Clumsy 2]] until it spends an Interact action to bend itself back into shape."

  - name: "Vulnerable to Telekinetic Haul"
    desc: "  Casting [[Spells/Telekinetic Haul|Telekinetic Haul]] on the gold defender squeezes its form, compressing it into a smaller and much more awkward shape. The gold defender becomes [[Conditions/Clumsy|Clumsy 3]] and can't use Light Reflection. The gold defender must take a 1-minute activity, which has the manipulate trait, to restore its shape, removing the clumsy condition and restoring its Light Reflection."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+28 (magical, reach, reach 10 feet)\n__Damage__  3d10 + 12 bludgeoning"

  - name: "Gold Defender Poison"
    desc: " (poison) Any [[Conditions/Drained|Drained]] value from this poison is reduced by 1 every hour\n\n**Saving Throw** DC 33 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6 poison and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 4d6 poison and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 8d6 poison and [[Conditions/Drained|Drained 3]] (1 round)."

  - name: "Inexorable March"
    desc: "`pf2:1`  The gold defender Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a DC 37 Fortitude check save. On a critical success, the resisting creature takes no damage; otherwise, it is damaged as if hit by the defender's fist Strike."

  - name: "Light Reflection"
    desc: "`pf2:2` (primal) **Requirements** The gold defender is not in darkness\n* * *\n\n**Effect** The gold defender reshapes its skin into a reflective surface that magnifies ambient light into a precise beam that burns all creatures in a 30-foot cone, dealing 14d6 fire damage (DC 31 Reflex check save if the gold defender is in dim light, DC 33 Reflex check save if it's in bright light). It can't use Light Reflection again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and catches fire, taking 1d6 persistent fire damage.\n\n**Critical Failure** As failure, but the persistent fire damage is 5d6 persistent fire."
 
```

```encounter-table
name: Gold Defender
creatures:
  - 1: Gold Defender
```




