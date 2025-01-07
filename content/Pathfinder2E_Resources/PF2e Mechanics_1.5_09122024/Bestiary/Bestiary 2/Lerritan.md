---
title: "Lerritan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dmT06H2KtHuZI4sP" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Lerritan"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Lerritan"
level: "Creature 21"

alignment: ""
size: "grg"
trait_01: [[earth]]
trait_02: [[elemental]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Low-Light Vision"
languages: "Common, Jotun, Petran, Pyric"
skills:
  - name: "Skills"
    desc: "Athletics: +41, Crafting: +33, Intimidation: +35, Religion: +36, Survival: +38"
abilityMods: [10, 5, 7, 2, 7, 4]
speed: 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +38, __Ref__ +34, __Will__ +36"
hp: 490
health:
  - name: ""
  - name: HP
    desc: "490; __Immunities__  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 20; __Resistances__ piercing 20, slashing 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|+3 Greater Striking Warhammer]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Tenacious Flames"
    desc: " (aura,fire,primal) 100 feet. Creatures in the emanation cannot recover from persistent fire damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+40 (magical, reach 25 feet, shove)\n__Damage__  4d12 + 18 bludgeoning 2d6 fire"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (agile, reach 25 feet)\n__Damage__  4d10 + 18 piercing 2d6 fire"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+39 (brutal, range increment 120 feet)\n__Damage__  4d6 + 18 bludgeoning 2d6 fire"

  - name: "Primal Innate Spells"
    desc: "DC 46, attack +36; __10th __ (1 slots) _[[Spells/Cataclysm|Cataclysm]]_; __9th __ (2 slots) _[[Spells/Fireball|Fireball]]_, _[[Spells/Falling Stars|Meteor Swarm]]_; __8th __ (1 slots) _[[Spells/Earthquake|Earthquake]]_; __7th __ (1 slots) _[[Spells/Interplanar Teleport|Plane Shift (To the Material Plane, Plane of Fire, or Plane of Earth only)]]_\n__Cantrips__  __(10th)__ _[[Spells/Produce Flame|Produce Flame]]_"

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  A lerritan can break stony scales off its body to throw; these scales reform at the end of each round, so the lerritan is never without a supply of rocks to hurl.\n* * *\n\nThe monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "Volcanic Eruption"
    desc: "`pf2:2` (earth,fire,primal) The volcano on the lerritan's back erupts and sends lava bombs raining down in a 30-foot emanation, dealing 12d12 fire damage.\n\nEach creature in the area must attempt a DC 46 Reflex check saving throw. The lava globules quickly cool into heavy stones, transforming the area into greater difficult terrain for non-lerritans.\n\nThe lerritan can't use for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is [[Conditions/Encumbered|Encumbered]] for 1 round.\n\n**Failure** The creature takes full damage and is [[Conditions/Immobilized|Immobilized]] (Escape DC 46).\n\n**Critical Failure** The creature takes double damage and is encased in a rocky crust with lava on the inside. The creature is [[Conditions/Restrained|Restrained]] (Escape DC 46), can't breathe, takes 3d12 persistent fire damage, and can't recover from this persistent fire damage until freed."
 
```

```encounter-table
name: Lerritan
creatures:
  - 1: Lerritan
```



Lerritans are unstoppable giants with skin of volcanic glass and blood of roiling lava. These malicious arsonists would see the world burned to a cinder. They pay homage to Ymeri, the evil elemental demigod of fire, and they bully other fiery creatures. When the urge to immolate grows too great to ignore, lerritans burn forests, destroy villages, and boil rivers, but they avoid large bodies of water.
