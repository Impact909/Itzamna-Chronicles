---
title: "Titan Centipede"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W0Qk0RXQvx16j8S5" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Titan Centipede"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Titan Centipede"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +21"
abilityMods: [8, 1, 5, -5, 5, -4]
speed: 50 feet,  climb 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +16, __Will__ +18"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+21 (reach 20 feet)\n__Damage__  2d10 + 12 piercing plus titan-centipede-venom"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+19 ()\n__Damage__  2d8 + 10 bludgeoning"

  - name: "Impaling Critical"
    desc: "  When a titan centipede scores a critical hit with its mandibles, the target is painfully pierced with barbed spines and bristles, taking 1d6 bleed and becoming [[Conditions/Off-Guard|Off-Guard]] as long as the bleed damage continues."

  - name: "Titan Centipede Venom"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 2d8 poison damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 3** 2d10 poison damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Slowed|Slowed 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 28 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Undulate"
    desc: "`pf2:1`  The titan centipede Strides up to its Speed or Steps. During this movement, it can pass through spaces as narrow as 10 feet without [[Actions/Squeeze|Squeezing]]."
 
```

```encounter-table
name: Titan Centipede
creatures:
  - 1: Titan Centipede
```



These colossal, solitary centipedes claim vast hunting grounds.
