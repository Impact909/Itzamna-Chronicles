---
title: "Nanoshard Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hsT2EblyejfhtEO7" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Nanoshard Swarm"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Nanoshard Swarm"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[metal]]
trait_03: [[swarm]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +19, Stealth: +21"
abilityMods: [6, 6, 4, 3, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +17, __Ref__ +21, __Will__ +16"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  bleed,  paralyzed,  poison,  sleep,  swarm mind,  precision,  grabbed,  prone,  restrained; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ bludgeoning 5, electricity 10, piercing 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Electromagnetic Dispersal"
    desc: "  When a nanoshard swarm takes electricity damage, they automatically shift into swarm form."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+19 (reach 60 feet, versatile b)\n__Damage__  2d8 + 9 piercing"

  - name: "Barrier Form"
    desc: "`pf2:3` (concentrate,polymorph) **Requirements** The nanoshard swarm is in swarm form\n* * *\n\n**Effect** The nanoshard swarm forms a continuous 6-inch-thick solid wall, up to 60 feet long and 10 feet high, originating from any one square in its current space. The wall can follow any path, with each 5 feet being placed on the border between squares. It doesn't need to stand vertically, so it can form a bridge or set of stairs, for example. The wall must be formed in an unbroken open space where its edges don't pass through any creatures or objects.\n\nA single 5-foot-by-5-foot section of the wall can be destroyed by dealing 18 points of damage to it, which also reduces the swarm's total Hit Points. A nanoshard swarm can't be knocked [[Conditions/Prone|Prone]] or forcibly moved while in barrier form, nor can it voluntarily move. A nanoshard swarm in barrier form can originate tendril attacks from any square of its wall."

  - name: "Battle Form"
    desc: "`pf2:2` (concentrate,polymorph) **Requirements** The nanoshard swarm is in swarm form\n* * *\n\n**Effect** The nanoshard swarm coalesces into a Huge shape that looks like a humanoid or beast and can hold items. In battle form, its Speed is 15 feet, it's [[Conditions/Clumsy|Clumsy 1]], and it has the following Strike.\n\n**Melee** `pf2:1` limb (reach 20 feet), **Damage** 4d8+9 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf (Swarm Form)]]"
    desc: "`pf2:2`  DC 27 Reflex check, 2d8+6 bludgeoning damage, Escape DC 27, Rupture 18\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Swarm Form"
    desc: " (concentrate) The nanoshard swarm collapses into its natural form: a Huge sea of tiny metal spheres. It drops anything it's holding. While in swarm form, the nanoshard swarm's Speed is 25 feet, it can move through any area large enough for a single sphere to fit through without having to Squeeze, and it gains Engulf."
 
```

```encounter-table
name: Nanoshard Swarm
creatures:
  - 1: Nanoshard Swarm
```



This bizarre entity is actually a massive collective consisting of tens of thousands of constituent parts, each a tiny metal sphere barely the size of a pebble. Controlled by a single elemental spirit, the swarm is capable of flowing like liquid through the smallest openings before shaping itself into a powerful combatant, a solid wall, or any other form circumstances might require.
