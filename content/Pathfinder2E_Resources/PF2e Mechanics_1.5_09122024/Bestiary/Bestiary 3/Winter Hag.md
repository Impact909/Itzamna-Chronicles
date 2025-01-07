---
title: "Winter Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MR49JiRtBOlXkoIx" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Winter Hag"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Winter Hag"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[evil]]
trait_04: [[hag]]
trait_05: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, See the Unseen"
languages: "Aklo, Common, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Deception: +17, Diplomacy: +15, Occultism: +15, Survival: +14"
abilityMods: [4, 2, 3, 4, 3, 6]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +13, __Will__ +16"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  cold; __Weaknesses__ cold iron 5, fire 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) A winter hag adds [[Spells/Cone of Cold|Cone of Cold]], [[Spells/Solid Fog|Solid Fog]], and [[Spells/Wall of Ice|Wall of Ice]] to her coven's spells.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

  - name: "Snow Vision"
    desc: "  Snow doesn't impair a winter hag's vision; she ignores [[Conditions/Concealed|Concealment]] from snowfall."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ice Staff"
    desc: "+17 (magical, two-hand d8)\n__Damage__  2d4 + 7 bludgeoning 1d6 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile)\n__Damage__  2d6 + 7 slashing 1d6 cold"

  - name: "Occult Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Fly|Fly (At Will)]]_, _[[Spells/Ice Storm|Ice Storm]]_; __3rd __  _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Paralyze|Paralyze]]_\n__Cantrips__  __(4th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Ray of Frost|Ray of Frost]]_\n__Constant__  __(4th)__ _[[Spells/Vanishing Tracks|Pass Without Trace]]_, _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Coven Spells"
    desc: "DC 23, attack +15; __8th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Scouting Eye|Prying Eye]]_, _[[Spells/Solid Fog|Solid Fog]]_, _[[Spells/Talking Corpse|Talking Corpse]]_, _[[Spells/Wall of Ice|Wall of Ice]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Craft Ice Staff"
    desc: " (cold,downtime,occult) A winter hag can spend 1 day performing a specific ritual to create a _+1 Striking Staff_ of black ice. Once per day, she can use the staff to cast [[Spells/Cone of Cold|Cone of Cold]]. The staff's magic functions only in the hands of the hag who created it; for anyone else, it is a mundane staff. If the hag dies or if the staff remains in another creature's possession for 24 hours, the staff melts into a puddle of foul-smelling water."

  - name: "Ice Climb"
    desc: "  A winter hag can Climb at the listed Speed, but only on ice. She ignores difficult terrain from ice and snow, and she doesn't risk falling when crossing ice."
 
```

```encounter-table
name: Winter Hag
creatures:
  - 1: Winter Hag
```



On long, dark winter nights, folk at the edges of civilization have learned to be wary of old women who come knocking at their door. They look for her tracks in the snow and other telltale signs to make sure she isn't a winter hag who plans to drag them off and feast on their bones.

In truth, winter hags are more subtle monsters, entrapping humanoids in schemes that create mistrust and anger within a village before picking off the residents one or two at a time, heightening the fear and anger of those who remain. When her work is done, a winter hag revels in the silence of a frost-rimed village in which no hearth fires are left burning.

* * *

Foul creatures who appear as wizened old women, hags share little in common with the humanoids they terrorize. They are hateful entities whose greatest joy lies in the corruption and ultimate destruction of anything good and virtuous. Whatever power created the first hags is lost to time, but numerous hag varieties have arisen over the ages, each with their own powers and abilities to spread pain and suffering.
