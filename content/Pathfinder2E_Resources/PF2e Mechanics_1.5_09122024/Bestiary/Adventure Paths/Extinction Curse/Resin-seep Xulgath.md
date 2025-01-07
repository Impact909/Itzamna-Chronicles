---
title: "Resin-seep Xulgath"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.u5LFTRI0jNJAj1LD" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Resin-seep Xulgath"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Resin-seep Xulgath"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +20, Intimidation: +16, Survival: +19, Thievery: +21"
abilityMods: [4, 5, 3, 1, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +19, __Ref__ +23, __Will__ +17"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Weaknesses__ acid 10, slashing 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|+1 Striking Dagger]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+21 (agile, finesse, magical, versatile s)\n__Damage__  2d4 + 11 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 ()\n__Damage__  1d8 + 11 piercing plus resin-crust"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile, finesse)\n__Damage__  1d6 + 11 slashing plus resin-crust"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+21 (agile, magical, thrown 10 ft., versatile s)\n__Damage__  2d4 + 11 piercing plus xulgath-bile"

  - name: "Resin Crust"
    desc: " (incapacitation,poison) A creature damaged by a resin-seep xulgath's jaws or claw Strike must succeed at a DC 28 Reflex check save or be covered with clumps of noxious resin, taking 2d8 poison damage and a -15-foot penalty to its Speeds for 1 minute (on a critical failure, the creature is also [[Conditions/Clumsy|Clumsy 1]] for 1 minute). The creature is [[Conditions/Sickened|Sickened 1]] for as long it has a Speed penalty. A creature can spend an [[Actions/Interact|Interact]] action to scrape the resin off, decreasing the Speed penalty by 5 with each such action."

  - name: "Resin Spray"
    desc: "`pf2:2` (poison) The resin-seep xulgath flexes its pores and emits a 30-foot line of resin that deals 3d12 poison damage and knocks the target 5 feet back (DC 28 Reflex check save; on a success or critical success the target isn't knocked back, and on a critical failure the target is knocked back 10 feet). The resin-seep xulgath can't use Resin Spray again for 1d4 rounds."

  - name: "Xulgath Bile"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n\n**Maximum Duration** 1 hour\n\n**Stage 1** [[Conditions/Fatigued|Fatigued]] (1 minute).\n\n**Stage 2** Fatigued and [[Conditions/Unconscious|Unconscious]] (1 minute).\n\n_**Dev Note**: Xulgath Bile is not included on this creature's original stat block except for the ranged dagger strike. We have included it here to allow GMs to choose to use it. It is a copy from Xulgath Bilebearer and the DC has been increased to match this level._"
 
```

```encounter-table
name: Resin-seep Xulgath
creatures:
  - 1: Resin-seep Xulgath
```




