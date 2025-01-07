---
title: "Skinsaw Seamer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ReYeiLCS7bDzpACL" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Skinsaw Seamer"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Skinsaw Seamer"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Common, Daemonic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +17, Deception: +16, Medicine: +17, Religion: +17, Thievery: +16, Norgorber Lore: +16"
abilityMods: [3, 4, 0, 2, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +18, __Will__ +17"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Dagger|Dagger]], [[Equipment/Shortsword|+1 Striking Shortsword]], [[Equipment/War Razor|War Razor]], [[Equipment/Leather Armor|Leather Armor]], Assorted Rags and Textiles, Metal Wire, [[Equipment/Religious Symbol (Silver)|Religious Symbol (Silver) of Norgorber]], [[Equipment/Skinsaw Mask|Skinsaw Mask]]"
abilities_mid:
  - name: ""
  - name: "Wire Catch"
    desc: "`pf2:r`  Every Skinsaw seamer keeps a sewing needle attached to a loop of thick silk, wrapped loosely around their hand not holding a weapon, which they can use in combat to snag or disarm attackers\n\n**Trigger** A creature hits the seamer with a melee Strike\n* * *\n\n**Effect** The seamer attempts an Athletics check to either [[/act grapple]] or [[/act disarm]] the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` War Razor"
    desc: "+20 (agile, backstabber, deadly d8, finesse)\n__Damage__  1d4 + 7 piercing"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+18 (agile, finesse, magical, versatile s)\n__Damage__  2d6 + 7 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+20 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 7 piercing"

  - name: "Flay"
    desc: "`pf2:1`  **Requirements** The Skinsaw seamer dealt damage with a melee weapon other than its war razor with their last action\n* * *\n\n**Effect** The seamer makes a war razor Strike against the same creature that they just damaged. On a hit, the seamer slices a strip of flesh from the target and deals 1d6 bleed in addition to the war razor's usual damage."

  - name: "Quick Stitch"
    desc: "`pf2:2`  **Requirements** The Skinsaw seamer is currently grappling a creature\n* * *\n\n**Effect** The seamer stitches a piece of cloth to the creature's arm, face, or leg, potentially hindering it. The creature must attempt a DC 26 Reflex check saving throw; if the seamer has already successfully used their Flay ability against the creature within the past minute, the creature's save result is one degree of success worse.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d4 piercing damage.\n\n**Failure** The creature is [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Dazzled|Dazzled]], [[Conditions/Enfeebled|Enfeebled 1]], or [[Conditions/Off-Guard|Off-Guard]] (seamer's choice). This effect lasts until the creature spends a single action to tear out the stitching, which deals 1d6 piercing damage to it.\n\n**Critical Failure** The creature is [[Conditions/Clumsy|Clumsy 2]], [[Conditions/Blinded|Blinded]], [[Conditions/Enfeebled|Enfeebled 2]], or off-guard (seamer's choice). This effect lasts until the creature spends 2 actions to tear out the stitching, which deals 2d6 piercing damage to it."
 
```

```encounter-table
name: Skinsaw Seamer
creatures:
  - 1: Skinsaw Seamer
```




