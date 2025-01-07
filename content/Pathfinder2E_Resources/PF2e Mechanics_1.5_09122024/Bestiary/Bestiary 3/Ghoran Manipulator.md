---
title: "Ghoran Manipulator"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oynt6hvxSlSrpdeD" 
tags:
  - pf2e/creature/type/ghoran
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Ghoran Manipulator"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Ghoran Manipulator"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[ghoran]]
trait_02: [[humanoid]]
trait_03: [[plant]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Deception: +11, Diplomacy: +9, Nature: +9, Performance: +11, Stealth: +6"
abilityMods: [0, 1, 3, 0, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +8, __Will__ +11"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortbow|Shortbow]], [[Equipment/Spear|Spear]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Anguished Cry"
    desc: "`pf2:r` (emotion,mental) **Trigger** A humanoid enemy damages the ghoran manipulator with a melee attack\n* * *\n\n**Effect** The ghoran manipulator rearranges its facial petals and wails, mimicking humanoid anguish to engender sympathy. The triggering creature must attempt a DC 20 Will check save.\n* * *\n\n**Success** The target is unaffected and is temporarily immune for 1 hour.\n\n**Failure** The target takes a -2 circumstance penalty on attack rolls against the ghoran manipulator until the start of its next turn.\n\n**Critical Failure** As failure, and the target is [[Conditions/Stupefied|Stupefied 2]] until the start of its next turn."

  - name: "Appetizing Aroma"
    desc: " (aura,olfactory) 10 feet. A creature entering or starting its turn in the aura must attempt a DC 17 Will check save. Creatures that don't eat are immune to Appetizing Aroma.\n\n**Success** The creature is unaffected and is temporarily immune for 1 hour.\n\n**Failure** The creature is distracted by a desire to consume the ghoran. For 1 round it becomes [[Conditions/Off-Guard|Off-Guard]] and [[Conditions/Fascinated|Fascinated]] by the ghoran manipulator."

  - name: "Delicious"
    desc: "  Ghorans were originally created to be scrumptious food.\n\nA ghoran manipulator takes 5 additional damage from jaws Strikes, fangs Strikes, or other similar Strikes with a creature's mouth. When a ghoran manipulator is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by a creature's jaws, fangs, or mouth, the DC to [[Actions/Escape|Escape]] is increased by 2."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+7 ()\n__Damage__  1d6 + 2 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+8 (thrown 20 ft.)\n__Damage__  1d6 + 2 piercing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+8 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 2 piercing"

  - name: "Occult Spontaneous Spells"
    desc: "DC 20, attack +12; __2nd __ (2 slots) _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Phantom Pain|Phantom Pain]]_; __1st __ (3 slots) _[[Spells/Charm|Charm]]_, _[[Spells/Sanctuary|Sanctuary]]_, _[[Spells/Sleep|Sleep]]_, _[[Spells/Soothe|Soothe]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Light|Light]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "Primal Innate Spells"
    desc: "DC 20, attack +12; __2nd __  _[[Spells/Detect Poison|Detect Poison]]_, _[[Spells/Cornucopia|Goodberry]]_; __1st __  _[[Spells/Cleanse Cuisine|Purify Food and Drink]]_"
 
```

```encounter-table
name: Ghoran Manipulator
creatures:
  - 1: Ghoran Manipulator
```



Ghorans are sentient plants who grow in the shape of humanoids. A ghoran's body is composed of one large seed encased in rich vegetable tissue covered with dense, green rinds. In place of a face ghorans sport a bouquet of vividly colored flower petals with gaps and ridges suggesting facial features, which they can shift to express emotion.

Magically created to be a delicious and nutritious food source that could adapt to hazardous environments, ghorans evolved to develop sentience, speech, and ambulatory bodies that could mimic humanoid forms and behavior to discourage predation. Ghorans find the concept of gender confounding, though some display visual gender cues to put humanoids at ease or leverage societal expectations to their own advantage.

This ghoran manipulator relies on charm to survive.
