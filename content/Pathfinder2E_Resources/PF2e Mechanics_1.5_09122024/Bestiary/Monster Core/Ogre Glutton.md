---
title: "Ogre Glutton"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.P4VKDE1Cc4tMxCsa" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Ogre Glutton"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ogre Glutton"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +10, Survival: +6"
abilityMods: [6, -1, 4, -2, 0, -2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +14, __Ref__ +7, __Will__ +6"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]], [[Equipment/Leather Armor|Leather Armor]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+14 (reach 10 feet, sweep)\n__Damage__  1d12 + 8 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  1d8 + 8 piercing plus gluttons-feast,grab"

  - name: "Glutton's Feast"
    desc: "  If the ogre glutton damages a living creature with their jaws Strike, they gain 1d4 temporary Hit Points for 1 minute.\n\n[[Bestiary Effects/Effect_ Glutton's Feast|Effect: Glutton's Feast]]"

  - name: "Glutton's Rush"
    desc: "`pf2:2`  The ogre glutton Strides twice and makes a jaws Strike. If they damage a living creature with this Strike, the temporary Hit Points they receive from Glutton's Feast is increased to 2d4."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Small, 2d4+4 bludgeoning, Rupture 14\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ogre Glutton
creatures:
  - 1: Ogre Glutton
```



Ogre gluttons take the act of feeding to a horrific extreme, capable of extending their already cavernous mouths wide enough to gulp down a halfling. Stories of ogre gluttons being tricked into eating razor-edged shields or barrels filled with poisoned meat are common, but such tales are of little consolation to those who have been gobbled whole by these ravenous giants. In addition to their sadistic table manners, ogre gluttons have a disturbing knack for coming up with violent "games" that are little more than drawn-out torments, yet those who somehow manage to beat a glutton at the rules of their own game can often enrage the ogre enough that the resulting tantrum provides an opportunity for the captives to escape.

* * *

For many societies, ogres embody brutish, amoral violence and greedy cruelty. Standing 10 feet tall and densely muscled, ogres are usually as strong as they are vicious. The worst ogres are sadists, enjoying remorseless murder, torture, and violence in all of its forms. Although they prefer to vent their violent urges on other humanoids—the smaller the better—ogre captivity can end in a horrifying fate for anyone unlucky enough to fall within their meaty grasp: becoming dinner. But for all their creativity in inflicting pain, ogres often forget that their playthings lack their own robust fortitude and high pain tolerance, and many of their captives die sooner than the ogres might prefer. Meanwhile, those who manage to survive captivity in an ogre's larder often emerge with lasting mental scars. A captive able to keep their wits about them, however, can sometimes trick the brutes by promising treasure, more plentiful food sources, or other crude amusements, taking advantage of an ogre's often-limited intellect to engineer opportunities to escape or gain revenge.

Ogres are social creatures only in the most debased sense. They gather together in groups called families, though members are not always related by blood. The most powerful ogre in any family is the "boss"—usually the family's patriarch or matriarch—whom the other ogres in the family learn to quickly obey or risk being brutalized by the boss's loyal kin. Ogres lair in caves, crumbling ruins, or dilapidated shacks close enough to humanoid settlements or animal trails to make raiding easy. Their lairs are filthy and frequently contain all-too-recognizable evidence of their depravity, along with assorted treasures stolen from past captives.
