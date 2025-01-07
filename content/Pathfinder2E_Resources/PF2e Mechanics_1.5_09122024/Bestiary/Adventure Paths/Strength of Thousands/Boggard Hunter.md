---
title: "Boggard Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WFH4k3oBtRRLwJyx" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Boggard Hunter"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #171: Hurricane&#x27;s Howl"
name: "Boggard Hunter"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[chaotic]]
trait_04: [[evil]]
trait_05: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Boggard"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Intimidation: +12, Stealth: +15, Survival: +14"
abilityMods: [5, 2, 3, -1, 3, 1]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder #171: Hurricane&#x27;s Howl_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +15, __Will__ +12"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|Greatclub]], 5x [[Equipment/Javelin|Javelin]], [[Equipment/Studded Leather Armor|Studded Leather Armor]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+18 (backswing, shove)\n__Damage__  1d10 + 7 bludgeoning"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+18 (reach 10 feet)\n__Damage__  1d4 + 7 bludgeoning plus tongue-grab"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+15 (thrown 30 ft.)\n__Damage__  1d6 + 7 piercing"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A boggard hunter deals an additional 2d6 precision damage precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Swamp Stride"
    desc: "  A boggard hunter ignores difficult terrain caused by swamp terrain features."

  - name: "Terrifying Croak"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The boggard unleashes a terrifying croak. Any non-boggard within 30 feet becomes [[Conditions/Frightened|Frightened 1]] unless they succeed at a DC 25 Will check save; those who critically succeed are temporarily immune for 1 minute."

  - name: "Tongue Grab"
    desc: "  If a boggard hunter hits a creature with her tongue, that creature becomes [[Conditions/Grabbed|Grabbed]]. Unlike with a normal grab, the creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the boggard hunter's tongue.\n\nA creature can sever the tongue by hitting AC 22 and dealing at least 7 slashing damage. Though this doesn't deal any damage to the boggard, it prevents it from using their tongue Strike until they regrows their tongue, which takes a week."
 
```

```encounter-table
name: Boggard Hunter
creatures:
  - 1: Boggard Hunter
```




