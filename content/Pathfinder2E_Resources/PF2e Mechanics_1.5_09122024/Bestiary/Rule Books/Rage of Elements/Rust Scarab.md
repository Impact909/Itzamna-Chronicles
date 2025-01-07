---
title: "Rust Scarab"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DsEIlBdjE71PLBuX" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Rust Scarab"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Rust Scarab"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Plane of Metal Lore: +11"
abilityMods: [6, 2, 5, 2, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +9, __Will__ +11"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ electricity 5, physical 5 (except adamantine)"
abilities_top:
  - name: ""

  - name: "Heavy"
    desc: "  As long as it is immobile, the elemental can't be forcibly moved or knocked [[Conditions/Prone|Prone]]. If it takes a move action, it loses this immunity until the start of its next turn."

  - name: "Rust Vision"
    desc: "  A rust scarab ignores the [[Conditions/Concealed|Concealed]] condition from rust clouds."

abilities_mid:
  - name: ""
  - name: "Crumbling Carapace"
    desc: "  When a rust scarab is reduced to fewer than half its maximum Hit Points or is damaged by a critical hit, its outer shell breaks into a veil of rusty metal flakes. This causes it to lose its resistance to physical damage and its heavy ability, but it gains a rust cloud aura and a 35-foot land Speed."

  - name: "Rust Cloud"
    desc: "  A rust scarab whose carapace is broken is constantly surrounded by a cloud of rust flakes that cause it to be [[Conditions/Concealed|Concealed]] from creatures more than 5 feet away from it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 ()\n__Damage__  2d8 + 6 slashing plus tetanus"

  - name: "Tetanus"
    desc: " (disease) **Saving Throw** DC 19 Fortitude check\n\n**Onset** 1 week\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 week)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and can't speak (1 day)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] with spasms (1 day)\n\n**Stage 4** death"

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, claw, DC 23 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Rust Scarab
creatures:
  - 1: Rust Scarab
```



These elementals resemble enormous beetles, with thick outer shells composed of multiple layers of heavily pockmarked, rusted plates protecting a jagged metallic skeleton.

* * *

Metal elementals can manifest in a wide variety of different forms, from shapeless amalgams of different metals to humanoid and beast-like monstrosities.

## Metal Forms

Though metal elementals are made almost entirely of metal, most are composed of layers of different metals in tiny fragments, as complex as a body of flesh or plant matter. Many of these metals are rusted or decayed from the natural, slow entropy of the Plane of Metal.
