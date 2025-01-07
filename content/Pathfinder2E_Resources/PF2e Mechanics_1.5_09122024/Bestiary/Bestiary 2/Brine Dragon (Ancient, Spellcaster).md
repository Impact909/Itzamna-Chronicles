---
title: "Brine Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TtpqxYER5aywsZCj" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/elemental
  - pf2e/creature/type/lawful
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Brine Dragon (Ancient, Spellcaster)"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Brine Dragon (Ancient, Spellcaster)"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[elemental]]
trait_04: [[lawful]]
trait_05: [[water]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey, Thalassic, Utopian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +32, Deception: +32, Intimidation: +34, Nature: +30, Society: +30, Survival: +29"
abilityMods: [9, 5, 6, 5, 5, 6]
speed: 50 feet,  fly 140 feet,  swim 70 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +31, __Ref__ +30, __Will__ +30; +1 status to all saves vs. magic"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Immunities__  acid,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Brine Spit"
    desc: "`pf2:r` (concentrate) **Trigger** A creature the brine dragon observes within 30 feet uses a concentrate action\n* * *\n\n**Effect** The dragon spits a glob of caustic salt water at the creature. The creature takes 7d6 acid damage (DC 36 Reflex check save). On a failure, the concentrate action is disrupted."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 36 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (acid, magical, reach 20 feet)\n__Damage__  3d10 + 17 piercing 5d4 acid"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (magical, reach 25 feet)\n__Damage__  3d12 + 17 bludgeoning"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+32 (magical, reach 20 feet)\n__Damage__  2d12 + 17 piercing"

  - name: "Primal Prepared Spells"
    desc: "DC 38, attack +33; __8th __  _[[Spells/Desiccate|Horrid Wilting]]_; __7th __  _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Regenerate|Regenerate]]_; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Control Water|Control Water]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_; __4th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Solid Fog|Solid Fog]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Animal Messenger|Animal Messenger]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Humanoid Form|Humanoid Form]]_, _[[Spells/Water Breathing|Water Breathing]]_; __1st __  _[[Spells/Create Water|Create Water]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Negate Aroma|Negate Aroma]]_\n__Cantrips__  __(8th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Sigil|Sigil]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Primal Innate Spells"
    desc: "DC 38, attack +30; __6th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_; __5th __  _[[Spells/Control Water|Control Water (x3)]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_; __4th __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_, _[[Spells/Mist|Obscuring Mist (At Will)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (acid,primal) The dragon breathes a spray of acidic salt water that deals 18d6 acid damage in a 120-foot line (DC 38 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The dragon tries to capsize an adjacent aquatic vessel of their size or smaller. They must succeed at an Athletics check with a DC of 35 (reduced by 5 for each size smaller the vessel is than the dragon) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Desiccating Bite"
    desc: "`pf2:2`  The dragon makes a jaws Strike. On a hit, the target takes 6d6 persistent acid damage, and is [[Conditions/Sickened|Sickened 3]] from the pain of salt and brine in its wounds."

  - name: "Painful Strikes"
    desc: " (acid) The brine dragon's body is encrusted with salty, acidic crystals. When a target takes damage from one of the dragon's melee Strikes, it must succeed at a DC 38 Fortitude check Save or be [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 3]] on a critical failure). The target then becomes temporarily immune for 1 minute."
 
```

```encounter-table
name: Brine Dragon (Ancient, Spellcaster)
creatures:
  - 1: Brine Dragon (Ancient, Spellcaster)
```



Brine dragons are usually blue-green in color, with shiny scales, crests that help them glide through the water, and sweeping neck frills. They care little for either good or evil. As they are both opinionated and willing to impose their sense of order on others, many brine dragons eventually seek to rule over a meticulously crafted community. These communities are orderly and well-planned, with rigid standards of courtesy and unchanging laws set down by the dragon themself. A settlement seeded by a brine dragon can be made of members of almost any ancestry, but the most common inhabitants are humans, merfolk, tengus, or sahuagin.

Depending on the dragon's personality, their community members might view their brine dragon ruler as anything from a benevolent force of order to a fearful tyrant. Regardless, the typical brine dragon has little patience for kindness or philanthropy, and the strength and health of their settlement as a whole are of greater concern than individuals' well-being. A notable exception to this dispassion rises when an outside force encroaches on their lands. In these cases, the brine dragon is quick to step in and aid in the defense of their community.

Although brine dragons enjoy cultivating settlements, they rarely make their lairs within the city limits, instead preferring to dwell in sea caves or cliffside grottoes overlooking the coastline. Here they can retreat for privacy as needed, or can accumulate and display their gathered wealth in a place where they feel safe spreading out their treasures. Brine dragon hoards often consist of a mix of offerings and taxes paid by those they rule over and strange discoveries salvaged from sunken ships.
