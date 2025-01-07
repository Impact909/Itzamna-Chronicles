---
title: "Gunpowder Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fU5fJbn1essy5B3s" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Gunpowder Ooze"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Impossible Lands"
name: "Gunpowder Ooze"
level: "Creature 14"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Motion Sense (Precise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +28"
abilityMods: [8, 3, 6, -5, 2, -5]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Lost Omens: Impossible Lands_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +28, __Ref__ +21, __Will__ +24"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  critical hits,  piercing,  precision,  slashing,  unconscious,  visual,  mental; __Weaknesses__ fire 20"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A gunpowder ooze can sense nearby creatures through vibration and air or water movement."

abilities_mid:
  - name: ""
  - name: "Combust"
    desc: "  Due to the volatile nature of its composition, the gunpowder ooze reacts explosively when exposed to open flame. Any time the gunpowder ooze takes fire damage from a source other than a gunpowder ooze's combust or gunpowder residue, it explodes, dealing 15d6 fire damage to creatures in a 15-foot emanation including itself (DC 34 Reflex check). When the gunpowder ooze combusts, it automatically splits as long as it has 10 or more HP."

  - name: "Split"
    desc: "  When a gunpowder ooze that has 10 or more HP is hit by an attack that would deal slashing or piercing damage, it splits into two identical oozes, each with half the original's HP. One ooze is in the same space as the original, and the other is in an adjacent, unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or heavy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+29 (reach 10 feet)\n__Damage__  3d12 + 14 bludgeoning plus gunpowder-residue"

  - name: "**Ranged** `pf2:1` Blast"
    desc: "+26 (propulsive, range increment 60 feet)\n__Damage__  3d6 fire plus gunpowder-residue 3d8 + 10 bludgeoning plus gunpowder-residue"

  - name: "Gunpowder Residue"
    desc: " (fire) A creature hit by the gunpowder ooze's pseudopod or blast is coated in explosive material unless it succeeds at a DC 34 Reflex check save. If a creature makes an attack with a firearm, takes fire damage, or uses an action, activity, or item with the fire trait while coated with the residue, the residue explodes, dealing 7d6 fire damage to the creature and all adjacent creatures (DC 34 Reflex check). The residue remains active for 24 hours, until it's ignited, or until it's scrubbed off (an activity that takes at least 10 minutes and requires soap and water). A creature can only be coated with one layer of gunpowder residue at a time."
 
```

```encounter-table
name: Gunpowder Ooze
creatures:
  - 1: Gunpowder Ooze
```



Gunpowder oozes are explosive gunpowder given life. By necessity, crafters of explosives and firearms are a careful lot, but even the best safety habits can be thwarted by greed, distraction, or carelessness. The release of toxic byproducts from gunsmithing would be an environmental problem anywhere, but when volatile runoff seeps into the Mana Wastes, it can interact with wild magic, causing a living, explosive nightmare.

A gunpowder ooze is a pockmarked, charcoal gray mass that slithers across the blighted verge between Alkenstar and the Mana Wastes with the sound of sizzles and sudden pops. It pursues and consumes any sort of organic matter, firing bullet-like projectiles to bring down prey. The ooze instinctively avoids fire, so travelers forced to camp in known gunpowder ooze territory often light bonfires despite the danger of advertising their presence to the Mana Wastes' other residents. Suggestions that local populations of oozes be weaponized, periodically put forward by unwise Alkenstari and Mana Waste tacticians, are uniformly shot down by cooler heads; those who attempt to proceed anyway usually meet explosive ends.
