---
title: "Caligni Dancer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nwvv3xtobtac3szg" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Caligni Dancer"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Caligni Dancer"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[caligni]]
trait_02: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Greater Darkvision"
languages: "Caligni"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Diplomacy: +8, Performance: +6, Stealth: +7, Thievery: +7"
abilityMods: [0, 4, 2, -1, 1, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +9, __Will__ +4"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18, final dance"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Light Mace|Baton (Light Mace)]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Distracting Frolic"
    desc: "`pf2:r` (fortune,manipulate) **Trigger** An ally within 10 feet of the dancer rolls a saving throw against a mental or illusion effect\n* * *\n\n**Effect** The target ally can roll the save twice and take the better result.\n\n[[Bestiary Effects/Effect_ Distracting Frolic|Effect: Distracting Frolic]]"

  - name: "Final Dance"
    desc: " (occult,shadow,visual) When the dancer dies, their body dissolves into a swirling mass of darkness and light. All creatures in a 10-foot emanation must succeed at a DC 17 Will check save or be [[Conditions/Dazzled|Dazzled]] for 1d4 rounds.\n\nThe dancer's possessions are left in a pile where they died."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Baton"
    desc: "+9 (agile, finesse, shove)\n__Damage__  1d4 bludgeoning"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+9 (agile, finesse, versatile s)\n__Damage__  1d4 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+9 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 16, attack +8; __1st __  _[[Spells/Counter Performance|Counter Performance (Visual Only)]]_\n__Cantrips__  __(1st)__ _[[Spells/Courageous Anthem|Courageous Anthem]]_"

  - name: "Dancer's Curse"
    desc: "`pf2:1` (curse,mental,occult) The caligni dancer touches a foe and curses it.\n\nIf the target fails a DC 18 Will check save, it gains [[Conditions/Clumsy|Clumsy 1]] and [[Conditions/Stupefied|Stupefied 1]].\n\nThe target is then temporarily immune for 24 hours.\n\nThese conditions persist until the curse is removed. The victim can attempt a new DC 18 Will check save once per hour to end the curse."

  - name: "Sneak Attack"
    desc: "  The caligni dancer deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Caligni Dancer
creatures:
  - 1: Caligni Dancer
```



Caligni dancers serve as intermediaries between caligni factions, carrying messages and negotiating deals between the notoriously independent groups. Although physically fragile, the dancers serve an important role within caligni society and are rarely seen without guards.

* * *

Calignis lurk in subterranean cities, with each caligni growing into a specific role and form determined by supernatural influences in caligni society. Regardless of their size or role, all calignis are gaunt, with pale flesh and white eyes. Many relish the chance to creep above ground at night to steal resources, shadow their surface counterparts, or simply make mischief.
