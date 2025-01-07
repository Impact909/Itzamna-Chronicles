---
title: "Helicoprion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FcHXEYmSqVklpIc6" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Helicoprion"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Helicoprion"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Scent (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +24, Stealth: +17, Survival: +15"
abilityMods: [8, 3, 6, -4, 3, -1]
speed:  swim 60 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +19, __Will__ +16"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230"
abilities_top:
  - name: ""

  - name: "Blood Scent"
    desc: "  The helicoprion can smell blood in the water from up to 1 mile away."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 (reach 10 feet)\n__Damage__  2d10 + 12 slashing plus improved-grab 1d8 bleed plus improved-grab"

  - name: "Deshell"
    desc: "`pf2:1` (attack) **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in the helicoprion's jaws\n* * *\n\n**Effect** The shark rips into the creature dealing 3d10 slashing damage (DC 26 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 2d10+10 bludgeoning, Rupture 22\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Helicoprion
creatures:
  - 1: Helicoprion
```




