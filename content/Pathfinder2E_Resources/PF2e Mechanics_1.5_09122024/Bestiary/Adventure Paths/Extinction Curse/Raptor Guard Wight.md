---
title: "Raptor Guard Wight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ArGFjw1Lqa16LMfr" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Raptor Guard Wight"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Raptor Guard Wight"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Draconic, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +27, Intimidation: +27, Stealth: +24, Survival: +22"
abilityMods: [8, 5, 3, 0, 3, 4]
speed: 25 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +23, __Will__ +21"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|+1 Striking Spear]], [[Equipment/Hide Armor|+1 Resilient Hide Armor]], [[Equipment/Demon Mask (Greater)|Demon Mask (Greater)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Death Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 32 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]] and [[Conditions/Doomed|Doomed 1]] for as long as it is sickened; on a critical failure, the creature is instead [[Conditions/Doomed|Doomed 2]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to any creature's death stench for 1 minute."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+27 (magical)\n__Damage__  2d6 + 14 piercing plus drain-life,terror-master"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile)\n__Damage__  3d6 + 14 slashing plus drain-life,terror-master"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 ()\n__Damage__  3d8 + 14 piercing plus drain-life,terror-master"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+24 (magical, range increment 20 feet)\n__Damage__  2d6 + 14 piercing plus hungry-spear,terror-master"

  - name: "Drain Life"
    desc: " (divine) When the Raptor Guard wight damages a living creature with a melee Strike, the wight gains 13 temporary Hit Points and the target creature must succeed at a DC 32 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the wight increases the drained condition by 1 on a failed save, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Hungry Spear"
    desc: " (divine) The Raptor Guard wight's ranged spear Strikes apply drain life, but the wight doesn't gain any temporary Hit Points if the attack hits."

  - name: "Terror Master"
    desc: "  As long as the Raptor Guard wears its dinosaur-skull helm, its Strikes deal an additional 1d10 void damage, or an additional 2d10 void damage to [[Conditions/Frightened|Frightened]] creatures."

  - name: "Wight Spawn"
    desc: " (divine) A living humanoid slain by a Raptor Guard wight's melee Strike rises as a [[Monster Core/Wight|Wight]] after [[/gmr 1d4 #rounds]]{1d4 rounds}. This wight spawn is under the command of the Raptor Guard that killed it. It doesn't have the drain life or wight spawn abilities and is [[Conditions/Clumsy|Clumsy 2]]. If the creator of the wight spawn dies, the wight spawn becomes a full-fledged, autonomous wight; it regains its free will, gains the drain life and wight spawn abilities, and is no longer clumsy."
 
```

```encounter-table
name: Raptor Guard Wight
creatures:
  - 1: Raptor Guard Wight
```


Variant wight


