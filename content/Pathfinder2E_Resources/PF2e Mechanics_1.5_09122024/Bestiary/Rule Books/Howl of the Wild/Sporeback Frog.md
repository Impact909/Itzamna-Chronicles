---
title: "Sporeback Frog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Qau3fWatVrwQRegJ" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Sporeback Frog"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Sporeback Frog"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +12, Stealth: +13"
abilityMods: [4, 3, 5, -4, 2, 1]
speed: 25 feet,  burrow 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +12, __Will__ +9"
hp: 94
health:
  - name: ""
  - name: HP
    desc: "94; __Weaknesses__ fire 4; __Resistances__ poison 8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d8 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+15 (reach 15 feet)\n__Damage__ "

  - name: "Seed Spores"
    desc: "  A creature hit by the sporeback frog's tongue Strike takes 1d6 persistent poison damage as fungal spores begin to grow."

  - name: "Soporific Spores"
    desc: "`pf2:2` (mental,poison) The sporeback frog shakes the plants and fungi on its back until they emit a cloud of spores in a 20-foot emanation. All creatures in the area must succeed a DC 22 Fortitude check save or become [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Stupefied|Stupefied 2]] for 1 minute ([[Conditions/Clumsy|Clumsy 3]] and [[Conditions/Stupefied|Stupefied 3]] on a critical failure). This ability can't be used again for 1d4 rounds."
 
```

```encounter-table
name: Sporeback Frog
creatures:
  - 1: Sporeback Frog
```



This burrowing frog digs itself into moist earth so poisonous moss and toxic mushrooms can grow on its body.
