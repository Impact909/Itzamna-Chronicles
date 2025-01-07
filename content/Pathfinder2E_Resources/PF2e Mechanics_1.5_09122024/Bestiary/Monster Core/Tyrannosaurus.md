---
title: "Tyrannosaurus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.D7RpVyk4OtUFIrZd" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Tyrannosaurus"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tyrannosaurus"
level: "Creature 10"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +24"
abilityMods: [8, 1, 5, -4, 3, 0]
speed: 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +15, __Will__ +19"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 (deadly d12, reach 20 feet)\n__Damage__  2d12 + 12 piercing plus grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+22 (reach 15 feet)\n__Damage__  2d10 + 12 bludgeoning"

  - name: "Fling"
    desc: "`pf2:1`  **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] in the tyrannosaurus's jaws\n* * *\n\n**Effect** The tyrannosaurus flings the creature into the air up to 10 feet up from its mouth and 20 feet away. The creature falls 25 feet (assuming the tyrannosaurus flings it as high as it can) and takes falling damage accordingly. If the flung creature lands on another creature, the creature it lands on takes the same amount of bludgeoning damage. The creature being landed on can attempt a DC 23 Reflex check save."

  - name: "Pin Prey"
    desc: "`pf2:r`  **Trigger** The tyrannosaurus critically hits a Large or smaller foe with its foot\n* * *\n\n**Effect** The creature struck by the foot is knocked [[Conditions/Prone|Prone]] and held in place. As long as the tyrannosaurus doesn't move from its position, the pinned creature is [[Conditions/Grabbed|Grabbed]].\n\nA tyrannosaurus gains a +2 circumstance bonus to attack a creature it has pinned in this manner but can only Swallow Whole if that creature is grabbed with its jaws."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 3d6+8 bludgeoning damage, Rupture 26\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 29 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tyrannosaurus
creatures:
  - 1: Tyrannosaurus
```



Widely regarded as the king of the dinosaurs, the tyrannosaurus is a massive predator with a wide mouth filled with viciously sharp teeth. Some tribes of giants have even trained tyrannosauruses as mounts or beasts of war.

* * *

Remnants from the world's primeval era, these enormous reptilian animals still exist in large numbers in remote wildernesses or underground in magical Darklands caverns. Lizardfolk, orcs, giants, and other humanoids who live near dinosaurs use the animals as mounts, guards, or hunting beasts. Occasionally, rich nobles will collect dinosaurs to display them in menageries, which almost inevitably leads to cast-offs being nursed back to health by druids and other champions of nature. When dinosaurs establish themselves in regions outside their normal habitats, it's often the result of a large collection being released.
