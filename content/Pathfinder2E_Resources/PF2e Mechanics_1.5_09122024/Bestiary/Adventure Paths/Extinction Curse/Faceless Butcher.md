---
title: "Faceless Butcher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MfOaROZ93BdCDQ9P" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Faceless Butcher"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Faceless Butcher"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common; one regional language, can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +24, Deception: +24, Intimidation: +22, Stealth: +24"
abilityMods: [7, 5, 6, 1, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +22, __Will__ +20"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Resistances__ bludgeoning 8"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Cleaver, Bag of Faces"
  - name: "Suppressed Alignment"
    desc: "  When using their Change Shape ability, the faceless butcher loses their alignment aura and thus cannot be detected by spells such as [[Spells/Detect Alignment|Detect Alignment]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 10 feet. DC 26 Will check\n\nThis aura is suppressed if the faceless butcher is using Change Shape.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cleaver"
    desc: "+24 (forceful, sweep)\n__Damage__  2d12 + 7 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (agile, nonlethal)\n__Damage__  2d10 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Cleaver"
    desc: "+22 (thrown 10 ft.)\n__Damage__  2d12 + 7 slashing"

  - name: "Change Shape"
    desc: "`pf2:1` (concentrate,occult,polymorph) The faceless butcher can take on the exact form of any Small, Medium, or Large humanoid whose face they carry in their bag of faces, changing their shape and physical features to precisely match that of the victim whose face they wear. This doesn't change the butcher's Speed or attack or damage bonuses with their Strikes."

  - name: "Remove Face"
    desc: "`pf2:2` (attack) **Requirements** The faceless butcher is within reach of a [[Conditions/Dying|Dying]], [[Conditions/Immobilized|Immobilized]], or [[Conditions/Unconscious|Unconscious]] creature\n* * *\n\n**Effect** The faceless butcher attempts a cleaver Strike or an Athletics check check against the creature's Fortitude DC. On a success, the faceless butcher deals damage as if they had made a successful cleaver Strike against the creature and removes the creature's face. On a critical success, the damage doubles and the creature takes 4d6 bleed. Once its face is removed, the creature takes a permanent -4 status penalty to Charisma checks and Charisma-based skill checks. This penalty can be removed only if the victim recovers its face from the faceless butcher and has a [[Spells/Restoration|Restoration]] spell cast on it.\n\n[[Bestiary Effects/Effect_ Remove Face|Effect: Remove Face]]"

  - name: "Sudden Slices"
    desc: "`pf2:2`  **Requirements** The faceless butcher is undetected by their target\n* * *\n\n**Effect** The faceless butcher Strides once and makes two cleaver Strikes against the target. During the Stride, they gain a +10-foot circumstance bonus to their Speed."
 
```

```encounter-table
name: Faceless Butcher
creatures:
  - 1: Faceless Butcher
```



The deformed flesh on this humanoid horror's head bears grim holes where their eyes, nose, mouth, and ears should be, and little else. Stories of faceless butchers always center on the monstrous murderer's preferred weapon: a wicked and bloodstained meat cleaver, which the butcher uses to carve flesh from skull to add to their collection of stolen faces. Once they've taken a victim's face, the faceless butcher can wear it, transform into an exact replica of the deceased, and begin stalking their next victim.
