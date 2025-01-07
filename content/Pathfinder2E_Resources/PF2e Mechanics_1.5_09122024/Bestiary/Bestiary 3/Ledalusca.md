---
title: "Ledalusca"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XG6zxLU9F8G0KMAw" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Ledalusca"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Ledalusca"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[cold]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Deception: +5, Stealth: +9, Thievery: +7"
abilityMods: [4, 3, 2, 0, 2, 1]
speed: 25 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +9, __Will__ +6"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  cold,  paralyzed,  poison,  sleep; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

  - name: "Recall Reflection"
    desc: " (illusion,primal) A ledalusca can recall and replay any reflection ever cast on its surface, although it must still [[Actions/Seek|Seek]] to consciously notice fine or significant details."

abilities_mid:
  - name: ""
  - name: "Shell Block"
    desc: "`pf2:r`  **Trigger** The ledalusca takes physical damage from an attack\n\n**Requirements** The ledalusca's shell is frozen (see Freeze Shell)\n* * *\n\n**Effect** The ledalusca angles their shell to absorb the blow, gaining resistance 5 to the triggering damage. If they take bludgeoning or fire damage after applying this resistance, their frozen shell shatters until they freeze a new one."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+10 ()\n__Damage__  1d6 + 4 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Ice Shard"
    desc: "+9 (deadly d6, thrown 20 ft.)\n__Damage__  1d6 + 4 piercing 1d4 cold"

  - name: "Freeze Shell"
    desc: "`pf2:1` (cold,manipulate) The ledalusca freezes their surface into a translucent, faintly colored ice sculpture matching the mirror image of a Medium creature or object they have seen before. While in this form, instead of a wave, they have the following Strike:\n\n**Melee** `pf2:1` ice shell +10/+5/+0, **Damage** 1d4 cold damage\n\nThe physical damage is a type that matches the new shape of the ledalusca's frozen shell. The ledalusca can revert to their liquid form by taking this action again."

  - name: "Hold Still"
    desc: "`pf2:1` (concentrate) Until the next time they act, the ledaluca appears to be either an ice sculpture (if under the effects of Freeze Shell) or a pool of still water (if not). They have an automatic result of 28 on Deception checks and DCs to pass as what they appear to be."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Ledalusca
creatures:
  - 1: Ledalusca
```



Ledaluscas are reflective water elementals that can bring forth images previously reflected on their surfaces and wholly freeze themselves in the shapes of what they reflected. They explore and protect the calmest boundaries of the icy regions of the Plane of Water, where ice forms in shiny, flawless sheets.

Insatiably curious, their eagerness propels some ledaluscas to pickpocket interesting-looking objects to play with. Others travel to different planes to locate, observe, and reflect a wider variety of creatures than those on their home plane. They pretend to be ice sculptures or still pools for this purpose, especially if they can find a spot in a high-traffic area to inhabit. Despite their perfect mimicry, ledaluscas are unable to create an appearance from scratch, nor can they adjust the appearance they take on or combine elements of different reflections. Some of them find this disheartening, like artists vexed by a lack of creativity.

One of the strangest encounters a ledalusca can experience is with a creature or object that has no reflection. A ledalusca can see a vampire, for example, but is unable to reproduce its image. For a creature that effectively has an unlimited memory for images, this proves utterly confusing. The vague memory of the encounter sticks in the ledalusca's mind like a splintering a humanoid's finger.
