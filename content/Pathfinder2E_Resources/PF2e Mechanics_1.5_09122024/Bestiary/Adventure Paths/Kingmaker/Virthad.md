---
title: "Virthad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HbPmfrmQdIsTaAKI" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Virthad"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Virthad"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Chthonian, Common, Goblin"
skills:
  - name: "Skills"
    desc: "Deception: +18, Diplomacy: +16, Nature: +15, Religion: +17, Society: +15, Stealth: +18"
abilityMods: [4, 4, 3, 3, 6, 4]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +16, __Will__ +18"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dogslicer|+1 Striking Dogslicer]], [[Equipment/Clothing (Ordinary)|Robes]], Sack of Flytrap Pods"
abilities_mid:
  - name: ""
  - name: "End the Charade"
    desc: "`pf2:r` (attack) **Trigger** The doppelganger is transformed with Change Shape and another creature moves adjacent to it or takes a hostile action against it.\n* * *\n\n**Effect** The doppelganger reverts to its natural form and can make a Strike against the triggering creature. If the creature was unaware the doppelganger was in disguise, that creature is [[Conditions/Off-Guard|Off-Guard]] against this attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dogslicer"
    desc: "+19 (agile, backstabber, finesse, goblin)\n__Damage__  2d6 + 7 slashing"

  - name: "Divine Prepared Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_; __3rd __  _[[Spells/Blindness|Blindness]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Ghoulish Cravings|Ghoulish Cravings]]_, _[[Spells/Silence|Silence]]_, _[[Spells/Noise Blast|Sound Burst]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Sanctuary|Sanctuary]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 23, attack +15; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The doppelganger takes on the specific appearance of any Small or Medium humanoid who it has seen and whose appearance it remembers. This doesn't change the doppelganger's Speed or its attack and damage bonuses with its Strikes but might change the damage type its Strikes deal (typically to bludgeoning).\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Deploy Flytraps"
    desc: "`pf2:2` (divine,manipulate) **Requirements** Virthad is carrying a sack of prepared flytrap pods\n* * *\n\n**Effect** Virthad dumps the contents of the sack into two adjacent squares while invoking prayers to Lamashtu. The pods grow into two elite [[Monster Core/Snapping Flytrap|Snapping Flytraps]] that immediately attack any non-worshipper of Lamashtu they can detect."
 
```

```encounter-table
name: Virthad
creatures:
  - 1: Virthad
```


Doppelganger priest of Lamashtu


