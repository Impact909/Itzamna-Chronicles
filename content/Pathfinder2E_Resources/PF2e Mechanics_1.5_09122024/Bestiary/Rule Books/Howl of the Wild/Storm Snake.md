---
title: "Storm Snake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iXftRKMhZlUcCPYP" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/dragon
  - pf2e/creature/type/electricity
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Storm Snake"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Storm Snake"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[dragon]]
trait_03: [[electricity]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Stealth: +10"
abilityMods: [3, 5, 2, -1, 3, 0]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +15, __Will__ +9"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Resistances__ electricity 8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Static Shock"
    desc: "`pf2:r`  **Trigger** A creature touches the storm snake or damages it with an unarmed melee attack or non-reach melee weapon\n* * *\n\n**Effect** The triggering enemy is shocked for 2d8 electricity damage (DC 19 Fortitude check save). On a failed save, the target is [[Conditions/Stunned|Stunned 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+12 ()\n__Damage__  2d4 + 5 slashing 1d4 electricity"

  - name: "Lightning Strike"
    desc: "`pf2:1`  The storm snake redirects the lightning it has absorbed from storms, dealing 2d10 electricity damage to a single target within 20 feet (DC 19 Reflex check save). On a failure, the target is [[Conditions/Dazzled|Dazzled]] until the end of its next turn."

  - name: "Static Field"
    desc: "`pf2:2`  The storm snake gathers all static electricity in the area before releasing it in a 30-foot emanation that deals 3d12 electricity damage to all non-plant creatures (DC 19 Reflex check save) and grants plant creatures 5 temporary Hit Points that last for 1 minute. Plant life in the area begins to grow significantly faster than the average for plants of their genus; in forests, fields, or otherwise floral locations, this immediately transforms the area into non-magical difficult terrain. The storm snake can't use Static field again for 1d4 rounds.\n\n[[Bestiary Effects/Effect_ Static Field|Effect: Static Field]]"
 
```

```encounter-table
name: Storm Snake
creatures:
  - 1: Storm Snake
```




