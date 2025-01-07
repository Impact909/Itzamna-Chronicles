---
title: "The Vanish Man"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hZRVC8zNsPsoqJeV" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "The Vanish Man"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "The Vanish Man"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Common; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +33, Deception: +33, Intimidation: +29, Stealth: +31"
abilityMods: [9, 5, 6, 1, 4, 7]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +29, __Ref__ +28, __Will__ +27"
hp: 265
health:
  - name: ""
  - name: HP
    desc: "265; __Resistances__ bludgeoning 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Cleaver, Bag of Faces"
  - name: "Vanished Alignment"
    desc: "  The Vanish Man doesn't have an alignment aura and cannot be detected by spells such as [[Spells/Detect Alignment|Detect Alignment]]."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 10 feet. DC 33 Will check\n\nThis aura is suppressed while the Vanish Man is using Change Shape.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cleaver"
    desc: "+32 (deadly d12, forceful, sweep)\n__Damage__  3d12 + 9 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+32 (agile, nonlethal)\n__Damage__  3d10 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Cleaver"
    desc: "+30 (deadly d12, thrown 10 ft.)\n__Damage__  3d12 + 9 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 34, attack +24; __4th __ (1 slots) _[[Spells/Invisibility|Invisibility (Self Only)]]_; __2nd __ (3 slots) _[[Spells/Invisibility|Invisibility (x3)]]_\n__Constant__  __(8th)__ _[[Spells/Vanishing Tracks|Pass Without Trace]]_"

  - name: "Change Shape"
    desc: "`pf2:1` (concentrate,occult,polymorph) The vanish man can take on the exact form of any Small, Medium, or Large humanoid whose face they carry in their bag of faces, changing their shape and physical features to precisely match that of the victim whose face they wear. This doesn't change the butcher's Speed or attack or damage bonuses with their Strikes."

  - name: "Remove Face"
    desc: "`pf2:2` (attack) **Requirements** The vanish man is within reach of a [[Conditions/Dying|Dying]], [[Conditions/Immobilized|Immobilized]], or [[Conditions/Unconscious|Unconscious]] creature\n* * *\n\n**Effect** The vanish man attempts a cleaver Strike or an Athletics check check against the creature's Fortitude DC. On a success, the vanish man deals damage as if they had made a successful cleaver Strike against the creature and removes the creature's face. On a critical success, the damage doubles and the creature takes 4d6 bleed. Once its face is removed, the creature takes a permanent -4 status penalty to Charisma checks and Charisma-based skill checks. This penalty can be removed only if the victim recovers its face from the vanish man and has a [[Spells/Restoration|Restoration]] spell cast on it.\n\n[[Bestiary Effects/Effect_ Remove Face|Effect: Remove Face]]"

  - name: "Sudden Slices"
    desc: "`pf2:2`  **Requirements** The vanish man is undetected by their target\n* * *\n\n**Effect** The vanish man Strides once and makes two cleaver Strikes against the target. During the Stride, they gain a +10-foot circumstance bonus to their Speed."
 
```

```encounter-table
name: The Vanish Man
creatures:
  - 1: The Vanish Man
```


Variant faceless butcher


