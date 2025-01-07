---
title: "Pulping Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vk8BHoS42TEadrFx" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Pulping Golem"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Pulping Golem"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +32"
abilityMods: [8, -1, 4, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +23, __Will__ +24"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Immunities__  fire,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 15 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Golem Antimagic"
    desc: "  harmed by acid (6d10+4, 2d8+4 from areas and persistent damage); healed by fire (area 2d8+4 HP); slowed by electricity\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem. **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical. **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical. **Slowed By** Any magic of this type that targets the golem causes it to be slowed 1 for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round. **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Neutralize Poison"
    desc: "  Casting [[Spells/Cleanse Affliction|Cleanse Affliction]] on the golem deactivates its Breath Weapon for 1 minute."

  - name: "Vulnerable to Rust"
    desc: "  Magical rusting effects, like a rust monster's antennae, affect the iron golem normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+30 (magical, reach 10 feet)\n__Damage__  3d10 + 14 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The pulping golem spills its cauldron stomach to the floor, dealing 9d12 fire damage to creatures within 10 feet (DC 33 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Extend Legs"
    desc: "`pf2:1`  The pulping golem extends its legs up to a height of 40 feet, raising its body high into the air. While its legs are extended, its movement speed is halved, and it takes a -2 penalty to its Fortitude save DC against Shove and Trip attempts."

  - name: "Inexorable March"
    desc: "`pf2:1`  The iron golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a DC 39 Fortitude check save. On a critical success, the resisting creature takes no damage; otherwise, it is damaged as if hit by the golem's fist."

  - name: "Iron Golem Poison"
    desc: " (poison) Any [[Conditions/Drained|Drained]] value from this poison is reduced by 1 every hour.\n\n**Saving Throw** DC 35 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6+4 poison and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 4d6+4 poison and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 8d6+4 poison and [[Conditions/Drained|Drained 3]] (1 round)."
 
```

```encounter-table
name: Pulping Golem
creatures:
  - 1: Pulping Golem
```


Variant elite iron golem

Traditionally crafted into the forms of giant suits of armor or powerful animals, iron golems are products of exquisite artistry and skill. Their articulated joints and sturdy armored bodies require great care and mathematical precision to craft, and regular cleaning and oiling ensure they don't rust over the ages. With proper care, iron golems can remain in good shape for thousands of years, being passed down for generations, as long as they aren't destroyed by meddlesome adventurers. In addition to their incredible strength, iron golems possess a potent toxic breath weapon that is often more than enough to dispatch entire groups of opponents.
