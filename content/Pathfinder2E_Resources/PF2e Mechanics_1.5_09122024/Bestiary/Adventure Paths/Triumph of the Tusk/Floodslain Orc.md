---
title: "Floodslain Orc"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kGKejKfwQJtfiYvJ" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Floodslain Orc"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Floodslain Orc"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[undead]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +10"
abilityMods: [4, 2, 3, 1, 2, -2]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +12, __Ref__ +9, __Will__ +6"
hp: 44
health:
  - name: ""
  - name: HP
    desc: "44, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ fire 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x Orc Knuckle Dagger, Shoddy Breastplate"
abilities_mid:
  - name: ""
  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Knuckle Dagger"
    desc: "+11 (agile, disarm)\n__Damage__  1d6 + 6 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, nonlethal)\n__Damage__  1d8 + 6 bludgeoning plus drowning-touch"

  - name: "Drowning Touch"
    desc: " (occult) When the floodslain creature damages a creature with a non-weapon melee attack, the target's lungs begin to fill with water. The target must attempt a Fortitude check save against the floodslain's Will DC. A target affected by Drowning Touch can spend a single action coughing in an attempt to recover, which immediately lets them attempt a new Fortitude save against the effect. A success improves the previous result by 1 step. A critical success improves the previous result by 2, and a critical failure decreases it by 1.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Slowed|Slowed 2]] for 1 round.\n\n**Critical Failure** The creature is slowed 2 and drowning."

  - name: "[[Creature Family Ability Glossary/(Floodslain) Floodslain Spawn|Floodslain Spawn]]"
    desc: " (occult) A living animal or humanoid killed by a floodslain creature will rise as a floodslain if their corpse is left in water for 24 hours. The new floodslain isn't under the control of the floodslain creature that killed it."

  - name: "Sodden Ground"
    desc: " (aura,occult,water) 20 feet. Water flows endlessly from a floodslain creature, making the area around it slippery. The ground in the aura is difficult terrain for all non-floodslain creatures."

  - name: "Vomit Flotsam"
    desc: "`pf2:2` (occult) A floodslain creature's body is filled with debris from their horrific death, which they can spew at their enemies. The floodslain vomits flotsam in a 15-foot cone. Any creature in the area takes 3d8 bludgeoning damage with a Reflex check save against the floodslain's Fortitude DC."
 
```

```encounter-table
name: Floodslain Orc
creatures:
  - 1: Floodslain Orc
```



Countless orcs have fallen victim to the Deluge over the years. Some were caught unawares by the sudden flooding, while others lost their lives trying to save loved ones, valuable goods, livestock, or their property. A few were even thrown into the raging waters during conflicts with other orcs.

* * *

The sudden, crashing waters of the Deluge kill many creatures in Belkzen each year. The surprise and terror these victims of the Deluge feel during their last moments is sometimes enough to raise them from the dead as floodslain. As the waters that killed them recede, the undead seek others to join them. Despite their broken, shattered bodies, floodslain are often recognizable to those who knew them in life.

Floodslain creatures are rare outside Belkzen, leading some scholars to speculate that the waters of the Deluge are somehow cursed. Others believe the proximity of Gallowspire could be the cause. If so, this means the Gravelands could soon see floodslain arise there too, as the Whispering Tyrant furthers his plots after escaping that prison.

## Panicked Eyes

One distinctive feature all floodslain share are their wide, panic-stricken eyes. A floodslain's gaze is permanently frozen in the expression of terror the creature felt moments before its death. Some floodslain are rumored to have the ability to spread this fear to others with a mere glance.

## In Search of Water

Floodslain tend to move toward lower ground, instinctively seeking water. Belkzen's flat floodplains, however, mean that the creatures wander in unpredictable ways. A common saying among old orc crafters is "build on high, keep dry," but many add "build low, the dead flow."
