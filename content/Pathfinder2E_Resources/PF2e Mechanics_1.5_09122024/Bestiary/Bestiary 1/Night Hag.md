---
title: "Night Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BG2YgVxnEl1aDcbc" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Night Hag"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Night Hag"
level: "Creature 9"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[hag]]
trait_04: [[humanoid]]
trait_05: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Empyrean"
skills:
  - name: "Skills"
    desc: "Arcana: +18, Deception: +18, Diplomacy: +18, Intimidation: +14, Occultism: +20, Religion: +20"
abilityMods: [5, 4, 6, 4, 5, 3]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +17, __Will__ +18; +2 status to all saves vs. magic, -2 to all saves (if heartstone is lost)"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  sleep; __Weaknesses__ cold iron 10; __Resistances__ mental 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heartstone|Heartstone]]"
  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) A night hag adds [[Spells/Dominate|Dominate]], [[Spells/Nightmare|Nightmare]], [[Spells/Scrying|Scrying]], and [[Spells/Spellwrack|Spellwrack]] to her coven's spells.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

  - name: "Nightmare Rider"
    desc: "  When a night hag rides a [[Monster Core/Nightmare|Nightmare]], the nightmare also gains the night hag's status bonus to saves against magic, and both the hag and rider benefit when the night hag uses her _[[Equipment/Heartstone|Heartstone's]]_ [[Spells/Ethereal Jaunt|Ethereal Jaunt]] innate spell."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (magical, unholy)\n__Damage__  2d8 + 8 piercing plus abyssal-plague 1d6 spirit plus abyssal-plague"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile, magical, unholy)\n__Damage__  2d10 + 8 slashing 1d6 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __9th __  _[[Spells/Seize Soul|Bind Soul (At Will) (Heartstone)]]_, _[[Spells/Ethereal Jaunt|Ethereal Jaunt (At Will) (Heartstone)]]_; __8th __  _[[Spells/Dream Council|Dream Council]]_; __5th __  _[[Spells/Nightmare|Nightmare]]_, _[[Spells/Shadow Blast|Shadow Blast (Heartstone) (x2)]]_; __3rd __  _[[Spells/Dream Message|Dream Message (At Will)]]_, _[[Spells/Force Barrage|Magic Missile (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_; __1st __  _[[Spells/Enfeeble|Ray of Enfeeblement (At Will)]]_, _[[Spells/Sleep|Sleep (At Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic (3rd)]]_\n__Constant__  __(2nd)__ _[[Spells/Detect Alignment|Detect Alignment (All Alignments)]]_"

  - name: "Coven Spells"
    desc: "DC 23, attack +15; __8th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_; __6th __  _[[Spells/Dominate|Dominate]]_, _[[Spells/Scrying|Scrying]]_, _[[Spells/Spellwrack|Spellwrack]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Scouting Eye|Prying Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_; __4th __  _[[Spells/Nightmare|Nightmare]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Abyssal Plague"
    desc: " (disease) A creature can't recover from drained until abyssal plague is cured.\n\n**Saving Throw** DC 28 Fortitude check\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained]] increases by 2 (1 day)"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The night hag can take on the appearance of any Medium female humanoid. This doesn't change her Speed or her attack and damage bonuses with her Strikes, but might change the damage type her Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Dream Haunting"
    desc: " (mental,occult) If a night hag is ethereal and hovering over a sleeping chaotic or evil creature, she can ride the victim's back until dawn. The creature endures tormenting dreams as the hag casts [[Spells/Nightmare|Nightmare]] on it, and is exposed to abyssal plague. Any drained caused by dream haunting is cumulative.\n\nOnly an ethereal being can confront the night hag and stop her dream haunting."

  - name: "Spell Ambush"
    desc: "  A creature [[Conditions/Off-Guard|Off-Guard]] to the night hag takes a -2 circumstance penalty to checks and DCs to defend against her spells."
 
```

```encounter-table
name: Night Hag
creatures:
  - 1: Night Hag
```



Night hags are thieves and merchants of mortal souls. These foul creatures collect souls in dark gems or crystalline jars to sell in fiendish markets, and are themselves empowered by potent magic jewels known as _[[Equipment/Heartstone|Heartstones]]_. They haunt the Ethereal Plane, where they prey upon mortals in their dreams, debilitating them with horrific nightmares as they rest. A night hag may find a particular target and haunt them continuously over the course of weeks, slowly and cruelly breaking down the victim's will and ability to resist, until their soul is forfeit.

A night hag is a canny mastermind and soul broker, willing to consider any deal as long as she is convinced she has the upper hand. Although a night hag finds it easy to travel the Ethereal Plane and prey upon helpless souls that can't fight back, these souls are also the least desirable to the evil outsiders the night hag bargains with, and so a night hag gathers allies and minions that allow her to prey on more potent souls without personally risking herself. Their favored minions are [[Monster Core/Nightmare|Nightmares]], with whom they share a special bond.

Above all, night hags avoid fighting foes that can harry them on the Ethereal Plane, picking fights only when they are certain they can escape.

* * *

Malevolent crones who lurk at the edges of civilization, hags use their deceptive, magical abilities to prey upon humanoids, manipulating and corrupting them. Some say hags arose from fey that became twisted by their inner selfishness. Hags gather together in covens for greater power, craft unique magical items known as _[[Equipment/Hag Eye|Hag Eyes]]_, and are known to replace infant humanoids with their own offspring-these children are[[Monster Core/Changeling Exile|Changelings]] who have the potential to become hags themselves.
