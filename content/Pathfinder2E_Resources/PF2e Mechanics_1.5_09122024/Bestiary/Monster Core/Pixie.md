---
title: "Pixie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i2zTODP0CrphwDBv" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/sprite
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Pixie"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Pixie"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[fey]]
trait_02: [[sprite]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Deception: +11, Nature: +10, Stealth: +11"
abilityMods: [-1, 5, 1, 3, 2, 3]
speed: 15 feet,  fly 45 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +8, __Ref__ +14, __Will__ +12; +1 status to all saves vs. magic"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longbow|Longbow]], [[Equipment/Shortsword|Shortsword]], 60x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+13 (agile, finesse, magical, versatile s)\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+13 (deadly d10, magical, range increment 100 feet, reload 0, volley 20 ft.)\n__Damage__  1d8 + 4 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 21, attack +13; __4th __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_; __3rd __  _[[Spells/Dispel Magic|Dispel Magic]]_; __2nd __  _[[Spells/Entangling Flora|Entangling Flora]]_, _[[Spells/Revealing Light|Revealing Light]]_; __1st __  _[[Spells/Illusory Disguise|Illusory Disguise]]_\n__Cantrips__  __(2nd)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Light|Light]]_, _[[Spells/Shield|Shield]]_"

  - name: "Sprinkle Pixie Dust"
    desc: "`pf2:1` (manipulate,primal) The pixie sprinkles pixie dust onto one of their arrows. If the pixie hits a creature with that arrow before the pixie's next turn, the arrow inflicts one of the following special effects of the pixie's choice instead of dealing damage. Each effect depends on the target's DC 21 Will check save. On a critical hit, the target gets a result one degree worse than it rolled.\n\n*   **Charm** (emotion, incapacitation, mental) The arrow has the effect of a [[Spells/Charm|Charm]] spell, except the target doesn't gain a bonus to its save if the only hostile act was the pixie firing its bow, and the pixie can choose to direct the target's adoration toward another creature rather than itself.\n*   **Memory Loss** (mental) On a failed Will save, the target loses the last 5 minutes of its memory.\n*   **Sleep** (incapacitation, mental, sleep) The target suffers the effects of a 3rd-rank [[Spells/Sleep|Sleep]] spell.\n*   **Subdual** (mental, nonlethal) The target takes 4d6 mental damage, depending on its basic Will save."
 
```

```encounter-table
name: Pixie
creatures:
  - 1: Pixie
```



Insatiably curious, overly excitable, and just a bit puckish, pixies are wanderers and tricksters who use their pixie dust to create all sorts of whimsical situations, as well as to defend themselves. They take great pride in their skill at archery, even when not using their arrows to deliver magical ailments. They often practice by shooting drops of dew or severing vines and hairs. Other creatures often have trouble understanding a pixie's rapid, rambling way of speaking.

* * *

Elusive, flighty, and ebullient, sprites are what many villagers first imagine when they hear the terms "fey" or "fairy." While their dispositions vary, all sprites share a connection to magic and a diminutive size. This family of fey shares its name with its slightest and most populous member, the common sprite.
