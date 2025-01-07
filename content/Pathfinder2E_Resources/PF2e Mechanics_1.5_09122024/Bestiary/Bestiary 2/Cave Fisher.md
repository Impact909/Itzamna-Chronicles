---
title: "Cave Fisher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y5FkysY2jQudfiXA" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Cave Fisher"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Cave Fisher"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +9"
abilityMods: [4, 3, 3, -5, 1, -3]
speed: 15 feet,  climb 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +9, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 ()\n__Damage__  1d10 + 6 slashing"

  - name: "**Ranged** `pf2:1` Filament"
    desc: "+11 (range increment 60 feet)\n__Damage__ "

  - name: "Pull Filament"
    desc: "`pf2:1`  The cave fisher pulls a creature [[Conditions/Grabbed|Grabbed]] by its filament toward itself, even suspending the target vertically if necessary. The cave fisher attempts an Athletics check check against the creature's Fortitude DC. On a success, the cave fisher pulls the creature 15 feet closer to it (30 feet closer on a critical success)."

  - name: "Sticky Filament"
    desc: "  Any creature hit by the cave fisher's sticky filament is [[Conditions/Grabbed|Grabbed]]. The cave fisher can move while it has a creature grabbed with its filament, but it automatically releases the creature if the cave fisher moves beyond the filament's 60-foot length. The cave fisher can use only one filament at a time, and it can sever the filament and release any creature grabbed by it as a free action. The filament can be severed by a Strike that deals at least 10 slashing damage to it. This doesn't deal any damage to the cave fisher itself. The filament has AC 17, and its [[Actions/Escape|Escape]] DC is 19."
 
```

```encounter-table
name: Cave Fisher
creatures:
  - 1: Cave Fisher
```



Cave fishers lurk in dark corners near the ceilings of caves and underground structures, lying in wait for prey to approach. When it does, the cave fisher excretes thin, tough, and very sticky filaments at its prey with lightning speed to capture it.

A cave fisher eats just about any live prey smaller than itself, though anything smaller than a rat isn't much of a meal for it. When a cave fisher captures such a creature, it often leaves the hapless animal entangled, using it as bait to attract larger creatures. Because the adhesive on its filament doesn't last long, the fisher frequently needs to eat one filament and excrete a new one. The filaments are translucent and can be hard to see when they're still and in darkness.

Cave fishers hatch with the ability to excrete filaments, but they molt many times before reaching their adult size of about 7 feet long and 400 pounds. They often leave shed shells in conspicuous locations as decoys.
