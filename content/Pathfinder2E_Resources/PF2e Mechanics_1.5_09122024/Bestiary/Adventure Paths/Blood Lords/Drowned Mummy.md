---
title: "Drowned Mummy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YrdZsXOElBxIJo10" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Drowned Mummy"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Drowned Mummy"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[lawful]]
trait_04: [[mummy]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Echolocation 120 Feet, Darkvision"
languages: "Necril, Thalassic; telepathy 30 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +32, Intimidation: +28, Nature: +30, Stealth: +30"
abilityMods: [9, 5, 6, 3, 7, 1]
speed: 25 feet,  swim 40 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +29, __Ref__ +28, __Will__ +32"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ fire 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|+2 Greater Striking Trident]]"
  - name: "Aquatic Echolocation (Precise) 120 feet"
    desc: "  A drowned mummy can use its hearing as a precise sense at the listed range but only underwater."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Water Pressure"
    desc: " (aura,primal) 30 feet. A creature that begins its turn within the aura feels overburdened by the weight of the water around it and must succeed at a DC 35 Fortitude check save or become [[Conditions/Encumbered|Encumbered]] for as long as it remains in the area. A creature that succeeds is temporarily immune to water pressure for 24 hours. Water pressure only functions while the drowned mummy is underwater and can only affect creatures that are in contact with the same body of water."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Trident"
    desc: "+33 (magical)\n__Damage__  3d8 + 15 piercing plus aquatic-advantage"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+33 (agile)\n__Damage__  2d8 + 15 bludgeoning plus aquatic-advantage,rancid-bloat"

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+31 (magical, thrown 20 ft.)\n__Damage__  3d8 + 15 piercing plus aquatic-advantage"

  - name: "Aquatic Advantage"
    desc: "  A drowned mummy's Strikes deal an additional 2d6 damage against creatures in the same body of water as the drowned mummy."

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  **Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Rancid Bloat"
    desc: " (curse,disease,divine) This disease and damage from it can't be healed unless this curse is removed. A creature killed by rancid bloat rots away to waterlogged pieces of flesh and can't be resurrected except by an 8th-rank [[Spells/Resurrect|Resurrect]] ritual or similar magic.\n\n**Saving Throw** DC 38 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 minute)\n\n**Stage 2** 12d6 void damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)\n\n**Stage 3** 16d6 void damage, [[Conditions/Clumsy|Clumsy 4]], and [[Conditions/Enfeebled|Enfeebled 4]] (1 day)"

  - name: "Whirlpool"
    desc: "`pf2:2` (primal,water) **Requirements** The drowned mummy is underwater\n* * *\n\n**Effect** The drowned mummy commands the water to churn, creating a powerful whirlpool centered on itself. Each creature within a 30-foot emanation centered on the drowned mummy takes 14d8 bludgeoning damage (DC 38 Reflex check) as the powerful current batters them around. A creature that fails this save is pushed 20 feet away from the mummy and also falls [[Conditions/Prone|Prone]] on a critical failure. The drowned mummy can't use Whirlpool again for 1d4 rounds."
 
```

```encounter-table
name: Drowned Mummy
creatures:
  - 1: Drowned Mummy
```



Rarely artificially created, drowned mummies are miserable, dripping undead that have adapted to exist in an aquatic environment, usually over centuries, after their tomb or lair becomes flooded.
