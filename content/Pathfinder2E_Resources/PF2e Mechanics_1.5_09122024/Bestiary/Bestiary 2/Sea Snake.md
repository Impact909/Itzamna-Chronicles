---
title: "Sea Snake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y3EIty4UAfK6jcbl" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Sea Snake"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Sea Snake"
level: "Creature 0"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +2, Stealth: +5, Survival: +5"
abilityMods: [0, 3, 1, -4, 1, -2]
speed: 15 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +9, __Will__ +3"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The sea snake can hold its breath for about an hour."

abilities_mid:
  - name: ""
  - name: "Lash Out"
    desc: "`pf2:r` (move) **Trigger** A creature within the sea snake's reach uses a move action\n* * *\n\n**Effect** The sea snake makes a bite Strike against the attacker."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+7 (agile, finesse)\n__Damage__  1d8 piercing plus sea-snake-venom"

  - name: "Sea Snake Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d6 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)"
 
```

```encounter-table
name: Sea Snake
creatures:
  - 1: Sea Snake
```



These lithe snakes like to frequent the shallow waters of tropical seas. Their 4-foot-long, blue-green bodies easily blend into the water where they lurk to ambush prey. Tales speak of massive sea snakes that swim in deeper waters and follow ships, waiting for sailors to fall overboard or climbing the side to snatch them from the deck.
