---
title: "Vampire Squid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0nRfriFYVg8OtcSp" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Vampire Squid"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Vampire Squid"
level: "Creature 0"

alignment: ""
size: "Small"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +4, Stealth: +7"
abilityMods: [0, 3, 0, -4, 3, -2]
speed:  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +4, __Ref__ +8, __Will__ +6"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Resistances__ cold 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+7 (finesse)\n__Damage__  1d8 piercing"

  - name: "**Melee** `pf2:1` Tentacles"
    desc: "+7 (agile, finesse)\n__Damage__  1d6 bludgeoning"

  - name: "Glowing Mucus"
    desc: "`pf2:1`  **Frequency** once per day\n\n**Requirements** The vampire squid is in water\n* * *\n\n**Effect** The vampire squid ejects a cloud of bioluminescent mucus in a 15-foot cone. Non-squid creatures within the cloud must attempt a DC 16 Fortitude check save or become [[Conditions/Sickened|Sickened 1]]. The glowing mucus remains in the area for 1 minute, and any creature that ends its turn in the area must succeed at a DC 13 Fortitude check save or become [[Conditions/Sickened|Sickened 1]]."
 
```

```encounter-table
name: Vampire Squid
creatures:
  - 1: Vampire Squid
```



Vampire squid are neither undead nor blood drinkers. Their name is instead inspired by their red eyes and the dark, cloak-like webbing between their arms. Living in the lightless depths of the ocean, the vampire squid can eject a cloud of bioluminescent mucus that nauseates predators.
