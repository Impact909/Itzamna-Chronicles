---
title: "Sedacthy Marauder"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PLD7Wx4DGEsqa9UK" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/sedacthy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Sedacthy Marauder"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sedacthy Marauder"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[humanoid]]
trait_03: [[sedacthy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision, Wavesense (Imprecise) 30 Feet"
languages: "Thalassic; Sea Speech"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Intimidation: +13, Survival: +9"
abilityMods: [6, 3, 4, 0, 1, 3]
speed: 20 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +14, __Ref__ +9, __Will__ +9"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Spear|Spear]], [[Equipment/Breastplate|Breastplate]]"
  - name: "Sea Speech"
    desc: "  A sedacthy speaking Thalassic can be understood by any animal that has a swim Speed or the amphibious or aquatic trait. By spending a week regularly interacting with such an animal, the sedacthy can make it permanently helpful."

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 30 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "Vengeful Throw"
    desc: "`pf2:r`  **Trigger** The marauder takes damage from a creature 20 feet or further away\n* * *\n\n**Effect** The marauder makes a ranged spear Strike against the triggering creature. This attack doesn't take a range increment penalty if the target is within the second range increment."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile)\n__Damage__  2d4 + 8 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  1d4 bleed 1d4 + 8 piercing"

  - name: "**Melee** `pf2:1` Spear"
    desc: "+14 ()\n__Damage__  1d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+11 (thrown 20 ft.)\n__Damage__  1d6 + 10 piercing"

  - name: "Challenging Shriek"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The marauder unleashes a terrifying battle cry. Each enemy in a 30-foot emanation must attempt a DC 21 Will check save. Regardless of the results, creatures are temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Immobilized|Immobilized]] for 1 round and [[Conditions/Frightened|Frightened 3]]."

  - name: "Shared Feast"
    desc: "`pf2:2`  The sedacthy makes a jaws Strike. If it hits, an ally of their choice can spend a reaction to make a jaws Strike against the same target. Allies with beaks or similar attacks can use those instead of jaws."
 
```

```encounter-table
name: Sedacthy Marauder
creatures:
  - 1: Sedacthy Marauder
```



Physically imposing sedacthies prove their status by controlling dangerous aquatic creatures like great white sharks and giant moray eels.

* * *

Sedacthies are amphibious, fish-like humanoids who lurk in Golarion's oceans and are known for leading their animal servants ashore to devour air breathers. When an entire fishing village disappears overnight, sedacthies are the first suspects. Sedacthies pride themselves as natural leaders, with ambition limited only by their strict adherence to hierarchy. A sedacthy's station is determined by the strength of the animal servants they press into service, and the mettle they prove during hunts and in battles against outsiders.
