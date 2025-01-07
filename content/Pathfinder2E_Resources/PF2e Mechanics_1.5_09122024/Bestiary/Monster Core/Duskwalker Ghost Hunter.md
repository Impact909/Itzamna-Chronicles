---
title: "Duskwalker Ghost Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.an0LOWaB1a6zR7S2" 
tags:
  - pf2e/creature/type/duskwalker
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Duskwalker Ghost Hunter"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Duskwalker Ghost Hunter"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[duskwalker]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Deception: +6, Intimidation: +6, Nature: +8, Stealth: +12, Survival: +8"
abilityMods: [2, 4, 1, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21 (22 against prey; see Spirit Hunter); __Fort__ +9, __Ref__ +12, __Will__ +10; +1 status to all saves vs. death effects"
hp: 56
health:
  - name: ""
  - name: HP
    desc: "56; __Immunities__  effects that would transform their body or soul to an undead; __Resistances__ void 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], 2x [[Equipment/Hatchet|Hatchet]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Ghost Dodge"
    desc: "`pf2:r`  **Trigger** The duskwalker is targeted by a Strike or spell\n* * *\n\n**Effect** The duskwalker gains a +2 circumstance bonus to AC, resistance 5 to spirit damage, and increases their resistance to void damage to 5, all against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+12 (agile, sweep)\n__Damage__  1d6 + 5 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+14 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 5 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+14 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 4 piercing"

  - name: "Ghost Hunter"
    desc: "  The duskwalker's weapons have the benefits of the _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune on attacks against incorporeal undead."

  - name: "Spirit Hunter"
    desc: "`pf2:1`  The duskwalker designates a single creature they can observe as their prey.\n\nThe duskwalker gains a +2 circumstance bonus to Deception checks, Intimidation checks, and Stealth checks against their prey and to any check to Recall Knowledge about it, and deal an additional 2 spirit damage with all weapon Strikes against their prey.\n\nThese effects last until the duskwalker uses Spirit Hunter again."

  - name: "Spirit Shot"
    desc: "`pf2:1`  **Frequency** once per round\n\n**Requirements** The duskwalker has designated a creature as their prey using Spirit Hunter\n* * *\n\n**Effect** The duskwalker makes two ranged Strikes against their prey. If both Strikes hit, combine their damage for the purpose of resistances and weaknesses."
 
```

```encounter-table
name: Duskwalker Ghost Hunter
creatures:
  - 1: Duskwalker Ghost Hunter
```



Duskwalkers are infused with the same energies as psychopomps. These ashen scions are reborn in the mortal Universe to guard the cycle of life and death.

* * *

Many immortals dwell upon the other planes of the Great Beyond. Some are benevolent and kind, like angels. Others are cruel and destructive, like demons. And some fit roles outside of morality, like psychopomps. It's far from unheard of for mortals and immortals alike to become entangled romantically, and the children of such engagements carry a supernatural element in their bloodlines for generations to follow. After the first generation, this otherworldly influence usually lies dormant, but now and then, the influence can manifest strongly in descendants many years later. These inheritors of extraplanar legacies are known collectively as planar scions.
