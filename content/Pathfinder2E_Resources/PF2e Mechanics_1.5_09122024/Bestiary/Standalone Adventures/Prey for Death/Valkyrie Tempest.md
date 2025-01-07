---
title: "Valkyrie Tempest"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3BrN8RFIel5F6WEf" 
tags:
  - pf2e/creature/type/aesir
  - pf2e/creature/type/monitor
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Valkyrie Tempest"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Valkyrie Tempest"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[aesir]]
trait_02: [[monitor]]
trait_03: [[troop]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Common, Jotun; Ravenspeaker, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +30, Diplomacy: +29, Intimidation: +29, Religion: +28"
abilityMods: [9, 6, 6, 4, 5, 6]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +24, __Ref__ +20, __Will__ +23"
hp: 312
health:
  - name: ""
  - name: HP
    desc: "312, Thresholds 208 (12 squares), 104 (8 squares);; __Weaknesses__ area damage 19, splash damage 10; __Resistances__ electricity 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 208 (12 squares), 104 (8 squares)\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 35, attack +27; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (Troop and Mounts Only)]]_; __6th __  _[[Spells/Blessed Boundary|Blessed Boundary]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Weapon Storm|Weapon Storm]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Bolster the Wounded"
    desc: "`pf2:r` (divine,healing) **Trigger** The tempest ends its turn and is not at maximum HP\n* * *\n\n**Effect** The tempest restores 5d10 healing HP. This healing can't increase a tempest's Hit Points beyond the maximum of its current Hit Point threshold."

  - name: "Rain of Spears"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The tempest attacks with their electrified spears, targeting all adjacent enemies (DC 38 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d6+10 piercing damage plus 1d12 electricity\n\n`pf2:2` 2d6+10 piercing damage plus 2d12 electricity\n\n`pf2:3` 3d6+10 piercing damage plus 3d12 electricity"

  - name: "Tempest of Battle"
    desc: "`pf2:2` (divine,electricity) **Frequency** once per day\n* * *\n\n**Effect** The tempest calls down a massive lightning storm in a 60-foot emanation. Spears of lightning rain down upon enemies in the area, dealing 10d12 electricity damage (DC 38 Reflex check save)."

  - name: "Troop Movement"
    desc: "  Whenever the troop Strides or Flies, they first Form Up as a free action into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Troop Spellcasting"
    desc: "  When the tempest Casts a Spell, its members combine their efforts into casting a more powerful version of the spell. When Casting a Spell that has an area of a burst, cone, or line and doesn't have a duration, increase the area of that spell. Add 5 feet to the radius of a burst that normally has a radius of at least 10 feet (a burst with a smaller radius is not affected). Add 5 feet to the length of a cone or line that is normally 15 feet long or smaller, and add 10 feet to the length of a larger cone or line."
 
```

```encounter-table
name: Valkyrie Tempest
creatures:
  - 1: Valkyrie Tempest
```




