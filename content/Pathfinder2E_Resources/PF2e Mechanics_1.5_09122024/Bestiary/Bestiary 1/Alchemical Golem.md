---
title: "Alchemical Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gQlYQajrHmqdwuxO" 
tags:
  - pf2e/creature/type/alchemical
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Alchemical Golem"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Alchemical Golem"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[alchemical]]
trait_02: [[construct]]
trait_03: [[golem]]
trait_04: [[mindless]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +22"
abilityMods: [6, 4, 3, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +19, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  acid,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 12 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alchemical Chambers"
    desc: "  An alchemical golem's body contains six alchemical chambers filled with different substances. When an alchemical golem ability calls upon a randomly determined alchemical effect, roll 1d6 and consult the following:\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | Acid Damage |\n| 2 | Cold Damage |\n| 3 | Electricity Damage |\n| 4 | Fire Damage |\n| 5 | Poison Damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

  - name: "Alchemical Rupture"
    desc: "  When an alchemical golem takes physical damage from a critical hit or is affected by a [[Spells/Shatter|Shatter]] spell, one glass chamber within its body shatters, spewing alchemical liquid in a 5-foot emanation.\n\nRoll on the alchemical chambers list to determine which one shatters-on a roll of 1-5, creatures in the area take 10d6 damage of the appropriate type (DC 28 Reflex check). On a roll of 6, creatures must instead save against the sickness effect.\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | 10d6 acid damage DC 28 Reflex check |\n| 2 | 10d6 cold damage DC 28 Reflex check |\n| 3 | 10d6 electricity damage DC 28 Reflex check |\n| 4 | 10d6 fire damage DC 28 Reflex check |\n| 5 | 10d6 poison damage DC 28 Reflex check |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  harmed by sonic (5d8 untyped, 2d6 untyped from areas or persistent damage); healed by acid (area 2d4 healing Hit Points); slowed by cold\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Shatter"
    desc: "  Casting a [[Spells/Shatter|Shatter]] spell on an alchemical golem affects the golem normally, but also causes an alchemical rupture."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Syringe"
    desc: "+22 (magical, reach 10 feet)\n__Damage__  2d10 + 6 piercing plus alchemical-injection"

  - name: "**Ranged** `pf2:1` Bomb"
    desc: "+20 (magical, thrown 20 ft.)\n__Damage__ "

  - name: "Alchemical Injection"
    desc: "  When an alchemical golem hits a creature with a syringe Strike, roll 1d6 on the alchemical chambers list to determine the additional effect of the attack. The syringe deals an additional 2d6 damage of the appropriate type (or exposes the target to the sickness effect, as appropriate).\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | 2d6 acid damage |\n| 2 | 2d6 cold damage |\n| 3 | 2d6 electricity damage |\n| 4 | 2d6 fire damage |\n| 5 | 2d6 poison damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

  - name: "Generate Bomb"
    desc: "`pf2:1` (manipulate) The golem fills an empty vial from one of its alchemical chambers to create a bomb and then makes a bomb Strike.\n\nDetermine the type of bomb created by rolling 1d6 on the alchemical chambers list.\n\nOn a roll of 1-4, it creates the corresponding greater alchemical bomb: an [[Equipment/Acid Flask (Greater)|Acid Flask]] from chamber 1, a [[Equipment/Frost Vial (Greater)|Frost Vial]] from chamber 2, [[Equipment/Bottled Lightning (Greater)|Bottled Lightning]] from chamber 3, or [[Equipment/Alchemist's Fire (Greater)|Alchemist's Fire]] from chamber 4.\n\nOn a roll of 5, it creates a poisonous bomb that deals 3d10 poison damage and 3 poison splash damage with no other effects.\n\nOn a roll of 6, it creates a sickness bomb, which exposes the target and all creatures in the splash radius to the sickness effect; creatures hit by only the splash receive a +2 circumstance bonus to their Fortitude saves.\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | Acid Flask: 1 acid + 3d6 persistent acid + 3 splash acid damage |\n| 2 | Frost Vial: 3d6 cold + 3 splash cold damage, and -10-foot status penalty to Speeds until end of targets next turn [[Equipment Effects/Effect_ Frost Vial (Greater)\\|Effect: Frost Vial (Greater)]] |\n| 3 | Bottled Lightning: 3d6 electricity + 3 splash electricity damage, and [[Conditions/Off-Guard\\|Off-Guard]] until start of targets next turn |\n| 4 | Alchemist's Fire: 3d8 fire + 3 persistent fire + 3 splash fire damage |\n| 5 | Poisonous Bomb: 3d10 poison + 3 splash poison damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"
 
```

```encounter-table
name: Alchemical Golem
creatures:
  - 1: Alchemical Golem
```



This golem is a walking alchemical nightmare capable of inflicting all manner of painful wounds. Its ability to follow orders is granted by the otherwise mindless humanoid brain that floats in its dome-like head. In exceptionally rare cases, the brain used in its creation might retain fragments of memories or even actual intellect, resulting in an alchemical golem with a personality and agenda of its own.

* * *

Crafted of base materials and then magically animated into a powerful guardian, the legendary golem is a living construct that mindlessly obeys its creator's commands-often continuing to do so for years or even centuries after its creator's death. There exist two known methods of animating a golem. The traditional method involves harvesting and implanting an elemental soul or essence within the newly crafted host statue, a procedure seen as vile and blasphemous to those who value the sanctity of the soul; evil or amoral golem crafters tend to prefer this method. The other, less disreputable technique involves siphoning pure vitality energy into the statue to artificially imitate the creation of a soul. The result does not give the golem a true soul and is generally a more costly and time-consuming method of creation. Regardless of the method used, the resulting golem functions the same. A golem's unique animating force leaves it susceptible to certain forms of magic, but apart from these few weaknesses, it is impervious to magic and difficult to damage with weapons.

Golems work best in play as foes to vanquish rather than allies to accompany player characters on adventures. The process of creating a golem is time-consuming, expensive, and difficult, and only the most talented spellcasters or artisans can even hope to accomplish such an undertaking. While certain magical texts-so-called "golem manuals"-are said to aid golems crafters, for the most part the creation of a golem should be something left in the hands of the Game Master.

Golems have components that can be harvested as trophies or magical components; the value depends on the golem in question. Examples of components that can be harvested from golems are listed in the sidebars.
