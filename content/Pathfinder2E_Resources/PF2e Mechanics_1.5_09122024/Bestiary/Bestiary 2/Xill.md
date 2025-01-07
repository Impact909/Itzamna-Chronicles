---
title: "Xill"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.llQRItGyq5VBjNTt" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/ethereal
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Xill"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Xill"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[ethereal]]
trait_03: [[evil]]
trait_04: [[lawful]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +14, Deception: +12, Intimidation: +14, Stealth: +15, Warfare Lore: +12"
abilityMods: [4, 5, 3, 0, 3, 0]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +15, __Ref__ +17, __Will__ +11"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longbow|+1 Longbow]], 2x [[Equipment/Scimitar|Scimitar]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Breastplate|Breastplate]], 40x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+16 (forceful, sweep)\n__Damage__  2d6 + 7 slashing"

  - name: "**Melee** `pf2:1` Bite"
    desc: "+16 ()\n__Damage__  2d8 + 7 piercing plus xill-paralysis"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+17 (deadly d10, magical, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  2d8 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 24, attack +14; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (To Ethereal Plane or Material Plane only) (Self only)]]_"

  - name: "Double Slash"
    desc: "`pf2:1` (flourish) The xill makes two scimitar Strikes against a single target. If both hit, combine their damage for the purpose of the target's resistances and weaknesses. The xill applies its multiple attack penalty to each strike normally."

  - name: "Implant"
    desc: "`pf2:2` (manipulate) **Requirements** The xill is adjacent to a [[Conditions/Unconscious|Unconscious]], willing, or [[Conditions/Paralyzed|Paralyzed]] creature\n* * *\n\n**Effect** The xill implants xill eggs in the creature's flesh."

  - name: "Xill Eggs"
    desc: " (disease) The [[Conditions/Sickened|Sickened]] condition from xill eggs doesn't improve on its own until the disease is cured or runs its course. It can be cured with a 10-minute operation that requires a successful DC 26 Medicine check check and deals 4d6 slashing damage to the host\n\n**Saving Throw** DC 24 Fortitude check\n\n**Maximum Duration** 24 hours\n\n**Stage 1** infested with no ill effect (8 hours)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (8 hours)\n\n**Stage 3** [[Conditions/Sickened|Sickened 2]] (4 hours)\n\n**Stage 4** [[Conditions/Sickened|Sickened 2]] and 2d6 bleed as larval xills burrow out of the body and immediately fade away into the Ethereal Plane (1 hour)"

  - name: "Xill Paralysis"
    desc: " (incapacitation,occult) A creature hit by the xill's bite Strike must attempt a DC 24 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected and is immune to xill paralysis for 1 minute.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\n**Critical Failure** The creature is paralyzed. It can attempt a new save at the end of each of its turns to recover, and the save DC decreases by 1 each round."
 
```

```encounter-table
name: Xill
creatures:
  - 1: Xill
```



Xills visit the Material Plane, where they're often known as ethereal stalkers, primarily to maraud and to kidnap creatures back to their native Ethereal Plane. These four-armed, warmongering monsters paralyze their victims before implanting them with eggs using an ovipositor normally kept retracted behind their mandibles. Their single-minded drive to expand and conquer is so all-encompassing that while they work together dutifully and without dissent, there is little else in their lives.
