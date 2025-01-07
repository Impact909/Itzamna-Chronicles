---
title: "Alapolo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kVBXCM6fyZh3szQH" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Alapolo"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Alapolo"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[shadow]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Deception: +30, Diplomacy: +30, Performance: +30, Stealth: +36, Shadow Lore: +30"
abilityMods: [0, 9, 5, 0, 6, 9]
speed: 40 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +26, __Ref__ +34, __Will__ +29"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310; __Immunities__  light"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Cloying Pull"
    desc: "`pf2:r`  **Trigger** A creature within the alapolo's reach attempts to move away from the alapolo\n* * *\n\n**Effect** The triggering creature must succeed at a DC 36 Reflex check save or its movement ends before it leaves the alopolo's reach."

  - name: "One with Shadows"
    desc: "  The alapolo isn't affected by darkness, light, or shadow effects"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Claw"
    desc: "+33 (agile, finesse, magical, reach 10 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "Enticing Invitation"
    desc: "`pf2:2` (incapacitation,mental,primal) The alapolo whispers an invitation to a creature within 30 feet. The creature must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and temporarily immune to all Enticing Invitations for 24 hours.\n\n**Success** The target must spend 1 action on its next turn dancing in place.\n\n**Failure** The target becomes [[Conditions/Drained|Drained 1]]. It is also [[Conditions/Fascinated|Fascinated]] by the alapolo for 1 minute and can't attack the alapolo as long as it's fascinated. While fascinated, the target must spend 2 actions on each of its turns dancing in place.\n\n**Critical Failure** As failure, except the target is [[Conditions/Drained|Drained 3]] and must spend 3 actions on each of its turns dancing in place."

  - name: "Shifting Shadows"
    desc: "  An alapolo's movement doesn't trigger reactions."

  - name: "Weighty Shadow"
    desc: "`pf2:2` (primal) **Requirements** The alapolo is adjacent to a target creature, or the GM determines the alapolo is adjacent to that creature's shadow\n* * *\n\n**Effect** The alapolo petulantly stomps on a target's shadow, making it incredibly heavy to drag around. The creature takes a -20-foot penalty to its Speeds for 1 minute. As normal, this penalty can't reduce a creature's Speed below 5 feet. Any creatures [[Conditions/Fascinated|Fascinated]] by the alapolo due to its Enticing Invitation are freed from their fascination when the alapolo uses this ability, jarred by the graceless stomping."
 
```

```encounter-table
name: Alapolo
creatures:
  - 1: Alapolo
```



Short-lived, strange creatures called alapolos cling to the shadows in eerie moonlight, inviting others to dance. Although these "shadow dancers" aren't actively malevolent, they become petulant when others won't dance with them.
