---
title: "Izhkarial"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.alieSXXmtkMvoMim" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/primal
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Izhkarial"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Izhkarial"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[primal]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +32, Deception: +29, Intimidation: +31, Nature: +28, Performance: +29, Society: +28, Survival: +26"
abilityMods: [8, 5, 5, 4, 4, 5]
speed: 50 feet,  fly 140 feet,  swim 70 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +29, __Ref__ +29, __Will__ +28; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  acid,  paralyzed,  sleep"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff of Elemental Power (Major)|Staff of Elemental Power (Major)]], [[Equipment/Singing Shortbow|Singing Shortbow]], [[Equipment/Bands of Force (Greater)|Bands of Force (Greater)]], [[Equipment/Spacious Pouch (Type IV)|Spacious Pouch (Type IV)]]"
abilities_mid:
  - name: ""
  - name: "Brine Spit"
    desc: "`pf2:r` (concentrate) **Trigger** A creature the brine dragon observes within 30 feet uses a concentrate action\n* * *\n\n**Effect** The dragon spits a glob of caustic salt water at the creature. The creature takes 6d6 acid damage (DC 34 Reflex check save). On a failure, the concentrate action is disrupted."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (acid, magical, reach 20 feet)\n__Damage__  3d10 + 16 piercing 4d4 acid"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 16 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (magical, reach 25 feet)\n__Damage__  3d12 + 16 bludgeoning"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+30 (magical, reach 20 feet)\n__Damage__  2d12 + 16 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 37, attack +29; __6th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_; __5th __  _[[Spells/Control Water|Control Water (x3)]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_; __4th __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_, _[[Spells/Mist|Mist (At Will)]]_"

  - name: "Brine Breath"
    desc: "`pf2:2` (acid,primal) Izhkarial breathes a spray of acidic salt water that deals 17d6 acid damage in a 120-foot line (DC 37 Reflex check save). She can't use Brine Breath again for [[/gmr 1d4 #Recharge Brine Breath]]{1d4 rounds}."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The dragon tries to capsize an adjacent aquatic vessel of their size or smaller. They must succeed at an Athletics check with a DC of 35 (reduced by 5 for each size smaller the vessel is than the dragon) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Desiccating Bite"
    desc: "`pf2:2`  The dragon makes a jaws Strike. On a hit, the target takes 5d6 persistent acid damage, and is [[Conditions/Sickened|Sickened 3]] from the pain of salt and brine in its wounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one wing Strike in any order."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Breath Weapon whenever they score a critical hit with a Strike."

  - name: "Painful Strikes"
    desc: " (acid) The brine dragon's body is encrusted with salty, acidic crystals. When a target takes damage from one of the dragon's melee Strikes, it must succeed at a DC 38 Fortitude check Save or be [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 3]] on a critical failure). The target then becomes temporarily immune for 1 minute."
 
```

```encounter-table
name: Izhkarial
creatures:
  - 1: Izhkarial
```


Variant brine dragon

Brine dragons are usually blue-green in color, with shiny scales, crests that help them glide through the water, and sweeping neck frills. They care little for either good or evil. As they are both opinionated and willing to impose their sense of order on others, many brine dragons eventually seek to rule over a meticulously crafted community. These communities are orderly and well-planned, with rigid standards of courtesy and unchanging laws set down by the dragon themself. A settlement seeded by a brine dragon can be made of members of almost any ancestry, but the most common inhabitants are humans, merfolk, tengus, or sahuagin.

Depending on the dragon's personality, their community members might view their brine dragon ruler as anything from a benevolent force of order to a fearful tyrant. Regardless, the typical brine dragon has little patience for kindness or philanthropy, and the strength and health of their settlement as a whole are of greater concern than individuals' well-being. A notable exception to this dispassion rises when an outside force encroaches on their lands. In these cases, the brine dragon is quick to step in and aid in the defense of their community.

Although brine dragons enjoy cultivating settlements, they rarely make their lairs within the city limits, instead preferring to dwell in sea caves or cliffside grottoes overlooking the coastline. Here they can retreat for privacy as needed, or can accumulate and display their gathered wealth in a place where they feel safe spreading out their treasures. Brine dragon hoards often consist of a mix of offerings and taxes paid by those they rule over and strange discoveries salvaged from sunken ships.
