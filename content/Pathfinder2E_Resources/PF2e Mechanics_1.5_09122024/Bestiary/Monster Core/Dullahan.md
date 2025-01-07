---
title: "Dullahan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7sjNXKK0lfVvUBjv" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Dullahan"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dullahan"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Lifesense 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Intimidation: +17, Stealth: +13, Survival: +15"
abilityMods: [6, 2, 2, 2, 3, 4]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +13, __Ref__ +15, __Will__ +17"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95, fast healing 5; __Immunities__  death effects,  disease,  fear effects,  paralyzed,  poison,  unconscious,  bleed; __Weaknesses__ holy 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hatchet|+1 Hatchet]], [[Equipment/Longsword|+1 Longsword]], [[Equipment/Full Plate|Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 5]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 23 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Keen Longsword"
    desc: "+18 (magical, versatile p)\n__Damage__  1d8 + 10 slashing plus head-hunter"

  - name: "**Melee** `pf2:1` Keen Returning Hatchet"
    desc: "+17 (agile, sweep)\n__Damage__  1d6 + 10 slashing plus head-hunter"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, nonlethal)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Keen Returning Hatchet"
    desc: "+14 (agile, thrown 10 ft.)\n__Damage__  2d8 + 10 slashing plus head-hunter"

  - name: "Head Hunter"
    desc: "  Any slashing weapon gains the _[[Equipment/Keen|Keen]]_ rune while a dullahan wields it, and any hatchet they wield gains the _[[Equipment/Returning|Returning]]_ rune as well. If the dullahan kills a creature with a critical hit using a slashing weapon, the target is decapitated as though the dullahan had used Reap on the target."

  - name: "Reap"
    desc: "`pf2:2`  The dullahan removes the head of a dead creature within reach. Each creature within the area of the dullahan's frightful presence must attempt a new save, even if it is temporarily immune."

  - name: "Summon Steed"
    desc: "`pf2:2` (occult) The dullahan summons a war horse with elite adjustments and the fiend and unholy traits. This steed remains until it is slain, the dullahan Dismisses this effect, or the dullahan Summons a Steed again."
 
```

```encounter-table
name: Dullahan
creatures:
  - 1: Dullahan
```



Riding on a horse as black as night, the headless hunter known as the dullahan tracks down and takes the heads of those they deem unfit to continue living. When closing in for the kill, the dullahan first whispers their victim's name, then swiftly collects their prize, casting a pall of dread upon all who witness the grim execution.

A dullahan manifests when a particularly violent warrior is beheaded and the warrior's soul stubbornly clings to material existence (or is refused entry to the afterlife). Most dullahans return to their former homelands, where they can exact vengeance on those they feel wronged them in life (or their living descendants). A dullahan's concept of justice is swift and merciless, and once they've selected a target, they're unwavering in their cause.

Perhaps even more than revenge, a dullahan desires their own rotted head. An individual who wields the head of a dullahan is powerful indeed, for a dullahan will grudgingly serve such a master in the hopes of reclaiming their missing skull. Mighty fiends such as devils command dullahans to harvest souls or lead armies for them, while a mortal might use such an undead warrior to fulfill a personal vendetta. A dullahan won't hesitate to kill their liege and reclaim their head when the opportunity presents itself.
