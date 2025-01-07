---
title: "Flood Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EBvtIIQhcAyKxzk0" 
tags:
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Flood Ghoul"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Flood Ghoul"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[ghoul]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +9, Stealth: +8, Survival: +6"
abilityMods: [3, 4, 3, 1, 1, 3]
speed: 25 feet,  swim 30 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +10, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet, DC 15 Fortitude check\n\n* * *\n"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (finesse)\n__Damage__  1d8 + 4 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 slashing plus grab"

  - name: "Aquatic Ambush"
    desc: "`pf2:1`  45 feet\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The flood ghoul is adjacent to the corpse of a creature that died within the last hour\n* * *\n\n**Effect** The flood ghoul devours a chunk of the corpse and regains 2d6 healing Hit Points. It can regain Hit Points from any given corpse only once."

  - name: "Death Echo"
    desc: "`pf2:1` (occult) **Requirements** The flood ghoul has damaged a creature with a melee attack\n* * *\n\n**Effect** The flood ghoul unleashes a wave of memories of its death by drowning. The targeted creature must succeed at a DC 15 Will check save or become [[Conditions/Paralyzed|Paralyzed]] for 1 round as they relive the flood ghoul's dying moments. A creature who successfully saves becomes temporarily immune for 1 hour."

  - name: "Forbidden Cravings"
    desc: " (curse) **Saving Throw** DC 18 Will check\n\n**Stage 1** carrier with no ill effects (1 day)\n\n**Stage 2** 2d6 void damage and the target is [[Conditions/Sickened|Sickened 1]] until it consumes raw meat (1 day)\n\n**Stage 3** as stage 2\n\n**Stage 4** as stage 2 unless the target has consumed raw meat in the past 24 hours; then it takes 4d6 void damage and is [[Conditions/Sickened|Sickened 2]] until it consumes raw meat\n\n**Stage 5** If the creature has eaten raw meat in the past 24 hours, it dies and rises as a ghoul; if not, it returns to stage 4 ."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Whispers|Ghoul Whispers]]"
    desc: "`pf2:1` (auditory,linguistic,occult) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], or [[Conditions/Unconscious|Unconscious]] creature is within the ghoul's reach\n* * *\n\n**Effect** The ghoul whispers dark thoughts and vile cravings into the creature's ears. The creature must attempt a save against the forbidden cravings curse."

  - name: "Swift Leap"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  "
 
```

```encounter-table
name: Flood Ghoul
creatures:
  - 1: Flood Ghoul
```


Variant ghoul

Ghouls stalkers are ravenous undead who haunt graveyards and eat corpses.

* * *

Few creatures are more ubiquitous to sinister locations such as lonely graveyards and ruined crypts than the flesh-eating undead known as ghouls.
