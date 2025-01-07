---
title: "Cursebreaker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PuqNQSbeFHI5vYLt" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Cursebreaker"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Cursebreaker"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23, Kibwe Lore: +12"
abilityMods: [6, 0, 4, -5, 3, -5]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +17, __Will__ +20"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  acid,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by cold and water (5d8 damage, 2d6 damage from areas or persistent damage); healed by acid (area 2d6 healing Hit Points); slowed by earth\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Stone to Flesh"
    desc: "  A [[Spells/Stone to Flesh|Stone to Flesh]] spell negates Cursebreaker's golem antimagic and its resistance to physical damage for 1 round.\n\nA [[Spells/Petrify|Petrify]] spell reverses this effect immediately."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+21 (magical, reach 10 feet)\n__Damage__  2d10 + 10 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 0, attack +0; __10th __  _[[Compendium.pf2e.spells-srd.Item.OyFCwQuw8XRazsNr|Remove Curse (At Will) (See Undo Curse)]]_"

  - name: "Impose Paralysis"
    desc: "`pf2:r` (incapacitation) **Trigger** Cursebreaker hits a [[Conditions/Slowed|Slowed]] creature\n* * *\n\n**Effect** The creature must succeed at a DC 27 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]] for 1 round."

  - name: "[[Creature Family Ability Glossary/(Golem) Inexorable March|Inexorable March]]"
    desc: "`pf2:1`  DC 32 Fortitude check\n\nOn a critical success, the resisting creature takes no damage; otherwise it is damaged as if hit by Cursebreaker's fist.\n* * *\n\nThe golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a Fortitude save."

  - name: "Slowing Pulse"
    desc: "`pf2:1` (arcane,concentrate) Each creature in a 10-foot emanation must succeed at a DC 27 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] for 1 minute.\n\nCursebreaker can't use Slowing Pulse again for 1d4 rounds."

  - name: "Undo Curse"
    desc: "  Cursebreaker can cast a 10th-rank [[Spells/Cleanse Affliction|Cleanse Affliction]] spell at will, targeting every resident of the city of Kibwe. Cursebreaker must be stationed in the upper level of the Archive of the Sun with its sun symbols activated to use this ability."
 
```

```encounter-table
name: Cursebreaker
creatures:
  - 1: Cursebreaker
```


Variant stone golem


