---
title: "Athach"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.v2zAY908324OyRUG" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Athach"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Athach"
level: "Creature 12"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[giant]]
trait_04: [[humanoid]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Intimidation: +21"
abilityMods: [7, 3, 7, -1, 4, 3]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +20, __Will__ +21"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  An athach gains an extra reaction at the start of each of its turns that it can use only to make an Attack of Opportunity with its claw. It can't use more than one Attack of Opportunity triggered by the same action.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+25 (reach 10 feet)\n__Damage__  3d12 + 13 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 ()\n__Damage__  3d8 + 13 piercing plus athach-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile)\n__Damage__  3d8 + 13 slashing"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+25 (brutal, range increment 120 feet)\n__Damage__  3d8 + 13 bludgeoning"

  - name: "Athach Venom"
    desc: " (poison) **Saving Throw** DC 32 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]]\n\n**Stage 2** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]]\n\n**Stage 3** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]]"

  - name: "Swift Claw"
    desc: "`pf2:r`  **Trigger** The athach hits a creature with two fist Strikes\n* * *\n\n**Effect** The athach makes a claw Strike with no multiple attack penalty against the creature it hit with its fist Strikes. This claw attack does not increase the athach's multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Athach
creatures:
  - 1: Athach
```



The towering and brutish giants known as athaches are reviled for both their monstrosity and their cruelty. Beyond an athach's filthy habits, this giant is made stranger by the gangly third arm that protrudes from their torso and ends in a twitching, long-fingered claw. Huge, tusk-like fangs descend from an athach's upper jaw and prop their mouth open, leaking long strands of viscous drool that is itself is a toxic venom and coats the athach's fangs.

Athachs despise civilization almost as much as they despise their own kind, and they delight in committing sadistic acts and terrorizing victims. An athach does not keep a traditional territory of their own, but rather wanders the hinterlands of settled territories until they find a suitably easy settlement of smaller humanoids to target. Once the athach has chosen their target, the giant establishes a hidden lair in a location like an abandoned farmhouse or cave, and from there they launch their reign of torment. After a few weeks of harassing, capturing, and torturing victims, the athach bores of their games. The giant then goes on a final rampage, destroying every dwelling and eating every creature they can find. Sometimes, the giant allows a survivor or two to escape, forcing these terrified victims to spend the rest of their lives spreading word of the athach's fearsomeness.
