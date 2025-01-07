---
title: "Coldmire Pond"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M8jNugatjjDLRw4H" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Coldmire Pond"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Coldmire Pond"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +18"
abilityMods: [5, 3, 5, 2, 2, 0]
speed: 20 feet,  swim 50 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +19, __Will__ +13"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Shallow Waters"
    desc: "  The coldmire pond can occupy the same space as other creatures. Creatures who move through the coldmire pond treat it as difficult terrain. Two creatures both occupying the coldmire pond's space are flanking it, regardless of their actual positions within the coldmire pond."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Clammy Pseudopod"
    desc: "+20 ()\n__Damage__  2d8 + 9 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6 bludgeoning plus 1d6 cold, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Drag Below"
    desc: "`pf2:2`  **Requirements** The coldmire pond occupies the same space as a target it has [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The coldmire pond pulls the target below the surface. The target must succeed at a DC 26 Reflex check save or fall [[Conditions/Prone|Prone]] and begin drowning."

  - name: "Flash Flood"
    desc: "`pf2:2` (primal,water) Water surges out of the coldmire pond in a 20-foot emanation and crashes into nearby creatures, knocking them off their feet. Creatures in the area, as well as any creatures currently sharing the coldmire pond's space, take 4d8 bludgeoning damage and are knocked [[Conditions/Prone|Prone]] (DC 26 Reflex check save). Creatures standing inside the coldmire pond treat their result as one step worse."
 
```

```encounter-table
name: Coldmire Pond
creatures:
  - 1: Coldmire Pond
```



Coldmire ponds are often mistaken for shallow pools of water, but these sentient bodies of living water actually crawl along the ground or float through other liquids. Coldmires are dangerous ambush predators, drowning creatures that stray too close to or, even more hazardously, stand or swim inside their waters.
