---
title: "Noxious Needler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dCgmUxfwWMNzuaIK" 
tags:
  - pf2e/creature/type/alchemical
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Noxious Needler"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Noxious Needler"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[alchemical]]
trait_02: [[construct]]
trait_03: [[mindless]]
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
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +19, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine or bludgeoning), spells 10 (except sonic)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alchemical Chambers"
    desc: "  A noxious needler's body contains six alchemical chambers filled with different substances. When a noxious needler's ability calls upon a randomly determined alchemical effect, roll 1d6 and consult the following (if you roll the result of a chamber that was shattered, there is no alchemical effect):\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | Acid Damage |\n| 2 | Cold Damage |\n| 3 | Electricity Damage |\n| 4 | Fire Damage |\n| 5 | Poison Damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

  - name: "Alchemical Rupture"
    desc: "  When a noxious needler takes physical damage from a critical hit or is affected by a shatter spell, one glass chamber within its body shatters, spewing alchemical liquid in a 5-foot emanation. Roll on the alchemical chambers list to determine which one shatters—on a roll of 1–5, creatures in the area take 10d6 damage of the appropriate type (DC 28 basic Reflex). On a roll of 6, creatures must instead save against the sickness effect.\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | 10d6 acid damage DC 28 Reflex check |\n| 2 | 10d6 cold damage DC 28 Reflex check |\n| 3 | 10d6 electricity damage DC 28 Reflex check |\n| 4 | 10d6 fire damage DC 28 Reflex check |\n| 5 | 10d6 poison damage DC 28 Reflex check |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Syringe"
    desc: "+22 (magical, reach 10 feet)\n__Damage__  2d10 + 6 piercing plus alchemical-injection"

  - name: "**Ranged** `pf2:1` Bomb"
    desc: "+20 (magical, thrown 20 ft.)\n__Damage__ "

  - name: "Alchemical Injection"
    desc: "  When a noxious needler hits a creature with a syringe Strike, roll 1d6 on the alchemical chambers list to determine the additional effect of the attack. The syringe deals an additional 2d6 damage of the appropriate type (or exposes the target to the sickness effect, as appropriate).\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | 2d6 acid damage |\n| 2 | 2d6 cold damage |\n| 3 | 2d6 electricity damage |\n| 4 | 2d6 fire damage |\n| 5 | 2d6 poison damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"

  - name: "Generate Bomb"
    desc: "`pf2:1` (manipulate) The needler fills an empty vial from one of its alchemical chambers to create a bomb and then makes a bomb Strike. Roll 1d6 on the table below. On a roll of 1–5, the bomb deals 3d10 damage and 3 splash damage, matching the damage type of the chamber; you can instead choose to create an alchemical bomb of 11th level or lower that deals the same damage type, such as an acid flask on a roll of 1. On a roll of 6, it creates a sickness bomb, which exposes the target and all creatures in the splash radius to the sickness effect; creatures hit by only the splash receive a +2 circumstance bonus to their Fortitude saves.\n\n  \n\n| 1d6 | Alchemical Effect |\n| --- | --- |\n| 1 | Acid Damage: 3d10 acid + 3 splash acid damage |\n| 2 | Cold Damage: 3d10 cold + 3 splash cold damage |\n| 3 | Electricity Damage: 3d10 electricity + 3 splash electricity damage |\n| 4 | Fire Damage: 3d10 fire + 3 splash fire damage |\n| 5 | Poison Damage: 3d10 poison + 3 splash poison damage |\n| 6 | Sickness: DC 26 Fortitude check save or [[Conditions/Sickened\\|Sickened 1]] ([[Conditions/Sickened\\|Sickened 2]] on a critical failure) |"
 
```

```encounter-table
name: Noxious Needler
creatures:
  - 1: Noxious Needler
```



This construct is a walking alchemical nightmare capable of inflicting all manner of painful wounds. The noxious needlers' ability to follow orders is granted by the otherwise mindless humanoid brain that floats in their dome-like heads, allowing them to serve as laborers and guards for their creators.

In exceptionally rare cases, the brain used in their creation might retain fragments of memories or even an actual intellect, resulting in a noxious needler with a personality and agenda of its own. Unwilling creations often hunt down their creators, venting their rage on similar targets if revenge is impossible. Others blankly replicate the experiments from their last memory
