---
title: "Azarpal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PAoC6nenRl6QDsxf" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Azarpal"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Azarpal"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[fey]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Low-Light Vision"
languages: "Common, Diabolic, Fey"
skills:
  - name: "Skills"
    desc: "Crafting: +23, Deception: +27, Stealth: +26, Thievery: +24, Cooking Lore: +23"
abilityMods: [4, 7, 5, 5, 4, 8]
speed: 30 feet,  burrow 15 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +26, __Will__ +20"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  disease,  Azarpal Poison; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Fury Cocktail (Moderate)|Skeptical Fury Cocktail (Moderate)]], [[Equipment/Poison Fizz (Moderate)|Poison Fizz (Moderate)]], 4x Regional Meals"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (finesse)\n__Damage__  3d12 + 12 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+26 (agile, finesse)\n__Damage__  3d10 + 10 bludgeoning"

  - name: "Occult Innate Spells"
    desc: "DC 30, attack +22; __7th __  _[[Spells/Illusory Disguise|Illusory Disguise]]_"

  - name: "Azarpal Poison"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n\n**Onset** 1 minute\n\n**Maximum Duration** 6 minutes\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 minute)\n\n**Stage 2** [[Conditions/Fatigued|Fatigued]] and [[Conditions/Sickened|Sickened 2]] (1 minute)\n\n**Stage 3** 2d12 poison damage plus fatigued and [[Conditions/Sickened|Sickened 3]] (1 minute); the sickened condition value caused by azarpal poison cannot be reduced below 1 as long as the poison's duration remains active."

  - name: "Culinary Alchemy"
    desc: "  The azarpal knows the formulas for all common and uncommon alchemical foods of its level or lower found on pages 46–51 of Treasure Vault without needing a formula book. A typical azarpal carries about 700 gp of alchemical food."

  - name: "Gulp or Grab"
    desc: "`pf2:3` (manipulate) The Azarpal swallows a single meal or alchemical food and stores it in one of six stomachs. Therein, the food doesn't spoil (drinks must be swallowed in closed containers, or they spill and affect the azarpal normally). The azarpal can use this activity to reach into its mouth and retrieve a stored item as well. Any item that remains stored in an azarpal's stomach for at least 24 hours becomes laced with azarpal poison."

  - name: "Lasting Illusion"
    desc: "  When an azarpal casts illusory disguise and only targets themselves, the duration increases to 24 hours."

  - name: "Twirl Tail"
    desc: "`pf2:1`  The azarpal lashes and twirls their confounding tail, snapping and lashing it in all adjacent squares. Until the start of the azarpal's next turn, all non-azarpals treat the squares adjacent to the azarpal as difficult terrain."
 
```

```encounter-table
name: Azarpal
creatures:
  - 1: Azarpal
```



Azarpals resemble bipedal hogs with wide-tusked mouths, bloated bellies, and long, bristly tails. They can store food in their multiple stomachs for long periods of time, slowly infusing it with a signature poison that causes those afflicted to sweat profusely and succumb to intense nausea.

Azarpals love spreading discontent via poisoned food. They delight in traveling caravan routes, disguised as merchants, constantly sampling regional cuisines, and choosing their favorites for stomach storage and poison infusion. Then, upon reaching a land where the dish is rare or sought after, they find a place to leave the meal out for an unwary traveler. They might also find a way to introduce the poisoned meal to a tavern or restaurant and hang back to watch the resulting fun.

## Removing Azarpal Poison

Once an item of food or drink has been laced with azarpal poison, it can be detoxified through the use of a cleanse cuisine spell or by spending an hour using alchemical supplies to nullify the poison. This latter option requires access to an alchemical lab and a successful Crafting check against the azarpal's poison save DC.
