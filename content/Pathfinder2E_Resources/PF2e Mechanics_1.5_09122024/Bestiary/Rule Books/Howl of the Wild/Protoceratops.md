---
title: "Protoceratops"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MAjTWbL8xWhAbw2E" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Protoceratops"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Protoceratops"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8"
abilityMods: [4, 2, 3, -4, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +8, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Defensive Posture"
    desc: "`pf2:1`  The protoceratops tucks in its head and presents its sturdy frill, granting a +1 circumstance bonus to AC adjacent allies. The protoceratops remains in its Defensive Posture until the start of its next turn, but only grants the bonus while allies remain adjacent"

  - name: "Frill Block"
    desc: "`pf2:r`  **Requirements** The protoceratops is in its Defensive Posture\n\n**Trigger** An adjacent ally would take damage from a physical attack\n* * *\n\n**Effect** The protoceratops partially blocks the blow with its frill, reducing the damage by 5."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Head"
    desc: "+10 ()\n__Damage__  1d8 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 bludgeoning plus knockdown"
 
```

```encounter-table
name: Protoceratops
creatures:
  - 1: Protoceratops
```



Though it lacks the distinctive horns of its larger relative the triceratops, the protoceratops is more than capable of holding its own in combat, using its tail to knock enemies to the ground and its sturdy frill to turn away blows.
