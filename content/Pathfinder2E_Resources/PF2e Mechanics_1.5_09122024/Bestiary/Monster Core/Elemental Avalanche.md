---
title: "Elemental Avalanche"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Mf7qc9VivSNqbt8p" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Elemental Avalanche"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Elemental Avalanche"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision, Tremorsense (Imprecise) 90 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Stealth: +14"
abilityMods: [7, -1, 8, 0, 3, -1]
speed: 25 feet,  burrow 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +26, __Ref__ +17, __Will__ +21"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 90 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Earthbound"
    desc: "  When not touching solid ground, the elemental avalanche is [[Conditions/Slowed|Slowed 1]], can't use reactions, and can't Trample."

abilities_mid:
  - name: ""
  - name: "Crumble"
    desc: "`pf2:r`  **Trigger** The elemental avalanche takes damage from a hostile source while atop rock or earth\n* * *\n\n**Effect** The elemental avalanche crumbles into the ground, Burrowing down 20 feet. This Burrowing does not trigger reactions.\n\nThe elemental avalanche can't Crumble again for 1d4 rounds."

  - name: "Spike Stones"
    desc: " (aura,earth,primal) 10 feet.\n\nSpikes of rock rise up from all stone surfaces in the emanation, creating difficult terrain. A creature moving in the terrain takes 2d8 piercing damage for each square of spikes it moves into (a Large or larger creature takes damage only once for each square it moves, even if its space covers multiple squares of spikes). Creatures with the earth trait ignore all effects within the area.\n\nThe elemental avalanche can disable or activate this aura using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (reach 20 feet)\n__Damage__  2d12 + 11 bludgeoning plus knockdown"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+24 (brutal, range increment 80 feet)\n__Damage__  2d12 + 7 bludgeoning"

  - name: "Earth Glide"
    desc: "  The elemental avalanche can Burrow through any earthen matter, including rock. When it does so, the elemental avalanche moves at its full burrow Speed, leaving no tunnels or signs of its passing."

  - name: "Grinding Stones"
    desc: "`pf2:2`  The elemental avalanche deals 4d12 bludgeoning damage to each [[Conditions/Prone|Prone]] creature within the elemental's melee reach with a DC 30 Reflex check save."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, fist, DC 30 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Elemental Avalanche
creatures:
  - 1: Elemental Avalanche
```



Stubborn and ponderous, elemental avalanches are massive beings of living rock and dirt. Once their ire is raised, they will take the shortest route to resolving the problem, usually by burying it in rock.

* * *

Earth elementals make excellent bodyguards for adventuresome spelunkers and are ideal protectors of important subterranean locations such as vaults and treasuries.
