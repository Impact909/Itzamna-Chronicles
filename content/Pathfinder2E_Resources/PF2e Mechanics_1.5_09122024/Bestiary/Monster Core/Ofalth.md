---
title: "Ofalth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TGi44LBwmuUPBoV6" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Ofalth"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ofalth"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Stealth: +19"
abilityMods: [7, 3, 6, -2, 2, -2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +22, __Ref__ +17, __Will__ +18"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170, filth wallow; __Immunities__  disease,  poison"
abilities_top:
  - name: ""

  - name: "Refuse Pile"
    desc: "  When they're not in danger, an ofalth can spend 1 minute settling into a 10-foot pile that looks like a heap of garbage. Until the next time it takes an action, the ofalth gains a +2 circumstance bonus to AC.\n\nA creature that enters the area of the garbage heap or interacts with it must attempt a save against the ofalth's stench."

abilities_mid:
  - name: ""
  - name: "Filth Wallow"
    desc: "  An ofalth gains fast healing 2 when in an area with a high concentration of debris or excrement, such as a refuse heap or sewer."

  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 30 feet, DC 28 Fortitude check\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (reach 10 feet)\n__Damage__  2d12 + 13 bludgeoning plus wretched-weeps"

  - name: "**Ranged** `pf2:1` Offal"
    desc: "+19 (range increment 30 feet)\n__Damage__  2d10 + 9 bludgeoning plus wretched-weeps"

  - name: "Wretched Weeps"
    desc: " (disease) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d4 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 1]] (1 day);\n\n**Stage 3** 2d6 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"
 
```

```encounter-table
name: Ofalth
creatures:
  - 1: Ofalth
```



Fully grown ofalths capture victims and slowly eat them alive.

* * *

Found in castle dung heaps, city dumps, and sewers, ofalths are living amalgamations of wet detritus, sewage, and rubbish. They carry a disease called wretched weeps that causes the victim's blood to seep from its pores.
