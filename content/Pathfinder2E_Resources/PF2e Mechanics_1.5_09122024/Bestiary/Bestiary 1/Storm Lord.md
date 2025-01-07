---
title: "Storm Lord"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gnVFee0WOcaoUD1d" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Storm Lord"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Storm Lord"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Stealth: +18"
abilityMods: [4, 7, 4, -1, 3, 0]
speed:  fly 75 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +15, __Ref__ +20, __Will__ +16"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Disperse"
    desc: "`pf2:r`  **Trigger** The storm lord takes damage from a hostile action.\n* * *\n\n**Effect** The storm lord disperses.\n\nUntil the end of the current turn, it can't be attacked or targeted, doesn't take up space, and any auras or emanations it has are suppressed. At the end of the turn, the storm lord reforms in any space in which it can fit within 50 feet of where it dispersed and any auras or emanations it has are restored as long as their duration didn't run out while it was dispersed."

  - name: "High Winds"
    desc: " (air,aura) 20 feet. Air within the emanation is difficult terrain for Flying creatures that do not have the air trait."

  - name: "Swiftness"
    desc: "  The storm lord's movement doesn't trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+20 (finesse, reach 15 feet)\n__Damage__  2d12 + 10 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Lightning Lash"
    desc: "+20 (range increment 50 feet)\n__Damage__  2d12 + 4 electricity"

  - name: "[[Bestiary Ability Glossary/Push|Push 5 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Storm Lord
creatures:
  - 1: Storm Lord
```



Storm lords wage battles to claim important territory within the Plane of Air.

* * *

Hailing from the Plane of Air, these beings appear in a variety of sizes and shapes.
