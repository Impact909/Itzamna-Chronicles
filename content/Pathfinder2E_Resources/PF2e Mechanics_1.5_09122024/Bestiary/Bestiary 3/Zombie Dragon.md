---
title: "Zombie Dragon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PAX7EivY2Ya2Shan" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Zombie Dragon"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Zombie Dragon"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[zombie]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +19"
abilityMods: [6, 3, 4, -5, 3, -2]
speed: 30 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +18, __Will__ +16"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  The zombie dragon is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Upper Jaw"
    desc: "+21 (reach 15 feet)\n__Damage__  2d10 + 12 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, reach 10 feet)\n__Damage__  2d8 + 12 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 (reach 20 feet)\n__Damage__  2d6 + 10 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2`  The zombie dragon breathes a wave of fetid viscera that deals 5d6 bludgeoning damage and 5d6 poison damage (DC 28 Reflex check save). A creature that critically fails is also [[Conditions/Sickened|Sickened 2]].\n\nThe zombie dragon can't use Breath Weapon again for 1d4 rounds."
 
```

```encounter-table
name: Zombie Dragon
creatures:
  - 1: Zombie Dragon
```



The rotted husk of a once great dragon, this abomination has lost all its former splendor, but none of the ferocity. Its patchy, rotted wings don't generate enough lift to keep it aloft, but the foul necromantic energies animating it still allow it to fly, albeit slowly.

* * *

Necromancers most often create these mindless undead as obedient, expendable servitors. Left to its own devices, a zombie seeks only to consume the living, stopping only when its rotting body can no longer hold together.
