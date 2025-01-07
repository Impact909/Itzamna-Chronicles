---
title: "Veshumirix"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.imGEC8HE0Vx5jwEi" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Veshumirix"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Veshumirix"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Common, Draconic, Petran, Pyric, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +30, Deception: +26, Intimidation: +32, Nature: +24, Stealth: +27, Survival: +24"
abilityMods: [7, 4, 5, 4, 4, 6]
speed: 50 feet,  fly 160 feet,  swim 50 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +29, __Ref__ +28, __Will__ +26; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** Veshumirix is targeted with an attack.\n* * *\n\n**Effect** Veshumirix raises his wing, gaining a +2 circumstance bonus to AC against the triggering attack. If Veshumirix is Flying, he descends 10 feet after the attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (fire, magical, reach 15 feet)\n__Damage__  3d10 + 15 piercing 4d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+31 (magical, reach 20 feet)\n__Damage__  2d12 + 15 bludgeoning"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+31 (magical, reach 15 feet)\n__Damage__  2d10 + 15 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __8th __  _[[Spells/Breathe Fire|Burning Hands (At Will)]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Produce Flame|Produce Flame]]_\n__Constant__  __(4th)__ _[[Spells/Fire Shield|Fire Shield]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (fire,primal) Veshumirix breathes a blast of magma that deals 9d6 fire damage and 4d12 bludgeoning damage in a 60-foot cone (DC 42 Reflex check save).\n\nHe can't use Breath Weapon again for 1d4 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  Veshumirix makes two claw Strikes and one horns Strike in any order."

  - name: "Draconic Momentum"
    desc: "  Veshumirix recharges his Breath Weapon whenever he scores a critical hit with a Strike."

  - name: "Magma Swim"
    desc: "  A magma dragon's swim Speed functions only when the dragon is swimming through magma or molten lava."

  - name: "Volcanic Purge"
    desc: "`pf2:1`  If the next action Veshumirix uses is Breath Weapon, the magma clings to those it damages. Each creature that fails its save against the Breath Weapon takes 4d6 persistent fire damage, and as long as it has this persistent fire damage, it also takes a -10-foot status penalty to its Speeds.\n\n[[Bestiary Effects/Effect_ Volcanic Purge|Effect: Volcanic Purge]]"
 
```

```encounter-table
name: Veshumirix
creatures:
  - 1: Veshumirix
```




