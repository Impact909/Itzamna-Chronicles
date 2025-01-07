---
title: "Mythic Ogre Boss"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8HjirHxitEesbEnK" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Mythic Ogre Boss"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder War of Immortals"
name: "Mythic Ogre Boss"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Intimidation: +16, Stealth: +11"
abilityMods: [7, 0, 4, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder War of Immortals_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +12, __Will__ +15"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "6x [[Equipment/Javelin|Javelin]], [[Equipment/Gut-Ripper|Gut-Ripper]], [[Equipment/Breastplate|Breastplate]]"
  - name: "[[Creature Family Ability Glossary/(Mythic) Titanic Might|Titanic Might]]"
    desc: "  A mythic brute ignores size limitations when performing actions like [[Actions/Grapple|Grapple]] or [[Actions/Trip|Trip]]."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Ferocity|Mythic Ferocity]]"
    desc: "`pf2:r`  **Cost** 1 Mythic Point\n\n**Trigger** The monster is reduced to 0 HP\n* * *\n\n**Effect** The monster avoids being knocked out and remains at half its maximum HP, but its wounded value increases by 1. When it is [[Conditions/Wounded|Wounded 3]], it can no longer use this ability."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ogre Hook"
    desc: "+19 (deadly d10, reach 10 feet, trip)\n__Damage__  1d10 + 11 piercing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+12 (thrown 30 ft.)\n__Damage__  1d6 + 11 piercing"

  - name: "Bellowing Command"
    desc: "`pf2:1` (auditory,emotion,fear,linguistic,mental) The ogre boss issues a command to hasten their fellows. Each ogre ally who hears and understands this command becomes [[Conditions/Quickened|Quickened]] until the end of that ally's next turn but can use the extra action only to Step or Stride."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Power|Mythic Power]]"
    desc: "  The creature has a pool of 3 Mythic Points, and can spend those Mythic Points for any of the actions it has."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Skill|Mythic Skill]]"
    desc: "  **Cost** 1 Mythic Point\n* * *\n\n**Effect** The Mythic Ogre Boss attempts its next Athletics skill check with a +4 bonus and is considered to have mythic proficiency for that check. This applies to one skill when this ability is gained and a second skill if the creature is 12th level or higher."

  - name: "Sweeping Hook"
    desc: "`pf2:r`  **Trigger** The ogre boss successfully [[Actions/Trip|Trips]] a creature using an ogre hook\n* * *\n\n**Effect** The ogre boss makes an ogre hook Strike against the creature they tripped."
 
```

```encounter-table
name: Mythic Ogre Boss
creatures:
  - 1: Mythic Ogre Boss
```



For ogres, the biggest, strongest, and most violent among them are the ones who claim the right to lead. When such a creature gains mythic power, its cruelty is likely to be matched only by its immense durability. Mythic ogre bosses are capable of felling even mighty and enormous prey like gigantic dinosaurs with their ogre hooks, using preposterously unbelievable strength to drag them down and rend them asunder. If a group of mythic ogre bosses were to band together, they could prove a terrifying threat, conquering villages or even a small city with relative ease. Fortunately, their philosophies of violence and strength over all else means that whenever such beings come into contact, they are far more likely to immediately war with each other to prove who is the strongest.
