---
title: "Imprecasia"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mVAFzIKytLX62SOY" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Imprecasia"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #199: To Bloom Below the Web"
name: "Imprecasia"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Nature: +23, Survival: +23"
abilityMods: [3, 6, 5, 3, 6, 5]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #199: To Bloom Below the Web_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +18, __Ref__ +23, __Will__ +21"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  curse; __Weaknesses__ cold iron 10; __Resistances__ void 10"
abilities_top:
  - name: ""

  - name: "Scent Curse"
    desc: "  The imprecasia can smell the presence of curses of a level equal to or lower than their own level within 30 feet; this is an imprecise sense."

abilities_mid:
  - name: ""
  - name: "Drink Death"
    desc: "`pf2:r` (primal) **Trigger** A creature within 30 feet of the imprecasia is [[Conditions/Dying|Dying]]\n* * *\n\n**Effect** The imprecasia inhales, drawing a thin blue streak of vapor out of the dying creature's body into their mouth. The dying creature's dying condition is reduced by 1, and the imprecasia regains 2d10+9 Hit Points."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claws"
    desc: "+23 (agile, finesse, magical)\n__Damage__  2d12 + 9 slashing plus homelands-hostility"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +22; __5th __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Cleanse Affliction|Cleanse Affliction (Curse Only)]]_, _[[Spells/Deafness|Deafness]]_, _[[Spells/Mirage|Mirage]]_\n__Cantrips__  __(6th)__ _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Devour Curse"
    desc: "`pf2:2` (primal) The imprecasia casts [[Spells/Cleanse Affliction|Cleanse Affliction]] against a curse afflicting a creature, but with a cast of two actions rather than 10 minutes. If they succeed in removing the curse, they also drains vitality from the creature, causing it to become [[Conditions/Drained|Drained 1]] unless it succeeds at a DC 30 Fortitude check save ([[Conditions/Drained|Drained 2]] on a critical failure). If the curse is removed, the imprecasia doesn't expend that use of remove curse as a primal innate spell.\n\n## Targeting Items\n\nAn imprecasia can cast remove curse on a cursed item rather than on a creature, but they can't use Devour Curse on it. They can only do so on an item that's of a level equal to or less than their own level; on a success, the item is uncursed for 24 hours if it's of a level equal to or higher than the imprecasia's level –4, or uncursed permanently if it's lower level than that."

  - name: "Homeland's Hostility"
    desc: " (curse,primal) A creature that takes damage from the imprecasia's claws must attempt a DC 30 Will check save. On a failure, it treats all terrain within 60 feet of an imprecasia as difficult terrain."
 
```

```encounter-table
name: Imprecasia
creatures:
  - 1: Imprecasia
```



An imprecasia, commonly known as a curse eater, is a solitary fey drawn to the energy emanating from curses. They appear as emaciated humanoid creatures with shadowy wings, long thin hands with sharp claws, and insectile heads with feathery antenna.

An imprecasia's appearance in a region signifies the land is troubled, but they're not unpopular creatures. On the contrary, an imprecasia's whereabouts are coveted information, as they have the ability to fully consume curses on objects and creatures. Many carrying the weight of a curse seek out curse eaters, most of whom will gladly accept doomed objects or charitably destroy an individual's curse.

An imprecasia will never accept the idea of healing a cursed land or blighted region. One might even seek to strengthen the afflictions on a region simply to ensure a regular supply of food. A bolder imprecasia tracks cursed families over generations, feeding off their misfortune until the curse ends or the bloodline dies off. Any who attempt to destroy such curses may find themselves the enemy of an imprecasia defending their source of sustenance.
