---
title: "Animated Fireplace"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iyDPRUoPAPl6jgZY" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Animated Fireplace"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Animated Fireplace"
level: "Creature 5"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [6, -2, 5, -5, 0, -5]
speed: 15 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 24
armorclass:
  - name: AC
    desc: "24 (20 when broken); construct armor; __Fort__ +15, __Ref__ +6, __Will__ +8"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Hardness__ 7; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 7)"
    desc: "  Like normal objects, the animated fireplace has Hardness. This Hardness reduces any damage the fireplace takes by 7. Once the animated fireplace is reduced to fewer than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 20."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hearth"
    desc: "+15 (magical)\n__Damage__  2d8 + 6 bludgeoning plus grab 1d6 fire plus grab"

  - name: "Bellow Soot"
    desc: "`pf2:2`  The animated fireplace coughs out a cloud of soot, filling a 20-foot emanation; creatures within the soot are [[Conditions/Concealed|Concealed]], and creatures outside the cloud are concealed to creatures within it. Creatures that begin their turn within the cloud must succeed at a DC 19 Fortitude check save or be [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure); creatures immune to inhaled effects automatically succeed at this save. The fireplace can't Bellow Soot again for 1d4 rounds."

  - name: "Fan the Flames"
    desc: "`pf2:3`  The animated fireplace releases a gout of flame in a 30-foot cone that deals 3d6 fire damage (DC 22 Reflex check)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d6+5 fire, Rupture 5\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Animated Fireplace
creatures:
  - 1: Animated Fireplace
```


Variant animated furnace

Many animated objects have useful functions but become dangers when uncontrolled.
