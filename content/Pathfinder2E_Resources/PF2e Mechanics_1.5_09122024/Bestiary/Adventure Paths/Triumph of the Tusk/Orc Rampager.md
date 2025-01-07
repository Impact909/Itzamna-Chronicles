---
title: "Orc Rampager"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Xt5S9rlDM7EauGzG" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Orc Rampager"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Orc Rampager"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +11, Survival: +10"
abilityMods: [5, 2, 4, 1, 2, 2]
speed: 30 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +14, __Ref__ +11, __Will__ +8"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Orc Necksplitter, Longbow, Hide Armor, 20x Arrows"
abilities_mid:
  - name: ""
  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Necksplitter"
    desc: "+14 (forceful, sweep)\n__Damage__  1d8 + 9 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (agile, shove)\n__Damage__  1d4 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+12 (deadly d10, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 4 piercing"

  - name: "Rampaging Strikes"
    desc: "`pf2:2`  The orc rampager Strides and makes two melee Strikes at any point during that movement. Each Strike must target a different creature. The attacks count toward the rampager's multiple attack penalty, but the penalty doesn't increase until after Rampaging Strikes is complete."
 
```

```encounter-table
name: Orc Rampager
creatures:
  - 1: Orc Rampager
```



Fueled by bloodlust in battle, orc rampagers are fearsome combatants. They often serve as the elite shock troops of an orc hold. They train to move quickly through enemy ranks, striking all around them to disrupt their foe's defenses. The speed and fury of a group of orc rampagers working together is terrifying to behold.

* * *

The orcs of Belkzen are survivors to the core. Shaped by the unforgiving landscape, they're experts at managing resources and making do with scarcity. Aside from the relative peace from late spring through early summer during the Flood Truce, Belkzen's orc holds are nearly always at odds with each other, though these conflicts rarely rise to the level of war. Instead, there are raids for supplies, skirmishes to establish borders or retake lost territory, and feuds over personal slights. Outsiders who travel in Belkzen often become embroiled in these conflicts; sometimes they even trigger the fights themselves.

The members of a given hold are often quite spread out, rather than centralized, so communication and coordination is sporadic. Even the Empty Hand orcs of Urgir rarely stay in the city all year long. At the very least, they travel a few miles to the Flood Road when the aurochs arrive, and they may wander even further afield when the mood strikes.

## Orc Faith

With so many sudden disruptions to the orc pantheon, the faithful find themselves in a confusing time of change. Fervent worshippers of Lanishra, Sezelrian, and Zagresh don't particularly like the new deities who have usurped their old gods. Some of these zealots desperately cling to their old faiths, and many still hold a sliver of their fallen deity's power, further adding to the confusion.

## Salvage

Orcs are experts at repurposing materials for their own use. Belkzen doesn't have rich soil or abundant deposits of valuable metals and minerals. Instead, orc crafters rely on salvage from battles or trade with outsiders for their raw materials. It's common for a basic tool, such as a knife or cooking pot, to be very old yet kept in perfect working condition. Even when a tool breaks, orc crafters find ways to reuse as much of it as they can manage.
