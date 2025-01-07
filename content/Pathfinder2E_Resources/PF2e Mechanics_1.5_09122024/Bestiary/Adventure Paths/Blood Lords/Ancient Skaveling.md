---
title: "Ancient Skaveling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZcFU8UV7VGq0Supq" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Ancient Skaveling"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Ancient Skaveling"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Echolocation 60 Feet"
languages: "Aklo, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +29, Intimidation: +25"
abilityMods: [8, 6, 4, 3, 8, 4]
speed: 15 feet,  fly 30 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +25, __Ref__ +27, __Will__ +29"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

  - name: "Echolocation 60 feet"
    desc: "  The ancient skaveling can use its hearing as a precise sense at the listed range"

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+29 ()\n__Damage__  3d12 + 16 piercing plus ghoul-fever,paralysis"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+29 (agile)\n__Damage__  3d8 + 16 bludgeoning plus paralysis"

  - name: "Bone-Shattering Screech"
    desc: "`pf2:2` (auditory,emotion,fear,mental,occult,sonic) The skaveling unleashes a devastating screech that not only chills the bones but shatters them. The screech can be heard throughout the region and alerts all creatures in the Hanging Castle. Creatures in a 20-foot emanation take 12d6 sonic damage must also attempt a DC 36 Will check save.\n\nThe skaveling can't use Bone-Shattering Screech again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Bone-Shattering Screech for 24 hours.\n\n**Success** The creature takes half damage and is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes full damage and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature takes double damage and is [[Conditions/Frightened|Frightened 3]] and is [[Conditions/Stunned|Stunned 3]]."

  - name: "Ghoul Fever"
    desc: " (disease) **Saving Throw** DC 36 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a ghoul the next midnight"

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any creature hit by the skaveling's Strikes must attempt a DC 36 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]].\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each save."
 
```

```encounter-table
name: Ancient Skaveling
creatures:
  - 1: Ancient Skaveling
```


Variant skaveling

Hideous necromantic rituals give rise to skavelings, or ghoul bats, monstrosities that are not true ghouls but instead are specifically crafted undead creatures. Their creators are the bloodsucking urdefhans of the Darklands, who create skavelings from giant bats specially raised on diets of toxic fungus and the flesh of ghouls-especially brains harvested from these undead. Upon reaching maturity, these giant bats are ritually slain via the use of cytillesh oil. While this poison simply rots away the flesh of most creatures, one of these specially prepared bats will immediately rise from death as a skaveling after succumbing to its effects.

Despite its tattered wings and sagging skin, a skaveling is more than capable of flight, even when carrying a creature mounted on its back-urdefhans often use skavelings as mounts in this way. Their intelligence is more advanced than that of the typical giant bat, and in combat they function more as allies than as mere mounts, capable of making their own tactical decisions. Yet even though they can reason and think, skavelings remain loyal to the urdefhans who created them, and they never take actions in a fight that would knowingly put their masters in harm's way.
