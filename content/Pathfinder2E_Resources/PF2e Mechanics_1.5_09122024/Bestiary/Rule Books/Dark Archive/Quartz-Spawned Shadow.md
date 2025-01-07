---
title: "Quartz-Spawned Shadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.do9oJroXOjZtji2R" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Quartz-Spawned Shadow"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Quartz-Spawned Shadow"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Stealth: +14"
abilityMods: [-5, 4, 0, -2, 2, 3]
speed:  fly 30 feet
sourcebook: "_Pathfinder Dark Archive_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  An object shedding magical light (such as from the [[Spells/Light|Light]] spell) is treated as magical when used to attack the shadow."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+15 (finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "Crystal Siphon"
    desc: "`pf2:2` (death,divine,void) **Requirements** The shadow and the target are both within 40 feet of the crystal that spawned the shadow, and the crystal isn't covered or obstructed\n* * *\n\n**Effect** Shadows in the shape of tendrils curl around the target, drawing out a portion of the target's vitality and siphoning it into the crystal. The target takes 4d6 void damage (DC 21 Fortitude check). On a failure, they are also [[Conditions/Enfeebled|Enfeebled 1]]. This enfeebled condition is cumulative with other enfeebled conditions from quartz-spawned shadows, to a maximum of enfeebled 4. If Crystal Siphon increases the creature's enfeebled value to 3 or more, the target's shadow is pulled entirely into the shadow's crystal.\n\nWhile the target's shadow is trapped, they feel an [[Conditions/Invisible|Invisible]] tether linking them to the crystal, and they become [[Conditions/Slowed|Slowed 1]] whenever they are more than 40 feet away from it. The enfeebled condition from Crystal Siphon can't be reduced until the crystal is broken; if the crystal is broken, the effect immediately ends."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."
 
```

```encounter-table
name: Quartz-Spawned Shadow
creatures:
  - 1: Quartz-Spawned Shadow
```



The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light. Those who parley with shadows, typically by keeping them at bay with a glowing weapon, may learn great secrets, for they are ideal spies.
