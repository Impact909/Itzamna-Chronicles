---
title: "Necrophidius"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BUmPDb8VwZOMJEq5" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Necrophidius"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Necrophidius"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +10, Stealth: +9"
abilityMods: [3, 4, 0, -5, 2, -5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +11, __Will__ +9"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ bludgeoning 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+8 (agile, finesse)\n__Damage__  1d10 + 3 piercing plus necrophidic-paralysis"

  - name: "Dance of Death"
    desc: "`pf2:3` (mental,occult,visual) The necrophidius sways, its serpentine form undulating and clattering in a hypnotic rhythm. Each creature that witnesses the dance must attempt a DC 18 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 24 hours.\n\n**Success** The creature is unnerved by the swaying and becomes [[Conditions/Off-Guard|Off-Guard]] until the end of the necrophidius's next turn.\n\n**Failure** The creature is distracted by the swaying, becoming [[Conditions/Stunned|Stunned 1]]. After it recovers, it is off-guard until the end of the necrophidius's next turn.\n\n**Critical Failure** As failure, but [[Conditions/Stunned|Stunned 3]]."

  - name: "Necrophidic Paralysis"
    desc: " (incapacitation,occult) A living creature bitten by a necrophidius must succeed at a DC 20 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 for each save attempted. A creature that succeeds at this save is temporarily immune to necrophidic paralysis for 24 hours."
 
```

```encounter-table
name: Necrophidius
creatures:
  - 1: Necrophidius
```



Although the necrophidius is a mindless construct with no particular ability to comprehend the complexities of good or evil, these sinister-looking constructs are often crafted by evil or macabre creators seeking to imbue their guardians with a frightening aesthetic.

Constructed from bones harvested from serpents and humans, a necrophidius is animated by occult magic, not unlife. Each necrophidius is built from the skeleton of a large snake, but its skull has been replaced by that of a humanoid creature. Some death cults or particularly cruel crafters seek out the skulls of specific individuals against whom they bear grudges to provide the head for their necrophidius. The final step of the construction is the alteration of the teeth and jaws to give the creature a more serpentine visage, complete with fangs.

If a necrophidius's creator dies, the construct follows the last series of commands it was given. If it cannot do so, the necrophidius aimlessly wanders the area near where it last served its creator and attacks any creatures it encounters. Some believe that those who know the secrets of a necrophidius's origins can command it, provided its original creator no longer exists and no one else currently commands it. There are also a number of reports concerning strangely aware and intelligent necrophidiuses that roam with a purpose and track down or hunt specific living creatures they interpret as the targets of former assassination missions.
