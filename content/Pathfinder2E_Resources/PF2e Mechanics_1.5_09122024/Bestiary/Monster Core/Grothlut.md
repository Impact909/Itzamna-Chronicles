---
title: "Grothlut"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p22qRtGSdcNQNehh" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Grothlut"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Grothlut"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[mindless]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11"
abilityMods: [4, -2, 4, -5, 0, -3]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +5, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  acid,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Disgusting Demise"
    desc: " (acid,poison) When the grothlut is reduced to 0 Hit Points, its digestive organs rupture, unleashing alchemical acid and poison upon all creatures in a 30-foot emanation. Each creature in the area must succeed at a DC 19 Fortitude check save or take 2d6 acid damage and become [[Conditions/Sickened|Sickened 1]] (double damage and [[Conditions/Sickened|Sickened 2]] on a critical failure)."

  - name: "Piteous Moan"
    desc: " (auditory,aura,concentrate,emotion,mental,occult) 60 feet.\n\nEach nongrothlut creature that enters or starts its turn within the area must succeed at a DC 17 Will check saving throw or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure). The creature then becomes temporarily immune for 1 minute.\n\nThe grothlut can Dismiss this aura.\n\nA grothlut usually does not begin moaning until it senses the presence of a non-grothlut creature, and it usually stops once it doesn't sense any more such creatures."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile)\n__Damage__  1d10 + 8 slashing"

  - name: "**Ranged** `pf2:1` Digestive Spew"
    desc: "+7 (acid, range increment 15 feet, splash)\n__Damage__  2d6 acid 1d6 acid"
 
```

```encounter-table
name: Grothlut
creatures:
  - 1: Grothlut
```



Sluglike abominations, grothluts are grotesque dregs of the fleshwarping process. While their head and torso are vaguely humanoid, their arms are rubbery and move awkwardly at their sides. Wretched creatures, they moan piteously when other creatures are near, perhaps as the last remnants of their mind pleads to be free from their horrid warped form.

Many fleshwarpers consider the grothlut to be a failure of a creation, as the transformation all but stamps out consciousness. Others disagree, arguing that warping the creature's mind makes it all the more useful, since it becomes pliable and easy to herd. Cultists of Haagenti typically use grothluts as guardians that slowly patrol the edges of their enclaves. Once in position, grothluts can be used as crude shock troops, unleashed to soften enemy forces before more valuable warriors wade in and cut down the enemies who have been nauseated by the grothluts' exploded organs and flesh.

* * *

Magical mishaps, divine curses, and untested technology are all capable of wreaking drastic transformations on the body, and are all rampant on the world of Golarion and beyond. Creatures that have undergone changes so drastic they no longer can be considered the same ancestry as they were before are known as fleshwarps. These beings are rare, and their unsettling appearance often provokes horrified responses from other people.

Some creatures revel in the total degradation of their defeated foes through fleshwarping. Though the technique was originally taught to mortals by the demon lord Haagenti, mortals have spent eons modifying and perfecting the method. Fleshcrafters torture their enemies in vats of churning magical reagents, reshaping their flesh and psyche alike into horrid and monstrous things.
