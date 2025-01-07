---
title: "Casino Bouncer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TU3gdFGDKAXxJPsa" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Casino Bouncer"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Casino Bouncer"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Diplomacy: +15, Intimidation: +19, Society: +16"
abilityMods: [4, 2, 5, 0, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +13, __Will__ +13"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sap|+1 Striking Sap]], [[Equipment/Chain Shirt|Chain Shirt]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, finesse, nonlethal, unarmed)\n__Damage__  2d6 + 6 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Sap"
    desc: "+21 (agile, magical, nonlethal)\n__Damage__  2d6 + 6 bludgeoning"

  - name: "Escort from the Premises"
    desc: "`pf2:2`  **Requirements** The casino bouncer has Grabbed a Medium or smaller target and is wielding a nonlethal weapon in the other hand\n* * *\n\n**Effect** The casino bouncer makes a Strike against the grabbed target with the nonlethal weapon. If the Strike hits, it deals damage as usual and the casino bouncer moves the target 5 feet (this is forced movement) and Steps into the space the target had just occupied."

  - name: "Intimidating Stare"
    desc: "`pf2:1` (concentrate,emotion,mental,visual) The casino bouncer attempts to [[Action Macros/Demoralize_ Intimidation|Demoralize]] a creature with a mere glance. The casino bouncer doesn't take a penalty to their Intimidation check if the target doesn't speak the same language.\n\nIf the bouncer rolls a critical success, the target can't reduce the value of its frightened condition until 1d4 rounds have passed."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Casino Bouncer
creatures:
  - 1: Casino Bouncer
```




