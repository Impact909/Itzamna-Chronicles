---
title: "Jorogumo Disciple"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5RtkUOddkvMXY7H8" 
tags:
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Jorogumo Disciple"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Jorogumo Disciple"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Aklo, Common, Fey; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +30, Crafting: +27, Deception: +31, Diplomacy: +31, Occultism: +27, Performance: +29, Religion: +29, Stealth: +29"
abilityMods: [6, 5, 5, 3, 5, 7]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +27, __Will__ +29"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315; __Weaknesses__ cold iron 10; __Resistances__ poison 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Darting Legs"
    desc: "`pf2:r`  **Requirements** The jorogumo has their spider legs extended or has Changed Shape\n\n**Trigger** The jorogumo is targeted with an attack\n* * *\n\n**Effect** The jorogumo raises a leg, gaining a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 ()\n__Damage__  3d12 + 14 piercing plus jorogumo-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile)\n__Damage__  3d8 + 14 slashing"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+25 (range increment 60 feet)\n__Damage__ "

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Speak with Animals|Speak with Animals (Spiders Only, Constant)]]_, _[[Spells/Suggestion|Suggestion]]_, _[[Spells/Summon Animal|Summon Animal (Spiders Only)]]_; __7th __  _[[Spells/Outcast's Curse|Outcast's Curse (x3)]]_; __6th __  _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Suggestion|Suggestion (x3)]]_; __3rd __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_\n__Constant__  __(8th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The jorogumo takes on the appearance of any Small or Medium spider. This doesn't change their Speed or Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Jorogumo Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 37 Fortitude check\n* * *\n\n**Maximum Duration** 4 hours\n\n**Stage 1** 3d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)\n\n**Stage 3** 4d6 poison damage and Stupefied 2 (1 round)\n\n**Stage 4** [[Conditions/Paralyzed|Paralyzed]] for 1d4 hours"

  - name: "Skilled Poisoner"
    desc: "  When the jorogumo disciple successfully Strikes an [[Conditions/Off-Guard|Off-Guard]] creature with their jaws, that creature takes a –2 circumstance penalty to its initial save against the poison."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The jorogumo's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Spider Legs"
    desc: "`pf2:1` (concentrate,occult,polymorph) **Requirements** The jorogumo is in humanoid form\n* * *\n\n**Effect** Eight large spider legs sprout from the jorogumo's back, granting them a 40-foot climb Speed and allowing them to use the Darting Legs reaction."

  - name: "Web Trap"
    desc: "  A creature hit by the jorogumo's web attack is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface, preventing the creature from moving.\n\nThe DC to [[Actions/Escape|Escape]] or [[Actions/Force Open|Force Open]] the web trap is 37."
 
```

```encounter-table
name: Jorogumo Disciple
creatures:
  - 1: Jorogumo Disciple
```


Variant jorogumo

Appearing as beautiful, well-dressed humans, jorogumo lurk in the high mountains and prey on travelers. These evil creatures can fully change into a giant spider or sprout spider legs from their backs, and they often keep giant spiders as pets. Jorogumo usually eat their prey, but some humanoids meet an even more gruesome fate as living incubators for jorogumo eggs. Though most jorogumos are solitary creatures, some have taken up worship of Norgorber and serve as valuable allies to thieves' guilds following that god's guise as the Gray Master.
