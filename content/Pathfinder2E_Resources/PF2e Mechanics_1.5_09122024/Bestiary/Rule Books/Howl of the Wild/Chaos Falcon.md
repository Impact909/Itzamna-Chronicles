---
title: "Chaos Falcon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y1dcGYaJROZ7nFOw" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/beast
  - pf2e/creature/type/electricity
  - pf2e/creature/type/fire
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Chaos Falcon"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Chaos Falcon"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[beast]]
trait_03: [[electricity]]
trait_04: [[fire]]
trait_05: [[water]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Common, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +19, Nature: +19, Stealth: +19"
abilityMods: [5, 7, 3, 4, 4, 3]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +22, __Will__ +16"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Resistances__ fire 10, electricity 10, cold 10"
abilities_top:
  - name: ""

  - name: "Storm Bolt"
    desc: "  The chaos falcon's bolt Strike always deals the damage type of their storm nexus aura."

  - name: "Stormsight"
    desc: "  Wind, precipitation, and clouds don't impair a chaos falcon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from storms, mist, precipitation, and the like."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+21 (reach 10 feet)\n__Damage__  3d10 + 10 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+21 (agile)\n__Damage__  3d6 + 10 slashing"

  - name: "**Ranged** `pf2:1` Bolt"
    desc: "+23 (range 120 feet)\n__Damage__  6d6 untyped plus storm-bolt"

  - name: "Dive-bomb"
    desc: "`pf2:2` (earth,fire,primal) **Requirements** The chaos falcon is Flying\n* * *\n\n**Effect** The chaos falcon Flies twice straight down. If they reach the ground or a similarly solid object at the end of this movement, their landing shatters that surface into sharp shards and droplets of molten stone deal 4d6 fire and 3d8 piercing damage (DC 26 Reflex check save) to all other creatures within 20 feet."

  - name: "Flash Storm"
    desc: "`pf2:1` (air,primal,water) Water condenses around the ash particles in the chaos falcon's 15-foot aura, pelting everything beneath it with driving rain. Creatures in that area must succeed at a DC 26 Reflex check save or be pushed 20 feet down, falling [[Conditions/Prone|Prone]] if they start or end this movement on the ground."

  - name: "Storm Nexus"
    desc: " (aura,primal) 15 feet, 3d6 untyped, DC 26 Reflex check save. The chaos falcon is surrounded by a cloud of volcanic ash, lightning arcing within the cloud as it glows hot in some areas and collects ice in others. A chaos falcon can change the damage type of this aura to cold, electricity, or fire as an action, which has the concentrate trait."
 
```

```encounter-table
name: Chaos Falcon
creatures:
  - 1: Chaos Falcon
```



The extreme weather that gives birth to chaos falcons grants them a mix of abilities not found in other elemental birds. To them, lightning is as natural as fire and heat as comfortable as cold. The variability of their attacks makes them dangerous, even for the well prepared.

Like their elemental cousins, chaos falcons are often the harbingers of storms. They're also seen as omens of volcanic activity, as they will travel across great distances to play and dance in the resulting eruption. Between this association and their tendency to rain both fire and ice, their presence is considered dangerous by nearby settlements.

Fortunately, chaos falcons are solitary birds that prefer to stay away from the noise of civilization. They nest in volcanic vents or areas with geothermal activity, relying on the heat of the earth to incubate their eggs while hunting in the wilderness nearby. Unless their peace is disrupted or their safety threatened, they're unlikely to attack creatures that move through their habitat.
