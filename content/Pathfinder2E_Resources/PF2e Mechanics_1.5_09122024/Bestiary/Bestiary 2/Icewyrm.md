---
title: "Icewyrm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.alss3n81ywstk6iE" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/cold
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Icewyrm"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Icewyrm"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[cold]]
trait_03: [[elemental]]
trait_04: [[water]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +21"
abilityMods: [7, 7, 5, -1, 5, 3]
speed: 25 feet,  swim 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +21, __Will__ +17"
hp: 185
health:
  - name: ""
  - name: HP
    desc: "185; __Immunities__  bleed,  cold,  paralyzed,  poison,  sleep; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Explosion"
    desc: " (cold) When the icewyrm dies, it explodes, dealing 8d6 cold damage to each creature in a 10-foot emanation (DC 27 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (reach 15 feet)\n__Damage__  2d12 + 13 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+23 (agile, reach 15 feet)\n__Damage__  2d6 + 13 slashing 1d6 cold"

  - name: "**Ranged** `pf2:1` Ice Shard"
    desc: "+23 (range increment 60 feet)\n__Damage__  1d6 + 13 piercing 1d6 cold"

  - name: "Breath Weapon"
    desc: "`pf2:2` (cold,primal) The icewyrm breathes a 60-foot line of freezing shards of razor-sharp ice, dealing 3d12 cold damage and 3d12 piercing damage to every creature in the line (DC 29 Reflex check save).\n\nThe icewyrm can't use Breath Weapon again for 1d4 rounds."

  - name: "Ice Burrow"
    desc: "  The Icewyrm can Burrow through ice or snow with a Speed of 20 feet. It moves at its full burrow Speed, leaving no tunnels or signs of its passing."
 
```

```encounter-table
name: Icewyrm
creatures:
  - 1: Icewyrm
```



Resembling wingless, serpentine dragons formed of jagged ice and shot through with veins of nearly frozen water, these elementals dwell within icebergs and enjoy striking out at passing ships or creatures. They're especially common in frigid stretches of ocean in the Plane of Water, where icebergs cluster together into enormous islands of ice.
