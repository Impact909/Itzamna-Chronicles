---
title: "Ravener"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a9qZRMID2U7x9I4U" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Ravener"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Ravener"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[fire]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Common, Draconic, Dwarven, Jotun, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Arcana: +37, Athletics: +39, Deception: +38, Diplomacy: +38, Intimidation: +40, Stealth: +35"
abilityMods: [9, 5, 9, 5, 6, 8]
speed: 60 feet,  fly 180 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +38, __Ref__ +34, __Will__ +37; +1 status to all saves vs. magic"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500; __Immunities__  death effects,  disease,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 20, holy 20"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair an ancient red ravener's vision; it ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

  - name: "Soulsense"
    desc: "  A ravener senses the spiritual essence of living and undead creatures within the listed range. Creatures whose material bodies are one unit with their souls, like celestials and fiends, appear brighter to this sense."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Cowering Fear"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 42 Will check\n\nA ravener's frightful presence causes creatures to cower in fear as well. As long as a creature is at least [[Conditions/Frightened|Frightened 2]] or more as a result of the ravener's frightful presence, it is also [[Conditions/Immobilized|Immobilized]] from the fear.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Discorporate"
    desc: "`pf2:0`  **Trigger** The ravener takes excess damage to their soul ward but still has at least 51 Hit Points in their soul ward\n* * *\n\n**Effect** The ravener draws deeply into their soul ward, discorporating their body into soul energy in order to escape. They take 50 damage to their soul ward and their physical body vanishes, reappearing 1d4 hours later in a random location within 1 mile from the location where they used Discorporate."

  - name: "Dragon Heat"
    desc: " (arcane,aura,fire) 10 feet. 4d6 fire damage (DC 41 Reflex check save)"

  - name: "Redirect Fire"
    desc: "`pf2:r` (arcane,fire) **Trigger** A creature within 100 feet casts a fire spell, or a fire spell otherwise comes into effect from a source within 100 feet\n* * *\n\n**Effect** The ravener makes all the choices to determine the targets, destination, and other effects of the spell, as though they were the caster."

  - name: "Soul Ward"
    desc: "  200 HP\n\nAn intangible field of necromantic energy protects a ravener from total destruction. A soul ward has 150 maximum Hit Points, or 200 if the ravener is level 21 or higher. Whenever a ravener would be reduced below 1 Hit Point, all damage in excess of what would reduce them to 1 Hit Point is instead dealt to their soul ward. If this damage reduces the soul ward to fewer than 0 Hit Points, the ravener is destroyed. A soul ward's Hit Points can be restored only via specific ravener abilities such as Consume Soul, ravenous breath, or vicious criticals. A ravener who goes more than a week without successfully using Consume Soul to feed on a dying creature starves, and their soul ward loses 1d4 healing Hit Points each day until they feed. If the ravener's soul ward loses all its Hit Points while the ravener still has more than 1 HP, they become a ravener husk."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (fire, magical, reach 20 feet)\n__Damage__  4d10 + 17 piercing 3d6 fire 2d6 void"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+39 (agile, magical, reach 15 feet)\n__Damage__  4d8 + 17 slashing 2d6 void"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+37 (magical, reach 25 feet)\n__Damage__  4d10 + 15 slashing 2d6 void"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+37 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 15 slashing 2d6 void"

  - name: "Arcane Innate Spells"
    desc: "DC 44, attack +34; __8th __  _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_; __4th __  _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Consume Soul"
    desc: "  DC 44\n\n**Trigger** A living creature within 30 feet of the ravener dies\n* * *\n\n**Effect** The ravener tears the creature's soul from its body with their maw and gulps it down. The dying creature must attempt a DC 44 Fortitude check save with the same DC as the ravener's Breath Weapon.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The ravener tears off a small chunk of the creature's soul. If the victim is restored to life, they are [[Conditions/Drained|Drained 1]] in addition to any other side effects of returning to life. The ravener adds a number of Hit Points to their soul ward equal to half the creature's level.\n\n**Failure** As success, but the creature's soul is ravaged. The creature is [[Conditions/Drained|Drained 3]] and the ravener adds a number of Hit Points to their soul ward equal to the creature's level.\n\n**Critical Failure** As failure, but the ravener devours the entire soul. The victim can't be restored to life as long as the ravener exists except via a 10th-rank effect such as miracle or wish, and the ravener adds a number of Hit Points to their soul ward equal to twice the creature's level."

  - name: "Manipulate Flames"
    desc: "`pf2:1` (arcane,concentrate,fire) The ravener attempts to take control of a magical fire or a fire spell within 100 feet. If it succeeds at a counteract check (counteract rank 10, counteract modifier +34), the original caster loses control of the spell or magical fire, control is transferred to the ravener, and this action counts as the ravener having Sustained the Spell with the action (if applicable). The ravener can choose to end the spell instead of taking control, if they choose."

  - name: "Ravenous Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The ravener breathes a blast of flame that deals 20d6 fire damage plus 4d6 persistent void damage (DC 44 Reflex check save). A creature that fails its save is also [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] on a critical failure). If a creature is drained by the ravener's Ravenous Breath Weapon, the ravener's soul ward gains 5 healing HP.\n\nThe ravener can't use Breath Weapon again for [[/gmr 1d4 #Recharge Breath Weapon]]{1d4 rounds}."

  - name: "Vicious Criticals"
    desc: "  The ravener treats an attack roll as a critical hit on a roll of 19 or 20, as long as the attack roll was a success. Additionally, whenever the ravener makes a critical hit with one of their Strikes, the target must succeed on a DC 42 Fortitude check save or gain the [[Conditions/Drained|Drained 1]] condition. If the target already has a drained value of greater than 0, their drained value instead increases by 1, to a maximum of drained 4. Whenever the ravener applies drain to a creature in this way, their soul ward gains 5 Hit Points."
 
```

```encounter-table
name: Ravener
creatures:
  - 1: Ravener
```



The ravener presented here was once an ancient red dragon.
