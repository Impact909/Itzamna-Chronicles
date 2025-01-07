---
title: "Toilforged Sentinel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9oz2YS2l06AGuJqh" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2e/creature/type/soulbound
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Toilforged Sentinel"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Toilforged Sentinel"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[construct]]
trait_02: [[evil]]
trait_03: [[soulbound]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +13, Droskar Lore: +15"
abilityMods: [6, 3, 4, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +13, __Will__ +12"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ cold 6, water 11; __Resistances__ physical 10 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "Find the Faithless (Imprecise) 60 Feet"
    desc: " (magical) The toilforged sentinel detects the presence of creatures that don't worship Droskar within 60 feet as an imprecise sense."

abilities_mid:
  - name: ""
  - name: "Exertion Aura"
    desc: " (aura,divine,mental) 20 feet. A toilforged sentinel saps the energy of nearby creatures. Each round a living creature begins its turn in the aura, it must attempt a DC 22 Fortitude check save. On a failure, the creature takes 1d6 mental damage (2d6 on a critical failure) and becomes [[Conditions/Fatigued|Fatigued]]. This fatigue ends as soon as the creature remains outside of the aura for 1 minute."

  - name: "Vulnerability to Exorcism"
    desc: "  When a toilforged sentinel fails a saving throw against a spell that would banish tormented spirits or manipulate souls, such as [[Spells/Banishment|Banishment]] or [[Spells/Seize Soul|Seize Soul]], instead of experiencing the listed effect, it takes 10 damage per spell rank."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Grasping Claw"
    desc: "+16 (grapple, magical, reach 30 feet, tethered)\n__Damage__  2d8 + 11 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Hammer"
    desc: "+20 (magical, reach 15 feet, shove)\n__Damage__  2d12 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Flaming Cannon"
    desc: "+17 (range 200 feet)\n__Damage__  1d6 fire 3d10 bludgeoning"

  - name: "Droskar's Grasp"
    desc: "  The toilforged sentinel can Grab a creature using only one hand. It can move normally with a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its claw, carrying the creature along. If it has a creature grabbed in this way, it can't use its claw Strike. It activates Swallow Whole with its claw by depositing a grabbed creature into its soul furnace."

  - name: "Soul Furnace"
    desc: "  The toilforged sentinel has a cage incorporated into its central body, filled with profane fire and called a soul furnace. As long as a toilforged sentinels' soul furnace contains a living creature, the toilforged sentinel is [[Conditions/Quickened|Quickened]] (Stride or Strike)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d6 fire and 3d6 void, Rupture 21\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Toilforged Sentinel
creatures:
  - 1: Toilforged Sentinel
```



Toilforged sentinels are intelligent war machines painstakingly constructed from iron, steel, and other metals over the course of a full year. With twin treads, a central cage filled with eternal flames, and numerous weapons (including a hammer, cannon, and grasping claw capable of snatching up foes), a toilforged sentinel is an intimidating sight. Creatures consumed by a sentinel's flames become captives, their souls eternally bound to the flames, powering the device. Such souls are freed upon the sentinel's destruction.

## Salvation

Toilforged sentinels are religious constructs created to destroy heretics: those who refuse to worship Droskar. They take orders only from the clergy of Droskar and find particular satisfaction from consuming worshippers of Torag and other dwarven deities.
