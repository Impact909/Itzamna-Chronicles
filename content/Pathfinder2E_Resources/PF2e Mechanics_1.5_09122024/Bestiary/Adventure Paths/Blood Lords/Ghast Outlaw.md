---
title: "Ghast Outlaw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jf1WDYdKkjycFdX6" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Ghast Outlaw"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Ghast Outlaw"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +19, Deception: +16, Stealth: +21, Survival: +18, Thievery: +19"
abilityMods: [4, 6, 3, 0, 3, 1]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +20, __Will__ +16"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Thieves' Toolkit (Infiltrator)|Thieves' Tools (Infiltrator)]], [[Equipment/Striking Snare|Striking Snare]], [[Equipment/Backpack|Backpack]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 26 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (finesse)\n__Damage__  2d8 + 8 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, finesse)\n__Damage__  2d6 + 8 slashing plus ghast-paralysis"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghast is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghast devours a chunk of the corpse and regains 6d6 healing Hit Points\n\nIt can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 26 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The ghast's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Swift Leap"
    desc: "`pf2:1`  The ghast jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghast Outlaw
creatures:
  - 1: Ghast Outlaw
```


Ghast criminal


