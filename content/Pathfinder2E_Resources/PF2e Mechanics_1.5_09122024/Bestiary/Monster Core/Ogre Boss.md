---
title: "Ogre Boss"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6u86JEoK1i2RtEyl" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Ogre Boss"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ogre Boss"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Intimidation: +16, Stealth: +11"
abilityMods: [7, 0, 4, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +12, __Will__ +15"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "6x [[Equipment/Javelin|Javelin]], [[Equipment/Ogre Hook|+1 Ogre Hook]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ogre Hook"
    desc: "+19 (deadly d10, reach 10 feet, trip)\n__Damage__  1d10 + 11 piercing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+12 (thrown 30 ft.)\n__Damage__  1d6 + 11 piercing"

  - name: "Bellowing Command"
    desc: "`pf2:1` (auditory,emotion,fear,linguistic,mental) The ogre boss issues a command to hasten their fellows. Each ogre ally who hears and understands this command becomes [[Conditions/Quickened|Quickened]] until the end of that ally's next turn but can use the extra action only to Step or Stride."

  - name: "Sweeping Hook"
    desc: "`pf2:r`  **Trigger** The ogre boss successfully [[Actions/Trip|Trips]] a creature using an ogre hook\n* * *\n\n**Effect** The ogre boss makes an ogre hook Strike against the creature they tripped."
 
```

```encounter-table
name: Ogre Boss
creatures:
  - 1: Ogre Boss
```



In ogre society, might makes more than right—it makes the rules. The strongest or most violent ogre in a family (in most cases, this is the same ogre) is invariably that family's boss. Quick to hook fallen foes on their weapons, even other ogres fear the repercussions of displeasing an ogre boss. When an ogre boss barks out commands, the other members of the family move quickly to obey.

* * *

For many societies, ogres embody brutish, amoral violence and greedy cruelty. Standing 10 feet tall and densely muscled, ogres are usually as strong as they are vicious. The worst ogres are sadists, enjoying remorseless murder, torture, and violence in all of its forms. Although they prefer to vent their violent urges on other humanoids—the smaller the better—ogre captivity can end in a horrifying fate for anyone unlucky enough to fall within their meaty grasp: becoming dinner. But for all their creativity in inflicting pain, ogres often forget that their playthings lack their own robust fortitude and high pain tolerance, and many of their captives die sooner than the ogres might prefer. Meanwhile, those who manage to survive captivity in an ogre's larder often emerge with lasting mental scars. A captive able to keep their wits about them, however, can sometimes trick the brutes by promising treasure, more plentiful food sources, or other crude amusements, taking advantage of an ogre's often-limited intellect to engineer opportunities to escape or gain revenge.

Ogres are social creatures only in the most debased sense. They gather together in groups called families, though members are not always related by blood. The most powerful ogre in any family is the "boss"—usually the family's patriarch or matriarch—whom the other ogres in the family learn to quickly obey or risk being brutalized by the boss's loyal kin. Ogres lair in caves, crumbling ruins, or dilapidated shacks close enough to humanoid settlements or animal trails to make raiding easy. Their lairs are filthy and frequently contain all-too-recognizable evidence of their depravity, along with assorted treasures stolen from past captives.
