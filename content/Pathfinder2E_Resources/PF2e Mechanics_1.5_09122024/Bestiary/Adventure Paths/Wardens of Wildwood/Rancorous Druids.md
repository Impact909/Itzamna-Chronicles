---
title: "Rancorous Druids"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.g1aO95AxQpSTJZ5z" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Rancorous Druids"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Rancorous Druids"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; "
languages: "Common, Fey, Wildsong"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Intimidation: +21, Religion: +22"
abilityMods: [7, 2, 6, 2, 5, 4]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +17, __Will__ +22"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195, troop defenses; __Weaknesses__ area damage 15, splash damage 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Collective Swarm"
    desc: "`pf2:2`  The rancorous druids collectively transform into a swarm of Tiny insects. They cast [[Spells/Swarm Form|Swarm Form]] heightened to 6th rank, but the duration is 1 hour instead of 5 minutes."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 130 (12 squares), 65 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Primal Spontaneous Spells"
    desc: "DC 27, attack +19; __6th __ (2 slots) _[[Spells/Acid Grip|Acid Grip]]_, _[[Spells/Slow|Slow]]_; __5th __ (3 slots) _[[Spells/Fireball|Fireball]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Frostbite|Frostbite]]_, _[[Spells/Light|Light]]_"

  - name: "Rituals"
    desc: "_Blight (Doesn't Require Secondary Casters)_"

  - name: "Troop Movement"
    desc: "  Whenever the troop Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Troop Spellcasting"
    desc: "  When the rancorous priesthood Casts a Spell, their constituent members combine their efforts into casting a more powerful version of the spell than any one member could achieve alone.\n\nWhen Casting a Spell that has an area of a burst, cone, or line and doesn't have a duration, increase the area of that spell. Add 5 feet to the radius of a burst that normally has a radius of at least 10 feet (a burst with a smaller radius is not affected). Add 5 feet to the length of a cone or line that is normally 15 feet long or smaller, and add 10 feet to the length of a larger cone or line."

  - name: "Wild Swing"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The members of the mob wildly swing their weapons-primarily greataxes-in a chaotic attack at each enemy adjacent to the troop (DC 27 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d12+2 slashing damage\n\n`pf2:2` 2d12+9 slashing damage\n\n`pf2:3` 3d12+9 slashing damage"
 
```

```encounter-table
name: Rancorous Druids
creatures:
  - 1: Rancorous Druids
```


Variant rancorous priesthood

Followers of Rovagug must usually conceal their devotion to the Rough Beast, hiding in remote cave complexes or abandoned ruins; but they emerge from these strongholds when they sense weakness, gathering together into a destructive, homicidal mob to hunt down high-ranking priests of rival deities or slaughter entire towns. Alternatively, if their hidden bolthole is compromised, a mob of Rovagug's faithful might emerge-not hoping to save themselves, but intent only on taking their enemies with them as they die.
