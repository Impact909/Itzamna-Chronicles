---
title: "Orc Veteran"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pLp0ZHmMgE2gZCS8" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Orc Veteran"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Orc Veteran"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Orcish, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Intimidation: +4, Survival: +4"
abilityMods: [4, 2, 3, -1, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +7, __Will__ +4"
hp: 23
health:
  - name: ""
  - name: HP
    desc: "23"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x [[Equipment/Javelin|Javelin]], [[Equipment/Orc Necksplitter|Orc Necksplitter]], 2x [[Equipment/Shortsword|Shortsword]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Necksplitter"
    desc: "+7 (forceful, sweep)\n__Damage__  1d8 + 4 slashing"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+7 (agile, versatile p)\n__Damage__  1d6 + 4 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+5 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"
 
```

```encounter-table
name: Orc Veteran
creatures:
  - 1: Orc Veteran
```



Orc veterans have survived several bloody and chaotic conflicts, coming out the other side with scars and experience that make them even more dangerous opponents.

* * *

Many orcs are forged in the fires of violence and conflict, often from the moment they're born. As they live lives that are frequently cut brutally short, orcs revel in testing their strength against worthy foes, whether by challenging a higher-ranking member of their community for dominance, taming a powerful beast, or slaying a fearsome monster.

Tall and powerful, with long arms and thickly muscled legs, many orcs top 7 feet in height. Their heavy limbs and broad, almost bow-legged stances combine with a tendency to slouch forward to create an almost contradictory set of circumstances where an orc can tower over other humanoids while simultaneously staring them in the eye. These features, alongside a tendency to scar easily, can make them seem quite intimidating.

The half-orc dromaars, most commonly born of unions between orcs and humans, are often tested even more harshly than their full orc kin, but those who endure these tests can rise to positions of authority. "An orc can have what an orc can hold" is a saying that not only applies to an individual's ability to secure their own destiny and position, but is also likely the root of orcs referring to their communities as holds.
