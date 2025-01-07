---
title: "Shadow Yai"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9AE4uMzIJNfizXfJ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oni
  - pf2e/creature/type/shadow
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Shadow Yai"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Shadow Yai"
level: "Creature 16"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[giant]]
trait_05: [[humanoid]]
trait_06: [[oni]]
trait_07: [[shadow]]
trait_08: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Greater Darkvision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Arcana: +30, Athletics: +30, Deception: +33, Intimidation: +31, Performance: +33, Stealth: +30"
abilityMods: [8, 6, 5, 6, 6, 9]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +28, __Will__ +26"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290, regeneration 15 (deactivated by acid or fire)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|+2 Greater Striking Glaive]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Shadow Step"
    desc: "`pf2:1` (primal,shadow,teleportation) **Requirements** The shadow yai is in an area of dim light or darkness or is standing in the shadow of any Large or larger object\n* * *\n\n**Effect** The shadow yai instantly teleports to another location that's in dim light or darkness or to a space that's in the shadow of any Large or larger object within 60 feet."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+32 (deadly 2d8, forceful, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 14 slashing 2d6 sonic"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+28 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d8 + 14 bludgeoning plus shadow-touch"

  - name: "**Ranged** `pf2:1` Sonic Missile"
    desc: "+30 (magical, range increment 60 feet, sonic, unholy)\n__Damage__  3d10 + 11 sonic"

  - name: "Innate Primal Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Charm|Charm]]_, _[[Spells/Noise Blast|Sound Burst]]_; __5th __  _[[Spells/Command|Command (x3)]]_, _[[Spells/Umbral Journey|Shadow Walk]]_; __4th __  _[[Spells/Charm|Charm (x3)]]_, _[[Spells/Darkness|Darkness]]_; __3rd __  _[[Spells/Enthrall|Enthrall (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (at will, self only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The shadow yai takes on the appearance of a [[Monster Core/Shadow Giant|Shadow Giant]]. This doesn't change its Speed or Strike attack and damage.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Shadow Touch"
    desc: "  A shadow yai's touch harms their target's spiritual essence in addition to its body. A creature hit by the shadow yai's fist Strike must attempt a DC 36 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d6 void damage.\n\n**Failure** The creature becomes [[Conditions/Drained|Drained 1]] and takes 3d6 void damage. As long as the creature is drained as a result of this ability, it loses the ability to speak above a whisper. When the creature attempts to Cast a Spell with a verbal component, it must succeed at a flat check or the spell is disrupted. The DC of this flat check is equal to 5 plus the creature's drained value (for example, DC 7 if the creature is drained 2).\n\n**Critical Failure** As failure, but the creature becomes [[Conditions/Drained|Drained 2]] and takes 6d6 void damage."
 
```

```encounter-table
name: Shadow Yai
creatures:
  - 1: Shadow Yai
```



Oni who assume the form of shadow giants are known as shadow yais. Many shadow yais crave the pleasures of music and go to great lengths to secure bardic or musically inclined supplicants. Smaller beings who refuse to submit to a shadow yai are subject to painful, drawn out, and strangely beautiful deaths, for a shadow yai has a special way of evoking melodic cries and screams from their victims: a veritable symphony of pain. Individuals of particular musical skill who accompany a shadow yai can find the experience extremely lucrative and enriching-as long as they don't run afoul of their liege.
