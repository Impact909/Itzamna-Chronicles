---
title: "Lazurite-Infused Stone Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i9NjiTDoEkiXMDAD" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Lazurite-Infused Stone Golem"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Lazurite-Infused Stone Golem"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +28"
abilityMods: [8, -1, 5, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +19, __Will__ +20"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  acid,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by _cold_ and _vitality_ (5d10, 2d8 from areas or persistent damage); healed by _void_ (area 2d8 healing Hit Points); slowed by _earth_\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Necrotic Field"
    desc: " (aura,divine) 30 feet. Vitality energy effects within the golem's necrotic field deal only half their normal damage. Additionally, all undead within its aura deal an additional 1d6 void damage with their natural attacks.\n\n[[Bestiary Effects/Effect_ Necrotic Field|Effect: Necrotic Field]]"

  - name: "Vulnerable to Stone to Flesh"
    desc: "  A [[Spells/Stone to Flesh|Stone to Flesh]] spell negates the golem's antimagic and its resistance to physical damage for 1 round. A [[Spells/Petrify|Petrify]] spell reverses this effect immediately."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (magical, reach 10 feet)\n__Damage__  2d10 + 11 bludgeoning 2d6 void"

  - name: "Inexorable March"
    desc: "`pf2:1`  The golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can bar the way by succeeding at a DC 36 Fortitude check save. On a critical success, the resisting creature takes no damage; otherwise, it takes damage equal to that dealt by the golem's fist Strike"

  - name: "Necrotic Affliction"
    desc: "`pf2:r`  **Trigger** The golem hits a slowed creature.\n* * *\n\n**Effect** The creature must succeed at a DC 34 Fortitude check save or become [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] on a critical failure) as the golem's lazurite leeches vital energies and causes wounds to rot."

  - name: "Necrotic Pulse"
    desc: "`pf2:1` (arcane,concentrate,disease,void) Each creature in a 10-foot emanation must succeed at a DC 32 Fortitude check save or take 1d6 persistent void damage and be [[Conditions/Slowed|Slowed 1]] for 1 minute as their flesh and bones temporarily atrophy. The golem can't use Necrotic Pulse again for 1d4 rounds."
 
```

```encounter-table
name: Lazurite-Infused Stone Golem
creatures:
  - 1: Lazurite-Infused Stone Golem
```




