---
title: "Silverhand Salvo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EbYmlsKeaWePQc2l" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/fiend
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Silverhand Salvo"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Silverhand Salvo"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[fiend]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision"
languages: "Common, Diabolic, Empyrean; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Deception: +28, Diplomacy: +26, Intimidation: +28, Thievery: +28, Accounting Lore: +25, Games Lore: +29"
abilityMods: [5, 6, 4, 5, 6, 8]
speed: 25 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +22, __Ref__ +26, __Will__ +28"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Immunities__  fire; __Weaknesses__ holy 15; __Resistances__ physical 15 (except silver), poison 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sword Cane|+2 Greater Striking Unholy Sword Cane]], [[Equipment/Jeweled dawnsilver crown|Jewelry]]"
abilities_mid:
  - name: ""
  - name: "Risk Aura"
    desc: " (aura,divine,mental,misfortune) 30 feet. A feeling of recklessness surrounds a gambling devil. When a non-fiend creature enters the aura or begins its turn in the aura, it must attempt a DC 31 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Risk Aura for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The next time the creature rolls a d20, it must roll twice. If either roll is a natural 20, the creature uses that result; otherwise, it must take the lower of the two results.\n\n**Critical Failure** As failure, but applies to all of the creature's d20 rolls as long as it remains in the aura."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (agile, finesse, magical, unholy)\n__Damage__  3d4 + 11 bludgeoning"

  - name: "**Melee** `pf2:1` Sword Cane"
    desc: "+28 (agile, concealable, finesse, magical, unholy)\n__Damage__  3d6 + 11 piercing 1d4 spirit"

  - name: "**Ranged** `pf2:1` Thrown Coin"
    desc: "+28 (magical, range 30 feet, unholy)\n__Damage__  3d6 + 8 bludgeoning 1d6 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Illusory Creature|Illusory Creature]]_; __6th __  _[[Spells/Truesight|Truesight]]_; __5th __  _[[Spells/Ill Omen|Ill Omen (At Will)]]_, _[[Spells/Illusory Object|Illusory Object]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Figment|Figment]]_"

  - name: "Rituals"
    desc: "_Diabolic Pact_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The agadaz adopts the appearance of any Small or Medium humanoid. This doesn't change their Speed or their attack and damage bonuses with their Strikes, but it might change the type of damage their Strikes deal.\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Double Down"
    desc: "`pf2:r` (divine,fortune) **Trigger** The agadaz attempts a Strike, saving throw, or skill check\n* * *\n\n**Effect** The agadaz takes a –2 status penalty to the roll, then gains a +2 status bonus to the next Strike, saving throw, or skill check they attempt before the end of their turn, or before the end of their next turn if they used Double Down during another creature's turn."

  - name: "Produce Gold Coins"
    desc: "  **Frequency** once per round\n\n**Requirements** The agadaz has a free hand\n* * *\n\n**Effect** The agadaz creates up to 5 gp in their hand. At any one time, an agadaz can possess no more than 20 gp created in this way; coins created in excess of this value vanish. A coin created in this way vanishes automatically 1 hour after leaving the devil's possession."
 
```

```encounter-table
name: Silverhand Salvo
creatures:
  - 1: Silverhand Salvo
```


Variant male gambling devil

Gambling devils, known also as agadazes, resemble horned humans crafted out of living gold in their natural forms, though their shapeshifting abilities let them move among mortals undetected. They're most commonly encountered in Erebus, the third layer of Hell, where many serve Mammon as accountants. They're unusually impulsive and distractible for their kind. Other devils often view their Risk Aura as a hindrance, so they usually receive less important missions. They don't mind, for it gives them more time to meddle with mortals.

## Heavy Footsteps

Even when appearing in a humanoid guise, a gambling devil's body remains extremely dense and heavy, often weighing more than 500 pounds. Old gamblers' yarns warn to watch the footsteps of fellow gamblers and be wary of those whose tread seems disproportionate to their size, though in truth, all but the most careless gambling devils know how to step lightly in their humanoid forms.
