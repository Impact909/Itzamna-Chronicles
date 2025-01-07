---
title: "Sanzuwu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QQ4Iv2zyMsuF1at3" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Sanzuwu"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Sanzuwu"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[beast]]
trait_02: [[fire]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision"
languages: "Common; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +27, Diplomacy: +25"
abilityMods: [4, 8, 6, 4, 5, 4]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +29, __Will__ +23"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  fire,  light; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Golden Sun"
    desc: " (aura,primal) 10 feet. A golden aura envelopes the sanzuwu, protecting them from weak magic. Any non-cold spells of 3rd level or lower burn away and are ineffective. A sanzuwu can deactivate or activate the golden aura as a free action with the concentrate trait."

  - name: "Scorching Gaze"
    desc: "`pf2:r` (fire,primal) **Trigger** A creature within 30 feet targets the sanzuwu or one of their allies with a weapon attack\n* * *\n\n**Effect** The sanzuwu focuses their gaze on the triggering creature's weapon, heating it to a burning temperature for an instant. The creature takes 4d8 fire damage unless the creature Releases the weapon as a free action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+30 (finesse, fire, magical)\n__Damage__  3d6 + 14 piercing 3d6 fire"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+30 (agile, finesse, fire, magical)\n__Damage__  3d4 + 14 piercing 3d6 fire"

  - name: "Fiery Transformation"
    desc: "`pf2:2` (concentrate,fire,polymorph,primal) The sanzuwu transforms into an enormous bird made of flame. As the sanzuwu begins their transformation, creatures within a 10-foot emanation take 6d8 fire damage (DC 33 Reflex check save). While in their flame form, the sanzuwu gains the effects of 4th-rank [[Spells/Enlarge|Enlarge]]. They can use Fiery Transformation again to revert back to their standard form."

  - name: "Radiant Blast"
    desc: "`pf2:2` (fire,primal) The sanzuwu opens their mouth to produce a bead of burning energy, hurling it a point within 200 feet. The bead detonates, dealing 7d8 fire damage and 4d10 sonic damage to all creatures in a 30-foot burst (DC 33 Reflex check save). Creatures that critically fail become [[Conditions/Blinded|Blinded]] for 1 round. The sanzuwu can't use Radiant Blast again for 1d4 rounds."

  - name: "Scorch Earth"
    desc: "`pf2:2`  **Requirements** The sanzuwu is standing on the ground\n* * *\n\n**Effect** The sanzuwu Strides. A 6th-rank [[Spells/Wall of Fire|Wall of Fire]] appears in all the spaces the sanzuwu left during this movement, lasting for 1 round. The sanzuwu can't use Scorch Earth again for 1d4 rounds."

  - name: "Transfixing Sunbeam"
    desc: "`pf2:2` (incapacitation,light,primal) **Requirements** The sanzuwu is in their fiery form\n* * *\n\n**Effect** The sanzuwu spreads their wings, emitting a bright cascade of light in a 30-foot cone. Creatures in the cone must attempt a DC 33 Fortitude check save.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 2]]."
 
```

```encounter-table
name: Sanzuwu
creatures:
  - 1: Sanzuwu
```



Those who feast on the sun are said to carry its power within them. Sanzuwus are small crows with red plumage and dark throats. According to legend, they stole their burning power from the sun and now fly across the sky as blinding streaks of fire. When they land on the earth, it ignites around them, causing unbound destruction. A handful of people worship these radiant birds and inscribe their three-legged visage on coins, items, and weapons.
