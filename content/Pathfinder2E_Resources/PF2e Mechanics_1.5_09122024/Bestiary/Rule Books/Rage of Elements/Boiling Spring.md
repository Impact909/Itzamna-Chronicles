---
title: "Boiling Spring"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.33ep3Lu1L4SeEvkV" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Boiling Spring"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Boiling Spring"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[fire]]
trait_04: [[water]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +26, Stealth: +26"
abilityMods: [7, 7, 7, 2, 4, 2]
speed:  fly 30 feet,  swim 80 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +23, __Ref__ +26, __Will__ +20"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Immunities__  bleed,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "Steam Vision"
    desc: "  The boiling spring ignores the [[Conditions/Concealed|Concealed]] condition from mist and steam."

abilities_mid:
  - name: ""
  - name: "Evaporate"
    desc: "`pf2:r`  **Trigger** An effect would deal fire damage to the boiling spring, even if they would ignore the damage\n* * *\n\n**Effect** The boiling spring evaporates into the air. Until the beginning of the boiling spring's next turn, they can't be attacked or targeted. They still occupy their space, and their auras still function as normal."

  - name: "Sweltering Heat"
    desc: " (aura,fire) 25 feet. The boiling spring radiates heat, raising the air temperature around them. A creature that starts its turn in the emanation must succeed at a DC 33 Fortitude check save or become [[Conditions/Fatigued|Fatigued]] while it remains in the area; creatures immune to environmental heat effects or with any fire resistance are immune."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blistering Fist"
    desc: "+27 (fire)\n__Damage__  3d8 + 13 fire"

  - name: "**Ranged** `pf2:1` Heat Wave"
    desc: "+27 (fire, range increment 50 feet)\n__Damage__  3d12 fire"

  - name: "Freeze and Shatter"
    desc: "  If the boiling spring is destroyed with cold damage, their body freezes over and explodes, sending out a wave of frigid air and ice shards that deal 4d6 piercing damage plus 4d6 cold damage to creatures in a 20-foot emanation (DC 36 Reflex check save)."

  - name: "Scalding Breath"
    desc: "`pf2:2` (fire,primal) The boiling spring breathes out a cloud of steam in a 30-foot cone that deals 14d6 fire damage to each creature in the area (DC 33 Reflex check save). The boiling spring can't use Scalding Breath again for 1d4 rounds."
 
```

```encounter-table
name: Boiling Spring
creatures:
  - 1: Boiling Spring
```



Often mistaken for air elementals due to their hazy, almost-imperceptible forms, a boiling spring is a humanoid water elemental made of scalding steam and bubbling water. When summoned to the Universe, a boiling spring raises the ambient temperature around them, making the surrounding climate humid and muggy. They seem to enjoy the discomfort they cause, though some regard it as merely a fun prank while others truly revel in the misery and look for ways to cause more.
