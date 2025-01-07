---
title: "Withered"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yHgMCkeR3MLIhB4v" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Withered"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Withered"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[zombie]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Deception: +9, Intimidation: +9, Stealth: +13"
abilityMods: [5, 4, 4, 0, 2, 0]
speed: 35 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +13, __Will__ +9"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "6x [[Equipment/Dagger|Dagger]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "Slow"
    desc: "  A withered is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+14 (agile, versatile s)\n__Damage__  1d6 + 9 piercing"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+14 (agile, versatile s)\n__Damage__  1d4 + 9 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 ()\n__Damage__  1d8 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+13 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 9 piercing"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The withered zombie deals an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Sudden Surge"
    desc: "  **Trigger** The husk zombie's turn begins\n* * *\n\n**Effect** The withered has a sudden burst of speed. They are [[Conditions/Quickened|Quickened]] this turn and can use the extra action only to Stride or Strike. If the withered's first action this turn is a melee Strike, the target is [[Conditions/Off-Guard|Off-Guard]] against the attack.\n\nThe withered can't use Sudden Surge for 1d4 rounds."
 
```

```encounter-table
name: Withered
creatures:
  - 1: Withered
```



If a husk zombie survives for several years, their body continues to dry out, their flesh hardens, and their eyes turn into pale, glowing orbs set deep into otherwise empty sockets. Known as the withered, these zombies are cunning, capable of forming complex plans and even setting traps utilizing their less-intelligent brethren to lure the unsuspecting into deadly ambushes.

* * *

Simple to create and varied in purpose, these shambling undead are often used for their strength and endless stamina to conduct boring, repetitive tasks.
