---
title: "Warsworn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.D8Tnduf2sw99OTeu" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Warsworn"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Warsworn"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Common; (Can&#x27;t Speak Any Language)"
skills:
  - name: "Skills"
    desc: "Athletics: +33"
abilityMods: [9, 5, 7, -1, 5, 5]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +29, __Ref__ +25, __Will__ +27; +1 status to all saves vs. vitality"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 100 feet DC 35 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Corpse Wave"
    desc: "+32 (magical)\n__Damage__  4d12 + 9 bludgeoning plus energy-drain"

  - name: "**Melee** `pf2:1` Animated Weapon"
    desc: "+30 (agile, magical, reach 100 feet)\n__Damage__  4d4 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Scrap Ball"
    desc: "+28 (magical, range increment 100 feet)\n__Damage__  4d12 + 9 bludgeoning plus plummet"

  - name: "Absorb"
    desc: " (death,divine,void) **Trigger** The warsworn moves into a dying creature's space;\n* * *\n\n**Effect** The warsworn absorbs the dying creature into itself, instantly killing the creature and healing the warsworn for a number of Hit Points equal to the creature's level. As long as the warsworn still exists, absorbed creatures can't be resurrected except by [[Spells/Wish|Wish]] or a similarly powerful effect."

  - name: "Animated Weapons"
    desc: " (aura,divine) 100 feet.\n\nThe warsworn automatically controls unattended weapons in the aura, which levitate around the warsworn. The warsworn can telekinetically wield these weapons to make melee Strikes with a reach of 100 feet. These strikes deal four of the weapon's damage dice +9 and use the weapon's damage type."

  - name: "Energy Drain"
    desc: " (divine,void) When a warsworn hits with a corpse wave Strike or damages a creature with Trample, the target must succeed at a DC 35 Fortitude check save or become [[Conditions/Drained|Drained 2]] and [[Conditions/Doomed|Doomed 1]]. On a critical success, the target becomes temporarily immune to the warsworn's energy drain for 24 hours."

  - name: "Plummet"
    desc: "  A creature hit by a warsworn's scrap ball Strike must attempt a DC 37 Reflex check save. On a failure, the target falls [[Conditions/Prone|Prone]]; if the target was airborne, it falls up to 120 feet, taking damage from the fall and landing prone if the descent brings it to the ground. On a critical failure, the target is also held under a pile of scrap ([[/act escape dc=37]])."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, corpse wave, DC 37 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Warsworn
creatures:
  - 1: Warsworn
```



A warsworn is an animate mass of corpses composed of dozens, sometimes even hundreds, of victims of battle. They are formed by deities of undeath or war or, rarely, spontaneously manifest from the devastation of an especially horrendous battle.
