---
title: "Lignified Adamantine Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CXUjneUdfzWsAVcq" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Lignified Adamantine Golem"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Lignified Adamantine Golem"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +36"
abilityMods: [9, -1, 9, -5, 0, -5]
speed: 30 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +31, __Ref__ +25, __Will__ +27"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, repair mode; __Immunities__  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 15 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by acid (9d10 untyped damage, 2d10 untyped damage from areas or persistent damage); healed by plant (area 2d10 healing Hit Points); slowed by electricity\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Repair Mode"
    desc: "  When the golem is at 0 HP, it isn't destroyed. Instead, it enters repair mode, during which it is [[Conditions/Slowed|Slowed 1]], can't take reactions, and can take only the Self-Repair action. Once it has more than 30 HP, it can use any type of action and can use reactions, though it remains slowed 1 and can't take any reactions until the start of its next turn. If a critical hit with an adamantine weapon reduces the golem to 0 HP, or if such a weapon hits it while it's already at 0 HP, then the golem is destroyed."

  - name: "Vulnerable to Dispelling and Shape Wood"
    desc: "  The golem can be targeted by [[Spells/Disjunction|Disjunction]], [[Spells/Dispel Magic|Dispel Magic]], and [[Spells/Shape Wood|Shape Wood]]. If targeted by such a spell of 9th rank or higher, the golem has its resistance to physical damage lowered to 10 and is [[Conditions/Slowed|Slowed 1]] (or [[Conditions/Slowed|Slowed 2]] if in repair mode) for 1d4 rounds. During this time, if the golem is reduced to 0 HP while already in repair mode, it is destroyed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+33 (deadly 3d12, magical, reach 15 feet)\n__Damage__  3d10 + 15 bludgeoning plus destructive-strike"

  - name: "Destructive Strike"
    desc: "  On a critical hit, the golem's staff Strike breaks the target's armor, if any, in addition to dealing damage to the target. If the target has a shield raised, the golem breaks the shield instead."

  - name: "Inexorable March"
    desc: "`pf2:1`  The golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can try to bar the way by attempting a DC 43 Fortitude check save.\n* * *\n\n**Critical Success** The creature takes no damage and its armor takes no damage.\n\n**Success** The golem halts its movement and cannot enter the creature's square.\n\n**Failure** The resisting creature is damaged and its armor takes damage as if hit by the golem's staff."

  - name: "Self-Repair"
    desc: "`pf2:1` (manipulate) The golem repairs itself, regaining 30 Hit Points."

  - name: "Vent Splinters"
    desc: "`pf2:1` (arcane,fire) The golem vents a 30-foot cone of fiery splinters from its internal forge. This deals 13d6 piercing damage to all creatures in the cone (DC 38 Reflex check). Creatures who fail the save also take 2d6 persistent fire damage (4d6 persistent fire damage on a critical failure). The golem can't use Vent Splinters again for 1d4 rounds."
 
```

```encounter-table
name: Lignified Adamantine Golem
creatures:
  - 1: Lignified Adamantine Golem
```


Variant adamantine golem


