---
title: "Ravenile Rager"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8SQMIIO8vjsJJT6K" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lizardfolk
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Ravenile Rager"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Ravenile Rager"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lizardfolk]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; "
languages: "Common, Draconic, Iruxi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +28, Intimidation: +28, Nature: +23, Survival: +23"
abilityMods: [8, 4, 5, -1, 1, 0]
speed: 20 feet,  swim 10 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +29, __Ref__ +26, __Will__ +23"
hp: 306
health:
  - name: ""
  - name: HP
    desc: "306, regeneration 20 (deactivated by fire or acid); __Weaknesses__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Studded Leather Armor|+1 Resilient Studded Leather Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Fire or Acid)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Deep Breath"
    desc: "  A ravenile can hold their breath for 20 minutes."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (reach 10 feet)\n__Damage__  3d10 + 12 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, reach 10 feet)\n__Damage__  3d8 + 8 slashing"

  - name: "Forced Regeneration"
    desc: "`pf2:1` (concentrate) **Requirements** The ravenile's regeneration is currently active\n* * *\n\nThe ravenile regains 20 healing HP."

  - name: "Furious Wallop"
    desc: "`pf2:2`  **Requirements** The ravenile's regeneration is currently deactivated\n* * *\n\n**Effect** The ravenile makes a melee Strike.\n\nThis counts as two attacks for the ravenile's multiple attack penalty.\n\nIf this Strike hits, the ravenile deals an extra die of weapon damage and the target falls [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Ravenile Rager
creatures:
  - 1: Ravenile Rager
```




