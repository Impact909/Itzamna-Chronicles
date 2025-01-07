---
title: "Vescavor Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.g8UiEsq9t2Le2s7M" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/swarm
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Vescavor Swarm"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vescavor Swarm"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[fiend]]
trait_02: [[swarm]]
trait_03: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Chthonian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +10, Stealth: +13"
abilityMods: [-2, 5, 4, -3, 1, 1]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +15, __Will__ +9"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  mental,  precision,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, cold iron 5, holy 5, splash damage 5; __Resistances__ bludgeoning 5, piercing 5, slashing 2"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Devour All"
    desc: "`pf2:2`  The swarm eat away the very earth beneath their feet. The swarms Strides. All squares they occupy during their movement becomes difficult terrain. Any creatures they move through must succeed a DC 21 Reflex check save or fall [[Conditions/Prone|Prone]]."

  - name: "Maddening Gibbers"
    desc: "`pf2:2` (auditory,mental) Each stupefied creature in the swarm's space must attempt a DC 21 Will check saving throw as the swarm yammers the endless chorus of the Outer Rifts.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to Maddening Gibbers for 1 minute.\n\n**Success** The target is unaffected and is immune to Maddening Gibbers for 1 round.\n\n**Failure** The target becomes [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The target becomes confused for 1 round and can't target demons while confused in this way."

  - name: "Ravenous Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 3d6 piercing damage (DC 20 Fortitude check save). A creature that fails its save is also [[Conditions/Stupefied|Stupefied 1]] for 1 round."
 
```

```encounter-table
name: Vescavor Swarm
creatures:
  - 1: Vescavor Swarm
```



The most common and numerous vescavors are the raving swarms. If left alone and unchecked, many believe they would eventually consume themselves once everything else in the immediate vicinity was consumed. What is even more vexing than their hunger is their song. While it sounds like gibberish at first, once bitten, the song will drive people into chaos.

* * *

These gluttonous green vermin travel from the Outer Rifts in an endless search for food. Along the way, these acrid wasps devour everything in sight. Not even the ground itself is spared from their appetite. While any single vescavor is no problem, they travel in swarms to overwhelm anything trying to stop them. In a truly unfortunate situation, several swarms will be gathered and led by a vescavor queen. These queens, while fearsome on their own, can drive their brood into a feeding rage unlike any other. Swarms found without a queen are directionless, destroying anything around them indiscriminately.

Whenever a vescavor swarm is not eating, it gibbers mind-numbing songs from the fiends' dark world. Adapted to the shrieking jungles of their home plane, they issue a call that confuses and corrupts mortals.

Philosophers who ponder the Outer Rifts often conjecture as to what kind of soul forms a vescavor. The idea of insect souls being sent to the Outer Rifts is often laughed off but never entirely dismissed. Some assume that they are demons of gluttony, plain and simple. Some of the more creative explanations of vescavor origins posit that all the bits of soul eaten up by attacking demons are what coalesce into these endless swarms. Such an explanation would account for how these endlessly feeding demons also seem to be endless in number.
