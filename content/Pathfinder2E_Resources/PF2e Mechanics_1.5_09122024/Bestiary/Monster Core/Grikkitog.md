---
title: "Grikkitog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hLfNjEEwfcdJc8DJ" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Grikkitog"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Grikkitog"
level: "Creature 14"

alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[earth]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +28, Deception: +27, Survival: +25"
abilityMods: [8, 4, 5, 2, 5, 5]
speed: 20 feet,  burrow 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +23, __Will__ +24"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Resistances__ all damage 10 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Implant Core"
    desc: "`pf2:3` (manipulate) The grikkitog implants its core into an adjacent section of earth or stone, melding seamlessly and changing its visual appearance to match the surrounding rock. It's [[Conditions/Immobilized|Immobilized]] but automatically succeeds at its Deception check to Impersonate the stone around it; creatures actively searching for it can still attempt Perception checks against its Deception DC as normal. A grikkitog can release its implantation as a free action, which has the manipulate trait. A grikkitog's infestation aura and manifold vision are only active while implanted."

  - name: "Manifold Vision"
    desc: "  While its core is implanted, the grikkitog can see through the eyes it creates throughout the area of its infestation aura, gaining the benefits of [[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]."

abilities_mid:
  - name: ""
  - name: "Infestation Aura"
    desc: " (aura,earth,occult) 120 feet.\n\nWhile its core is implanted, a grikkitog infests all earth and stone within 120 feet, as long as there is a contiguous physical connection between the earth, including stone objects touching the ground. This effect spreads even if the grikkitog does not have line of effect, though it can affect earth or stone on the surface and exposed to the air only if at least part of its core is exposed as well.\n\nWithin the aura, it can grow maws and eyes everywhere. It can make jaws attacks against any creature, originating from any earth or stone in the aura adjacent to that creature. Determine cover from the origin point of the attack, not from the grikkitog's core."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (magical)\n__Damage__  3d12 + 14 piercing plus barbed-maw"

  - name: "Barbed Maw"
    desc: "  **Trigger** The grikkitog hits a creature with a jaws Strike\n* * *\n\n**Effect** The grikkitog sinks its barbed teeth into the target, which must succeed at a DC 34 Reflex check save or be [[Conditions/Immobilized|Immobilized]]. While immobilized, the victim takes 3d8 persistent bleed damage and the grikkitog feeds upon its flesh. The creature is immobilized until the grikkitog ends the effect as a free action or the target succeeds at a DC 38 check to [[Actions/Escape|Escape]].\n\nThe grikkitog can immobilize any number of creatures with these maws."

  - name: "Earth Glide"
    desc: "  The grikkitog can Burrow through dirt and stone at its full burrow Speed, leaving no tunnels or signs of its passing."
 
```

```encounter-table
name: Grikkitog
creatures:
  - 1: Grikkitog
```



Grikkitogs, also known as the "hungry earth," are strange parasites from the Plane of Earth that infest earth, rock, and stone in order to feed their endless hunger. A young grikkitog is a formless apparition until it corrupts an earth elemental host, forming the grikkitog's core. A grikkitog can then possess the earth and stone nearby with its voracious essence, forming maws and eyes all around it. These creatures can be particularly dangerous to small creatures that lair within gaps among rocks, as well as mountain climbers searching for the perfect handhold.
