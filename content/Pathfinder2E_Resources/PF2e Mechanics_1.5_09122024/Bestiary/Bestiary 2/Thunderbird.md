---
title: "Thunderbird"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TVQRwXgny6lXXSMN" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/beast
  - pf2e/creature/type/electricity
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Thunderbird"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Thunderbird"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[air]]
trait_02: [[beast]]
trait_03: [[electricity]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +23, Intimidation: +20, Nature: +20"
abilityMods: [8, 3, 7, 3, 5, 3]
speed: 25 feet,  fly 80 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +20, __Will__ +22"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  electricity; __Resistances__ sonic 10"
abilities_top:
  - name: ""

  - name: "Stormsight"
    desc: "  Wind, precipitation, and clouds don't impair a thunderbird's vision; it ignores the [[Conditions/Concealed|Concealed]] condition from storms, mist, precipitation, and the like."

abilities_mid:
  - name: ""
  - name: "Reactive Shock"
    desc: "`pf2:r` (move) **Trigger** A creature enters the thunderbird's reach or uses a move action within their reach\n* * *\n\n**Effect** A lightning bolt dancing on the thunderbird's body leaps onto the creature, dealing 8d6 electricity damage (DC 30 Reflex check save)."

  - name: "Storm Aura"
    desc: " (air,aura,concentrate,move,primal,water) 100 feet. The thunderbird is surrounded by a cyclone of wind and driving rain. This area is greater difficult terrain for flying creatures, who must successfully [[Actions/Maneuver in Flight|Maneuver in Flight]] (DC 27) or be blown 30 feet away from the thunderbird. Creatures on the ground must succeed at a DC 27 Reflex check save to perform any move action and are knocked [[Conditions/Prone|Prone]] on a critical failure.\n\nThe driving rain in the storm aura imposes a -2 circumstance penalty on Perception checks and extinguishes smaller flames.\n\nA thunderbird can deactivate or activate the storm aura as a free action with the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+24 ()\n__Damage__  2d6 + 12 piercing 3d6 electricity"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+24 (agile)\n__Damage__  2d8 + 12 slashing"

  - name: "**Ranged** `pf2:1` Thunderbolt"
    desc: "+23 (range increment 200 feet)\n__Damage__  3d6 electricity plus thunderstrike 3d6 sonic plus thunderstrike"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Lightning Blast"
    desc: "`pf2:2` (primal) The thunderbird spreads their wings and blasts their foe with thunderous bolts of lightning. Each creature in a 30-foot emanation takes 6d6 electricity damage and 6d6 sonic damage (DC 30 Reflex check save). The thunderbird can't use Lightning Blast for 1d4 rounds."

  - name: "Stormflight"
    desc: "  A thunderbird can move in wind with ease. They don't treat wind as difficult terrain or need to [[Actions/Maneuver in Flight|Maneuver in Flight]] in high winds."

  - name: "Thunderstrike"
    desc: "  A creature that takes damage from a thunderbird's thunderbolt Strike must succeed at a DC 28 Fortitude check save or be knocked [[Conditions/Prone|Prone]] and [[Conditions/Deafened|Deafened]] for 1 round."
 
```

```encounter-table
name: Thunderbird
creatures:
  - 1: Thunderbird
```



Thunderbirds bring storms on their wings. In times of drought, they are welcomed. Other times, they are offered gifts in hopes they might leave before flooding begins. When angered, they call down hurricanes and lay waste to entire villages, so many settlements conduct extensive rites to appease and honor local thunderbirds.

Thunderbird parents carry their newly hatched offspring to hidden mountaintop nests, where the young are struck by their first bolts of lightning and learn the mysteries of the storm.
