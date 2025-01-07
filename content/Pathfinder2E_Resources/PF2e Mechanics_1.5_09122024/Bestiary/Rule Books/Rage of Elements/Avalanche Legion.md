---
title: "Avalanche Legion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ucbjXNOg7YndRorW" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Avalanche Legion"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Avalanche Legion"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[earth]]
trait_02: [[elemental]]
trait_03: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +23"
abilityMods: [5, 0, 4, -2, 1, 0]
speed: 30 feet,  burrow 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +20, __Will__ +21"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, 16 squares Thresholds 160 (12 squares), 80 (8 squares); __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ area damage 15, splash damage 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Earthbound"
    desc: "  When not touching solid ground, the avalanche legion is [[Conditions/Slowed|Slowed 1]]."

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Earth Glide"
    desc: "  The avalanche legion can Burrow through any earthen matter, including rock. When it does so, the legion moves at its full burrow Speed, leaving no tunnels or signs of its passing."

  - name: "Pummeling Boulders"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The avalanche legion unleashes an onslaught of blows against each enemy within 5 feet (DC 28 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8 bludgeoning damage\n\n`pf2:2` 3d8+8 bludgeoning damage\n\n`pf2:3` 4d8+11 bludgeoning damage"

  - name: "Spinning Stones"
    desc: "`pf2:2`  The avalanche legion spins in place, kicking up a barrage of stones. Each creature in a 10-foot burst within 30 feet of the troop takes 2d12+10 bludgeoning damage (DC 28 Reflex check save). When the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Trample into the Earth"
    desc: "`pf2:3`  The avalanche legion speeds forward, running over creatures with their stone bodies and knocking them down. As [[Bestiary Ability Glossary/Trample|Trample]]; Gargantuan or smaller, 2d8 bludgeoning damage, DC 28 Reflex check. A creature that critically fails its save is knocked [[Conditions/Prone|Prone]]."

  - name: "Troop Movement"
    desc: "  Whenever the avalanche legion Strides or Burrows, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its respective Speed. This works just like a Gargantuan creature moving; for instance, if any square of the legion enters difficult terrain, the extra movement cost applies to all the elementals."
 
```

```encounter-table
name: Avalanche Legion
creatures:
  - 1: Avalanche Legion
```



Elementals of the Plane of Earth can be fiercely territorial. Some more solitary elementals protect their lairs on their own, but occasionally others band together to defend larger regions that serve as shared turf. Notable among these alliances are avalanche legions, who patrol the perimeter of these shared territories, driving off intruders who dare to trespass upon their home ground.

## Familial Instincts

Although elementals don't reproduce like typical creatures, living landslides sometimes develop bonds with smaller or weaker earth elementals, such as earth wisps, living boulders, and sod hounds. When several of these smaller elementals are gathered in one place, living landslides who cared for the creatures often continue to watch over their wards. Avalanche legions sometimes form from these gatherings, as multiple living landslides join forces to protect the smaller elementals.
