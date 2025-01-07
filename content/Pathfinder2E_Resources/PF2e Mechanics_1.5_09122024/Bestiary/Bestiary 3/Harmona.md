---
title: "Harmona"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9i34nX1qpk10phN6" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Harmona"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Harmona"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[chaotic]]
trait_02: [[fey]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Low-Light Vision"
languages: "Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Arcana: +20, Diplomacy: +22, Nature: +24, Performance: +22, Stealth: +23"
abilityMods: [0, 6, 3, 5, 7, 5]
speed: 10 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +18, __Ref__ +21, __Will__ +24"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  sonic; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Flit Back"
    desc: "`pf2:r`  **Trigger** A creature enters the harmona's space or an adjacent square\n* * *\n\n**Effect** The harmona Flies 10 feet away from the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+23 (finesse, magical)\n__Damage__  2d6 + 6 piercing 2d6 sonic"

  - name: "**Ranged** `pf2:1` Sonic Pulse"
    desc: "+23 (magical, range 60 feet, sonic)\n__Damage__  2d12 + 6 sonic plus push"

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Concussive Blow"
    desc: "`pf2:2` (primal,sonic) The harmona makes a beak Strike, channeling disruptive sound waves into the blow. On a hit, the target must succeed at a DC 30 Fortitude check save or become [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 2]] on a critical failure).\n\nAfter this Strike, the harmona can Fly up to half their fly Speed."

  - name: "Subsonic Pulse"
    desc: "`pf2:2` (primal) The harmona beats their wings rapidly towards the ground, creating a nearly inaudible rumble and sending a wave of shaking earth to overwhelm their enemies.\n\nEach creature in a 15-foot emanation must succeed at a DC 30 Fortitude check save or take 6d6 sonic damage. A creature that fails its save is knocked [[Conditions/Prone|Prone]] from the shaking ground."

  - name: "Ultrasonic Thrust"
    desc: "`pf2:2` (primal,sonic) The harmona beats their wings skyward, creating a spiraling vibration. Each creature in a 30-foot cone must attempt a DC 30 Reflex check save as the high-frequency blast flings them up and away.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is pushed 5 feet away and knocked off balance, becoming [[Conditions/Off-Guard|Off-Guard]] until the start of their next turn.\n\n**Failure** Sonic waves fling the creature 15 feet back from the harmona. The creature takes 6d6 bludgeoning damage from the fall and lands [[Conditions/Prone|Prone]].\n\n**Critical Failure** As failure, but the creature is flung 30 feet and takes double damage."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Harmona
creatures:
  - 1: Harmona
```



Catching a glimpse of a harmona is said to be lucky. Flying quickly, observing and scouting new areas, these brightly colored avian fey are all but hidden to the eye. A soft buzz accompanies them, discernible only to creatures with particularly keen hearing.

Intelligent and curious, these tiny fey birds freely roam the First World, accompanying high-ranking fey creatures such as queens or their courts. In turn, companions who treat a harmona with respect for their knowledge and skill benefit from the harmona's aid in times of need.

When these curious creatures find a natural gate between the planes, they glide through to explore and expand their knowledge. Those who find their way onto the Material Plane often choose to remain there in search of diverse and unusual places. This frequently leads them to the same locations that draw in curious adventurers. A harmona might befriend a non-fey adventurer as a companion, but they resent those who would treat them as pets and fight to the death to avoid capture.
