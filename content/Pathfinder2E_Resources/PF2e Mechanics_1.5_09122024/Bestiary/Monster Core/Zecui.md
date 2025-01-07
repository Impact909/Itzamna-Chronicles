---
title: "Zecui"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9oaBo8bDbibyMol4" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Zecui"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Zecui"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +15, Crafting: +12, Medicine: +14, Stealth: +17"
abilityMods: [3, 5, 2, 0, 2, 0]
speed: 30 feet,  burrow 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +17, __Will__ +12"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Shortsword|Shortsword]]"
abilities_mid:
  - name: ""
  - name: "Preserve Prey"
    desc: "`pf2:r` (healing,manipulate,occult,vitality) **Trigger** A living creature within 30 feet is reduced to 0 Hit Points\n* * *\n\n**Effect** The zecui channels corrupt vitality into the triggering creature, which still goes [[Conditions/Unconscious|Unconscious]] but does not gain the dying condition. While that creature is unconscious, the residual energy attempts to counteract any vitality spell healing that creature with a +15 counteract modifier."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+17 (agile, finesse, versatile s)\n__Damage__  2d6 + 7 piercing"

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+15 ()\n__Damage__  2d8 + 7 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+17 (agile, finesse)\n__Damage__  2d4 + 7 slashing plus grab"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+17 (range 30 feet)\n__Damage__ "

  - name: "Dual Stab"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The zecui makes two shortsword Strikes against an [[Conditions/Immobilized|Immobilized]] or [[Conditions/Off-Guard|Off-Guard]] target. These strikes count towards the zecui's multiple attack penalty, but it doesn't increase until after the second attack."

  - name: "Harden Chitin"
    desc: "`pf2:1`  The zecui fuses much of their chitin into a black metallic shell. They gain resistance 5 to all damage (except mental and spirit) until they next take a move action."

  - name: "Spit Mucus"
    desc: "  A creature hit by the zecui's spit attack is [[Conditions/Immobilized|Immobilized]] by the larva-infested mucus and stuck to the nearest surface until it [[/act escape dc=25]]{Escapes (DC 25)}. While that creature is immobilized, it is exposed to zecui larvae at the end of each of its turns."

  - name: "Zecui Larvae"
    desc: " (disease) **Saving Throw** DC 25 Fortitude check\n* * *\n\n**Stage 1** visible lumps as the larvae move but no ill effect (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 3]] and controlled by the zecui larva (1 day)\n\n**Stage 5** the creature dies and the adult zecui can emerge from the corpse as an Interact action"
 
```

```encounter-table
name: Zecui
creatures:
  - 1: Zecui
```



These chitinous entities can only grow to adulthood within a host creature, usually a humanoid or larger animal. When such hosts are particularly plentiful, zecuis can multiply at a horrifying rate, sealing hosts in subterranean chambers until their larvae grow to adulthood. However, during lean times, zecui adults will sate their hunger by eating those hosts along with any unlucky larvae gestating within, unable to be infested by their own young.

Between periods of wakefulness, zecuis hibernate for decades in burrows or buried within the soil. Sometimes an unincubated larva will be buried this way, waiting for a living host to come in contact with it. Once a zecui larva has gestated long enough to take control of its host, it may seek out larger and more powerful entities to devour the host, transferring themselves to a more plentiful source of food.
