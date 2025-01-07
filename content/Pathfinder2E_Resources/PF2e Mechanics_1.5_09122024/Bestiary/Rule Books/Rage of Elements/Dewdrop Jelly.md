---
title: "Dewdrop Jelly"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KQ1y78iYBUf5xHrA" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Dewdrop Jelly"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Dewdrop Jelly"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +7"
abilityMods: [2, 3, 3, -4, 1, 0]
speed:  fly 20 feet,  swim 50 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +7, __Ref__ +10, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Dissolve"
    desc: "`pf2:r`  **Trigger** The dewdrop jelly takes damage from a hostile action\n* * *\n\n**Effect** The dewdrop jelly dissolves into a fine mist. Until the start of the jelly's next turn, it can't be attacked or targeted and doesn't take up space. At the end of the round, the jelly re-forms in any open space within 25 feet of where it Dissolved."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+8 ()\n__Damage__  1d6 + 2 bludgeoning"

  - name: "Overflow"
    desc: "`pf2:3` (move) The dewdrop jelly flattens its bell and shoots forward, Flying or Swimming twice in a straight line toward its target and attempting a tentacle Strike. On a success, the dewdrop attaches to the target's face, covering its mouth in the suspended water of its gelatinous body. If the target cannot breathe water, it begins to drown. The DC to [[Actions/Escape|Escape]] is 16."
 
```

```encounter-table
name: Dewdrop Jelly
creatures:
  - 1: Dewdrop Jelly
```



Dewdrop jellies are small water elementals resembling jellyfish made of gelatinous bubbles. They typically travel in small schools, floating through the air or swimming through the endless seas of their home plane. When threatened, the jellies discorporate into a thin, vaporous mist, reconstituting into their bubble shape only after the danger has passed. Their clever elusiveness makes them hard to find, leading some to claim that dewdrop jellies are mythical flights of fancy told to entertain children.
