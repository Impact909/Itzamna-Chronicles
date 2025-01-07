---
title: "Alchemical Horror"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.eP9cmtDwxUi8RKlH" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Alchemical Horror"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Alchemical Horror"
level: "Creature 21"

alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[evil]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +39"
abilityMods: [10, 5, 9, -3, 0, 0]
speed: 20 feet,  swim 50 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +37, __Ref__ +32, __Will__ +27"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  disease,  poison,  sickened; __Resistances__ acid 20, precision 20"
abilities_top:
  - name: ""

  - name: "Alchemical Reaction"
    desc: "  **Trigger** The alchemical horror takes damage from an alchemical bomb\n* * *\n\n**Effect** The volatile substances that compose the alchemical horror froth outward as they react with the bomb. The bomb's full effects affect creatures in every space within 15 feet of the alchemical horror, and splash damage affects creatures 5 feet beyond that."

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 30 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (acid, magical, reach 10 feet)\n__Damage__  4d8 + 18 bludgeoning plus grab 2d6 acid plus grab"

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+37 (acid, magical, reach 15 feet)\n__Damage__  4d10 + 18 bludgeoning 2d6 acid"

  - name: "Alchemical Torrent"
    desc: "`pf2:2` (acid,primal) The alchemical horror spews a torrent of alchemical fluids in a 30-foot cone that deals 20d6 acid damage to creatures in the area (DC 43 Reflex check save).\n\nThe alchemical horror can't use this ability again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 4d12+18 bludgeoning damage, Rupture 40\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Alchemical Horror
creatures:
  - 1: Alchemical Horror
```




