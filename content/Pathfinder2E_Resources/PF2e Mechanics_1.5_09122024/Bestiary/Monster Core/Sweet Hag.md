---
title: "Sweet Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nMp10siLiEYfTi4v" 
tags:
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Sweet Hag"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sweet Hag"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[hag]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Aklo, Common, Fey, Jotun; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +11, Deception: +10, Nature: +8, Occultism: +8, Society: +9"
abilityMods: [5, 3, 3, 2, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +11, __Will__ +12; +1 to all saves vs. magic"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) A sweet hag adds [[Spells/Charm|Charm]], [[Spells/Honeyed Words|Honeyed Words]], and [[Spells/Outcast's Curse|Outcast's Curse]] to their coven's spells.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Candy Cane Claw"
    desc: "+14 (agile, magical)\n__Damage__  1d10 + 5 piercing plus soporific-touch"

  - name: "Occult Innate Spells"
    desc: "DC 20, attack +14; __2nd __  _[[Spells/Create Food|Create Food (Sweets Only)]]_, _[[Spells/Invisibility|Invisibility (At Will)]]_, _[[Spells/Laughing Fit|Laughing Fit]]_, _[[Spells/Shrink|Shrink]]_, _[[Spells/Sleep|Sleep]]_; __1st __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Cleanse Cuisine|Cleanse Cuisine (At Will)]]_, _[[Spells/Spider Sting|Spider Sting]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Light|Light]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Coven Spells"
    desc: "DC 20, attack +14; __8th __  _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Honeyed Words|Honeyed Words]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Betraying Touch"
    desc: "`pf2:1`  The sweet hag touches a creature that doesn't realize the hag is an enemy. The betrayed creature is affected by soporific strike with a –4 circumstance penalty to their saving throw."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The sweet hag can take on the appearance of any Medium humanoid woman. This doesn't change their Speed or their attack and damage bonuses with their Strikes, but it might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Poisoned Candy"
    desc: "`pf2:2` (occult) The sweet hag casts an innate spell that can normally target 1 creature on a piece of food, typically a sweet treat. The spell is stored in the food. The first creature that eats any of the food is affected by the spell and takes a –4 circumstance penalty to their saving throw against that effect."

  - name: "Soporific Touch"
    desc: " (incapacitation,occult) A creature damaged by a sweet hag's claw must succeed at a DC 20 Fortitude check save or be [[Conditions/Enfeebled|Enfeebled 1]] for 1 day.\n\nIf the creature critically fails or fails this save while already enfeebled by soporific strike, it falls [[Conditions/Unconscious|Unconscious]] and dreams of eating delicious sweets; this is a mental sleep effect. If not woken up before 1 minute passes, the creature wakes up automatically."
 
```

```encounter-table
name: Sweet Hag
creatures:
  - 1: Sweet Hag
```



Sweet hags use bright colors, pleasant visages, and sugary treats to draw in children and the young at heart. Their favorite prey is impoverished youngsters who are unlikely to be missed—sweet hags offer them food and a veneer of kindness before devouring the hapless child. Sweet hags also enchant their food to magically charm others, often using these bespelled servitors to handle all of their busywork. Though they present a lovely and generous face to the world, they turn vicious when insulted or defied. A sweet hag's true form is a dribbling mass of flesh with gumdrop eyes, often resembling melting taffy.

* * *

Hags are malevolent predators who use magic and manipulation to lure children and young adults into their clutches. Though their true forms are eldritch and horrifying, hags spend much of their lives disguised as ordinary women. They seek out targets who are unhappy, innocent, or otherwise vulnerable, preying on their weaknesses before snatching them up. The typical hag is abusive, controlling, and narcissistic. Though less malicious hags possibly exist, they rarely reveal their true forms, making them nearly impossible to find.
