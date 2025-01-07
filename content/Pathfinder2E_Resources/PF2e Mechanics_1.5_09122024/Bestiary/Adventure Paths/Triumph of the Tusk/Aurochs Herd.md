---
title: "Aurochs Herd"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rfr4F87Ro2uYOGCp" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Aurochs Herd"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Aurochs Herd"
level: "Creature 7"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Survival: +14"
abilityMods: [6, 2, 6, -5, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +12, __Will__ +12"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (16 squares); Thresholds 100 (12 squares), 50 (8 squares); __Weaknesses__ area damage 10, splash damage 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Stampede"
    desc: "`pf2:r`  **Trigger** The aurochs herd's Hit Points drops below a threshold\n* * *\n\n**Effect** The aurochs herd uses Trample but moves in a direction directly opposite of the threat; the DC increases to DC 27 Reflex check and the bludgeoning damage increases to 4d6+6 bludgeoning ([[Conditions/Prone|Prone]] creatures take 5d6+6 bludgeoning damage instead)."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Circle of Horns"
    desc: "`pf2:1`  The largest males in the herd form a ring of protection around the more vulnerable members. The herd gains a +2 circumstance bonus to AC until the start of its next turn."

  - name: "Horn"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The aurochs herd makes a melee attack against each enemy within 5 feet (DC 22 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8+8 piercing damage\n\n`pf2:2` 2d8+10 piercing damage\n\n`pf2:3` 2d10+9 piercing damage"

  - name: "Puncturing Charge"
    desc: "`pf2:2`  **Requirements** The aurochs herd has formed a Circle of Horns\n* * *\n\n**Effect** The aurochs herd Strides to an enemy and makes a Horn Strike, dealing 3d8+8 piercing damage plus [[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, hoof (3d6+6 bludgeoning damage; [[Conditions/Prone|Prone]] creatures take 4d6+6 bludgeoning damage), DC 25 Reflex check save (any creature that fails its save is knocked prone).\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Troop Movement"
    desc: "  Whenever the aurochs herd Strides, it first Forms Up as a free action to condense into a 20-by-20-foot area (minus any missing squares,) and then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any of the herd's squares enter difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Aurochs Herd
creatures:
  - 1: Aurochs Herd
```



Massive aurochs herds roam the badlands of Belkzen, grazing upon the limited grass and plant life dispersed throughout the wasteland's valleys. Having adapted to the arid mountain terrain, aurochs herds eat a much more diverse diet of scrub and brush than their domesticated counterparts as they steadily migrate down the Flood Road. The herds show little patience for predators and demonstrate a preference for charging threats with their razor-sharp horns. Bull aurochs display natural instincts to strategically protect other, weaker members of the herd, often surprising intruders with their coordinated tactics and defensive maneuvers.

## Unlikely War Beasts

Followers of Zagresh have a history of capturing wild aurochs for use in magical experiments, taking the strongest of a herd to make the beasts even larger and more aggressive. Once the aurochs have been transformed into monstrous goliaths, their captors bard them with armored plates and magical weapons that complement their horns. In battle, these aurochs are utilized to pull siege weapons, break through enemy defenses, and trample frontline forces.
