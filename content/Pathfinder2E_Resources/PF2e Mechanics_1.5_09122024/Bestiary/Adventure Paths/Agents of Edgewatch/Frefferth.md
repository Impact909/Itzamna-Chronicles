---
title: "Frefferth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i4oGdEI5REUzqBcQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Frefferth"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Frefferth"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Lifesense 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Intimidation: +23, Stealth: +16, Survival: +17"
abilityMods: [6, 3, 3, 3, 4, 6]
speed: 20 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +14, __Ref__ +16, __Will__ +19"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, fast healing 8; __Immunities__  death effects,  disease,  fear effects,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|Alietta (+1 Striking Bastard Sword)]], 3x [[Equipment/Spear|+1 Spear]], [[Equipment/Full Plate|+1 Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 8]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 25 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Rejuvenation"
    desc: " (divine) When Frefferth is destroyed, his body and items dissipate into shadowy nothingness and the knight re-forms after 1d4 days within the sarcophagus in area **D12**, fully healed.\n\nFrefferth can be trapped only by returning the [[Equipment/Chain of the Stilled Spirit|Chain of the Stilled Spirit]] to the sarcophagus (see areas **D12** and **D34**), in which case Frefferth's body dissipates, leaving his items in the spot where he was last slain."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Alietta"
    desc: "+21 (magical, two-hand d12)\n__Damage__  2d8 + 12 slashing plus head-hunter"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+20 (magical, thrown 20 ft.)\n__Damage__  1d6 + 12 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+19 (magical, thrown 20 ft.)\n__Damage__  1d6 + 12 piercing plus impaler"

  - name: "Head Hunter"
    desc: "  Any slashing weapon a dullahan wields becomes [[Equipment/Keen|Keen]], and any hatchet it wields becomes [[Equipment/Returning|Returning]].\n\nIf the dullahan kills a creature with a critical hit using a slashing weapon, the target is decapitated as though the dullahan had used Reap on the target.\n\nThese effects remain only while the dullahan holds the weapon."

  - name: "Impaler"
    desc: "  Whenever Frefferth damages a creature with a critical hit using a ranged piercing weapon, the weapon remains impaled in the victim's body.\n\nThe victim becomes [[Conditions/Clumsy|Clumsy 1]] as long as they are impaled; the impaling weapon can be removed by the affected creature or an adjacent ally as a 2-action activity that has the manipulate trait."

  - name: "Reap"
    desc: "`pf2:2`  Frefferth removes the head of a dead creature within reach.\n\nEach creature within the area of Frefferth's frightful presence must attempt a new save, even if they are temporarily immune."

  - name: "Summon Steed"
    desc: "`pf2:2` (occult) Frefferth summons a [[Monster Core/Nightmare|Nightmare]].\n\nThis steed remains until it is slain, Frefferth [[Actions/Dismiss|Dismisses]] it, or Frefferth summons another steed."
 
```

```encounter-table
name: Frefferth
creatures:
  - 1: Frefferth
```




