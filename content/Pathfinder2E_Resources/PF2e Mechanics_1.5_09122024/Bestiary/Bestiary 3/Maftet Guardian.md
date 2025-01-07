---
title: "Maftet Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.G7aBir2E8MuT0RVd" 
tags:
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Maftet Guardian"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Maftet Guardian"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Sphinx"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Arcana: +13, Athletics: +15, Stealth: +13, Ruins Lore (Applies Only to Their Home Ruins): +15"
abilityMods: [5, 3, 4, 3, 2, 0]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +15, __Will__ +12"
hp: 92
health:
  - name: ""
  - name: HP
    desc: "92"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Scimitar|Scimitar]]"
abilities_mid:
  - name: ""
  - name: "Runic Resistance"
    desc: "`pf2:r` (arcane) **Trigger** The maftet takes damage from a Strike or spell effect\n* * *\n\n**Effect** The maftet's protective runic tattoos glow, granting them resistance 5 to one damage type dealt by the triggering attack.\n\nThis resistance applies against the triggering effect and lasts for 1 minute or until the maftet uses this ability again, whichever comes first. If the triggering effect deals multiple damage types, the maftet chooses which type to resist.\n\n[[Bestiary Effects/Effect_ Runic Resistance|Effect: Runic Resistance]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+17 (forceful, magical, sweep)\n__Damage__  2d6 + 8 slashing"

  - name: "Arcane Innate Spells"
    desc: "DC 23, attack +15; __1st __  _[[Spells/Sanctuary|Sanctuary (x3)]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(3rd)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Paired Strike"
    desc: "`pf2:2`  **Requirements** The maftet is wielding two scimitars\n* * *\n\n**Effect** The maftet makes two Strikes against the same target, one with each of their scimitars. The maftet combines the damage of any attacks that hit and applies resistances and weaknesses only once. This counts as one attack when calculating the maftet's multiple attack penalty."

  - name: "Powerful Scimitars"
    desc: " (arcane) Any non-magical scimitar becomes a _+1 striking scimitar_ while a maftet wields it."

  - name: "Raptor Dive"
    desc: "`pf2:3`  **Requirements** The maftet is flying at least 10 feet above the target\n* * *\n\n**Effect** The maftet Flies up to twice their fly Speed and makes a Paired Strike at the end of the movement. If both Strikes hit, the target is also knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Maftet Guardian
creatures:
  - 1: Maftet Guardian
```



Maftets are hawk-winged humanoids with leonine lower bodies that dwell in ancient ruins and cities thought lost, typically in desert or mountain regions. They view themselves as guardians and practice a specialized technique of dualwielding scimitars so central to their culture that a maftet's scimitars are often cherished family heirlooms. Most maftets venerate their ancestors in addition to various deities, and even a child can detail their family lineage back multiple generations. Maftet prides tend to be matriarchal and isolationist, though maftets aren't necessarily hostile to outsiders who respect their homes and don't seek to loot them.

When a young maftet comes of age, they receive runic tattoos from a pride's elder. These tattoos are imbued with magic that allows a maftet to enchant their wielded weapons, but the individualized designs tell of the maftet's ancestors, childhood adventures, and positive qualities. Such tattoos are considered sacred and never given to non-maftets.
