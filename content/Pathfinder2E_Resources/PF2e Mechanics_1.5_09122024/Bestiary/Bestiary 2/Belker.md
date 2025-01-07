---
title: "Belker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w9KiHYTMGJ9uMZoV" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Belker"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Belker"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[elemental]]
trait_03: [[evil]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Stealth: +15"
abilityMods: [2, 5, 3, -2, 4, 0]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +17, __Will__ +12"
hp: 78
health:
  - name: ""
  - name: HP
    desc: "78; __Immunities__  bleed,  paralyzed,  poison,  precision,  sleep"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  The belker ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "Smoke Form"
    desc: "  The belker can occupy the same space as other creatures."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile, finesse)\n__Damage__  2d10 + 5 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+17 (agile, finesse, reach 10 feet)\n__Damage__  2d8 + 5 bludgeoning"

  - name: "Noxious Fumes"
    desc: "`pf2:2`  **Requirements** The belker occupies the same space as a Medium or smaller creature\n* * *\n\n**Effect** The belker attempts to flow into the creature's lungs; the creature must attempt a DC 23 Fortitude check save. On a failure, the creature partially inhales the belker and is [[Conditions/Immobilized|Immobilized]] by the pain of the smoke rasping in its throat and lungs. The creature can attempt to exhale the belker by spending an action coughing and succeeding at a DC 23 Fortitude check save. Most of the belker remains outside the creature, so the belker can still act normally. If the belker moves out of the creature's space or uses Noxious Fumes again, the creature automatically exhales it."

  - name: "Smoke Slash"
    desc: "`pf2:1`  **Requirements** The belker is partially inhaled by a creature\n* * *\n\n**Effect** The belker automatically deals its claw damage to the inhaling creature by forming a claw to slash and scrape the creature from within."
 
```

```encounter-table
name: Belker
creatures:
  - 1: Belker
```



These reclusive elementals have glowing red eyes, leathery wings, and long, sharp claws. While they always retain their shape, belkers can control the solidity of their forms at will, transforming into clouds of smoke, ash, and dust.
