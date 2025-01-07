---
title: "Dancing Night Parade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8M5PQVmJKrKPxTXy" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/spirit
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Dancing Night Parade"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Dancing Night Parade"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[spirit]]
trait_03: [[troop]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +33, Deception: +37, Performance: +37, Society: +32, Dancing Lore: +32"
abilityMods: [8, 7, 5, 5, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, __Will__ +34"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450, Thresholds 300 (12 squares), 150 (8 squares); __Weaknesses__ bludgeoning 15, area damage 20, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Riotous Parade"
    desc: "  60 feet. The night parade sweeps up those nearby in a riotous celebration. All creatures in the aura must attempt a DC 39 Will check save. The target is then temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The target is unafflicted.\n\n**Success** The target laughs and dances. It can't use reactions as long as it stays in the area, and if it attempts to use a concentrate action, it must succeed at a DC 5 Flat check check; on a failure, the action is lost.\n\n**Failure** As success, except the target is also [[Conditions/Slowed|Slowed 1]] while in the area.\n\n**Critical Failure** As success, except the target is also slowed 1 while in the area and the flat check DC is 10."

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square enters difficult terrain, the extra movement cost applies to the whole troop."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 300 (12 squares), 150 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Seiya! Soiya!"
    desc: "`pf2:2` (emotion,mental,sonic) The night parade shouts a series of energetic call-and-responses, dealing 3d10 sonic damage and 4d6 mental damage to all creatures in a 10-foot burst within 20 feet (DC 41 Will check save). If the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Wasshoi! Wasshoi!"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The night parade dances with wild abandon, unintentionally striking nearby creatures. It deals damage to each adjacent creature (DC 41 Reflex check save), and any creature that fails its save is pushed 10 feet in any direction as the night parade bounces it overhead. The damage depends on the number of actions.\n\n`pf2:1` 1d10+7 bludgeoning damage\n\n`pf2:2` 4d10+14 bludgeoning damage\n\n`pf2:3` 6d10+14 bludgeoning damage"
 
```

```encounter-table
name: Dancing Night Parade
creatures:
  - 1: Dancing Night Parade
```




