---
title: "Grendel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8YtTYXwb1cNEeXoO" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Grendel"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Grendel"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +39, Intimidation: +34, Stealth: +34, Survival: +33"
abilityMods: [10, 5, 7, 0, 6, 5]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +36, __Ref__ +32, __Will__ +31"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360; __Resistances__ all damage 15 (except unarmed attacks)"
abilities_top:
  - name: ""

  - name: "Keen Hearing"
    desc: "  Grendel's hearing is a precise sense to a range of 120 feet."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  Grendel gains an extra reaction at the start of each of his turns that he can use only to make an Attack of Opportunity with his claw. He can't use more than one Attack of Opportunity triggered by the same action.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 38 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Unstoppable"
    desc: "`pf2:r`  **Trigger** Grendel would take [[Conditions/Persistent Damage|Persistent Damage]] or gain one of the following conditions: [[Conditions/Blinded|Blinded]], [[Conditions/Clumsy|Clumsy]], [[Conditions/Confused|Confused]], [[Conditions/Controlled|Controlled]], [[Conditions/Dazzled|Dazzled]], [[Conditions/Deafened|Deafened]], [[Conditions/Doomed|Doomed]], [[Conditions/Drained|Drained]], [[Conditions/Enfeebled|Enfeebled]], [[Conditions/Fascinated|Fascinated]], [[Conditions/Fatigued|Fatigued]], [[Conditions/Fleeing|Fleeing]], [[Conditions/Frightened|Frightened]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Petrified|Petrified]], [[Conditions/Sickened|Sickened]], [[Conditions/Slowed|Slowed]], [[Conditions/Stunned|Stunned]], or [[Conditions/Stupefied|Stupefied]]\n* * *\n\n**Effect** The persistent damage or condition from the triggering effect doesn't affect Grendel."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+37 (agile, magical, reach 10 feet)\n__Damage__  4d8 + 18 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (magical, reach 10 feet, versatile b)\n__Damage__  4d10 + 18 piercing"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+37 (brutal, range increment 150 feet)\n__Damage__  2d12 + 18 bludgeoning"

  - name: "Hands of the Murderer"
    desc: "  Grendel's fist Strikes deal 18 bludgeoning damage on a failure (but no damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "Tooth Grind"
    desc: "`pf2:1` (healing) **Requirements** Grendel is grabbing a creature\n* * *\n\n**Effect** Grendel makes a bludgeoning jaws Strike against the creature he's grabbing. On a hit, the creature also takes 2d6 bleed damage and becomes [[Conditions/Wounded|Wounded 1]], or increases its wounded value by 1 if already wounded. On a critical hit, the creature instead becomes wounded 2, or increases its wounded value by 2 if already wounded. If a creature dies from Tooth Grind, Grendel regains 40 healing HP; this is a healing effect."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Grendel
creatures:
  - 1: Grendel
```



This reaver of the cold marsh is not just a monster; he is a force of nature. Where there is peace and prosperity in the world, Grendel strikes, eager to prove that tranquility is transitory and death is the only constant. He stalks the edge of his fens, seeking settlements where joy holds sway. He strikes under cover of night, primarily targeting celebrations or festivals. The more happiness or joy he can extinguish, the better.

Although Grendel is a unique creature, killing him won't save the world from his ravages for long. Once Grendel's mother instinctively feels the pain of her violent son's death, she soon births a replacement. The new Grendel seems to avoid the sites his elder brothers terrorized, as if he instinctively knows that such a place hosts heroes powerful enough to defeat him.
