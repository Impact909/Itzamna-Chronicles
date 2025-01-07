---
title: Hungry Cottage
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #182: Graveclaw
aliases: "Actor.J9bBBSP2hJUptbQy" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Hungry Cottage"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 15
sourcebook: "_Pathfinder #182: Graveclaw_"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Iron Taviah's cottage comes to life and tries to eat everyone in it. The hazard is divided into three areas: the basement becomes the cottage's stomach; the stairs act as the cottage's throat, becoming a steep, slippery incline that is greater difficult terrain; and the ground floor is the inside of the cottage's mouth. Creatures within the cottage can move around within it but can't exit without pulling the mouth open or slipping out while its teeth gnash. Characters who successfully escape the cottage are safe from the hazard."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "The hungry cottage can't be damaged or disabled, but the danger in each area can be temporarily mitigated. In the stomach: DC 17 Athletics check (trained) to [[Actions/Climb|Climb]] atop the hoarded belongings and avoid contact with the acidic walls or floor for 1 round, or DC 25 Crafting check (expert) as a 2-action activity to concoct an alchemical antacid that neutralizes acid damage dealt by the stomach for 1d4 rounds. In the throat: DC 23 Athletics check (trained) to hold the throat open for one round, allowing all characters in the stairs to use a Reflex save result one degree of success greater than their roll to avoid being pushed into the stomach, or DC 23 Nature check or Survival as a 2-action activity to ease the throat's contractions and provide the same effect for 1d4 rounds. In the mouth: DC 22 Athletics check to [[Actions/Force Open|Force Open]] a window or a door and forcibly expel one creature that's within 10 feet of an exit from the cottage, or DC 25 Athletics check (expert) as a 2-action activity to jam furniture in place that prevents the teeth from gnashing for 1d4 rounds and allows anyone in the cottage to move from it during that time."
attacks:
  - name: ""

  - name: "The Cottage Hungers"
    desc: "`pf2:r` **Trigger** Iron Taviah is defeated in the cottage basement\n* * *\n\n**Effect** The basement floor absorbs Iron Taviah, and the cottage transforms into a hungry, semi-animate creature. The cottage rolls initiative."

  - name: "Acidic Assault"
    desc: "action (acid) The walls and floor of the stomach steam with digestive juices; all creatures in contact with these surfaces take 2d8+4 acid damage (DC 24 Fortitude check)."

  - name: "Gnashing Portal"
    desc: "action Creatures on the cottage's main floor are ground down as massive teeth appear from the floor and ceiling, gnash, and recede into the architecture, dealing 2d8+4 bludgeoning damage. Creatures in this area must attempt a DC 24 Reflex check save.\n* * *\n\n**Critical Success** The creature takes no damage and, if within 10 feet of an exit on the ground floor, can choose to exit the cottage.\n\n**Success** The creature takes half damage and, if within 10 feet of an exit on the ground floor, can attempt to escape the cottage as the teeth retract by attempting a DC 24 Reflex check save. On a success, the creature exits the cottage; on a critical failure, the creature falls [[Conditions/Prone|Prone]].\n\n**Failure** The creature takes full damage and is knocked prone.\n\n**Critical Failure** The creature takes double damage, is knocked prone, and is [[Conditions/Stunned|Stunned 1]]."

  - name: "Swallowing Staircase"
    desc: "action Muscular swallowing contractions force creatures down the stairs and into the stomach. Creatures on the stairs must attempt a DC 24 Reflex check save or be pushed 15 feet down the stairs (and across the basement floor with any excess forced movement if they're pushed to the bottom of the stairs). Creatures who critically fail this Reflex save fall [[Conditions/Prone|Prone]] at the end of this forced movement."

  - name: "Routine"
    desc: "The cursed cottage uses 3 actions: Acidic Assault in the stomach, Swallowing Staircase in the throat, and Gnashing Portal in the mouth (in that order). Checks to disable the areas might prevent these actions for a brief time."
  - name: "Reset"
    desc: "Once no creatures remain in the cottage, the hazard resets and returns to a normal cottage. The stairs and the basement are gone, however, as is Iron Taviah's body."
```

```encounter-table
name: Hungry Cottage
creatures:
  - 1: Hungry Cottage
```

