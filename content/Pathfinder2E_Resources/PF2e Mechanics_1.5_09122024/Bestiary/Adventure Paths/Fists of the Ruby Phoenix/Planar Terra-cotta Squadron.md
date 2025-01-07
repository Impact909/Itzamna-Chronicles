---
title: "Planar Terra-cotta Squadron"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HzgjPaD4vNlSLSeI" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Planar Terra-cotta Squadron"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Planar Terra-cotta Squadron"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[troop]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; "
languages: "Tien; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +20"
abilityMods: [8, 4, 8, 1, 3, 4]
speed: 25 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 37
armorclass:
  - name: AC
    desc: "37 39 with shields raised; __Fort__ +26, __Ref__ +23, __Will__ +24"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, troop defenses (200/100); __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ bludgeoning 15, area damage 20, splash damage 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Steel Shield|Steel Shield]]"
  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Planar Step"
    desc: "`pf2:1` (teleportation) The planar terra-cotta squadron momentarily moves beneath the Material Plane, instantly transporting itself to a location within 90 feet. The squadron can't use Planar Step again for 1d4 rounds"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 200 (12 squares), 100 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Aim as One"
    desc: "`pf2:2`  The troop launches a ranged attack in the form of a 10-foot burst within 100 feet that deals 3d8+13 damage (DC 33 Reflex check save). When the garrison is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Raise Shields"
    desc: "`pf2:1`  The troop raises steel shields, with the effects of [[Actions/Raise a Shield|Raise a Shield]]."

  - name: "Strike as One"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The garrison makes a melee attack against each enemy within 5 feet (DC 30 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d8 slashing damage.\n\n`pf2:2` 3d8+13 slashing damage.\n\n`pf2:3` 4d8+16 slashing damage."

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Planar Terra-cotta Squadron
creatures:
  - 1: Planar Terra-cotta Squadron
```


Variant terra-cotta soldier garrison

Terra-cotta warriors guard the tombs of ancient rulers, where they stand vigil, animating only when intruders break in to pilfer riches or defile the tomb itself. Each warrior is meticulously crafted from clay and given unique features.

* * *

These constructed warriors can work together as a trained group to repel intruders.
