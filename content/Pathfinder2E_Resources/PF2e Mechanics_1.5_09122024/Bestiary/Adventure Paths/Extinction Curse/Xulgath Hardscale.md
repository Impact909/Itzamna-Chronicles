---
title: "Xulgath Hardscale"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8c5XdCf8bh3epr9S" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Xulgath Hardscale"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Xulgath Hardscale"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +23, Diplomacy: +19, Intimidation: +21, Nature: +19, Stealth: +19, Survival: +21"
abilityMods: [5, 3, 4, 0, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +25, __Ref__ +22, __Will__ +19"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Javelin|Javelin]], [[Equipment/Warhammer|+1 Striking Warhammer]], [[Equipment/Sturdy Shield (Lesser)|Sturdy Shield (Lesser)]], [[Equipment/Breastplate|+1 Resilient Breastplate]], [[Equipment/Elixir of Life (Moderate)|Elixir of Life (Moderate)]], Necklace of Bone and Gems"
abilities_mid:
  - name: ""
  - name: "Aggressive Block"
    desc: "`pf2:0`  **Trigger** The hardscale uses the [[Bestiary Ability Glossary/Shield Block|Shield Block]] reaction, and the opponent that triggered Shield Block is adjacent to the hardscale and is not more than one size larger than it\n* * *\n\n**Effect** The hardscale makes an Athletics check to [[Actions/Shove|Shove]] the opponent. This shove doesn't increase the hardscale's multiple attack penalty. If they roll a critical failure, they get a failure instead. If they roll a success, they get a critical success instead."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Hardscale Shield Stance"
    desc: "  A hardscale always has their shield raised as if they had used the [[Actions/Raise a Shield|Raise a Shield]] action, as long as they meet that action's requirements."

  - name: "Powerful Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 32 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]], and on a critical failure, the creature is also [[Conditions/Slowed|Slowed 1]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stenches for 1 minute."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  At the beginning of each of their turns, the hardscale receives an additional reaction that they can use only for Shield Block.\n* * *\n\n**Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "Shield Warden"
    desc: "  If the hardscale has their shield raised, they can [[Bestiary Ability Glossary/Shield Block|Shield Block]] when an attack is made against an adjacent ally. If they do, the shield prevents that ally from taking damage instead of the hardscale."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+24 (magical, shove, deadly 2d8)\n__Damage__  2d8 + 11 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 ()\n__Damage__  3d6 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile)\n__Damage__  3d4 + 11 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+21 (thrown 20 ft.)\n__Damage__  1d6 + 11 piercing"

  - name: "Hammer Mastery"
    desc: "  The hardscale deals an extra 1d8 damage with weapons with the shove trait, and weapons with the shove trait gain the deadly 2d8 trait when the hardscale uses them (both the extra weapon damage die and the deadly trait have already been included in the hardscale's warhammer Strike above)."
 
```

```encounter-table
name: Xulgath Hardscale
creatures:
  - 1: Xulgath Hardscale
```




