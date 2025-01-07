---
title: "Tenebric Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.I5S0kQDSmEYhSh31" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Tenebric Giant"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Tenebric Giant"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[shadow]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Lifesense 80 Feet"
languages: "Common, Jotun, Necril; telepathy (with its creator only) 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Intimidation: +30, Religion: +30, Stealth: +29"
abilityMods: [9, 4, 9, 4, 7, 5]
speed: 25 feet
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +32, __Ref__ +27, __Will__ +30"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360, void healing; __Immunities__  death effects,  disease,  mental,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scythe|+2 Greater Striking Scythe]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 80 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scythe"
    desc: "+34 (deadly 2d10, magical, reach 15 feet, trip)\n__Damage__  3d10 + 17 slashing plus cloying-shadows"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, reach 15 feet)\n__Damage__  3d6 + 17 slashing plus cloying-shadows"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+32 (brutal, range increment 120 feet)\n__Damage__  3d6 + 17 bludgeoning plus cloying-shadows"

  - name: "Cloying Shadows"
    desc: " (occult,shadow) The tenebric giant's attacks leave behind a residue of energy from the Shadow Plane. A creature hit by the tenebric giant's melee Strike takes an additional 1d8 persistent void damage and must attempt a DC 36 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Blinded|Blinded]] until its next turn begins.\n\n**Failure** The creature is blinded for 1 minute.\n\n**Critical Failure** The creature is permanently blinded."

  - name: "Tenebric Stride"
    desc: "`pf2:2` (illusion,occult,shadow) The tenebric giant can move quickly in shadowy conditions. The tenebric giant Strides twice and makes a scythe Strike at any point during this movement against a target that is in darkness or dim light. This movement doesn't provoke reactions."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Tenebric Giant
creatures:
  - 1: Tenebric Giant
```



Necromancers reaching for the greatest heights of experimentation know that creating a new terror requires exacting, careful work at every stage of the process. In the case of the tenebric giant, this process begins with a tomb giant who dies after consuming a dose of several poisons combined with the shadow ash reagent. This creates the right circumstances for a necromancer to raise them as a tenebric giant. They're particularly obedient to the will of the necromancer who created them and are charged full of energy from the Shadow Plane, which grants them new powers and abilities.
