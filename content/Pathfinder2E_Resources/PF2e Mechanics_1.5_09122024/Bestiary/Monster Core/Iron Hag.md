---
title: "Iron Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aYzNnf3Nj2jb7GYy" 
tags:
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Iron Hag"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Iron Hag"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[hag]]
trait_02: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Aklo, Common, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +14, Deception: +13, Diplomacy: +11, Intimidation: +13, Stealth: +16"
abilityMods: [6, 4, 4, 1, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +12, __Will__ +14; +1 status to all saves vs. magic"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Resistances__ physical 3 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) An iron hag adds [[Spells/Earthbind|Earthbind]], [[Spells/Impaling Spike|Impaling Spike]], and [[Spells/Spellwrack|Spellwrack]] to their coven's spells. Their spell DC when leading a coven is 24.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, cold iron, magical, reach 10 feet)\n__Damage__  2d8 + 6 slashing plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 (cold iron, magical)\n__Damage__  2d6 + 6 piercing"

  - name: "Coven Spells"
    desc: "DC 24, attack +16; __8th __  _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_; __6th __  _[[Spells/Spellwrack|Spellwrack]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Impaling Spike|Impaling Spike]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Bonds of Iron"
    desc: "`pf2:2` (attack,occult) **Frequency** once per day\n* * *\n\n**Effect** The hag causes a cage built of cold iron fingernails to spring out of nothingness around one creature within 30 feet, attempting an Athletics check check to [[Actions/Grapple|Grapple]] against the target's Fortitude DC; if the target has a weakness to cold iron, the iron hag gains a +2 circumstance bonus to this check.\n\nOn a success, the creature is [[Conditions/Grabbed|Grabbed]] by the magical fingernails (or [[Conditions/Restrained|Restrained]] on a critical success). If the creature successfully [[/act escape dc=24]]{Escapes (DC 24)}, the cage crumbles into rust.\n\nAny creature can attempt to destroy the cage by attacking it. It has an AC of 19, Hardness 10, and 40 Hit Points."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The iron hag can take on the appearance of any Medium female humanoid. This doesn't change their Speed or their attack and damage bonuses with their Strikes but might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Embrace of Iron"
    desc: "`pf2:1`  **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the iron hag's claw\n* * *\n\n**Effect** The hag's nails tear into their captured victim, dealing 2d8 piercing damage (the nails are cold iron). Then the hag can attempt to [[Actions/Reposition|Reposition]] the creature. If the creature is adjacent to the hag, they can then attempt a jaws Strike against it."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Iron Hag
creatures:
  - 1: Iron Hag
```



Iron hags are kidnappers, targeting those too young to even remember to fight back. They most often snatch babies from their cradles, though they sometimes target fearful children or youths who suffer from anxiety. They then imprison their new wards in towers or enchanted dungeons, terrifying their victims with stories of the outside world to discourage them from even trying to escape. If these methods fail to be effective, iron hags become more straightforward in their methods of imprisonment, insisting it's for their captives' own good.

An iron hag's true form has unnaturally long arms. True to their name, they have teeth made of iron, as well as long iron toenails and claws.

* * *

Hags are malevolent predators who use magic and manipulation to lure children and young adults into their clutches. Though their true forms are eldritch and horrifying, hags spend much of their lives disguised as ordinary women. They seek out targets who are unhappy, innocent, or otherwise vulnerable, preying on their weaknesses before snatching them up. The typical hag is abusive, controlling, and narcissistic. Though less malicious hags possibly exist, they rarely reveal their true forms, making them nearly impossible to find.
