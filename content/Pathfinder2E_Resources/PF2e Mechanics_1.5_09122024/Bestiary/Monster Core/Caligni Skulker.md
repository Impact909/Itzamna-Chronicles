---
title: "Caligni Skulker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WNIkA76L1bRXCbun" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Caligni Skulker"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Caligni Skulker"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[caligni]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Greater Darkvision"
languages: "Caligni"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +4, Stealth: +10, Thievery: +8"
abilityMods: [0, 4, 3, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +9, __Ref__ +10, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, final night"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], 3x [[Equipment/Darkening Poison|Darkening Poison]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Final Night"
    desc: " (darkness,occult) When the caligni skulker dies, their remains dissolve into a 20-foot emanation of inky darkness before dissipating. The darkness extinguishes non-magical light sources and attempts to counteract magical light as a 1st-rank effect with a +10 counteract modifier.\n\nThe skulker's possessions are left in a pile where they died."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+10 (agile, finesse, versatile s)\n__Damage__  1d4 + 4 piercing plus darkening-poison"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+10 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 piercing plus darkening-poison"

  - name: "Sneak Attack"
    desc: "  The caligni skulker deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Tumble Behind"
    desc: "  When the caligni skulker Tumbles Through a creature's space, that creature is [[Conditions/Off-Guard|Off-Guard]] against the next attack the skulker makes against it before the end of its turn."
 
```

```encounter-table
name: Caligni Skulker
creatures:
  - 1: Caligni Skulker
```



Most often found on the surface are caligni skulkers, stealing staple goods and luxuries alike. When pressed into combat by more powerful caligni, skulkers will often be sacrificed in waves to wear down the enemy. Otherwise, skulkers are fairly cautious and prefer to flee unwinnable situations.

* * *

Calignis lurk in subterranean cities, with each caligni growing into a specific role and form determined by supernatural influences in caligni society. Regardless of their size or role, all calignis are gaunt, with pale flesh and white eyes. Many relish the chance to creep above ground at night to steal resources, shadow their surface counterparts, or simply make mischief.
