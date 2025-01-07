---
title: "Hegessik"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y1LdwRWwteLa7taE" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Hegessik"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Hegessik"
level: "Creature 15"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[monitor]]
trait_03: [[protean]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision"
languages: "Chthonian, Empyrean, Protean; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +27, Deception: +29, Diplomacy: +29, Intimidation: +27, Religion: +29, Stealth: +27, Survival: +27"
abilityMods: [8, 6, 7, 4, 6, 6]
speed: 30 feet,  fly 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +26, __Ref__ +23, __Will__ +29; +1 status to all saves vs. divine magic"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250, fast healing 10; __Resistances__ precision 10, protean anatomy 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Entropy Sense (Imprecise) 60 feet"
    desc: " (divine,prediction) A hegessik can anticipate the most likely location of a creature through their supernatural insight into the forces of chaotic probabilities and chance. This grants the hegessik the ability to sense creatures within the listed range.\n\nThe hegessik's entropy sense doesn't detect creatures under the effects of [[Spells/Veil of Privacy|Veil of Privacy]] or that are otherwise shielded from divinations and predictions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Maddening Whispers"
    desc: " (aura,divine,mental) 30 feet. A susurrus of distracting whispers and dilations in reality surround a hegessik.\n\nWhen a non-protean ends its turn in the aura, it must attempt a DC 33 Will check save. If it fails, it becomes [[Conditions/Confused|Confused]] for 1 round."

  - name: "Protean Anatomy 20"
    desc: " (divine) A hegessik's vital organs shift and change shape and position constantly. Immediately after the hegessik takes acid, electricity, or sonic damage, it gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first.\n\nThe hegessik is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the hegessik automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical, reach 10 feet)\n__Damage__  3d8 + 14 piercing plus warpwave-strike 1d6 spirit plus warpwave-strike"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet)\n__Damage__  2d8 + 14 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (magical, reach 15 feet)\n__Damage__  2d8 + 14 bludgeoning plus grab 1d6 spirit plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __8th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Divine Aura|Divine Aura (Chaotic Only)]]_, _[[Spells/Divine Wrath|Divine Wrath]]_; __7th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_, _[[Spells/Slow|Slow (At Will)]]_, _[[Spells/Teleport|Teleport (At Will) (Self Only)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Self Only)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_ __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The hegessik takes the appearance of any Large or smaller creature. This doesn't change its Speed or its attack and damage bonuses with its Strikes, but might change the damage type its Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+14 bludgeoning damage, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Leaching Glare"
    desc: "`pf2:1` (divine) The hegessik briefly opens its third eye.\n\nNon-protean creatures in a 30-foot cone must succeed at a DC 38 Will check save or become [[Conditions/Stupefied|Stupefied 2]] for 1 round ([[Conditions/Stupefied|Stupefied 3]] on a critical failure)."

  - name: "Telekinetic Reach"
    desc: "`pf2:2` (divine,force) The hegessik manifests psychic versions of its natural attacks and makes a Strike with each of its jaws, claw, and tail, in any order. These Strikes have a reach of 60 feet.\n\nThese attacks count toward the hegessik's multiple attack penalty, but the penalty doesn't increase until after it makes all the attacks."

  - name: "Warpwave Strike"
    desc: " (divine) Any creature struck and damaged by a hegessik's jaws Strike must succeed at a DC 36 Fortitude check save or be subject to a [[Rollable Tables/Warpwaves|Warpwave]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Hegessik
creatures:
  - 1: Hegessik
```




