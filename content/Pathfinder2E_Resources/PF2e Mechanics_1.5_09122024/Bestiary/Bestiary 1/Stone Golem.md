---
title: "Stone Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dZWklCNsYUdOkWwz" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Stone Golem"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Stone Golem"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +26"
abilityMods: [7, -1, 4, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +18, __Will__ +19"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  acid,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by cold and water (5d10 damage, 2d8 damage from areas or persistent damage); healed by acid (area 2d8 healing Hit Points); slowed by earth\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Stone to Flesh"
    desc: "  A [[Spells/Stone to Flesh|Stone to Flesh]] spell negates the golem's golem antimagic and its resistance to physical damage for 1 round. A [[Spells/Petrify|Petrify]] spell reverses this effect immediately."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (magical, reach 10 feet)\n__Damage__  2d10 + 13 bludgeoning"

  - name: "Impose Paralysis"
    desc: "`pf2:r` (incapacitation) **Trigger** The stone golem hits a [[Conditions/Slowed|Slowed]] creature.\n* * *\n\n**Effect** The creature must succeed at a DC 30 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]] for 1 round."

  - name: "[[Creature Family Ability Glossary/(Golem) Inexorable March|Inexorable March]]"
    desc: "`pf2:1`  DC 34 Fortitude check\n\nOn a critical success, the resisting creature takes no damage; otherwise it is damaged as if hit by the golem's fist.\n* * *\n\nThe golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a Fortitude save."

  - name: "Slowing Pulse"
    desc: "`pf2:1` (arcane,concentrate) Each creature in a 10-foot emanation must succeed at a DC 30 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] for 1 minute.\n\nThe golem can't use Slowing Pulse again for 1d4 rounds."
 
```

```encounter-table
name: Stone Golem
creatures:
  - 1: Stone Golem
```



Stone golems are slow and steady constructs typically carved from marble or granite. They're often made to serve as works of art when at rest, so some golem crafters employ master sculptors to ensure the constructs make beautiful statues. Older stone golems might be weathered, with scuffed or cracked surfaces or missing noses and digits, but this weathering is largely cosmetic and doesn't adversely impact the golems' functionality.

Tales tell of particularly immense stone golems residing in certain ancient ruins. Survivors from time-lost civilizations bent on carrying out orders from long-gone masters, these immense stone golems are much more powerful than most stone golems. They are always level 15 or higher and never smaller than Huge in size-most are Gargantuan. Because their size is so great and the structures they dwell in so dilapidated, the awakening of such a stone golem can cause surrounding structures to collapse, ancient foundations to buckle, and ceilings to come crashing down on foes. In addition to the statistics here, these massive stone golems attack with wide, sweeping strikes capable of knocking down multiple targets at once.

* * *

Crafted of base materials and then magically animated into a powerful guardian, the legendary golem is a living construct that mindlessly obeys its creator's commands-often continuing to do so for years or even centuries after its creator's death. There exist two known methods of animating a golem. The traditional method involves harvesting and implanting an elemental soul or essence within the newly crafted host statue, a procedure seen as vile and blasphemous to those who value the sanctity of the soul; evil or amoral golem crafters tend to prefer this method. The other, less disreputable technique involves siphoning pure vitality energy into the statue to artificially imitate the creation of a soul. The result does not give the golem a true soul and is generally a more costly and time-consuming method of creation. Regardless of the method used, the resulting golem functions the same. A golem's unique animating force leaves it susceptible to certain forms of magic, but apart from these few weaknesses, it is impervious to magic and difficult to damage with weapons.

Golems work best in play as foes to vanquish rather than allies to accompany player characters on adventures. The process of creating a golem is time-consuming, expensive, and difficult, and only the most talented spellcasters or artisans can even hope to accomplish such an undertaking. While certain magical texts-so-called "golem manuals"-are said to aid golems crafters, for the most part the creation of a golem should be something left in the hands of the Game Master.

Golems have components that can be harvested as trophies or magical components; the value depends on the golem in question. Examples of components that can be harvested from golems are listed in the sidebars.
