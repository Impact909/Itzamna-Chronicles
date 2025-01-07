---
title: "Pelegox Cube"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MP8KsZtPWQezmX1z" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Pelegox Cube"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Pelegox Cube"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[elemental]]
trait_02: [[metal]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; "
languages: "Talican; telepathy 30 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +21, Crafting: +20, Diplomacy: +21"
abilityMods: [4, 7, 6, 5, 3, 4]
speed:  fly 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +24, __Will__ +18"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, 140 (12 squares), 70 (8 squares); __Weaknesses__ area damage 15, splash damage 10; __Resistances__ electricity 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 30 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Metalsense"
    desc: "  A pelegox cube can sense metal creatures and objects as an imprecise sense."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Entrancing Shapes"
    desc: "`pf2:2` (mental,occult,visual) The pelegox cube rapidly shifts, creating a display of seemingly impossible geometric patterns. Creatures in a 60-foot cone take 9d6 mental damage (DC 29 Will check save). A creature that fails is also [[Conditions/Fascinated|Fascinated]] with the pelegox cube and [[Conditions/Stupefied|Stupefied 1]] for 1 minute."

  - name: "Scrambled Strike"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The pelegox cube rearranges to create jutting spikes, attacking each enemy within 10 feet (DC 27 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d6 piercing damage\n\n`pf2:2` 3d6+10 piercing damage\n\n`pf2:3` 5d6+10 piercing damage"

  - name: "Shard Volley"
    desc: "`pf2:2`  The pelegox cube magnetizes fragments of metal at range. This is a 10-foot burst within 30 feet that deals 2d6+10 piercing damage (DC 27 Reflex check save). When the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Troop Movement"
    desc: "  Whenever the troop Flies, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the entire troop."
 
```

```encounter-table
name: Pelegox Cube
creatures:
  - 1: Pelegox Cube
```



Pelegoxes are beings of condensed magnetic energy that fashion bodies for themselves using their surroundings. Though a pelegox's true form is a spherical core, it pulls metal fragments of various shapes and sizes to form a polyhedral shell. Though pelegoxes might develop preferences for a particular form when at rest, they continue to look for new configurations to call their own, happiest when they can experiment with endless possibilities, even if it means dismantling other metallic entities.

These piecemeal creatures move by a combination of magnetic levitation and propulsion, and when that doesn't work, by continuously piercing the ground and shifting their weight forward, looking almost like moving caltrops. Over time, the magnetic signature of a pelegox becomes visible, etched into its body in patterns of concentric lines. These unique designs make it possible to distinguish between individual pelegoxes even when their surface has eroded.

Pelegoxes are quick to form relationships with others of their kind. They delight in combining their individual bodies into ever larger, more elaborate structures and patterns. As such, it is rare to find a pelegox on their own—they prefer to travel in a clustered form.
