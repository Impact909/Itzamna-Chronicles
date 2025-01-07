---
title: "Crystal Sentinel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.12oOdrNVidbL5Rgb" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Crystal Sentinel"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Crystal Sentinel"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +27, Stealth: +23"
abilityMods: [8, 4, 5, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +22, __Will__ +18"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235; __Immunities__  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 15 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Golem Antimagic"
    desc: "  harmed by sonic (6d10, 2d8 from areas or persistent damage); healed by fire (area 2d10 HP); slowed by cold\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Spell Reflection"
    desc: "`pf2:r` (arcane) **Trigger** The crystal sentinel is targeted by a spell\n* * *\n\n**Effect** The crystal sentinel positions its magical, reflective surfaces to turn the spell back on the caster. It tries to counteract the spell by attempting an Acrobatics check for its counteract check. If it successfully counteract the spell, the effect is turned back on the caster."

  - name: "Vulnerable to Shatter"
    desc: "  A glass golem is affected by the [[Spells/Shatter|Shatter]] spell as though the golem were an unattended object."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bladed Limb"
    desc: "+27 (agile, magical, versatile p)\n__Damage__  3d6 + 14 slashing 1d6 bleed"

  - name: "Dazzling Brilliance"
    desc: "`pf2:2` (light,visual) The crystal sentinel creates waves of scintillating luminosity that cast bright light in a 120-foot emanation (and dim light for the next 120 feet). The light lasts until the start of the crystal sentinel's next turn, after which the crystal sentinel can't use Dazzling Brilliance for 1d4 rounds. A creature caught within the bright light or that enters the bright light must attempt a DC 33 Will check save.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Critical Failure** The creature is [[Conditions/Blinded|Blinded]] for 1 round, and then dazzled for an additional 4 rounds. While the creature remains dazzled, it's also [[Conditions/Confused|Confused]] (this additional effect has the emotion and mental traits)."
 
```

```encounter-table
name: Crystal Sentinel
creatures:
  - 1: Crystal Sentinel
```


Variant glass golem

Crafted of hardened glass and held together by magically treated lead, glass golems are both deadly guardians and works of exquisite art. Glass golems most often protect grand cathedrals or opulent palaces-testaments to the wealth and power of those they serve, or once served. Once spurred into action by the commands of their creators, glass golems are quicker and more agile than most other golems. Their sharp, blade-like limbs can easily sever veins and arteries, creating wounds that bleed profusely.

Of all the various types of golems, the glass golem is the one most akin to a work of art. Just as powerful aristocrats might use an ice golem for temperature regulation or a wood golem as an ego-boosting statue, a glass golem's colorful glass construction can elevate the beauty of any chamber by its mere presence.
