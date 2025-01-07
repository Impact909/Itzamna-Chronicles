---
title: "Athamaru Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cUHo24wUL2aRfWqU" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/locathah
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Athamaru Hunter"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Athamaru Hunter"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[humanoid]]
trait_03: [[locathah]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Low-Light Vision"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Diplomacy: +5, Nature: +7, Stealth: +8, Survival: +7"
abilityMods: [4, 3, 0, 1, 2, 0]
speed: 10 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +7, __Ref__ +10, __Will__ +9"
hp: 38
health:
  - name: ""
  - name: HP
    desc: "38"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Longspear|Longspear]], [[Equipment/Scale Mail|Scale Mail]], 12x [[Equipment/Bolts|Fan Bolts]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+11 (reach 10 feet)\n__Damage__  1d8 + 4 piercing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+10 (range increment 120 feet, reload 1)\n__Damage__  1d8 piercing plus fan-bolt"

  - name: "Cooperative Hunting"
    desc: "  After the hunter attempts a Strike at a Large or larger target (regardless of success or failure), the next Strike one of the hunter's allies makes against the same target gains a +2 circumstance bonus to the attack roll."

  - name: "Fan Bolt"
    desc: "  The hunter prepares their hooked crossbow bolts with carefully woven seaweed.\n\nOn a successful crossbow Strike, the bolt embeds and the seaweed fan deploys. The target takes a -10-foot status penalty to its swim Speed. A creature can Interact to attempt a DC 18 Athletics check check, removing the bolt on a success.\n\n[[Bestiary Effects/Effect_ Fan Bolt|Effect: Fan Bolt]]"

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) The athamaru hunter designates a single creature they can see and hear, or one they're Tracking, as their prey. The hunter gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] the prey and to Survival checks to [[Actions/Track|Track]] the prey.\n\nThe first time the athamaru hits their designated prey in a round, they deal an additional 1d8 precision damage. These effects last until the hunter uses Hunt Prey again."

  - name: "Pack Attack"
    desc: "  The hunter's Strikes deal an additional 1d8 damage to creatures within reach of at least two of the hunter's allies."

  - name: "Smooth Swimmer"
    desc: "  The athamaru hunter ignores difficult terrain caused by aquatic terrain features."
 
```

```encounter-table
name: Athamaru Hunter
creatures:
  - 1: Athamaru Hunter
```



Deep in the sea, schools of athamarus—piscine humanoids armed with spears and specialized crossbows—stalk sharks, sea serpents, and giant squid from the backs of their giant moray eel mounts. The first hunters to strike are armed with barbed harpoons that deploy large fans of seaweed, slowing and exhausting their prey. A daring few athamarus use the embedded harpoon as a handle to ride prey for a short time. Once the creature is tired, remaining hunters finish it with longspears. Athamarus developed this hunting tradition to forge skilled warriors and deter potential attackers, partially in response to centuries of oppression and mistreatment from other aquatic cultures.

Athamarus rarely hunt land-dwellers, instead offering to trade their services as guides in exchange for metal and ceramic items they can't build underwater—and for tubers, which they consider earthy delicacies. They render aid to damaged sailing ships and rescue shipwrecked sailors, providing food and guidance.

Athamaru communities—usually villages of 200 individuals or fewer—are matriarchal. The ruler of a given community is also the primary egg-layer, providing each generation with powerful familial bonds. The communities are tight-knit and loyal. Matriarchs are advised and assisted by primal spellcasters and healers.
