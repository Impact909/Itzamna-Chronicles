---
title: "Flea Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZWTkKbUpwz0P7CUV" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Flea Swarm"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Flea Swarm"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +9"
abilityMods: [-2, 5, 4, -5, 1, -4]
speed: 30 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +15, __Ref__ +16, __Will__ +6"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55; __Immunities__  disease,  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 4, splash damage 4; __Resistances__ physical 8 (except bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "Flea Fever"
    desc: " (disease) Drain from flea fever can't be reduced or recovered from naturally until the disease is cured.\n\n**Saving Throw** DC 19 Fortitude check\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1d4 hours)\n\n**Stage 2** drained 1 and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] and sickened 1 (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 3]] and sickened 1 (1 day)\n\n**Stage 5** dead"

  - name: "Suck Blood"
    desc: "`pf2:1`  **Requirements** The flea swarm's last action was Swarming Bites, and it dealt damage to at least one enemy\n* * *\n\n**Effect** The flea swarm drinks the creatures' blood. Each victim becomes [[Conditions/Drained|Drained 1]] and the swarm regains 3 healing HP for each victim drained."

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 2d4+7 piercing damage and must attempt a DC 22 Reflex check save. A creature that fails its save is exposed to flea fever."
 
```

```encounter-table
name: Flea Swarm
creatures:
  - 1: Flea Swarm
```



Flea swarms roil across city streets and rural hinterlands in a hissing, scraping scrabble, draining blood from any creatures unfortunate enough to cross their path.

* * *

Fleas are little more than a nuisance in most circumstances, but can be lethal when they grow to monstrous proportions or gather in enormous swarms.
