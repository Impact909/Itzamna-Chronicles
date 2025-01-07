---
title: "Granite Glyptodont"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.K0Pyjajljzqj5j8d" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Granite Glyptodont"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Granite Glyptodont"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Tremorsense (Imprecise) 90 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [6, 1, 6, 0, 5, 0]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +13, __Will__ +17"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 90 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+20 (forceful, reach 10 feet, versatile p)\n__Damage__  2d12 + 9 bludgeoning plus calcification"

  - name: "Calcification"
    desc: " (incapacitation,primal) A blow from a granite glyptodont's tail hardens the flesh of the creature struck. The target must succeed at a DC 26 Fortitude check saving throw or become [[Conditions/Slowed|Slowed 1]] (or [[Conditions/Slowed|Slowed 2]] on a critical failure). Further failed saves against calcification increase the value of the slowed condition. Once a creature's actions are reduced to 0 by calcification, that creature becomes [[Conditions/Petrified|Petrified]]. If the creature isn't petrified, the slowed conditions end once 1 minute passes without the creature failing a save against calcification.\n\nEvery 24 hours after it was petrified, the creature can attempt a DC 26 Fortitude check save to recover. On a success, it becomes flesh again, but is [[Conditions/Slowed|Slowed 1]] for the next 24 hours. On a critical success, the creature recovers and isn't slowed. On a failure, the creature remains petrified, but can try again in 24 hours. On a critical failure, the petrification is permanent, and the creature can't attempt any more saves."

  - name: "Earth Glide"
    desc: "  A granite glyptodont can [[Actions/Burrow|Burrow]] through earthen matter, including rock. When it does so, it moves at its full burrow Speed, leaving no tunnels or signs of its passing."
 
```

```encounter-table
name: Granite Glyptodont
creatures:
  - 1: Granite Glyptodont
```



This squat and stony creature looks like an armadillo with a large raised back and a flail-like tail. The granite glyptodont has no true need to feed, as with all elementals, yet it does seem to linger after transforming the flesh of those it calcifies, as if the mere proximity of flesh fossilizing into stone pleases it somehow.
