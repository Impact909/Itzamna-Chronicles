---
title: "Reefclaw (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.odZV5EoWDm68j063" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Reefclaw (BB)"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Reefclaw (BB)"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[aquatic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4"
abilityMods: [1, 4, 2, -3, 1, 1]
speed: 5 feet,  swim 30 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +7, __Ref__ +9, __Will__ +4"
hp: 17
health:
  - name: ""
  - name: HP
    desc: "17"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Death Frenzy"
    desc: "`pf2:r`  When the reefclaw is reduced to 0 hit points it can spend this reaction to make a claw Strike before dying."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (finesse)\n__Damage__  1d6 + 1 slashing plus grab,reefclaw-venom"

  - name: "Constrict"
    desc: "`pf2:1`  If the reefclaw has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]], it can spend one action to crush them in its coils. The creature takes 1d6 bludgeoning damage depending on its DC 17 Fortitude check save."

  - name: "Reefclaw Venom"
    desc: " (poison) A target that takes slashing damage from the reefclaw's claw Strike must succeed at a DC 17 Fortitude check save or take 1d6 poison damage."

  - name: "Grab"
    desc: "`pf2:1`  When the reeflclaw succeeds at its claw Strike, it can use this action immediately after to attempt to [[Actions/Grapple|Grapple]] the target. This Grapple doesn't apply or count toward the reefclaw's multiple attack penalty."
 
```

```encounter-table
name: Reefclaw (BB)
creatures:
  - 1: Reefclaw (BB)
```



Reefclaws are aquatic monsters that resemble huge shrimp or lobsters. Though reefclaws can't speak, they are intelligent enough to understand the local language of humanoids near their hunting grounds.
