---
title: "Onidoshi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mIxkIoVVspwnPXmd" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/oni
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Onidoshi"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Onidoshi"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[giant]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
trait_06: [[oni]]
trait_07: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Arcana: +13, Athletics: +16, Deception: +18, Intimidation: +18, Nature: +17"
abilityMods: [6, 3, 4, 3, 3, 4]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +15, __Will__ +15; +1 status to all saves vs. magic"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, regeneration 7 (deactivated by acid or fire)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Falchion|+1 Striking Falchion]], [[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Breastplate|Breastplate]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 7 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Falchion"
    desc: "+21 (forceful, magical, reach 10 feet, sweep, unholy)\n__Damage__  2d10 + 9 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+17 (deadly d10, range increment 100 feet, reload 0, unholy)\n__Damage__  2d6 + 9 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 24, attack +14; __5th __  _[[Spells/Cone of Cold|Cone of Cold]]_; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Vapor Form|Gaseous Form]]_, _[[Spells/Sleep|Sleep]]_; __3rd __  _[[Spells/Fear|Fear]]_; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Invisibility|Invisibility (At will) (Self only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The onidoshi takes on the appearance of an ogre. This doesn't change their Speed or Strike attack and damage.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."
 
```

```encounter-table
name: Onidoshi
creatures:
  - 1: Onidoshi
```



Onidoshi, or ogre mages, are oni with the material form of an ogre. Onidoshi's supernatural prowess and overwhelming intellect are enough to awe and cow entire families of rank-and-file ogres. Because of this, onidoshi are often found at the head of ogre war parties or orchestrating these violent campaigns from behind the scenes. It's rare for onidoshi to lead solitary existences, but those who do prefer to maraud the countryside or exploit villages and hoard the spoils for themselves.
