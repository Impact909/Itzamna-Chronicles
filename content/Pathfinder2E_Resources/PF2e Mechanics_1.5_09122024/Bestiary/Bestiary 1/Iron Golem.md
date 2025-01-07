---
title: "Iron Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0HNNF9T3rkY0TfHV" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Iron Golem"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Iron Golem"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
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
sourcebook: "_Pathfinder Bestiary_"
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
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by acid (6d10 damage, 2d8 damage from areas or persistent damage); healed by fire (area 2d8 healing Hit Points); slowed by electricity\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Neutralize Poison"
    desc: "  Casting [[Spells/Cleanse Affliction|Cleanse Affliction]] on the golem deactivates its Breath Weapon for 1 minute."

  - name: "Vulnerable to Rust"
    desc: "  Magical rusting effects, like a rust monster's antennae, affect the iron golem normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+28 (magical, reach 10 feet)\n__Damage__  3d10 + 12 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,poison) The iron golem exhales poisonous gas in a 10-foot radius centered on the corner of one of the iron golem's squares.\n\nThe gas persists for 1 round. Any creature in the area (or that later enters the area) is exposed to the iron golem's poison.\n\nThe golem can't use its Breath Weapon again for 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Golem) Inexorable March|Inexorable March]]"
    desc: "`pf2:1`  DC 37 Fortitude check\n\nOn a critical success, the resisting creature takes no damage; otherwise it is damaged as if hit by the golem's fist.\n* * *\n\nThe golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a Fortitude save."

  - name: "Iron Golem Poison"
    desc: " (poison) Any [[Conditions/Drained|Drained]] value from this poison is reduced by 1 every hour.\n\n**Saving Throw** DC 33 Fortitude check\n* * *\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 8d6 poison damage and [[Conditions/Drained|Drained 3]] (1 round)"
 
```

```encounter-table
name: Iron Golem
creatures:
  - 1: Iron Golem
```



Traditionally crafted into the forms of giant suits of armor or powerful animals, iron golems are products of exquisite artistry and skill. Their articulated joints and sturdy armored bodies require great care and mathematical precision to craft, and regular cleaning and oiling ensure they don't rust over the ages. With proper care, iron golems can remain in good shape for thousands of years, being passed down for generations, as long as they aren't destroyed by meddlesome adventurers. In addition to their incredible strength, iron golems possess a potent toxic breath weapon that is often more than enough to dispatch entire groups of opponents.

* * *

Crafted of base materials and then magically animated into a powerful guardian, the legendary golem is a living construct that mindlessly obeys its creator's commands-often continuing to do so for years or even centuries after its creator's death. There exist two known methods of animating a golem. The traditional method involves harvesting and implanting an elemental soul or essence within the newly crafted host statue, a procedure seen as vile and blasphemous to those who value the sanctity of the soul; evil or amoral golem crafters tend to prefer this method. The other, less disreputable technique involves siphoning pure vitality energy into the statue to artificially imitate the creation of a soul. The result does not give the golem a true soul and is generally a more costly and time-consuming method of creation. Regardless of the method used, the resulting golem functions the same. A golem's unique animating force leaves it susceptible to certain forms of magic, but apart from these few weaknesses, it is impervious to magic and difficult to damage with weapons.

Golems work best in play as foes to vanquish rather than allies to accompany player characters on adventures. The process of creating a golem is time-consuming, expensive, and difficult, and only the most talented spellcasters or artisans can even hope to accomplish such an undertaking. While certain magical texts-so-called "golem manuals"-are said to aid golems crafters, for the most part the creation of a golem should be something left in the hands of the Game Master.

Golems have components that can be harvested as trophies or magical components; the value depends on the golem in question. Examples of components that can be harvested from golems are listed in the sidebars.
