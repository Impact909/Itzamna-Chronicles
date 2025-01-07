---
title: "Animated Wine Vessel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ScQXa70eSpOUMjO1" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Animated Wine Vessel"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Animated Wine Vessel"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17"
abilityMods: [4, 0, 4, -5, 0, -5]
speed: 15 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 19
armorclass:
  - name: AC
    desc: "19 17 when broken; construct armor; __Fort__ +11, __Ref__ +7, __Will__ +7"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Hardness__ 4; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Actor.LCpPQlFHJ9feVhlS.Item.iuA961D6giH9Ci1G|Construct Armor (Hardness 4)]]"
    desc: "  Like normal objects, an animated wine vessel has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once an animated wine vessel is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 17."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (magical)\n__Damage__  2d8 + 4 bludgeoning plus grab"

  - name: "Spit Wine"
    desc: "`pf2:2` (water) The wine vessel opens its mouth and blows a stream of wine in a 15-foot line, dealing 2d8 bludgeoning damage (DC 19 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d8+4 bludgeoning plus Wine-Soaked, Rupture 10\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Wine-Soaked"
    desc: "  When a creature ends its turn Swallowed Whole by the animated wine vessel, it must succeed at a DC 19 Fortitude check save or become [[Conditions/Sickened|Sickened 1]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Animated Wine Vessel
creatures:
  - 1: Animated Wine Vessel
```



A beautiful wine vessel presents a mark of status among drinkers, to say nothing of an animated one that pours the wine on its own. Although normally harmless servants, these vessels will just as quickly follow instructions to swallow intruders and drown them in strong wine.
