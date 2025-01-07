---
title: "Carnotaurus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gr1Hg4vLK9IWearc" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Carnotaurus"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Carnotaurus"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Survival: +14"
abilityMods: [7, 2, 4, -4, 2, 0]
speed: 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +15, __Will__ +13"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (reach 15 feet)\n__Damage__  2d10 + 9 piercing plus vicious-mauling"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+18 (reach 15 feet)\n__Damage__  1d12 + 9 piercing"

  - name: "Headbutt"
    desc: "`pf2:r`  **Trigger** A creature ends a move action within reach of the carnotaurus's horn Strike\n* * *\n\n**Effect** The carnotaurus makes a horn Strike against the triggering creature."

  - name: "Powerful Charge"
    desc: "`pf2:2`  The carnotaurus lowers its horns and surges toward a foe. It Strides twice, then makes a horn Strike. If it moved at least 20 feet from its starting position, the Strike's damage is increased to 2d12+9 and knocks the target [[Conditions/Prone|Prone]] if successful."

  - name: "Vicious Mauling"
    desc: "  The carnotaurus's jaws Strike deals an additional 1d8 persistent bleed damage to [[Conditions/Prone|Prone]] targets."
 
```

```encounter-table
name: Carnotaurus
creatures:
  - 1: Carnotaurus
```



This 2,000-pound predator lives up to its name by ramming its prey with its distinctive horns lowered, knocking them [[Conditions/Prone|Prone]], and viciously tearing into fallen victims before they can regain their footing. Do not let its size fool you; this massive dinosaur is deceptively quick when charging a potential meal. Aggressive and highly territorial, a carnotaurus will not hesitate to hunt down and slay any creature unlucky enough to cross its path.
