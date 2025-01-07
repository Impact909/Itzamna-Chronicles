---
title: "Chalky"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fVgU7IdhRLJA0PUz" 
tags:
  - pf2e/creature/type/alchemical
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Chalky"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Chalky"
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
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +19, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  acid,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 12 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alchemical Chambers"
    desc: "  An alchemical golem's body contains six alchemical chambers filled with different substances. When an alchemical golem ability calls upon a randomly determined alchemical effect, roll 1d6 and consult the following :\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | [[Equipment/Elixir of Life (Lesser)\\|Elixir of Life (Lesser)]] |\n| 2 | [[Equipment/Bomber's Eye Elixir (Lesser)\\|Bomber's Eye Elixir (Lesser)]] |\n| 3 | [[Equipment/Bravo's Brew (Moderate)\\|Bravo's Brew (Moderate)]] |\n| 4 | [[Equipment/Cat's Eye Elixir\\|Cat's Eye Elixir]] |\n| 5 | [[Equipment/Cheetah's Elixir (Moderate)\\|Cheetah's Elixir (Moderate)]] |\n| 6 | [[Equipment/Juggernaut Mutagen (Greater)\\|Juggernaut Mutagen (Greater)]] |"

  - name: "Alchemical Rupture"
    desc: "  When an alchemical golem takes physical damage from a critical hit or is affected by a [[Spells/Shatter|Shatter]] spell, one glass chamber within its body shatters, spewing alchemical liquid in a 5-foot emanation.\n\nRoll on the alchemical chambers list to determine which one shatters - all creatures within a 5-foot emanation are affected by the elixir in the randomly rolled alchemical chamber, and these creatures may forego their Reflex saves against the effect if they wish."

  - name: "Golem Antimagic"
    desc: "  harmed by sonic (5d8 untyped, 2d6 untyped from areas or persistent damage); healed by acid (area 2d4 healing Hit Points); slowed by cold\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Shatter"
    desc: "  Casting a [[Spells/Shatter|Shatter]] spell on an alchemical golem affects the golem normally, but also causes an alchemical rupture."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Syringe"
    desc: "+22 (magical, reach 10 feet)\n__Damage__  2d10 + 6 piercing plus alchemical-injection"

  - name: "Alchemical Injection"
    desc: "  When an alchemical golem hits a creature with a syringe Strike, roll 1d6 on the alchemical chambers list to determine the additional effect of the attack.\n\nChalky's alchemical chambers are filled with helpful potions and elixirs rather than harmful substances. When Chalky targets an ally with its syringe Strike, the ally takes no damage and doesn't need to make a save against the rolled effect."
 
```

```encounter-table
name: Chalky
creatures:
  - 1: Chalky
```



This golem is a walking alchemical nightmare capable of inflicting all manner of painful wounds. Its ability to follow orders is granted by the otherwise mindless humanoid brain that floats in its dome-like head. In exceptionally rare cases, the brain used in its creation might retain fragments of memories or even actual intellect, resulting in an alchemical golem with a personality and agenda of its own.
