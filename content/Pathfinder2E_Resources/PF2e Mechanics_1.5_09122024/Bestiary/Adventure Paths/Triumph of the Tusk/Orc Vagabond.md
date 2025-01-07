---
title: "Orc Vagabond"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oCtmA3Anbu6RBBLS" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Orc Vagabond"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Orc Vagabond"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Intimidation: +7, Stealth: +9"
abilityMods: [4, 3, 3, 1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +10, __Will__ +6"
hp: 48
health:
  - name: ""
  - name: HP
    desc: "48"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Battle Axe, Longbow, Studded Leather Armor, 20x Arrows"
abilities_mid:
  - name: ""
  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+11 (sweep)\n__Damage__  1d8 + 6 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, nonlethal)\n__Damage__  1d4 + 6 bludgeoning"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+10 (deadly d10, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 3 piercing"

  - name: "Surprise Shooter"
    desc: "  The orc vagabond's ranged attacks deal an extra 1d6 precision damage to targets adjacent to at least one of the vagabond's allies."
 
```

```encounter-table
name: Orc Vagabond
creatures:
  - 1: Orc Vagabond
```



Tough and no-nonsense, orc vagabonds are just as likely to serve their own interests as they are those of a warlord. Some live as bandit leaders, assembling their own group of veterans and outcasts. Many others work as the elite guards of their hold, keeping a watchful eye out for trouble.

* * *

The orcs of Belkzen are survivors to the core. Shaped by the unforgiving landscape, they're experts at managing resources and making do with scarcity. Aside from the relative peace from late spring through early summer during the Flood Truce, Belkzen's orc holds are nearly always at odds with each other, though these conflicts rarely rise to the level of war. Instead, there are raids for supplies, skirmishes to establish borders or retake lost territory, and feuds over personal slights. Outsiders who travel in Belkzen often become embroiled in these conflicts; sometimes they even trigger the fights themselves.

The members of a given hold are often quite spread out, rather than centralized, so communication and coordination is sporadic. Even the Empty Hand orcs of Urgir rarely stay in the city all year long. At the very least, they travel a few miles to the Flood Road when the aurochs arrive, and they may wander even further afield when the mood strikes.

## Orc Faith

With so many sudden disruptions to the orc pantheon, the faithful find themselves in a confusing time of change. Fervent worshippers of Lanishra, Sezelrian, and Zagresh don't particularly like the new deities who have usurped their old gods. Some of these zealots desperately cling to their old faiths, and many still hold a sliver of their fallen deity's power, further adding to the confusion.

## Salvage

Orcs are experts at repurposing materials for their own use. Belkzen doesn't have rich soil or abundant deposits of valuable metals and minerals. Instead, orc crafters rely on salvage from battles or trade with outsiders for their raw materials. It's common for a basic tool, such as a knife or cooking pot, to be very old yet kept in perfect working condition. Even when a tool breaks, orc crafters find ways to reuse as much of it as they can manage.
