---
title: "Reaper Skull Puffball"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FhDCIgWEeNv5MwLN" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Reaper Skull Puffball"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Reaper Skull Puffball"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[fungus]]
trait_02: [[mindless]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Stealth: +17"
abilityMods: [4, 6, 3, -5, 2, -2]
speed: 10 feet,  fly 20 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +21, __Will__ +15"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  bleed,  fatigued,  poison,  sleep,  unconscious,  mental; __Weaknesses__ fire 10, piercing 10"
abilities_top:
  - name: ""

  - name: "[[Compendium.pf2e.bestiary-ability-glossary-srd.Item.CG9ZpebqEUsftFgn|Motion Sense 60 feet]]"
    desc: "  The monster senses motion through vibrations and air movement."

abilities_mid:
  - name: ""
  - name: "Spore Explosion"
    desc: "  When the reaper skull puffball dies, it explodes, dealing 8d8 poison damage to each creature in a 20-foot emanation (DC 28 Fortitude check save).\n\nCreatures that fail their save are exposed to skull rot."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+21 (finesse, reach 10 feet)\n__Damage__  2d12 + 8 bludgeoning plus paralysis"

  - name: "Paralysis"
    desc: " (incapacitation,poison) A creature hit by the puffball's tendril must succeed a DC 28 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. The paralyzed creature can attempt a new save at the end of each of its turns."

  - name: "Skull Rot"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d8 poison damage plus [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 2** 2d8 poison damage plus enfeebled 2 and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 3** 3d8 poison damage plus enfeebled 2 and [[Conditions/Drained|Drained 2]] (1d4 rounds)"

  - name: "Spore Cloud"
    desc: "`pf2:2` (poison) The puffball releases a 30-foot cone of spores that deals 4d8 poison damage (DC 28 Fortitude check save) to creatures in the cone.\n\nCreatures that fail this save are also exposed to skull rot."
 
```

```encounter-table
name: Reaper Skull Puffball
creatures:
  - 1: Reaper Skull Puffball
```



Many benign puffball fungi cling to the detritus of forest floors in Darklands caverns. These fungi's giant versions are more mobile and dangerous.

* * *

When this fungus detects prey, its tendrils writhe and exude a paralytic toxin.
