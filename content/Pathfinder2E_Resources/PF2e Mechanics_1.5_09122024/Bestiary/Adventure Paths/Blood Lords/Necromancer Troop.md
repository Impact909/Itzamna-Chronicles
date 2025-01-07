---
title: "Necromancer Troop"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tPAUrkcSwqG6Ps71" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Necromancer Troop"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Necromancer Troop"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; "
languages: "Common, Kelish, Necril, Osiriani"
skills:
  - name: "Skills"
    desc: "Arcana: +35, Athletics: +37, Intimidation: +33, Religion: +35"
abilityMods: [10, 5, 5, 8, 6, 6]
speed: 25 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +30, __Ref__ +30, __Will__ +35"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, troop defenses; __Weaknesses__ area damage 15, splash damage 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 180 (12 squares), 90 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Arcane Spontaneous Spells"
    desc: "DC 46, attack +38; __9th __ (2 slots) _[[Spells/Flense|Flense]]_, _[[Spells/Implosion|Implosion]]_; __8th __ (3 slots) _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Enervation|Enervation]]_, _[[Spells/Flense|Flense]]_; __7th __ (3 slots) _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Rouse Skeletons|Rouse Skeletons]]_\n__Cantrips__  __(10th)__ _[[Spells/Ancient Dust|Ancient Dust]]_, _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Torturous Trauma|Torturous Trauma]]_"

  - name: "Teach You a Lesson"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The members of the mob wildly swing their textbooks and supplies—primarily spellbooks and staves—in a chaotic attack at each enemy adjacent to the troop (DC 41 Reflex check). The damage depends on the number of actions.\n\n`pf2:1` 2d12+14 bludgeoning damage\n\n`pf2:2` 3d12+14 bludgeoning damage\n\n`pf2:3` 4d12+14 bludgeoning damage"

  - name: "Troop Movement"
    desc: "  Whenever the troop Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Troop Spellcasting"
    desc: "  When the necromancer troop Casts a Spell, their constituent members combine their efforts into casting a more powerful version of the spell than any one member could achieve alone. When Casting a Spell that has an area of a burst, cone, or line and doesn't have a duration, increase the area of that spell. Add 5 feet to the radius of a burst that normally has a radius of at least 10 feet (a burst with a smaller radius isn't affected). Add 5 feet to the length of a cone or line that's normally 15 feet long or smaller, and add 10 feet to the length of a larger cone or line."
 
```

```encounter-table
name: Necromancer Troop
creatures:
  - 1: Necromancer Troop
```




