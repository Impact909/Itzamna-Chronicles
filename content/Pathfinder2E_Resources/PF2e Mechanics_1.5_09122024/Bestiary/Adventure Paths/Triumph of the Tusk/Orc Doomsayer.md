---
title: "Orc Doomsayer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IRoHaZwUFRJ6pwZ3" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Orc Doomsayer"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Orc Doomsayer"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Deception: +12, Intimidation: +12, Medicine: +12, Religion: +13"
abilityMods: [3, 2, 4, 1, 5, 4]
speed: 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +9, __Will__ +15"
hp: 78
health:
  - name: ""
  - name: HP
    desc: "78"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Flail, Breastplate"
abilities_mid:
  - name: ""
  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flail"
    desc: "+13 (disarm, sweep, trip)\n__Damage__  1d6 + 3 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile, shove)\n__Damage__  1d4 + 3 bludgeoning"

  - name: "Divine Prepared Spells"
    desc: "DC 21, attack +14; __3rd __  _[[Spells/Chilling Darkness|Chilling Darkness]]_; __2nd __  _[[Spells/Augury|Augury]]_, _[[Spells/Silence|Silence]]_; __1st __  _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Heal|Heal]]_\n__Cantrips__  __(3rd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Dooming Proclamation"
    desc: "`pf2:3` (auditory,divine,emotion,fear,mental) The orc doomsayer shouts pronouncements that presage the unstoppable approach of a cataclysmic event. Each enemy within 30 feet attempts a DC 21 Will check save.\n* * *\n\n**Critical Success** No effect and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature's mind fills with images of the end times. The creature takes 3d6 mental damage and is [[Conditions/Frightened|Frightened 2]]."

  - name: "Infused Strikes"
    desc: "  The orc doomsayer's melee Strikes deal an extra 1d8 void damage."
 
```

```encounter-table
name: Orc Doomsayer
creatures:
  - 1: Orc Doomsayer
```



Driven by fervor bordering on zealotry, doomsayers spread the word of their destructive deities. Many are faithful followers of recently fallen gods. Though their deity has been cast down, an orc doomsayer's unwavering faith allows them to hold onto a sliver of their god's essence to power their abilities.

* * *

The orcs of Belkzen are survivors to the core. Shaped by the unforgiving landscape, they're experts at managing resources and making do with scarcity. Aside from the relative peace from late spring through early summer during the Flood Truce, Belkzen's orc holds are nearly always at odds with each other, though these conflicts rarely rise to the level of war. Instead, there are raids for supplies, skirmishes to establish borders or retake lost territory, and feuds over personal slights. Outsiders who travel in Belkzen often become embroiled in these conflicts; sometimes they even trigger the fights themselves.

The members of a given hold are often quite spread out, rather than centralized, so communication and coordination is sporadic. Even the Empty Hand orcs of Urgir rarely stay in the city all year long. At the very least, they travel a few miles to the Flood Road when the aurochs arrive, and they may wander even further afield when the mood strikes.

## Orc Faith

With so many sudden disruptions to the orc pantheon, the faithful find themselves in a confusing time of change. Fervent worshippers of Lanishra, Sezelrian, and Zagresh don't particularly like the new deities who have usurped their old gods. Some of these zealots desperately cling to their old faiths, and many still hold a sliver of their fallen deity's power, further adding to the confusion.

## Salvage

Orcs are experts at repurposing materials for their own use. Belkzen doesn't have rich soil or abundant deposits of valuable metals and minerals. Instead, orc crafters rely on salvage from battles or trade with outsiders for their raw materials. It's common for a basic tool, such as a knife or cooking pot, to be very old yet kept in perfect working condition. Even when a tool breaks, orc crafters find ways to reuse as much of it as they can manage.
