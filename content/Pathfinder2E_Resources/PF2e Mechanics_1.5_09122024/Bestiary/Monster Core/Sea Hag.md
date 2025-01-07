---
title: "Sea Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bqtoRMoBGtV5LqOp" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Sea Hag"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sea Hag"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[hag]]
trait_03: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Aklo, Common, Jotun, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +11, Deception: +10, Occultism: +8, Stealth: +8"
abilityMods: [4, 3, 4, 1, 3, 3]
speed: 25 feet,  swim 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +11, __Ref__ +8, __Will__ +10; +1 status to all saves vs. magic"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  polymorph; __Weaknesses__ cold iron 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) A sea hag adds [[Spells/Humanoid Form|Humanoid Form]], [[Spells/Mariner's Curse|Mariner's Curse]], and [[Spells/Water Walk|Water Walk]] to their coven's spells. Their spell DC when leading a coven is 20.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

  - name: "Sea Hag's Bargain"
    desc: " (concentrate,exploration,occult,polymorph) The sea hag can make a bargain with a willing creature who must be of sound mind. The creature gives away a special or cherished quality—such as its courage, its beauty, or its voice. In exchange, the sea hag spends 1 minute polymorphing the creature into a form the target desires.\n\nThis functions as [[Bestiary Ability Glossary/Change Shape|Change Shape]]. It might be a total transformation or just changing one or more aspects of the target's body, and it can't make the creature more than one size smaller or larger. The creature changes its Speeds as appropriate for the new form. It doesn't change the attack and damage bonuses with its Strikes, but it might change the damage type the Strikes deal. This has an unlimited duration, and as long as it's transformed, the creature is [[Conditions/Sickened|Sickened 2]] and can't reduce its sickened condition below 2. The creature can slowly and carefully eat and drink despite being sickened. The only way to restore the lost quality used as payment is to defeat the sea hag or make another bargain for its return. Ending the bargain in this way also removes the transformation."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile, magical)\n__Damage__  1d10 + 4 slashing"

  - name: "Coven Spells"
    desc: "DC 20, attack +12; __8th __ (1 slots) _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_; __5th __ (1 slots) _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Humanoid Form|Humanoid Form]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_, _[[Spells/Water Walk|Water Walk]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Dread Gaze"
    desc: "`pf2:2` (curse,emotion,fear,mental,occult) The hag gazes upon a creature, afflicting it with a gnawing sense of impending doom, with a result depending on its DC 20 Will check save. The target doesn't need to be able to see the sea hag.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is frightened 1 and is [[Conditions/Slowed|Slowed 1]] for 1 round. If the target was dying, it remains [[Conditions/Unconscious|Unconscious]] for 1 day. At the end of the day, it must attempt a DC 20 Fortitude check save; if it fails, it dies.\n\n**Critical Failure** As failure, but the creature is [[Conditions/Frightened|Frightened 2]] and slowed 1 for 1 minute."
 
```

```encounter-table
name: Sea Hag
creatures:
  - 1: Sea Hag
```



Sea hags specialize in transformation magic, preying on those who are desperate to change some aspect of their physical appearance. Targets often include those suffering from insecurity about their bodies or those desperate to reside in a different environment, such as aquatic creatures who wish to live on land. These hags are known for tempting desperate victims into tragic and excruciating bargains, though they're also happy to drown and eat mariners who stray too close to their dwellings.

A sea hag has the upper half of a humanoid and the lower half of an octopus, with translucent skin and glowing lights visible beneath their flesh. Sea hags can join covens, but their aquatic nature often prevents them from joining mixed covens with other kinds of hags.

* * *

Hags are malevolent predators who use magic and manipulation to lure children and young adults into their clutches. Though their true forms are eldritch and horrifying, hags spend much of their lives disguised as ordinary women. They seek out targets who are unhappy, innocent, or otherwise vulnerable, preying on their weaknesses before snatching them up. The typical hag is abusive, controlling, and narcissistic. Though less malicious hags possibly exist, they rarely reveal their true forms, making them nearly impossible to find.
