---
title: "Catoblepas"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nerj4u3jhWQQ6nbN" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Catoblepas"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Catoblepas"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Intimidation: +20, Stealth: +22, Survival: +20"
abilityMods: [7, 4, 6, -2, 4, 2]
speed: 35 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +20, __Will__ +22"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  disease,  poison,  olfactory"
abilities_top:
  - name: ""

  - name: "Stench"
    desc: " (aura,disease,olfactory) 30 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 30 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as itʼs sickened on a critical failure).\n\nWhile within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (magical, reach 10 feet)\n__Damage__  3d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+25 (magical, reach 15 feet)\n__Damage__  3d12 + 13 piercing"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+23 (magical)\n__Damage__  3d10 + 11 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2` (poison,primal) The catoblepas breathes a 60-foot cone of horrid fumes, dealing 13d6 poison damage (DC 32 Fortitude check save). The area of this cone is reduced to 30 feet underwater. Targets that fail their saving throw also become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure).\n\nThe catoblepas can't use its Breath Weapon again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, hoof, DC 32 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Catoblepas
creatures:
  - 1: Catoblepas
```



The catoblepas is an aggressive beast at the best of times. Though it prefers swamps, the catoblepas has been know to forage in plains and forests for short periods, leaving behind hunting grounds tainted by its foul breath and noxious waste that other predators and prey alike avoid for days or even weeks thereafter. The catoblepas bullies those creatures it believes are a match for it, and eats everything weaker.

A catoblepas is 15 feet long and weighs 2,200 pounds.
