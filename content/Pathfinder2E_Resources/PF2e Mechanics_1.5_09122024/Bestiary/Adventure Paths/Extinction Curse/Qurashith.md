---
title: "Qurashith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xcikq0CrtpJ6gM56" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Qurashith"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Qurashith"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Greater Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Chthonian; telepathy 120 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +32, Deception: +29, Stealth: +32, Survival: +28"
abilityMods: [9, 7, 6, -1, 5, 6]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +29, __Ref__ +30, __Will__ +28"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340; __Weaknesses__ holy 15; __Resistances__ acid 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Adhesive Body"
    desc: "  Any creature that Strikes the qurashith with a melee weapon must attempt a DC 37 Reflex check save. On a failure, the creature is disarmed of its weapon, which becomes stuck to the qurashith's body; if the Strike was an unarmed attack, the creature's limb sticks to the qurashith's body and the creature becomes immobilized. A creature must succeed at a DC 31 Athletics check check to retrieve a stuck weapon. On a failure, the creature takes 2d6 acid damage and the weapon remains stuck, and on a critical failure, the creature also becomes stuck to the qurashith and becomes [[Conditions/Immobilized|Immobilized]]. A stuck creature takes 2d6 acid damage each round it remains stuck to the qurashith and can use an [[Actions/Escape|Escape]] action to try to free itself from the monster (DC 31)."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 33 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 15 feet, unholy)\n__Damage__  3d12 + 17 piercing plus paralytic-saliva"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 15 feet, unholy)\n__Damage__  3d10 + 15 slashing"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+30 (range 60 feet, unholy)\n__Damage__  6d6 acid plus paralytic-saliva"

  - name: "Divine Innate Spells"
    desc: "DC 35, attack +27; __6th __ (1 slots) _[[Spells/Teleport|Teleport (At Will, Self Only)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Paralytic Saliva"
    desc: "  A creature that takes damage from a qurashith's jaws or spittle must succeed at a DC 39 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] for 1d4 rounds ([[Conditions/Slowed|Slowed 2]] on a critical failure). If a creature is already slowed when it fails its save, it becomes [[Conditions/Paralyzed|Paralyzed]] for 1 round."

  - name: "Psychic Howl"
    desc: "`pf2:2`  The qurashith unleashes a debilitating psionic scream. Creatures in a 60-foot cone must succeed at a DC 35 Will check save or become [[Conditions/Stupefied|Stupefied 2]] ([[Conditions/Stupefied|Stupefied 4]] on a critical failure) for 1 minute. A creature that critically succeeds at its Will save is immune to the qurashith's Psychic Howl for 24 hours. The qurashith can't use Psychic Howl again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  **Strike**: Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Qurashith
creatures:
  - 1: Qurashith
```



Qurashith-or "gluttonwings" in the Common tongue-are fearsome, bat-like predators that haunt the upper reaches of Gluttondark's cavern-worlds. These monstrosities are no mere beasts. A qurashith does not simply devour its victims; once it kills its prey, it physically subsumes the creature into its own body, metabolizing the prey's spiritual essence. Close inspection of a qurashith reveals that its body is an amalgamation of the fiend and its extraplanar and mortal victims, bound together by webs of demonic scar tissue and sticky acidic pus. While the individual personalities of a qurashith's victims gradually metabolize and diffuse into its very substance over time, a particularly charismatic or magically powerful victim might exert some influence over the qurashith's mind for a short time.
