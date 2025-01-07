---
title: "Pickled Punk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2HIcTwVwmSextH2M" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Pickled Punk"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Pickled Punk"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +5, Stealth: +7"
abilityMods: [2, 4, 3, -3, 0, -3]
speed: 20 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +8, __Ref__ +9, __Will__ +3"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 2"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Combustible"
    desc: "  The first time each round that a pickled punk takes fire damage, its fumes combust, dealing 5 fire damage to all other creatures within the area of its Suffocating Fumes aura."

  - name: "Suffocating Fumes"
    desc: " (aura,inhaled,poison) 5 feet. A creature that enters or begins its turn within the aura must attempt a DC 14 Fortitude check save, or DC 17 Fortitude check if the pickled punk is attached to the creature.\n\nOn a failed save, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+9 (agile, finesse, nonlethal)\n__Damage__  1d4 + 1 bludgeoning plus attach"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 ()\n__Damage__  1d6 + 1 piercing plus attach 2 poison plus attach"

  - name: "Attach"
    desc: "  When a pickled punk hits a target larger than itself, it uses bizarre excretions to adhere to that creature. This is similar to Grabbing the creature, but the pickled punk is not off-guard, and it moves with that creature rather than holding it in place.\n\nEach turn while attached, the pickled punk automatically deals the damage from its jaws Strike to the creature to which it's attached. It also wriggles about, gaining a +2 circumstance bonus to AC as long as it's not also grabbed or restrained."
 
```

```encounter-table
name: Pickled Punk
creatures:
  - 1: Pickled Punk
```




