---
title: "Aspis Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1XQa3IO7Go1fzbgP" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Aspis Guard"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Aspis Guard"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Dwarven, Mwangi"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Intimidation: +10, Society: +9, Survival: +12, Aspis Consortium Lore: +9"
abilityMods: [4, 1, 3, 0, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +10, __Will__ +12"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|+1 Striking Battle Axe]], [[Equipment/Crossbow|Crossbow]], [[Equipment/Dagger|Dagger]], [[Equipment/Tower Shield|Tower Shield]], [[Equipment/Half Plate|Half Plate]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Bravery"
    desc: "  When the guard rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+16 (magical, sweep)\n__Damage__  2d8 + 8 slashing plus powerful-swing"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+15 (agile, versatile s)\n__Damage__  1d4 + 8 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+12 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 8 piercing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+12 (range increment 120 feet, reload 1)\n__Damage__  1d8 + 4 piercing"

  - name: "Powerful Swing"
    desc: "  If the guard hits with a battle axe Strike, they can choose a creature adjacent to the target and within their own reach. That creature takes slashing damage equal to the result of the battle axe's weapon damage dice."

  - name: "Unburdened Iron"
    desc: "  The guard ignores Speed reduction from armor. In addition, any time the guard takes a penalty to their Speed, deduct 5 feet from the penalty."
 
```

```encounter-table
name: Aspis Guard
creatures:
  - 1: Aspis Guard
```




