---
title: "Stone Mauler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zBhwUNgRNhHbMEL1" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Stone Mauler"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Stone Mauler"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Tremorsense (Imprecise) 80 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Stealth: +12"
abilityMods: [6, -1, 7, -1, 3, -1]
speed: 35 feet,  burrow 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +23, __Ref__ +15, __Will__ +19"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 80 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Earthbound"
    desc: "  When not touching solid ground, a stone mauler is [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Crumble"
    desc: "`pf2:r`  **Trigger** The stone mauler takes damage from a hostile source while atop rock or earth\n* * *\n\n**Effect** The stone mauler crumbles into the ground, Burrowing down 15 feet. This Burrowing does not trigger reactions.\n\nThe stone mauler can't Crumble again for 1d4 rounds."

  - name: "Spike Stones"
    desc: " (aura,earth,primal) 5 feet.\n\nSpikes of rock rise up from all stone surfaces in the emanation, creating difficult terrain. A creature moving in the terrain takes 2d6 piercing damage for each square of spikes it moves into (a Large or larger creature takes damage only once for each square it moves, even if its space covers multiple squares of spikes). Creatures with the earth trait ignore all effects within the area.\n\nThe stone mauler can disable or activate this aura using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+21 (reach 10 feet)\n__Damage__  2d10 + 10 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+21 (brutal, range increment 80 feet)\n__Damage__  2d12 + 6 bludgeoning"

  - name: "Earth Glide"
    desc: "  The stone mauler can Burrow through any earthen matter, including rock. When it does so, the stone mauler moves at its full burrow Speed, leaving no tunnels or signs of its passing."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Stone Mauler
creatures:
  - 1: Stone Mauler
```



These towering heaps of earth can inflict tremendous damage up close and from afar.

* * *

Earth elementals make excellent bodyguards for adventuresome spelunkers and are ideal protectors of important subterranean locations such as vaults and treasuries.
