---
title: "Ravener Husk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q1pwTCRIvCCeASNA" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Ravener Husk"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Ravener Husk"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +28"
abilityMods: [8, 0, 6, -5, 4, 4]
speed: 60 feet,  fly 180 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +28, __Ref__ +22, __Will__ +26"
hp: 325
health:
  - name: ""
  - name: HP
    desc: "325; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "Soulsense"
    desc: "  A ravener senses the spiritual essence of living and undead creatures within the listed range. Creatures whose material bodies are one unit with their souls, like celestials and fiends, appear brighter to this sense."

abilities_mid:
  - name: ""
  - name: "Boneshatter"
    desc: "`pf2:r`  **Trigger** The ravener husk takes any amount of bludgeoning damage\n* * *\n\n**Effect** The ravener's brittle bones shatter, spraying bone shards everywhere. Every creature within a 10-foot emanation of the ravener husk takes 7d6 piercing damage (DC 31 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 31 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical, reach 15 feet)\n__Damage__  3d8 + 16 piercing 2d6 void"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet)\n__Damage__  3d4 + 16 slashing 2d6 void"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,void) The ravener husk breathes a torrent of void energy that deals 16d6 void damage in a 40-foot cone (DC 34 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Ravenous Repast"
    desc: "`pf2:3` (divine) **Frequency** once per day\n* * *\n\n**Effect** The ravener husk makes a jaws Strike against a deceased creature that has been dead no longer than 1 minute, was good aligned, and was at least level 15 in life. The ravener attempts a DC 5 Flat check check; if successful, they transform back into a ravener with 1 Hit Point in their soul ward."

  - name: "Vicious Criticals"
    desc: "  The ravener treats an attack roll as a critical hit on a roll of 19 or 20, as long as the attack roll was a success. Additionally, whenever the ravener makes a critical hit with one of their Strikes, the target must succeed on a DC 32 Fortitude check save or gain the [[Conditions/Drained|Drained 1]] condition. If the target already has a drained value of greater than 0, their drained value instead increases by 1, to a maximum of drained 4. Whenever the ravener applies drain to a creature in this way, their soul ward gains 5 Hit Points."
 
```

```encounter-table
name: Ravener Husk
creatures:
  - 1: Ravener Husk
```



Raveners require a steady diet of souls, and a ravener that's unable to feed for too long eventually cannibalizes their own soul. Should a ravener's soul ward ever be reduced to 0 Hit Points by hunger while the ravener has more than 1 Hit Point (see Soul Ward), they lose all traces of their former identity and descend into a feral, nearly mindless state. Even if a ravener husk later consumes soul energy, the transformation can be reversed only via Ravenous Repast.
