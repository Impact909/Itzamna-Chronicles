---
title: "Nightmare"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iy5S8r5Mq0vsOuF8" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Nightmare"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Nightmare"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Chthonian, Daemonic, Diabolic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +16, Intimidation: +14, Survival: +12"
abilityMods: [6, 3, 3, 1, 4, 2]
speed: 40 feet,  fly 90 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +15, __Ref__ +15, __Will__ +12"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Resistances__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Smoke"
    desc: " (aura) 15 feet.\n\nThe nightmare continually exhales black smoke. Creatures within the aura are [[Conditions/Concealed|Concealed]] to those outside it, and creatures outside the aura are concealed to creatures within it. Nightmares and their riders can see through this smoke.\n\nA creature that begins its turn in the area must succeed at a DC 23 Fortitude check save or be [[Conditions/Sickened|Sickened 2]]. It's then temporarily immune to being sickened by the smoke for 1 minute. This is an inhaled poison, and the nightmare and its rider are immune to it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 (magical, unholy)\n__Damage__  2d10 + 8 piercing"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+16 (agile, fire, magical, unholy)\n__Damage__  1d8 + 8 bludgeoning 1d6 fire"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +16; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (Self and Rider Only)]]_"

  - name: "Flaming Gallop"
    desc: "`pf2:2` (divine,fire,unholy) The nightmare Strides or Flies up to triple its Speed. Its hooves burst with intense flame, dealing 3d6 fire damage with a DC 24 Reflex check save to each creature other than the nightmare's rider that the nightmare moves adjacent to during its gallop. Each creature can be affected only once during a single use of Flaming Gallop."
 
```

```encounter-table
name: Nightmare
creatures:
  - 1: Nightmare
```



Nightmares are flaming equine harbingers of death.
