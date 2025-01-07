---
title: "Lesser Manifestation Of Dahak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zd5RkhI7xMO6soVf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/22
statblock: inline
name: "Lesser Manifestation Of Dahak"
level: 22
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Lesser Manifestation Of Dahak"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[fire]]
trait_05: [[unholy]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Common, Draconic, Elven"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Arcana: +42, Athletics: +42, Deception: +42, Diplomacy: +37, Intimidation: +45, Stealth: +35"
abilityMods: [10, 5, 9, 5, 6, 7]
speed: 60 feet,  fly 240 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 50
armorclass:
  - name: AC
    desc: "50; __Fort__ +36, __Ref__ +33, __Will__ +39; +1 status to all saves vs. magic"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ holy 24; __Resistances__ acid 24, cold 24, electricity 24, poison 24"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a red dragon's vision; it ignores the concealed condition from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Dragon Heat"
    desc: " (aura,divine,fire) 10 feet. 6d6 fire damage (DC 42 Reflex check save)"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 42 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Redirect Energy"
    desc: "`pf2:r` (divine) **Trigger** A creature within 100 feet casts an acid, cold, fire, electricity, or poison spell, or such a spell otherwise comes into effect from a source within 100 feet\n* * *\n\n**Effect** The manifestation of Dahak makes all the choices to determine the targets, destination, or other effects of the spell, as though it were the caster."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+42 (fire, magical, reach 20 feet)\n__Damage__  4d10 + 22 piercing 3d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+42 (agile, magical, reach 15 feet)\n__Damage__  4d8 + 22 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+40 (magical, reach 25 feet)\n__Damage__  4d10 + 17 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+40 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "Arcane Innate Spells"
    desc: "DC 46, attack +38; __8th __  _[[Spells/Wall of Fire|Wall of Fire (x4)]]_; __4th __  _[[Spells/Suggestion|Suggestion (x3)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine) The manifestation of Dahak breathes a blast of dragonstorm energy that deals 5d6 acid, 5d6 cold, 5d6 electricity, 5d6 fire, and 5d6 poison damage in a 60-foot cone (DC 46 Reflex check save).\n\nIt can't use Dragonstorm Breath again for 1d4 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one wing Strike in any order."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges its Breath Weapon whenever it scores a critical hit with a Strike."

  - name: "Manipulate Energy"
    desc: "`pf2:1` (concentrate,divine) The manifestation attempts to take control of a magical acid, cold, electricity, fire, or poison spell within 100 feet. If it succeeds at a counteract check (counteract rank 10, counteract modifier +36), the original caster loses control of the spell, control is transferred to the manifestation, and the manifestation counts as having Sustained the Spell with this action (if applicable). The manifestation can end the spell instead of taking control, if it chooses."
 
```

```encounter-table
name: Lesser Manifestation Of Dahak
creatures:
  - 1: Lesser Manifestation Of Dahak
```




