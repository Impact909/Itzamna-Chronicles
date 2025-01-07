---
title: "Krampus Celebrant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.687TslLiRDmvUtlF" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Krampus Celebrant"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Krampus Celebrant"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Intimidation: +18, Stealth: +15, Survival: +15"
abilityMods: [5, 3, 4, 1, 3, 4]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +16, __Will__ +13"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125; __Weaknesses__ holy 5; __Resistances__ cold 10, physical 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 23 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d8 + 9 slashing plus grab"

  - name: "**Melee** `pf2:1` Birch Bundle"
    desc: "+20 (backswing, forceful)\n__Damage__  2d10 + 9 bludgeoning"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+20 ()\n__Damage__  2d12 + 9 piercing"

  - name: "Innate Primal Spells"
    desc: "DC 26, attack +18; __2nd __  _[[Spells/Mist|Obscuring Mist]]_\n__Cantrips__  __(4th)__ _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Frightful Parade"
    desc: "`pf2:2`  The Krampus celebrant Strides up to its Speed and attempts a birch bundle Strike against one creature within its reach at any point during that movement."

  - name: "Relentless Torment"
    desc: "`pf2:r`  **Trigger** The Krampus celebrant hits a frightened creature with its birch bundle Strike\n* * *\n\n**Effect** The target must attempt a DC 26 Will check save to resist the effects of the fearful assault.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The creature takes 1d8 mental damage. At the end of the creature's next turn, its frightened condition doesn't decrease by 1.\n\n**Critical Failure** The creature takes 2d8 mental damage, and its frightened condition increases by 1 (maximum 4). At the end of its next turn, its frightened condition doesn't decrease by 1."

  - name: "Snowstride"
    desc: "  The Krampus celebrant ignores difficult terrain caused by snow and ice, and it treats greater difficult terrain caused by snow and ice as difficult terrain."

  - name: "Vandal"
    desc: "  Whenever the Krampus celebrant deals damage to an object, it ignores the first 10 points of the object's Hardness."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Krampus Celebrant
creatures:
  - 1: Krampus Celebrant
```




