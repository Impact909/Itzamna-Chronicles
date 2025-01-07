---
title: "Bramblehand Champion Construct"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7XoPWiiTpD6s7FzB" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Bramblehand Champion Construct"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Bramblehand Champion Construct"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9"
abilityMods: [4, 3, 1, -5, 1, -5]
speed: 20 feet
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +10, __Ref__ +10, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ fire 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Wooden Maul"
abilities_mid:
  - name: ""
  - name: "Critical Vulnerability"
    desc: "  A critical hit damages the construct's controls, making it [[Conditions/Clumsy|Clumsy 1]] until repaired. Additional critical hits increase this value, up to [[Conditions/Clumsy|Clumsy 4]]."

  - name: "Ridden Construct"
    desc: "  The construct is piloted by a [[Monster Core/Leaf Leshy|Leaf Leshy]] who can be targeted separately but has greater cover. The leshy can't take actions of their own while inside the construct, other than to leave it, which takes 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wooden Maul"
    desc: "+12 (nonlethal, reach 10 feet, shove)\n__Damage__  1d12 + 4 bludgeoning"

  - name: "Hammer Block"
    desc: "`pf2:r`  **Trigger** An ally within the bramble champion's reach is targeted by an attack, and the bramble champion can see the attacker\n* * *\n\n**Effect** The bramble champion interposes with its hammer, giving the ally a +2 circumstance bonus to AC against the triggering attack."
 
```

```encounter-table
name: Bramblehand Champion Construct
creatures:
  - 1: Bramblehand Champion Construct
```




