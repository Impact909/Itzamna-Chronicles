---
title: "Hooklimb Xulgath"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.usy0gIbkQWToN2ur" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Hooklimb Xulgath"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Hooklimb Xulgath"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[xulgath]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +21, Intimidation: +16, Stealth: +19, Survival: +16"
abilityMods: [7, 5, 3, 0, 2, 0]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +21, __Will__ +16"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190"
abilities_top:
  - name: ""

  - name: "Quick Catch"
    desc: "  The hooklimb always critically succeeds at checks to [[Actions/Grab an Edge|Grab an Edge]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Powerful Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 28 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]], and on a critical failure, the creature is also [[Conditions/Slowed|Slowed 1]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stenches for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 ()\n__Damage__  1d6 + 13 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile)\n__Damage__  2d8 + 13 slashing"

  - name: "Raking Claws"
    desc: "`pf2:1`  The hooklimb flexes hooklike barbs on its claws. Until the start of the hooklimb's next turn, its claws Strikes deal an additional 1d10 persistent bleed damage."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  **Strike:** Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Hooklimb Xulgath
creatures:
  - 1: Hooklimb Xulgath
```




