---
title: "Umbral Gnome Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.o1VZbAIcAcZFKrHV" 
tags:
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Umbral Gnome Warrior"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Umbral Gnome Warrior"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[gnome]]
trait_02: [[humanoid]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Gnomish, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +5, Stealth: +5"
abilityMods: [4, 2, 3, 0, 1, -1]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18 (20 with shield raised); __Fort__ +9, __Ref__ +8, __Will__ +5"
hp: 34
health:
  - name: ""
  - name: HP
    desc: "34"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Spear|Spear]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+10 ()\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+8 (range increment 120 feet, reload 2)\n__Damage__  1d10 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 15, attack +7; __1st __  _[[Spells/Illusory Disguise|Illusory Disguise]]_"
 
```

```encounter-table
name: Umbral Gnome Warrior
creatures:
  - 1: Umbral Gnome Warrior
```



Umbral gnome warriors are quick to charge into battle but focus on defending their kin and their homes over more aggressive tactics when a choice is available.

* * *

Gnomes are known for being creative and curious. They stand at around 3 feet tall, and their vivid personalities match their naturally vivid hair and eye color. Gnomes possess a natural connection to their ancestral home, the First World. They crave adventure and new experiences to fight off an ancestry-wide affliction known as the Bleaching. Gnomes who fail to dream and innovate begin to slowly lose their color and fall into a deep depression.

A notable subgroup of gnomes called umbral gnomes typically have gray or brown skin with a stony texture, and thin, pale hair or bald pates. Umbral gnomes are most numerous in the Darklands, where they go by the name drathnelar. Umbral gnomes often attribute these physical changes to the gnome deity regarded as the first of their kind, Nivi Rhombodazzle. Nivi was a surface gnome who traveled deep into the Darklands and was ultimately rewarded with demigodhood when she exchanged a particular gemstone with the dwarven deity, Torag. Nivi is immune to the Bleaching, and umbral gnomes are often immune or resistant to it as well.
