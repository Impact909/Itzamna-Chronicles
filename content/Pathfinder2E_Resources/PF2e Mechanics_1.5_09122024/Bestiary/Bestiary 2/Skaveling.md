---
title: "Skaveling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mpn7o2x5xiIqHxjX" 
tags:
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Skaveling"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Skaveling"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[undead]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Echolocation 40 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +13, Intimidation: +11"
abilityMods: [6, 4, 2, 1, 6, 2]
speed: 15 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +13, __Will__ +15"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

  - name: "Echolocation"
    desc: "  A skaveling can use its hearing as a precise sense at the listed range"

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+15 ()\n__Damage__  2d8 + 8 piercing plus ghoul-fever,paralysis"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+15 (agile)\n__Damage__  2d4 + 8 bludgeoning plus paralysis"

  - name: "Bone-Chilling Screech"
    desc: "`pf2:2` (auditory,emotion,fear,mental,occult) The skaveling unleashes a horrifying screech that chills the very bones of those close enough to feel it. The screech can be heard for miles, but each creature in a 20-foot emanation must also attempt a DC 22 Will check save.\n\nThe skaveling can't use Bone-Chilling Screech again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Bone- Chilling Screech for 24 hours.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Stunned|Stunned 1]] by fear."

  - name: "Ghoul Fever"
    desc: " (disease) **Saving Throw** DC 22 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a ghoul the next midnight"

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any creature hit by the skaveling's Strikes must attempt a DC 22 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]].\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each save."
 
```

```encounter-table
name: Skaveling
creatures:
  - 1: Skaveling
```



Hideous necromantic rituals give rise to skavelings, or ghoul bats, monstrosities that are not true ghouls but instead are specifically crafted undead creatures. Their creators are the bloodsucking urdefhans of the Darklands, who create skavelings from giant bats specially raised on diets of toxic fungus and the flesh of ghouls-especially brains harvested from these undead. Upon reaching maturity, these giant bats are ritually slain via the use of cytillesh oil. While this poison simply rots away the flesh of most creatures, one of these specially prepared bats will immediately rise from death as a skaveling after succumbing to its effects.

Despite its tattered wings and sagging skin, a skaveling is more than capable of flight, even when carrying a creature mounted on its back-urdefhans often use skavelings as mounts in this way. Their intelligence is more advanced than that of the typical giant bat, and in combat they function more as allies than as mere mounts, capable of making their own tactical decisions. Yet even though they can reason and think, skavelings remain loyal to the urdefhans who created them, and they never take actions in a fight that would knowingly put their masters in harm's way.
