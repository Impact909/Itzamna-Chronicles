---
title: "Skeletal Drummer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.37E56EJxLCVN5lIo" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Skeletal Drummer"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Skeletal Drummer"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Diplomacy: +9, Intimidation: +9, Performance: +13, Warfare Lore: +10"
abilityMods: [1, 3, 1, 3, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +12, __Will__ +9"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5, sonic 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Musical Instrument (Handheld)|Drum]]"
abilities_mid:
  - name: ""
  - name: "Rhapsodic Flourish"
    desc: "`pf2:r` (occult,sonic) **Trigger** The skeletal drummer would roll a saving throw against an auditory or sonic effect\n* * *\n\n**Effect** The skeletal drummer performs a refrain that deflects sonic vibrations. They roll a Performance check in place of the triggering saving throw. Sonic feedback rebounds from the effect, dealing 1d6 sonic damage to the source of the triggering effect if the Performance check succeeded or 2d6 sonic damage to the skeletal drummer on a failure."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stomp"
    desc: "+10 (finesse)\n__Damage__  2d8 + 3 bludgeoning"

  - name: "**Melee** `pf2:1` Drumstick"
    desc: "+10 (agile, finesse)\n__Damage__  2d6 + 3 bludgeoning"

  - name: "**Ranged** `pf2:1` Thunderous Beat"
    desc: "+10 (magical, range 40 feet, sonic)\n__Damage__  2d6 + 4 sonic"

  - name: "Destructive Finale"
    desc: "`pf2:2` (occult,sonic) **Requirements** March to War is in effect\n* * *\n\n**Effect** The skeletal drummer performs a boisterous finale. They choose a 30-foot cone or 15-foot emanation, and they deal 4d6 sonic damage to all creatures in that area (DC 21 Reflex check save). March to War immediately ends, and the skeletal drummer can't use March to War or Destructive Finale for [[/gmr 1d4 #rounds]]{1d4 rounds}."

  - name: "March to War"
    desc: "`pf2:2` (auditory,emotion,mental,occult) The skeletal drummer plays a regular beat that compels others to march. Each creature in a 30-foot emanation must attempt a DC 19 Will check save. Undead are immune. The effect lasts until the end of the skeletal drummer's next turn, but the skeletal drummer can Sustain the effect on all affected creatures that remain within the emanation.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 1 hour.\n\n**Success** The creature can't use actions with the move trait except to march, which uses the Stride action to move up to half the creature's Speed. If the creature has other Speeds, it can also march using those modes of travel.\n\n**Failure** As success, and the creature must spend at least 1 action each turn marching."
 
```

```encounter-table
name: Skeletal Drummer
creatures:
  - 1: Skeletal Drummer
```


Variant fiddling bones

To some, music is more than a hobby-it's an obsession. Every musician who lived and died for their craft runs the risk of returning as a fiddling bones, as do musicians who died before completing their magnum opus or receiving the accolades they believe they deserved. Driven to prove themselves even in undeath, fiddling bones often challenge famous performers to music duels.
