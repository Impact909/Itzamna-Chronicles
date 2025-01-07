---
title: "Ba'aupa Mdoudu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dDJNOCsIZBvqsJly" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Ba&#x27;aupa Mdoudu"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Ba'aupa Mdoudu"
level: "Creature 13"

alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27, Stealth: +25"
abilityMods: [8, 4, 5, -4, 4, -2]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +21, __Will__ +23"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245; __Immunities__  acid; __Resistances__ bludgeoning 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Reactive"
    desc: "  A ba'aupa mdoudu gains an additional reaction at the start of its turn but can use this reaction only to Slime Squirt."

  - name: "Skeleton Sense 60 feet"
    desc: "  Aba'aupa mdoudu can sense the presence of bones and skeletons within 60 feet; this is a precise sense when detecting dead bones but an imprecise one when detecting living bones."

  - name: "Slime Squirt"
    desc: "`pf2:r`  **Trigger** A creature inflicts slashing or piercing damage on the ba'aupa mdoudu with a melee Strike\n* * *\n\n**Effect** The attacking creature takes 2d10 acid damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (deadly d12)\n__Damage__  3d8 + 14 piercing 1d10 acid"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+23 (acid, range increment 60 feet)\n__Damage__  6d6 acid"

  - name: "Caustic Acid"
    desc: "  Whenever a creature takes acid damage from any of a ba'aupa mdoudu's abilities or Strikes, it must succeed at a DC 30 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure). On each subsequent failure, the drained condition value increases by 1 (or by 2 on a critical failure), to a maximum of drained 4."

  - name: "Caustic Rain"
    desc: "`pf2:2` (primal) The ba'aupa mdoudu spews copious amounts of acid into the air, creating a cascading rain to fall in a 10-foot emanation around itself. All creatures in the area take 14d6 acid damage (DC 33 Reflex check save) plus Caustic Acid. The ba'aupa mdoudu can't use Caustic Rain again for 1d4 rounds."

  - name: "Stone Tunneler"
    desc: "  A ba'aupa mdoudu can leave a tunnel when it burrows through earth or stone, and it usually does."
 
```

```encounter-table
name: Ba'aupa Mdoudu
creatures:
  - 1: Ba'aupa Mdoudu
```




