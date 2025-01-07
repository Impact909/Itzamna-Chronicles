---
title: "Floodslain Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.f9GxueDUxQYHz7ip" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Floodslain Wolf"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Floodslain Wolf"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[undead]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +6, Stealth: +8, Survival: +8"
abilityMods: [4, 3, 3, -4, 2, 0]
speed: 35 feet,  swim 35 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +11, __Will__ +7"
hp: 34
health:
  - name: ""
  - name: HP
    desc: "34, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ fire 2"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d8 + 4 piercing plus drowning-touch,knockdown"

  - name: "Drowning Touch"
    desc: " (occult) The target's lungs begin to fill with water and they must attempt a DC 17 Fortitude check save. A target affected by Drowning Touch can spend a single action coughing in an attempt to recover, which immediately lets them attempt a new Fortitude save against the effect. A success improves the previous result by 1 step. A critical success improves the previous result by 2, and a critical failure decreases it by 1.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Slowed|Slowed 2]] for 1 round.\n\n**Critical Failure** The creature is slowed 2 and drowning."

  - name: "Floodslain Spawn"
    desc: " (occult) A living animal or humanoid killed by a floodslain creature will rise as a floodslain if their corpse is left in water for 24 hours. The new floodslain isn't under the control of the floodslain creature that killed it."

  - name: "Pack Attack"
    desc: "  The floodslain wolf's Strikes deal 1d4 extra damage to creatures within reach of at least two of the floodslain wolf's allies."

  - name: "Sodden Ground"
    desc: " (aura,occult,water) 20 feet. Water flows endlessly from a floodslain creature, making the area around it slippery. The ground in the aura is difficult terrain for all non-floodslain creatures."

  - name: "Vomit Flotsam"
    desc: "`pf2:2` (occult) The floodslain vomits flotsam in a 15-foot cone. Any creature in the area takes 2d8 bludgeoning damage (DC 18 Reflex check save)."

  - name: "Knockdown"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Floodslain Wolf
creatures:
  - 1: Floodslain Wolf
```


Variant floodslain

The sudden, crashing waters of the Deluge kill many creatures in Belkzen each year. The surprise and terror these victims of the Deluge feel during their last moments is sometimes enough to raise them from the dead as floodslain. As the waters that killed them recede, the undead seek others to join them. Despite their broken, shattered bodies, floodslain are often recognizable to those who knew them in life.

Floodslain creatures are rare outside Belkzen, leading some scholars to speculate that the waters of the Deluge are somehow cursed. Others believe the proximity of Gallowspire could be the cause. If so, this means the Gravelands could soon see floodslain arise there too, as the Whispering Tyrant furthers his plots after escaping that prison.

## Panicked Eyes

One distinctive feature all floodslain share are their wide, panic-stricken eyes. A floodslain's gaze is permanently frozen in the expression of terror the creature felt moments before its death. Some floodslain are rumored to have the ability to spread this fear to others with a mere glance.

## In Search of Water

Floodslain tend to move toward lower ground, instinctively seeking water. Belkzen's flat floodplains, however, mean that the creatures wander in unpredictable ways. A common saying among old orc crafters is "build on high, keep dry," but many add "build low, the dead flow."
