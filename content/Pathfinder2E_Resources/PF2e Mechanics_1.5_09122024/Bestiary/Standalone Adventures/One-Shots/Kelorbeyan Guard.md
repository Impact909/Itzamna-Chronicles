---
title: "Kelorbeyan Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w8YWje1oB0c6SIXV" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Kelorbeyan Guard"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder One-Shot #4: Mark of the Mantis"
name: "Kelorbeyan Guard"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +12, Intimidation: +9, Society: +8"
abilityMods: [4, 3, 1, 0, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder One-Shot #4: Mark of the Mantis_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +13, __Will__ +10"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|Longsword]], [[Equipment/Sap|Sap]], [[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Lantern (Hooded)|Lantern (Hooded)]], [[Equipment/Signal Whistle|Signal Whistle]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+14 (versatile p)\n__Damage__  1d8 + 8 slashing"

  - name: "**Melee** `pf2:1` Sap"
    desc: "+14 (agile, nonlethal)\n__Damage__  1d6 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+13 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 6 piercing"

  - name: "Combat Grab"
    desc: "`pf2:1`  **Requirements** The Kelorbeyan guard has one hand free, and their target is in reach of that hand\n* * *\n\n**Effect** The guard makes a melee Strike while keeping one hand free. If the Strike hits, they grab the target using their free hand. The creature remains [[Conditions/Grabbed|Grabbed]] until the end of the guard's next turn or until it [[Actions/Escape|Escapes]], whichever comes first."

  - name: "Knockdown"
    desc: "`pf2:2`  The Kelorbeyan guard makes an attack to knock a foe off-balance, then follows up immediately with a sweep to topple them. The guard makes a melee Strike. If it hits and deals damage, they attempt an Athletics check to [[Actions/Trip|Trip]] the creature they hit. Both attacks count toward their multiple attack penalty, but the penalty doesn't increase until after they've made both."
 
```

```encounter-table
name: Kelorbeyan Guard
creatures:
  - 1: Kelorbeyan Guard
```




