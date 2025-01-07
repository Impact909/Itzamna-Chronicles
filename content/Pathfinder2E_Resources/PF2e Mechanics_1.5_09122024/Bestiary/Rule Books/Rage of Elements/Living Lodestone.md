---
title: "Living Lodestone"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fkFKXEbcWIWsF9kY" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Living Lodestone"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Living Lodestone"
level: "Creature 6"

alignment: ""
size: "Small"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [5, 3, 4, 0, 4, 4]
speed: 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +13, __Will__ +16"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ electricity 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Electromagnetic Disruption"
    desc: "  When living lodestone takes electricity damage, they automatically reverses polarity."

  - name: "Magnetic Field"
    desc: " (aura,metal,primal) 60 feet.\n\nA living lodestone constantly emits a powerful magnetic field that is either positively or negatively aligned. Each creature within the aura that is wielding a metallic weapon, wearing metallic armor, or made partially or entirely out of metal is subject to an effect determined by the lodestone's current polarity.\n\n**Negative** An affected creature is pushed 5 feet away from the lodestone at the start of each of its turns, and it treats each square in the aura as difficult terrain when moving closer to the lodestone. Unattended metal objects in the aura of 2 Bulk or less are pushed just outside the aura.\n\n**Positive** An affected creature is pulled 5 feet toward the lodestone at the start of each of its turns, and it treats each square in the aura as difficult terrain when moving farther from the lodestone. Unattended metal objects in the aura of 2 Bulk or less are pulled adjacent to the lodestone."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jolt"
    desc: "+15 ()\n__Damage__  2d6 + 8 electricity"

  - name: "**Ranged** `pf2:1` Hurled Metal Object"
    desc: "+13 (magical, primal, range increment 60 feet)\n__Damage__  2d10 + 7 bludgeoning"

  - name: "Hover"
    desc: "  A living lodestone floats above the ground high enough to ignore all difficult terrain and greater difficult terrain on the ground."

  - name: "Magnetic Disarm"
    desc: "`pf2:1` (primal) The living lodestone attempts to [[Actions/Disarm|Disarm]] a metal weapon from a creature within its magnetic field. On a critical success, the weapon is either pushed to just outside the aura if the polarity is negative or is pulled to the lodestone and sticks to it if the polarity is positive. An item stuck to the lodestone can be wrenched free with an Interact action."

  - name: "Reverse Polarity"
    desc: "`pf2:2`  The living lodestone switches the polarity of its magnetic field from positive to negative, or vice versa. Each creature affected by the lodestone's aura falls [[Conditions/Prone|Prone]] unless it succeeds at a DC 21 Reflex check save.\n\nThe lodestone can't Reverse Polarity again for 1d4 rounds."
 
```

```encounter-table
name: Living Lodestone
creatures:
  - 1: Living Lodestone
```



This rotating sphere of dark, shiny metal floats about 5 feet off the ground, constantly surrounded by a whirling frenzy of smaller metallic objects caught up in its powerful magnetic field.
