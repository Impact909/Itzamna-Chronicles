---
title: "Jewel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8kOCxS6lmta3dUhz" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/minion
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Jewel"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Jewel"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "tiny"
trait_01: [[animal]]
trait_02: [[minion]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Intimidation: +17"
abilityMods: [-2, 4, 2, -4, 4, 2]
speed: 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +17, __Ref__ +21, __Will__ +19"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 (agile, finesse)\n__Damage__  1d4 + 1 piercing plus ankle-bite"

  - name: "Ankle Bite"
    desc: "  If Jewel damages a Small or larger creature standing on the ground with her jaws Strike, that creature becomes [[Conditions/Off-Guard|Off-Guard]] for 1 round (or off-guard and [[Conditions/Clumsy|Clumsy 1]] for 1 round on a critical hit)."

  - name: "Distracting Yipping"
    desc: "`pf2:2` (auditory,emotion,mental) Jewel unleashes a torrent of grating, high-pitched yips. All creatures other than Pavetta within 20 feet must attempt a DC 25 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and becomes temporarily immune to Distracting Yipping for 24 hours.\n\n**Success** The creature takes a -2 status penalty to Perception checks for 1 round.\n\n**Failure** The creature takes a -4 status penalty to Perception checks and is [[Conditions/Off-Guard|Off-Guard]] for 1 round.\n\n**Critical Failure** As failure, but also, if the creature attempts any concentrate action during the round, they must succeed at a DC 11 Flat check or the action is lost."

  - name: "Return to Pavetta"
    desc: "  If Pavetta doesn't sustain her Release Jewel action, Jewel can only take Stride actions to return to Pavetta's square. If she's in her square, she takes no actions."
 
```

```encounter-table
name: Jewel
creatures:
  - 1: Jewel
```


Ferocious little dog


