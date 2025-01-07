---
title: "Naunet"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LMrzzsPee5jK6slV" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Naunet"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Naunet"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[monitor]]
trait_03: [[protean]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Chthonian, Empyrean, Protean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +16, Intimidation: +16, Stealth: +14, Survival: +12"
abilityMods: [5, 3, 5, 0, 3, 3]
speed: 25 feet,  fly 30 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +14, __Will__ +12; +1 status to all saves vs. magic"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, fast healing 2; __Resistances__ precision 5, protean anatomy 10"
abilities_top:
  - name: ""

  - name: "Entropy Sense (Imprecise) 30 feet"
    desc: " (divine,prediction) A naunet can anticipate the most likely presence of a creature through a supernatural insight into chaotic probabilities and chance. This grants it the ability to sense creatures within the listed range. A creature under the effects of [[Spells/Veil of Privacy|Veil of Privacy]] or that is otherwise shielded from divinations and predictions cannot be noticed via entropy sense."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 2]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Protean) Protean Anatomy|Protean Anatomy]]"
    desc: " (divine) A protean's vital organs shift and change shape and position constantly. Immediately after the protean takes acid, electricity, or sonic damage, it gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first. The protean is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the protean automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones.\n\n[[Bestiary Effects/Effect_ Protean Anatomy|Effect: Protean Anatomy]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (magical, reach 10 feet)\n__Damage__  2d10 + 8 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+18 (magical, reach 15 feet)\n__Damage__  2d8 + 8 bludgeoning plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+18 (agile, magical, reach 10 feet)\n__Damage__  2d8 + 6 piercing plus confounding-slam 1d6 spirit plus confounding-slam"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +16; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Acid Arrow|Acid Arrow]]_, _[[Spells/Solid Fog|Solid Fog]]_; __3rd __  _[[Spells/Shatter|Shatter (At Will)]]_; __2nd __  _[[Spells/Mist|Obscuring Mist (At Will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Lawful Only)]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "Adaptive Strike"
    desc: " (divine,polymorph) The naunet chooses adamantine, cold iron, or silver; its melee Strikes count as that type for 1 minute or until it uses Adaptive Strike again.\n\n[[Bestiary Effects/Effect_ Adaptive Strike|Effect: Adaptive Strike]]"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The naunet can take the appearance of any Small, Medium, or Large animal, beast, or humanoid. This doesn't change its Speed or its attack and damage bonuses with its Strikes but might change the damage type its Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Confounding Slam"
    desc: " (divine,emotion,mental) A creature hit by the naunet's tentacle Strike is [[Conditions/Stupefied|Stupefied 2]] for 1d4 rounds (DC 24 Will check negates). If the creature was already stupefied in this way, the duration extends by 1 round instead. A chaotic creature is only [[Conditions/Stupefied|Stupefied 1]] instead."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+8 bludgeoning damage, DC 26 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Naunet
creatures:
  - 1: Naunet
```



Pugnacious and powerfully muscled, naunets serve as scouts and rank-and-file troops of protean armies. Resembling a thick salamander with a wide head, a powerful tail, and tentacles tipped with snapping jaws in place of rear legs, naunets are the most bestial of the proteans and occupy one of their lowest castes. Naunets are 12 feet long and weigh 900 pounds.

All proteans are prone to unpredictable fits and unexpected action, but compared to most others, naunets are much more bestial. Always ready for a fight, naunets pride themselves in acting swiftly and striking before unpleasant distractions like diplomacy can blunt a combat's beginning.

* * *

Guardians of disorder and natives of the primal plane of chaos known as the Maelstrom, proteans consider it their calling to spread bedlam and hasten entropic ends. The most powerful proteans are demigods known collectively as the protean lords, although they are mysterious entities whose cults on the Material Plane tend to be obscure and secretive.

Proteans divide themselves into a loose caste system and possess a dizzying variety of powers. Most proteans have a serpentine body with the head of a primeval beast. Scholars have long been intrigued by this fact-that scions of dissolution and disorder would share so many features-pointing out that even in the purest chaos there is some semblance of order. Others note that the serpentine form is one of the most primeval shapes, perhaps suggesting that in a reality at the dawn of time, such shapes were all that could exist. The proteans themselves have little to say on the matter, which, perhaps ironically, only adds to the confusion and lack of consensus surrounding their kind. After all, if even chaos cannot be trusted to be chaotic, would that not be the purest form of entropy?
