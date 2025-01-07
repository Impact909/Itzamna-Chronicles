---
title: "Azuretzi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q9uPqOkXI9I30noc" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Azuretzi"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Azuretzi"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[monitor]]
trait_02: [[protean]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Chthonian, Empyrean, Protean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Arcana: +11, Deception: +13, Performance: +13, Stealth: +13, Survival: +11, Thievery: +13"
abilityMods: [2, 4, 4, 4, 2, 4]
speed: 25 feet,  fly 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +15, __Will__ +11; +1 status to all saves vs. magic"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, (fast healing 2); __Resistances__ precision 5, protean anatomy 8"
abilities_top:
  - name: ""

  - name: "Entropy Sense"
    desc: " (divine,prediction) An azureti can anticipate the most likely presence of a creature through a supernatural insight into chaotic probabilities and chance. This grants them the ability to sense creatures within the listed range. [[Spells/Veil of Privacy|Veil of Privacy]] prevents a creature from being detected via entropy sense automatically (without a counteract check)."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 2]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Protean) Protean Anatomy|Protean Anatomy]]"
    desc: " (divine) An azureti's vital organs shift and change shape and position constantly. Immediately after the azureti takes acid, electricity, or sonic damage, they gain the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case their resistance changes to match that type), whichever comes first.\n\nThe azureti is immune to polymorph effects unless they're a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the azureti automatically recovers at the end of their next turn as new sensory organs grow to replace the compromised ones.\n\n[[Bestiary Effects/Effect_ Protean Anatomy|Effect: Protean Anatomy]]"

  - name: "Spell Pilfer"
    desc: "`pf2:r`  **Trigger** A creature with an active spell effect within 30 feet of the azuretzi fails to resist another azuretzi's Mocking Touch\n* * *\n\n**Effect** The azuretzi attempts a Thievery check check to counteract one spell affecting the target creature. On a success, the azuretzi transfers the spell effect to themself, keeping the same remaining duration. The target then becomes temporarily immune to Spell Pilfer for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (finesse, magical)\n__Damage__  2d10 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, finesse, magical)\n__Damage__  2d8 + 5 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+13 (magical, reach 15 feet)\n__Damage__  2d12 + 5 bludgeoning plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +12; __4th __  _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Shatter|Shatter]]_; __2nd __  _[[Spells/Laughing Fit|Laughing Fit]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+5 bludgeoning, DC 21 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Mimic Form"
    desc: "`pf2:2` (concentrate,divine,polymorph) As Change Shape, but an azuretzi can assume the form of a Medium or smaller creature. They can mimic a specific creature they can see, but they must succeed at a DC 25 Perception check check or the attempt is disrupted. The azuretzi can transform into the same creature again without a check but can retain the details of only one specific appearance at a time. The azuretzi can Dismiss the effect as a free action to return to their natural form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Mocking Touch"
    desc: "`pf2:2` (divine) **Requirements** The azuretzi is not currently using Mocking Touch on a spell\n* * *\n\n**Effect** The azuretzi mocks a creature's magical ability with a touch. The azuretzi attempts a Thievery check check against the target's Will DC.\n* * *\n\n**Critical Success** The azuretzi learns all spells of 3rd rank or lower the target has available to cast and chooses one. The azuretzi gains that spell as a mock divine innate spell and can cast it once as an innate divine spell using their own DC and spell attack modifier. The spell is lost if unused after 24 hours. The creature can't cast the mock spell until the azuretzi casts it first or the 24 hour period passes, whichever comes first.\n\n**Success** As critical success, but the mock spell is lost after 1 hour, and the creature touched can cast the spell normally.\n\n**Failure** As critical success, but the mock spell is lost at the end of the azuretzi's next turn, and the creature touched can cast the spell normally.\n\n**Critical Failure** Mocking Touch has no effect."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Azuretzi
creatures:
  - 1: Azuretzi
```



Azuretzis are sinuous, serpentine creatures with daggersharp teeth covered in brilliant blue scales and mottled purple and pink highlights that shimmer in a pareidolic approximation of leering, laughing faces. The Maelstrom's chaotic forces spawn these small proteans from a variety of sources: physical mating between older azuretzis, the paradoxical promotion of bestial naunets, and possibly from mortal petitioners, though these azuretzis may just be confusing putative mortal memories with experiences gained from games of mimicry. Never expect azuretzis to operate by any rational, self-consistent rules.

Azuretzis represent the humor of chaos, particularly in the form of mockery and parody via exaggerated mimicry, twisting a target's features into a laughingstock.

* * *

Guardians of disorder and natives of the primal plane of chaos known as the Maelstrom, proteans consider it their calling to spread bedlam and hasten entropic ends. The most powerful proteans are demigods known collectively as the protean lords, although they are mysterious entities whose cults in the Universe tend to be obscure and secretive.

Proteans divide themselves into a loose caste system and possess a dizzying variety of powers. Most proteans have a serpentine body with the head of a primeval beast. Scholars have long been intrigued by this fact—that scions of dissolution and disorder would share so many features—pointing out that there is some semblance of order even in the purest chaos. Others note that the serpentine form is one of the most primeval shapes, perhaps suggesting that in a reality at the dawn of time, such shapes were all that could exist. The proteans themselves have little to say on the matter, which, perhaps ironically, only adds to the confusion and lack of consensus surrounding their kind. After all, if even chaos cannot be trusted to be chaotic, would that not be the purest form of entropy?
