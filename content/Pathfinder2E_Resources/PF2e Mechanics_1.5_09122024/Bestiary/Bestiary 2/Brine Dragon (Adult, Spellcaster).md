---
title: "Brine Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4XTsKyEIUgMDxIPO" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/elemental
  - pf2e/creature/type/lawful
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Brine Dragon (Adult, Spellcaster)"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Brine Dragon (Adult, Spellcaster)"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[elemental]]
trait_04: [[lawful]]
trait_05: [[water]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +25, Deception: +24, Intimidation: +24, Nature: +21, Society: +21, Survival: +21"
abilityMods: [7, 2, 5, 3, 5, 6]
speed: 40 feet,  fly 120 feet,  swim 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +20, __Will__ +21; +1 status to all saves vs. magic"
hp: 222
health:
  - name: ""
  - name: HP
    desc: "222; __Immunities__  acid,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Brine Spit"
    desc: "`pf2:r` (concentrate) **Trigger** A creature the brine dragon observes within 30 feet uses a concentrate action\n* * *\n\n**Effect** The dragon spits a glob of caustic salt water at the creature. The creature takes 5d6 acid damage (DC 30 Reflex check save). On a failure, the concentrate action is disrupted."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 30 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (acid, magical, reach 15 feet)\n__Damage__  3d10 + 12 piercing 3d4 acid"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile, magical, reach 10 feet)\n__Damage__  3d8 + 12 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+24 (magical, reach 20 feet)\n__Damage__  3d12 + 12 bludgeoning"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+24 (magical, reach 15 feet)\n__Damage__  1d12 + 12 piercing"

  - name: "Primal Prepared Spells"
    desc: "DC 33, attack +26; __5th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Control Water|Control Water]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_; __4th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Solid Fog|Solid Fog]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Animal Messenger|Animal Messenger]]_, _[[Spells/Humanoid Form|Humanoid Form]]_, _[[Spells/Water Breathing|Water Breathing]]_; __1st __  _[[Spells/Create Water|Create Water]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Negate Aroma|Negate Aroma]]_\n__Cantrips__  __(5th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Sigil|Sigil]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +24; __4th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_; __3rd __  _[[Spells/Hydraulic Push|Hydraulic Push (x3)]]_; __2nd __  _[[Spells/Mist|Obscuring Mist]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (acid,primal) The dragon breathes a spray of acidic salt water that deals 13d6 acid damage in a 100-foot line (DC 32 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Desiccating Bite"
    desc: "`pf2:2`  The dragon makes a jaws Strike. On a hit, the target takes 4d6 persistent acid damage, and is [[Conditions/Sickened|Sickened 2]] from the pain of salt and brine in its wounds."
 
```

```encounter-table
name: Brine Dragon (Adult, Spellcaster)
creatures:
  - 1: Brine Dragon (Adult, Spellcaster)
```



Brine dragons are usually blue-green in color, with shiny scales, crests that help them glide through the water, and sweeping neck frills. They care little for either good or evil. As they are both opinionated and willing to impose their sense of order on others, many brine dragons eventually seek to rule over a meticulously crafted community. These communities are orderly and well-planned, with rigid standards of courtesy and unchanging laws set down by the dragon themself. A settlement seeded by a brine dragon can be made of members of almost any ancestry, but the most common inhabitants are humans, merfolk, tengus, or sahuagin.

Depending on the dragon's personality, their community members might view their brine dragon ruler as anything from a benevolent force of order to a fearful tyrant. Regardless, the typical brine dragon has little patience for kindness or philanthropy, and the strength and health of their settlement as a whole are of greater concern than individuals' well-being. A notable exception to this dispassion rises when an outside force encroaches on their lands. In these cases, the brine dragon is quick to step in and aid in the defense of their community.

Although brine dragons enjoy cultivating settlements, they rarely make their lairs within the city limits, instead preferring to dwell in sea caves or cliffside grottoes overlooking the coastline. Here they can retreat for privacy as needed, or can accumulate and display their gathered wealth in a place where they feel safe spreading out their treasures. Brine dragon hoards often consist of a mix of offerings and taxes paid by those they rule over and strange discoveries salvaged from sunken ships.
