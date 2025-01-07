---
title: "Bregdi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pFQU0SQ29g0tSeaD" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Bregdi"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Bregdi"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +21, Stealth: +17, Survival: +18"
abilityMods: [6, 4, 4, -4, 3, -3]
speed: 20 feet,  swim 40 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +18, __Will__ +17"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Partial Amphibian"
    desc: "  The bregdi can breathe air for up to 10 minutes, or up to an hour so long as its skin remains wet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (reach 10 feet)\n__Damage__  2d12 + 8 piercing"

  - name: "**Melee** `pf2:1` Hook Claw"
    desc: "+21 (agile, reach 10 feet)\n__Damage__  2d8 + 8 piercing plus grab"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  50 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The bregdi tries to capsize an adjacent aquatic vessel of its size or smaller. It must succeed at an Athletics check with a DC of 35 (reduced by 5 for each size smaller the vessel is than the bregdi) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d8+7 bludgeoning damage, Rupture 18\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Tug"
    desc: "`pf2:1`  The bregdi pulls a creature it can reach or a creature holding something it can reach (such as a fishing line in the water).\n\nThe bregdi attempts an Athletics check check against the creature's Fortitude DC. On a success, it pulls the creature into an adjacent space. On a critical success, the bregdi can also make a jaws Strike against the creature pulled into an adjacent space."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Bregdi
creatures:
  - 1: Bregdi
```




