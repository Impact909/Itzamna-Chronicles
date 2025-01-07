---
title: "Warden of Caverns and Burrows"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8m5PnS1mt67EdsMm" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/22
  - remaster
statblock: inline
name: "Warden of Caverns and Burrows"
level: 22
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Warden of Caverns and Burrows"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[earth]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; "
languages: "voice of nature"
skills:
  - name: "Skills"
    desc: "Athletics: +42, Intimidation: +37, Stealth: +37, Subterranean Lore: +35"
abilityMods: [12, 8, 10, 6, 8, 9]
speed: 40 feet,  burrow 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +39, __Ref__ +36, __Will__ +33; +1 to all saves vs. primal"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500; __Immunities__  fire; __Weaknesses__ cold 20; __Resistances__ physical 10 (except adamantine), sonic 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Voice of Nature|Voice of Nature]]"
    desc: "  Though the Wardens of the Wild do not speak in words, they can communicate complex concepts flawlessly and wordlessly with any animal, beast, plant, or other creature of the natural world through prolonged eye contact. Sapient creatures with strong ties to the natural world, such as animal instinct barbarians or druids who speak the Wildsong, can somewhat understand a Warden of the Wild, though the meaning can be vague."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Warden's Crown|Warden's Crown]]"
    desc: "  A Warden of the Wild's horned crown commands respect from wild creatures. Wild creatures native to a warden's biome automatically improve their attitude toward it by one step (up to friendly) and typically do not take hostile actions towards each other while in the warden's presence."

abilities_mid:
  - name: ""
  - name: "Magmatic Reflex"
    desc: "`pf2:r`  **Trigger** The warden is targeted with an attack\n* * *\n\n**Effect** The warden issues a spray of magma as they jump away from danger. This spray deals 6d12 fire damage to all adjacent creatures (DC 42 Reflex check save). They then [[Actions/Leap|Leap]] or Step away, gaining a +2 circumstance bonus to their AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horned Crown"
    desc: "+41 (magical, reach 10 feet)\n__Damage__  4d12 + 22 piercing"

  - name: "**Melee** `pf2:1` Mandible"
    desc: "+41 (agile, magical, reach 15 feet)\n__Damage__  4d10 + 22 bludgeoning plus improved-grab"

  - name: "**Ranged** `pf2:1` Chirp"
    desc: "+33 (magical, range 60 feet)\n__Damage__  4d10 + 18 sonic"

  - name: "**Ranged** `pf2:1` Magma Jet"
    desc: "+33 (magical, range increment 60 feet)\n__Damage__  4d8 + 13 fire plus obsidian-cage 2d6 fire plus obsidian-cage"

  - name: "Bury Beneath Stone"
    desc: "`pf2:1` (attack,primal) **Requirements** The warden has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The warden attempts to wedge a creature they have grabbed in their mandibles within a crack in the earth that opens beneath them. The warden attempts an Athletics check check against the grabbed creature's Reflex DC. If they succeed, they bury the creature in the ground. The creature takes 10d10 bludgeoning damage. It is also [[Conditions/Restrained|Restrained]], [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating until it [[Actions/Escape|Escapes]] (DC 42). If the creature is still buried at the end of its turn, it takes 5d10 bludgeoning damage."

  - name: "Called to Depths"
    desc: "  The depths call to the warden, especially as they move through the air. When they [[Actions/Long Jump|Long Jump]], they can use any unused movement from the Long Jump to [[Actions/Burrow|Burrow]]. Additionally, the warden can Burrow through any earthen matter, including rock. When they do so, they move at their full burrow Speed."

  - name: "Erupting Jump"
    desc: "`pf2:2` (primal) The warden draws out a stream of lava, then jumps off the solidifying mass as it cools. The warden [[Actions/Leap|Leaps]] up to twice their Speed. When they land, the force of the impact deals 6d12 bludgeoning damage to all creatures within a 15-foot emanation with a DC 42 Fortitude check save. On a critical failure, the creature is also pushed 10 feet away from the warden."

  - name: "Obsidian Cage"
    desc: "  Rapidly cooling obsidian clings to the target's body and stiffens around their limbs. The target must attempt a DC 42 Reflex check save. On a failure, the target is [[Conditions/Immobilized|Immobilized]] until they [[Actions/Escape|Escape]] (DC 42). On a critical failure, the target is [[Conditions/Off-Guard|Off-Guard]] for as long as they remain immobilized."

  - name: "Vibratory Excavation"
    desc: "`pf2:2` (manipulate,primal) The warden screeches with a resonant call that tears apart earth and stone. They create a 10-foot-square, 50-foot-deep pit in earthen material or stone within 60 feet."

  - name: "Wall Cling"
    desc: "  The Warden of Caverns and Burrows clings to surfaces with their segmented feet. They do not need to use a hand to hold on to walls or ceilings."
 
```

```encounter-table
name: Warden of Caverns and Burrows
creatures:
  - 1: Warden of Caverns and Burrows
```



## The Connected Depths

As much as air currents flow through the skies, and the oceans connect the waters of world, the caverns and depths connect to each other as well, via several means. Underground flows of lava create tunnels and passages. Water's erosion also forms cave systems out of the stone.
