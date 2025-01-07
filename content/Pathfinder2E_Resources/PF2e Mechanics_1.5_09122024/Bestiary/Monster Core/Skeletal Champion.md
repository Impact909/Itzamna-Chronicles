---
title: "Skeletal Champion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pzbi2GbSlW5P7fTO" 
tags:
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Skeletal Champion"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Skeletal Champion"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[skeleton]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +8, Intimidation: +7"
abilityMods: [4, 4, 1, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19 (21 with shield raised); __Fort__ +5, __Ref__ +10, __Will__ +6"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Lance|Lance]], [[Equipment/Longsword|Longsword]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Chain Mail|Chain Mail]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+10 (versatile p)\n__Damage__  1d8 + 4 slashing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 slashing"

  - name: "**Melee** `pf2:1` Lance"
    desc: "+10 (deadly d8, jousting d6, reach 10 feet)\n__Damage__  1d8 + 4 piercing"
 
```

```encounter-table
name: Skeletal Champion
creatures:
  - 1: Skeletal Champion
```



These skeletons retain the cunning they possessed in life.

* * *

Animated skeletons are among the most common types of undead.
