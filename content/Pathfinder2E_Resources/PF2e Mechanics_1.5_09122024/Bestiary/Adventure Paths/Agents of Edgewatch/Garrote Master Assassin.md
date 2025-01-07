---
title: "Garrote Master Assassin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aUO4ot5RJ8ldeFqc" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Garrote Master Assassin"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Garrote Master Assassin"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +29, Deception: +26, Stealth: +32, Thievery: +30"
abilityMods: [5, 6, 3, 1, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +26, __Ref__ +31, __Will__ +27"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+2 Striking Crossbow, +2 Striking Dagger, +2 Resilient Studded Leather Armor, 4x Garrote Bolts, 20x Bolts"
abilities_mid:
  - name: ""
  - name: "Sidestep"
    desc: "`pf2:r`  **Trigger** The attack roll for a Strike targeting the assassin fails or critically fails\n* * *\n\n**Effect** The assassin deftly steps out of the way of the attack. If there's another creature adjacent to the assassin and within reach of the triggering attack, the assassin redirects the attack to that adjacent creature. The attacker then rerolls the Strike's attack roll against the new target."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+31 (agile, finesse, magical, versatile s)\n__Damage__  2d4 + 11 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+32 (agile, finesse, magical, thrown 10 ft., versatile s)\n__Damage__  2d4 + 11 piercing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+30 (magical, range increment 120 feet, reload 1)\n__Damage__  2d8 + 6 piercing"

  - name: "Point Blank"
    desc: "`pf2:1` (flourish) The master assassin makes a crossbow Strike against an adjacent enemy; unlike most ranged Strikes, this Strike doesn't provoke reactions. If successful, the attack deals an additional 4d8 precision damage."

  - name: "Running Reload"
    desc: "`pf2:1`  The master assassin Strides, Steps, or Sneaks, then Interacts to reload her crossbow."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The master assassin deals an additional 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Study Target"
    desc: "`pf2:3`  The master assassin observes a single target she can see, allowing her to use her Vorpal Garrote during the next round."

  - name: "Vorpal Garrote"
    desc: "`pf2:3` (death,incapacitation) **Requirements** The master assassin used Study Target during the previous round and must have a _garrote bolt_\n* * *\n\n**Effect** The master assassin makes a crossbow Strike against the target she previously studied. If she rolls a success on her attack roll, she gets a critical success instead. The target must attempt a DC 36 Fortitude check save.\n\n**Success** No additional effect.\n\n**Failure** The target takes an additional 3d12 precision damage.\n\n**Critical Failure** The target is decapitated and instantly dies unless it doesn't require a head to live."
 
```

```encounter-table
name: Garrote Master Assassin
creatures:
  - 1: Garrote Master Assassin
```




