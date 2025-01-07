---
title: "Melomach"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PZMt2d5tYybUbesL" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Melomach"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Melomach"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Crafting: +21, Intimidation: +28, Performance: +26"
abilityMods: [9, 4, 9, 0, 2, 7]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +23, __Will__ +23"
hp: 292
health:
  - name: ""
  - name: HP
    desc: "292; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ electricity 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Heavy"
    desc: "  As long as it is immobile, the elemental can't be forcibly moved or knocked [[Conditions/Prone|Prone]]. If it takes a move action, it loses this immunity until the start of its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (agile, reach 15 feet, versatile p, versatile s)\n__Damage__  3d12 + 18 bludgeoning"

  - name: "**Ranged** `pf2:1` Lightning"
    desc: "+21 (electricity, magical, range 120 feet)\n__Damage__  3d10 + 16 electricity"

  - name: "Lightning Punch"
    desc: "`pf2:2`  The melomach makes a fist Strike, then makes a lightning Strike against a different creature within 120 feet of the fist Strike's target. Both Strikes count toward the melomach's multiple attack penalty, but it doesn't increase until after both attacks are made."

  - name: "Rhythmic Stomp"
    desc: "`pf2:1` (emotion,mental,primal) **Frequency** once per round\n* * *\n\n**Effect** The melomach's footsteps raise a clanging sound through their body to create a brief musical phrase. The melomach Strides, then generates the effect of one of the following bard composition cantrips at 7th rank: [[Spells/Allegro|Allegro]], [[Spells/Dirge of Doom|Dirge of Doom]] (adds the fear trait), or [[Spells/Triple Time|Triple Time]]."

  - name: "Scream"
    desc: "`pf2:2` (primal,sonic) The melomach unleashes a guttural, ear-piercing wail. All creatures in a 120-foot cone take 7d12 sonic damage with a DC 32 Fortitude check save.\n\nThe melomach can't Scream again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage, is [[Conditions/Stunned|Stunned 1]], and is [[Conditions/Deafened|Deafened]] for 1 minute.\n\n**Critical Failure** The creature takes double damage, is [[Conditions/Stunned|Stunned 3]], and is deafened permanently."
 
```

```encounter-table
name: Melomach
creatures:
  - 1: Melomach
```



Melomachs are massive, vaguely humanoid elementals composed of metal debris. They take great pride in decorating and augmenting their metallic bodies with haphazardly placed spikes, blades, humanoid or bestial skulls, and other similar adornments, the more ostentatious the better. When two melomachs meet, the resulting contests of physical might and vocal prowess can last for days, often leaving the landscape ravaged for miles in every direction.
