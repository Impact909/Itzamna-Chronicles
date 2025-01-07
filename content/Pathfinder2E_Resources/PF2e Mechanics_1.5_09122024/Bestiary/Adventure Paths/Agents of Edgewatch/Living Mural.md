---
title: "Living Mural"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ogZfoLmxo3mJogjX" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Living Mural"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Living Mural"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[construct]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +38, Crafting: +27, Deception: +37, Stealth: +38"
abilityMods: [6, 10, 5, -2, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +31, __Ref__ +34, __Will__ +30"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Backdrop"
    desc: "  When a creature attempts to Strike a living mural and critically misses, the attacker hits the surface (a wall, canvas, or so on) behind the living mural. This can damage or break the weapon or surface."

  - name: "Surface-Bound"
    desc: "  A living mural can move only along flat surfaces such as floors and walls. This allows it to end its movement wrapped around corners when on a continuous surface.\n\nIf the surface it's on is destroyed (such as a portrait hit by a fireball spell or a puddle being splashed), the mural takes 10d6 damage and is shunted to the nearest flat surface. If there is no flat surface within 5 feet, the living mural is destroyed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+37 (agile, finesse, magical, reach 15 feet)\n__Damage__  4d8 + 15 bludgeoning"

  - name: "**Ranged** `pf2:1` Splatter"
    desc: "+35 (magical, nonlethal, range increment 30 feet)\n__Damage__  3d8 + 4 bludgeoning plus splash-of-color"

  - name: "Collective Attack"
    desc: "`pf2:2`  The subjects depicted within the living mural all reach out at once to attack. The living mural makes a fist Strike against each target within range.\n\nThese attacks count toward the living mural's multiple attack penalty, but this penalty doesn't increase until after all of the attacks are made."

  - name: "Paint the Masses"
    desc: "`pf2:2`  The living mural expels a 15-foot cone of paint.\n\nCreatures in the area must succeed at a DC 41 Reflex check save or be [[Conditions/Blinded|Blinded]] for 1 round.\n\nThe living mural can't use Paint the Masses again for 1d4 rounds."

  - name: "Splash of Color"
    desc: "  When the living mural hits with a splatter attack, the target is also [[Conditions/Blinded|Blinded]] for 1 round."
 
```

```encounter-table
name: Living Mural
creatures:
  - 1: Living Mural
```




