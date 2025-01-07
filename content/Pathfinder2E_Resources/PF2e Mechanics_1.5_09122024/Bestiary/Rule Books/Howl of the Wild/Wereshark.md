---
title: "Wereshark"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Jkg60mqIX5bSzLjD" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2e/creature/type/amphibious
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Wereshark"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Wereshark"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[werecreature]]
trait_05: [[amphibious]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Scent (Imprecise) 100 Feet"
languages: "Common; shark empathy"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Stealth: +9, Survival: +8"
abilityMods: [4, 3, 4, -1, 2, -1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +11, __Will__ +8"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|Trident]], [[Equipment/Studded Leather Armor|Studded Leather Armor]]"
  - name: "Blood Scent"
    desc: "  The wereshark can smell blood in the water from up to 1 mile away."

  - name: "Shark Empathy"
    desc: " (primal) A wereshark can communicate with sharks."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Trident"
    desc: "+14 ()\n__Damage__  1d8 + 7 piercing plus fish-fork"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  1d12 + 7 piercing plus werecreature-curse-of-the-werecreature"

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+13 (thrown 20 ft.)\n__Damage__  1d8 + 7 piercing"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) Medium human with fist +14 for 1d4+7 bludgeoning,\n\nor Large shark with jaws +14 for 1d12+7 piercing, no land Speed, and swim Speed 40 feet.\n\nThe wereshark doesn't have the amphibious trait in human or shark form and has the aquatic trait in shark form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Wereshark]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 18 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into the same kind of werecreature until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "Fish Fork"
    desc: "`pf2:1`  **Requirements** The wereshark critically hit with a trident Strike on their most recent action this turn\n* * *\n\n**Effect** The wereshark digs their trident deep within their target, skewering it before taking a massive bite. The target of the Strike becomes [[Conditions/Grabbed|Grabbed]] ([[Actions/Escape|Escape]] DC 18) and takes 1d4 bleed damage, and the wereshark attempts a jaws Strike against it. The wereshark can't use their trident while they have a creature grabbed with it, but they can pull the trident free with a single action that has the manipulate trait."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"
 
```

```encounter-table
name: Wereshark
creatures:
  - 1: Wereshark
```




