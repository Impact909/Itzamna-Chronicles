---
title: "Orc Commander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aVkyJQJgPJvPVAFr" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Orc Commander"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Orc Commander"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +6, Survival: +5"
abilityMods: [4, 2, 1, -1, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +6, __Will__ +7"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|Greatclub]], 6x [[Equipment/Javelin|Javelin]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+10 (backswing, shove)\n__Damage__  1d10 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+10 (agile, shove)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+8 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "Battle Cry"
    desc: "`pf2:1` (auditory,concentrate,emotion,mental) Bellowing mightily, the orc commander gives themself and all orc allies within 60 feet a +1 status bonus to attack and damage rolls until the start of the orc commander's next turn.\n\n[[Bestiary Effects/Effect_ Battle Cry|Effect: Battle Cry]]"
 
```

```encounter-table
name: Orc Commander
creatures:
  - 1: Orc Commander
```



When orcs raid, the strongest is chosen as the leader, backed up by their siblings and other immediate family. If leadership is contested, candidates vie for control with displays of physical prowess or stirring speeches.

* * *

Many orcs are forged in the fires of violence and conflict, often from the moment they're born. As they live lives that are frequently cut brutally short, orcs revel in testing their strength against worthy foes, whether by challenging a higher-ranking member of their community for dominance, taming a powerful beast, or slaying a fearsome monster.

Tall and powerful, with long arms and thickly muscled legs, many orcs top 7 feet in height. Their heavy limbs and broad, almost bow-legged stances combine with a tendency to slouch forward to create an almost contradictory set of circumstances where an orc can tower over other humanoids while simultaneously staring them in the eye. These features, alongside a tendency to scar easily, can make them seem quite intimidating.

The half-orc dromaars, most commonly born of unions between orcs and humans, are often tested even more harshly than their full orc kin, but those who endure these tests can rise to positions of authority. "An orc can have what an orc can hold" is a saying that not only applies to an individual's ability to secure their own destiny and position, but is also likely the root of orcs referring to their communities as holds.
