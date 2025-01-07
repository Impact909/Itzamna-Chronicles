---
title: "Shimmerthief"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.60TkQZYaMhbVVd64" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Shimmerthief"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #198: No Breath to Cry"
name: "Shimmerthief"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Echolocation 120 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Stealth: +17, Survival: +17"
abilityMods: [4, 6, 3, 0, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder #198: No Breath to Cry_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +12, __Ref__ +17, __Will__ +15"
hp: 119
health:
  - name: ""
  - name: HP
    desc: "119; __Immunities__  blinded,  dazzled,  visual"
abilities_top:
  - name: ""

  - name: "Echolocation 120 feet"
    desc: "  A shimmerthief can use their hearing as a precise sense at the listed range."

  - name: "Shimmervision"
    desc: "  A shimmerthief's sight allows them to sense sources of light from the same distance as creatures with standard vision but doesn't allow them to make out details. They can't detect anything other than light sources using this vision."

abilities_mid:
  - name: ""
  - name: "Gleam Theft"
    desc: " (aura,darkness,primal) 10 feet. A shimmerthief constantly absorbs ambient light. Bright light in their aura becomes dim light, and dim light becomes darkness. A shimmerthief can suppress or activate this aura as a single action with the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 ()\n__Damage__  2d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  2d6 + 10 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Darkness|Darkness]]_; __2nd __  _[[Spells/Blur|Blur]]_, _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Drain Light"
    desc: "`pf2:2` (darkness,primal) The shimmerthief targets a light source within 30 feet, then attempts to counteract it with a spell attack roll. If they succeed, the shimmerthief regains 2d8+10 Hit Points (4d8+20 Hit Points on a critical success)."

  - name: "Lasting Darkness"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The shimmerthief casts [[Spells/Darkness|Darkness]] as a 2nd-rank spell\n* * *\n\n**Effect** The duration of the shimmerthief's _darkness_ increases to 24 hours."

  - name: "[[Actor.OoTnmIkunSTCPet3.Item.pVX2irGBvUFMoufU|Unnerving Shriek]]"
    desc: "`pf2:2` (auditory,emotion,fear,mental,primal) The shimmerthief releases an unearthly wail, forcing creatures within 60 feet to attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is frightened 2 and [[Conditions/Fleeing|Fleeing]] for as long as it remains frightened."
 
```

```encounter-table
name: Shimmerthief
creatures:
  - 1: Shimmerthief
```



Shimmerthieves are blind, lizard-like cave dwellers with an insatiable yearning to consume the rare delicacy of light. This hunger compels them to travel beyond their subterranean lairs to the surface to feed, leaving pockets of darkness behind as they go.

They're far from unintelligent yet prefer to avoid other sapient creatures, aware that many find them off-putting. They become independent at a young age but are protective of their kind, and they travel in small groups when able. Prudent shimmerthieves try to avoid feeding on light in busy areas, but such places are also the most tempting, as bustling populations mean more light sources.

## Alternate Diets

Some shimmerthieves develop a taste for and the capacity to consume energy forms far more insidious than light, allowing them to feed on life energy or thought energy instead of light. Such behavior is considered monstrous by most shimmerthieves and a reason for exile. Shimmerthieves with these proclivities are dangerous predators that maintain the ability to feed on light and purposely create pockets of darkness to trap and feed on victims. A shimmerthief that feeds on life energy deals negative damage with their jaws, while one that feeds on thought energy deals mental damage with their jaws.
