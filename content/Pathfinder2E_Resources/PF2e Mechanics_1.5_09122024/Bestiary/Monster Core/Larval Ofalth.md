---
title: "Larval Ofalth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NNu33sgLehDlStPL" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Larval Ofalth"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Larval Ofalth"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +9"
abilityMods: [5, 1, 3, -2, 1, -2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20 (22 with trash shield raised); __Fort__ +11, __Ref__ +9, __Will__ +9"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  disease,  poison"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Item.Ki1NGG83kMOxxXDK|Trash Shield]]"
  - name: "Hide in Filth"
    desc: "  A larval ofalth can hide in any pile of filth or trash that is its size or larger, allowing it to use Stealth for initiative. If it rolls Stealth for initiative, on the first round of combat, creatures that haven't acted yet are [[Conditions/Off-Guard|Off-Guard]] to it."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 30 feet DC 19 Fortitude check\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 ()\n__Damage__  2d8 + 5 slashing plus wretched-weeps"

  - name: "**Ranged** `pf2:1` Leachate"
    desc: "+11 (range 20 feet)\n__Damage__  3d8 acid plus wretched-weeps"

  - name: "Wretched Weeps"
    desc: "  **Saving Throw** DC 19 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d4 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 1]] (1 day);\n\n**Stage 3** 2d6 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"
 
```

```encounter-table
name: Larval Ofalth
creatures:
  - 1: Larval Ofalth
```



Ofalths reproduce asexually. When they first hatch from their leathery eggs, larval ofalths resemble a tendril of flesh supported by spindly legs, but they soon cocoon themselves in trash, to serve as both armor and camouflage.

* * *

Found in castle dung heaps, city dumps, and sewers, ofalths are living amalgamations of wet detritus, sewage, and rubbish. They carry a disease called wretched weeps that causes the victim's blood to seep from its pores.
