---
title: "Adamantine Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i6VMv7VpN8rt62pK" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Adamantine Golem"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Adamantine Golem"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
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
    desc: "Athletics: +38"
abilityMods: [9, -1, 9, -5, 0, -5]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +33, __Ref__ +27, __Will__ +29"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, repair mode; __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 20 (except vorpal adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by acid (9d10 untyped damage, 2d10 untyped damage from areas or persistent damage); healed by fire (area 2d10 healing Hit Points); slowed by electricity\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Repair Mode"
    desc: "  When the adamantine golem is at 0 HP, it isn't destroyed. Instead, it enters repair mode, during which it is [[Conditions/Slowed|Slowed 1]], can't take reactions, and can take only the Self-Repair action.\n\nOnce it has more than 30 HP, it can use any type of action and can use reactions, though it remains slowed 1 and can't take any reactions until the start of its next turn.\n\nIf a critical hit with an adamantine _[[Equipment/Vorpal|Vorpal]]_ weapon reduces the golem to 0 HP, or if such a weapon hits it while it's already at 0 HP, then the golem is destroyed."

  - name: "Vulnerable to Dispelling"
    desc: "  The golem can be targeted by [[Spells/Disjunction|Disjunction]] and [[Spells/Dispel Magic|Dispel Magic]].\n\nIf targeted by such a spell of 9th level or higher, the golem has its resistance to physical damage lowered to 15 and is [[Conditions/Slowed|Slowed 1]] (or [[Conditions/Slowed|Slowed 2]] if in repair mode) for 1d4 rounds. During this time, if the golem is reduced to 0 HP while already in repair mode, it is destroyed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+35 (deadly 3d12, magical, reach 15 feet)\n__Damage__  3d10 + 17 bludgeoning plus destructive-strike"

  - name: "Destructive Strike"
    desc: "  On a critical hit, the adamantine golem's fist Strike breaks the target's armor, if any, in addition to dealing damage to the target. If the target has a shield raised, the golem breaks the shield instead."

  - name: "[[Creature Family Ability Glossary/(Golem) Inexorable March|Inexorable March]]"
    desc: "`pf2:1`  DC 45 Fortitude check\n\n**Critical Success** The creature takes no damage and its armor takes no damage.\n\n**Success** The golem halts its movement and cannot enter the creature's square.\n\n**Failure** The resisting creature is damaged and its armor takes damage as if hit by the adamantine golem's fist.\n* * *\n\nThe golem Strides up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a Fortitude save."

  - name: "Self-Repair"
    desc: "`pf2:1` (manipulate) The golem repairs itself, regaining 30 healing Hit Points."

  - name: "Vent"
    desc: "`pf2:1` (fire) The golem vents a 30-foot cone of superheated steam from its internal forge. This deals 15d6 fire damage to all creatures in the cone (DC 40 Reflex check).\n\nThe golem can't use Vent again for 1d6 rounds."
 
```

```encounter-table
name: Adamantine Golem
creatures:
  - 1: Adamantine Golem
```



Crafted from a nigh-indestructible metal of great rarity, adamantine golems can't be destroyed except by the most powerful foes. Crafting an adamantine golem requires a quantity of adamantine so massive that collecting it usually requires mounting a mining expedition to a distant planet, the Plane of Earth, or an Outer Plane.

* * *

Crafted of base materials and then magically animated into a powerful guardian, the legendary golem is a living construct that mindlessly obeys its creator's commands-often continuing to do so for years or even centuries after its creator's death. There exist two known methods of animating a golem. The traditional method involves harvesting and implanting an elemental soul or essence within the newly crafted host statue, a procedure seen as vile and blasphemous to those who value the sanctity of the soul; evil or amoral golem crafters tend to prefer this method. The other, less disreputable technique involves siphoning pure vitality energy into the statue to artificially imitate the creation of a soul. The result does not give the golem a true soul and is generally a more costly and time-consuming method of creation. Regardless of the method used, the resulting golem functions the same. A golem's unique animating force leaves it susceptible to certain forms of magic, but apart from these few weaknesses, it is impervious to magic and difficult to damage with weapons.

Golems work best in play as foes to vanquish rather than allies to accompany player characters on adventures. The process of creating a golem is time-consuming, expensive, and difficult, and only the most talented spellcasters or artisans can even hope to accomplish such an undertaking. While certain magical texts-so-called "golem manuals"-are said to aid golems crafters, for the most part the creation of a golem should be something left in the hands of the Game Master.

Golems have components that can be harvested as trophies or magical components; the value depends on the golem in question. Examples of components that can be harvested from golems are listed in the sidebars.
