---
title: "Veksciralenix"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RWewHMwWvoULZf5a" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/time
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Veksciralenix"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Veksciralenix"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[time]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Dwarven, Elven, Empyrean, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Arcana: +35, Athletics: +38, Deception: +34, Diplomacy: +36, Occultism: +38, Society: +34"
abilityMods: [10, 5, 7, 6, 8, 6]
speed: 60 feet,  fly 200 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +38, __Ref__ +33, __Will__ +35; +1 status to all saves vs. magic"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375; __Immunities__  void,  paralyzed,  sleep,  slowed"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Alien Presence"
    desc: " (aura,emotion,mental) 90 feet. A creature that first enters the area must attempt a DC 42 Will check save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to the Veksciralenix's Alien Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Slowed|Slowed 1]] for 1d4 rounds.\n\n**Critical Failure** The creature is [[Conditions/Slowed|Slowed 1]] for 1 minute."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Second Chance"
    desc: "`pf2:r`  **Frequency** three times per day\n\n**Trigger** Veksciralenix or a creature that Veksciralenix can see attempts a check and learns the results\n* * *\n\n**Effect** The triggering creature rerolls the triggering check and takes the second result."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (electricity, magical, reach 20 feet)\n__Damage__  4d10 + 18 piercing 4d6 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 15 feet)\n__Damage__  4d10 + 18 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+36 (magical, reach 25 feet)\n__Damage__  4d12 + 18 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+36 (agile, magical, reach 20 feet)\n__Damage__  3d10 + 18 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 42, attack +34; __10th __ (1 slots) _[[Spells/Freeze Time|Time Stop]]_; __9th __ (1 slots) _[[Spells/Teleport|Teleport]]_; __7th __ (1 slots) _[[Spells/Interplanar Teleport|Plane Shift]]_; __5th __ (1 slots) _[[Spells/Locate|Locate (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Rituals"
    desc: "_Legend Lore_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,electricity) The time dragon breathes in one of two ways.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds.\n* * *\n\n**Storm** The dragon breathes a burst of lightning in a 50-foot cone that deals 20d6 electricity damage (DC 42 Reflex check save).\n* * *\n\n**Time Displacement** (arcane, transmutation) The dragon breathes a time storm. Each creature within a 50-foot cone must attempt a DC 42 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 4]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 6]]."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  Veksciralenix makes two claw Strikes and one wing Strike in any order."

  - name: "Draconic Momentum"
    desc: "  Veksciralenix recharges their Breath Weapon whenever they score a critical hit with a Strike."
 
```

```encounter-table
name: Veksciralenix
creatures:
  - 1: Veksciralenix
```




