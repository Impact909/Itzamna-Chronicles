---
title: "Drelev Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.k7eZYM4phI4xUui7" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Drelev Guard"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Drelev Guard"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +16"
abilityMods: [4, 2, 4, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +14, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Longsword|+1 Striking Longsword]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Breastplate|Breastplate]], 20x [[Equipment/Arrows|Arrows]], 10x [[Equipment/Gold Pieces|Gold Pieces]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Actions/Raise a Shield|Raise a Shield]]"
    desc: "`pf2:1` (general) **Requirements** You are wielding a shield\n* * *\n\nYou position your shield to protect yourself. When you have Raised a Shield, you gain its listed circumstance bonus to AC. Your shield remains raised until the start of your next turn.\n\n[[Equipment Effects/Effect_ Raise a Shield|Effect: Raise a Shield]]"

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+19 (magical, versatile p)\n__Damage__  2d8 + 8 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+17 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 8 piercing"

  - name: "Formation Fighters"
    desc: "  Drelev guard gains a +2 circumstance bonus on attack and damage rolls as long as he is adjacent to at least two other Drelev guards."

  - name: "Intimidating Strike"
    desc: "`pf2:2` (emotion,fear,mental) The Drelev guard makes a melee Strike. If he hits and deals damage, the target is [[Conditions/Frightened|Frightened 1]], or [[Conditions/Frightened|Frightened 2]] on a critical hit."
 
```

```encounter-table
name: Drelev Guard
creatures:
  - 1: Drelev Guard
```


Human fighter


