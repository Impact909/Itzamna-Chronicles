---
title: "Abendego Jailer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Uyh5pyM8UjiABB3i" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Abendego Jailer"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #171: Hurricane&#x27;s Howl"
name: "Abendego Jailer"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +21, Intimidation: +18, Thievery: +20"
abilityMods: [5, 4, 1, 0, 3, 2]
speed: 20 feet
sourcebook: "_Pathfinder #171: Hurricane&#x27;s Howl_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +21, __Will__ +17"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|Mancatcher]], [[Equipment/Dagger|Dagger]], [[Equipment/Scale Mail|+1 Scale Mail]], [[Equipment/Manacles (Average)|Manacles (Average)]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol of Norgorber (Wooden)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mancatcher"
    desc: "+23 (reach 10 feet)\n__Damage__  1d8 + 9 slashing plus restrain"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+23 (agile, versatile s)\n__Damage__  1d4 + 9 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+22 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 9 piercing"

  - name: "Restrain"
    desc: "  When the jailer makes a successful mancatcher Strike, their target must succeed at a DC 27 Reflex check save or become [[Conditions/Grabbed|Grabbed]] until the end of the jailer's next turn.\n\nEach time the target fails an attempt to [[Actions/Escape|Escape]] the jailer, it takes 2d6 piercing damage."

  - name: "Subduing Attack"
    desc: "  Abendego jailers deal an additional 3d6 precision damage to creatures that are [[Conditions/Frightened|Frightened]] or within reach of at least one of their allies.\n\nThe jailer can make an attack with this additional damage as a nonlethal attack, if they choose."
 
```

```encounter-table
name: Abendego Jailer
creatures:
  - 1: Abendego Jailer
```


Human prison guard


