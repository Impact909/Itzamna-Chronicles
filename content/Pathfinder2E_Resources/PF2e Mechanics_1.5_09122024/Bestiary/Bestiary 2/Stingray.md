---
title: "Stingray"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Mt31haiHKdHRjxlR" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Stingray"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Stingray"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +5, Stealth: +7"
abilityMods: [1, 3, 1, -4, 1, -4]
speed:  swim 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +7, __Will__ +5"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15"
abilities_top:
  - name: ""

  - name: "Electrolocation"
    desc: "  A stingray in water can use its electrolocation as an imprecise sense at the listed range to detect living creatures that are in the same body of water as itself."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sting"
    desc: "+7 (agile, finesse)\n__Damage__  1d6 + 1 piercing plus stingray-venom"

  - name: "Stingray Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d4 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)"
 
```

```encounter-table
name: Stingray
creatures:
  - 1: Stingray
```



Found in salt or fresh water, stingrays are normally passive creatures, but when threatened or cornered, they lash out with their tails to lance foes with their toxic stingers. Stingrays often bury themselves in mud, sand, or sea grass, and unfortunately for those wading in shallow waters, stepping on an unseen stingray is a surefire way to receive a painful sting.
