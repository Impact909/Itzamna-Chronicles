---
title: "Orc Scrapper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TOO04JQcEHYhB8a2" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Orc Scrapper"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Orc Scrapper"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Orcish, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +5, Intimidation: +2"
abilityMods: [3, 2, 2, 0, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +5, __Ref__ +4, __Will__ +2"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Javelin|Javelin]], 2x [[Equipment/Orc Knuckle Dagger|Orc Knuckle Dagger]], [[Equipment/Breastplate|Breastplate (Shoddy)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Knuckle Dagger"
    desc: "+7 (agile, disarm)\n__Damage__  1d6 + 3 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal)\n__Damage__  1d4 + 3 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+4 (thrown 30 ft.)\n__Damage__  1d6 + 3 piercing"
 
```

```encounter-table
name: Orc Scrapper
creatures:
  - 1: Orc Scrapper
```



Acting as the most common orc combat unit, orc scrappers are ferocious fighters who rely on unrelenting strength, rather than combat experience, to prove their mettle and attempt to rise in the hold's standing.

* * *

Many orcs are forged in the fires of violence and conflict, often from the moment they're born. As they live lives that are frequently cut brutally short, orcs revel in testing their strength against worthy foes, whether by challenging a higher-ranking member of their community for dominance, taming a powerful beast, or slaying a fearsome monster.

Tall and powerful, with long arms and thickly muscled legs, many orcs top 7 feet in height. Their heavy limbs and broad, almost bow-legged stances combine with a tendency to slouch forward to create an almost contradictory set of circumstances where an orc can tower over other humanoids while simultaneously staring them in the eye. These features, alongside a tendency to scar easily, can make them seem quite intimidating.

The half-orc dromaars, most commonly born of unions between orcs and humans, are often tested even more harshly than their full orc kin, but those who endure these tests can rise to positions of authority. "An orc can have what an orc can hold" is a saying that not only applies to an individual's ability to secure their own destiny and position, but is also likely the root of orcs referring to their communities as holds.
