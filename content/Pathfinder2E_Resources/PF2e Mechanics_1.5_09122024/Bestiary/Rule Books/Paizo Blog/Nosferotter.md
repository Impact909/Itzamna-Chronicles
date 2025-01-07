---
title: "Nosferotter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZQKeHKeQ9RpnDnez" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Nosferotter"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog: April Fool&#x27;s Bestiary"
name: "Nosferotter"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[undead]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Diplomacy: +8"
abilityMods: [1, 3, 1, 2, 0, 4]
speed: 30 feet
sourcebook: "_Pathfinder Blog: April Fool&#x27;s Bestiary_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +4, __Ref__ +6, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d4 + 6 slashing"

  - name: "**Melee** `pf2:1` Jaw"
    desc: "+10 ()\n__Damage__  1d8 + 6 piercing"

  - name: "**Ranged** `pf2:1` Throw Rock and/or Skull"
    desc: "+10 (thrown 30 ft.)\n__Damage__  1d4 + 6 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  30 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Dead Gaze"
    desc: "`pf2:2` (mental,visual) Look into its beady little eyes. You are now [[Conditions/Stunned|Stunned]] for 1 round unless you succeeded on a DC 20 Will check save."

  - name: "Squeak of Doom"
    desc: "`pf2:3` (auditory,emotion,mental) The nosferotter lets out an ominous, but cute, squeak. All creatures within 30 feet must attempt a DC 20 Will check save.\n\nThey are then temporarily immune for 1 day.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature can do nothing but wonder whether the nosferotter is cute or terrifying for 1 round.\n\n**Failure** The creature is so confused that it attacks its allies for 1 round.\n\n**Critical Failure** As failure, but permanently. It's that bad."
 
```

```encounter-table
name: Nosferotter
creatures:
  - 1: Nosferotter
```




