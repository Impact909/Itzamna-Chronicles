---
title: "Guillotine Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SW6U1jfCSR4dJzro" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Guillotine Golem"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Guillotine Golem"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +38"
abilityMods: [9, 0, 6, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +33, __Ref__ +28, __Will__ +29"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 20 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by _acid_ (9d8 damage, 3d8 damage from areas or persistent damage); healed by _electricity_ (area 3d8 Hit Points); slowed by _fire_\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Neutralize Poison"
    desc: "  Casting [[Spells/Cleanse Affliction|Cleanse Affliction]] on the golem deactivates its Breath Weapon for 1 minute."

  - name: "Vulnerable to Rust"
    desc: "  Magical rusting effects, like a rust monster's antennae, affect the guillotine golem normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blade"
    desc: "+36 (magical, reach, reach 10 feet)\n__Damage__  3d12 + 15 slashing plus decapitation"

  - name: "Breath Weapon"
    desc: "`pf2:2` (occult,poison) The guillotine golem emits poisonous gas in a 10-foot burst centered on the corner of one of the golem's squares. The gas persists for 1 round. Any creature in the area (or that later enters the area) is exposed to the golem's poison. The golem can't use its Breath Weapon again for 1d4 rounds."

  - name: "Decapitation"
    desc: "  If the guillotine golem critically hits a creature with its blade Strike, the creature must succeed at a DC 40 Fortitude check save or be decapitated, dying instantly unless it can survive without a head."

  - name: "Guillotine Golem Poison"
    desc: " (poison) Any drained value from this poison is reduced by 1 every hour.\n* * *\n\n**Saving Throw** DC 40 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 3d6 poison and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 5d6 poison and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 10d6 poison and [[Conditions/Drained|Drained 3]] (1 round)."

  - name: "Inexorable March"
    desc: "`pf2:1`  The guillotine golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a DC 44 Fortitude check save. On a critical success, the resisting creature takes no damage; otherwise, it is damaged as if hit by the golem's blade Strike."
 
```

```encounter-table
name: Guillotine Golem
creatures:
  - 1: Guillotine Golem
```




