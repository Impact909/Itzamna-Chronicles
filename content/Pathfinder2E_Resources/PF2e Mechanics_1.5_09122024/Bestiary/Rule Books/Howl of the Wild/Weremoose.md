---
title: "Weremoose"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rqbMifsakoEvBZgx" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Weremoose"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Weremoose"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[werecreature]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: "Common; deer empathy"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Intimidation: +8"
abilityMods: [4, 1, 4, -1, 1, 1]
speed: 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +11, __Ref__ +8, __Will__ +6"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]], 2x [[Equipment/Hatchet|Hatchet]], [[Equipment/Scale Mail|Scale Mail]]"
  - name: "Deer Empathy"
    desc: " (primal) A weremoose can communicate with deer, including moose."

abilities_mid:
  - name: ""
  - name: "Cold Adaptation"
    desc: "  The weremoose treats environmental cold effects as if they were one step less extreme."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+11 (sweep)\n__Damage__  1d12 + 6 slashing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+11 (agile, sweep)\n__Damage__  1d6 + 6 slashing"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+11 ()\n__Damage__  1d8 + 6 piercing plus werecreature-curse-of-the-werecreature"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+8 (agile, thrown 10 ft.)\n__Damage__  1d6 + 6 slashing"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) Medium human with fist +11 for 1d4+6 bludgeoning,\n\nor\n\nLarge moose with antler and hoof +11 for 1d8+6 bludgeoning.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Weremoose]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 17 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into the same kind of werecreature until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its antlers by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Thundering Charge"
    desc: "`pf2:2`  The weremoose Strides twice and then makes an antler Strike. A Medium or smaller creature damaged by this attack must succeed at a DC 17 Fortitude check save or be [[Conditions/Stunned|Stunned 1]]."
 
```

```encounter-table
name: Weremoose
creatures:
  - 1: Weremoose
```




