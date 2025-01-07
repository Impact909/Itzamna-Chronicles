---
title: "Aiudara Wraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.k1pn99WffJLt7JAg" 
tags:
  - pf2e/creature/type/astral
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Aiudara Wraith"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Aiudara Wraith"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[astral]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[wraith]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Lifesense 60 Feet"
languages: "Common, Elven, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Arcana: +31, Stealth: +35"
abilityMods: [-5, 9, 5, 0, 7, 8]
speed:  fly 60 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +33, __Ref__ +37, __Will__ +33"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Teleportation Attachment"
    desc: "`pf2:r` (teleportation) **Trigger** A creature within 60 feet uses a teleportation effect\n* * *\n\n**Effect** The aiudara wraith teleports with the creature, arriving in an empty space of its choice adjacent to the triggering creature's destination. If the triggering effect targets multiple creatures, the aiudara wraith chooses which creature it arrives beside."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spectral Hand"
    desc: "+35 (agile, finesse, magical)\n__Damage__  4d10 + 16 force plus dimensional-shunt,drain-life"

  - name: "Dimensional Shunt"
    desc: "`pf2:2` (arcane,teleportation) The aiudara wraith's touch displaces creatures and flings them through space. The creature must attempt a DC 40 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected and becomes temporarily immune to dimensional shunt for 1 minute.\n\n**Success** The creature is pushed 5 feet in a random direction.\n\n**Failure** The creature is teleported 20 feet in a direction of the aiudara wraith's choice.\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Stunned|Stunned 2]]."

  - name: "Drain Life"
    desc: " (arcane) When an aiudara wraith damages a living creature with its spectral hand Strike, the aiudara wraith gains 18 temporary Hit Points and the target must succeed at a DC 40 Fortitude check save or become [[Conditions/Drained|Drained 1]] and [[Conditions/Stupefied|Stupefied 1]] as long as it is drained. Further damage dealt by the aiudara wraith's spectral hand Strikes increases the value of the drained and stupefied conditions by 1 each on a failed save, to a maximum of 10 for both."

  - name: "Instantaneous Movement"
    desc: " (arcane,teleportation) An aiudara wraith moves by means of localized teleportation. An aiudara wraith's Stride does not have the move trait. When an aiudara wraith Strides, it reaches its destination within the range of its Speed immediately."
 
```

```encounter-table
name: Aiudara Wraith
creatures:
  - 1: Aiudara Wraith
```



Dahak's influence in Alseta's Landing created a soul-draining effect that slays unprotected creatures within, transforming them into ghostly creatures known as aiudara wraiths, but these rare undead can rise within modern aiudara portals as well. Each time an individual travels through an aiudara, there's a chance their passage could leave a faint imprint of their subconscious in the network. Normally this imprint simply fades away, but when an aiudara is damaged or the individual is suffering from necromantic contagions, these imprints can accumulate and, in time, coalesce on the Astral Plane or within Alseta's Landing as a full-fledged aiudara wraith. The wraith is forced to live with an incomplete sense of self, always seeking its own memories and swiftly growing violent and vengeful as its quest to reclaim these ephemeral notions constantly meets with failure.
