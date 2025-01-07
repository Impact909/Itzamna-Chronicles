---
title: "Solar Glass Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XfPziYN8AJ5iM73M" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Solar Glass Golem"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Solar Glass Golem"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
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
    desc: "Acrobatics: +20, Athletics: +22, Stealth: +18"
abilityMods: [7, 5, 7, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +20, __Ref__ +20, __Will__ +17"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Golem Antimagic"
    desc: "  Harmed by sonic (8d6, 2d6 from areas or persistent damage); healed by fire (area 2d6 HP); slowed by cold\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Spell Reflection"
    desc: "`pf2:r` (arcane) **Trigger** The glass golem is targeted by a spell\n* * *\n\n**Effect** The glass golem positions its magical, reflective surfaces to turn the spell back on the caster. It tries to counteract the spell by attempting an Acrobatics check for its counteract check. If it successfully counteract the spell, the effect is turned back on the caster."

  - name: "Vulnerable to Shatter"
    desc: "  A glass golem is affected by the [[Spells/Shatter|Shatter]] spell as though the golem were an unattended object."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stained Glass Frame"
    desc: "+24 (agile, magical, versatile p)\n__Damage__  2d6 + 13 slashing 1d6 bleed"

  - name: "Solar Flare"
    desc: "`pf2:2` (light) The glass golem holds up its stained-glass frame and angles it downward, causing the image of the sun in the artwork to flash brightly, illuminating a 30-foot cone. This blast of light deals 8d6 fire damage to creatures in the area, plus 4d6 additional vitality damage to undead creatures. Each creature in the area must attempt a DC 30 Reflex check save. If this solar flare overlaps an area of magical darkness, it attempts to counteract the darkness effect (+22 counteract check).\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Dazzled|Dazzled]] for 1 minute.\n\n**Critical Failure** The creature takes full damage and is [[Conditions/Blinded|Blinded]] permanently."
 
```

```encounter-table
name: Solar Glass Golem
creatures:
  - 1: Solar Glass Golem
```


Variant glass golem

Crafted of hardened glass and held together by magically treated lead, glass golems are both deadly guardians and works of exquisite art. Glass golems most often protect grand cathedrals or opulent palaces-testaments to the wealth and power of those they serve, or once served. Once spurred into action by the commands of their creators, glass golems are quicker and more agile than most other golems. Their sharp, blade-like limbs can easily sever veins and arteries, creating wounds that bleed profusely.

Of all the various types of golems, the glass golem is the one most akin to a work of art. Just as powerful aristocrats might use an ice golem for temperature regulation or a wood golem as an ego-boosting statue, a glass golem's colorful glass construction can elevate the beauty of any chamber by its mere presence.
