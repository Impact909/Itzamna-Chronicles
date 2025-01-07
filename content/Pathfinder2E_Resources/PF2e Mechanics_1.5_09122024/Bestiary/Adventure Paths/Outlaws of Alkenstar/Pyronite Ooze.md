---
title: "Pyronite Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PDu4opItUk8zzeRu" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Pyronite Ooze"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Pyronite Ooze"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +22"
abilityMods: [7, -5, 7, -5, 0, -5]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +24, __Ref__ +14, __Will__ +19"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Immunities__  bludgeoning,  critical hits,  fire,  precision,  unconscious,  visual,  mental; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Constant Explosions"
    desc: " (aura,fire) 5 feet. 4d6 fire, DC 29 Reflex check. This aura can't cause other pyronite oozes to split."

  - name: "Rejoin"
    desc: "  If two or more Medium pyronite oozes end their turn in adjacent spaces, they merge into a Large pyronite ooze, combining their current Hit Points."

  - name: "Split"
    desc: "  When a Large pyronite ooze is hit by an attack that would deal bludgeoning or fire damage and it has 10 or more HP, it explodes, dealing 6d6 fire damage to creatures in a 10-foot radius (DC 29 Reflex check). This explosion can't cause other pyronite oozes to split. After exploding, the ooze splits into two Medium pyronite oozes, each with half the original's HP, which each fly through the air and land 15 feet from the original ooze in a random direction. If no space is unoccupied where the ooze would land, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or sturdy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+23 (reach 10 feet)\n__Damage__  3d10 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Blast"
    desc: "+21 (fire, range increment 40 feet)\n__Damage__  3d8 + 3 fire"

  - name: "Exploding Split"
    desc: "`pf2:2`  **Requirements** The pyronite ooze is Large\n* * *\n\n**Effect** The pyronite ooze explodes in a violent conflagration, dealing 3d6 fire and 3d6 bludgeoning damage to all creatures in a 30-foot radius (DC 29 Reflex check). This explosion can't cause other pyronite oozes to split. After exploding, the ooze splits into two Medium pyronite oozes (see above), but this splitting doesn't deal additional damage."
 
```

```encounter-table
name: Pyronite Ooze
creatures:
  - 1: Pyronite Ooze
```



With the discovery of the incredible gelatinous explosive called pyronite, it was perhaps inevitable alchemical monstrosities made of the stuff would soon follow. So-called pyronite oozes sometimes spontaneously manifest from stockpiles of pyronite or other powerful explosives, typically amid mana storms or when affected by powerful magic.

Pyronite oozes have an extremely unstable life cycle and are defined by their ability to continuously explode and reform themselves. A pyronite ooze's violent explosions hinder observations, making it difficult to learn anything from the volatile jelly. To complicate matters further, pyronite oozes seem drawn to other unstable alchemical concoctions. Test subjects brought to the Spellscar Desert have been observed bathing themselves in pools of magic-polluted effluvia. Although they typically reform into a single entity after exploding, pyronite oozes bathed in chemicals sometimes remain apart after splitting, creating two independent oozes. Some speculate that an as yet unknown reagent must be essential for the oozes to reproduce on their own.
