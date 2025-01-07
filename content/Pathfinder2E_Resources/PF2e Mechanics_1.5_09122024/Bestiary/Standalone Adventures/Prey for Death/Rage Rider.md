---
title: "Rage Rider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.c87nvT5TNcG2QI8G" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Rage Rider"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Rage Rider"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common, Skald"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Intimidation: +16, Nature: +19, Survival: +19"
abilityMods: [5, 3, 4, 0, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +20, __Ref__ +17, __Will__ +19"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Resistances__ cold 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|+1 Striking Returning Spear]], [[Equipment/Studded Leather Armor|+1 Cold-Resistant Studded Leather Armor]], [[Equipment/Harness|Exquisite Kokogiak Harness]]"
abilities_mid:
  - name: ""
  - name: "Catch and Release"
    desc: "`pf2:r`  **Requirements** The rage rider has a hand free\n\n**Trigger** An enemy critically misses the rage rider with a thrown weapon attack\n* * *\n\n**Effect** The rage rider catches the thrown weapon and makes a ranged Strike with it."

  - name: "Exquisite Kokogiak Harness"
    desc: "  A rage rider is equipped with an exquisitely crafted harness when riding a kokogiak. Two rage riders can ride a willing kokogiak at once using such a harness, and both of their hands remain free while doing so. When a rage rider is attached to a kokogiak, they can't use any action that uses their speed (such as Step or Stride), and all DCs to forcibly move the rage rider or to knock them from their mount are increased by 5. If a kokogiak being ridden by a rage rider using such a harness is killed or falls [[Conditions/Unconscious|Unconscious]], the rage rider takes 3d6 bludgeoning damage from the fall (DC 30 Reflex check save). A rage rider can release their harness with an Interact action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+22 (magical)\n__Damage__  2d6 + 11 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+20 (magical, thrown 20 ft.)\n__Damage__  2d6 + 11 piercing"

  - name: "Ruinous Rage"
    desc: "`pf2:1` (concentrate,emotion,mental) The rage rider enters a state of pure rage that lasts either for 1 minute, until there are no enemies they can perceive, or until they fall [[Conditions/Unconscious|Unconscious]], whichever comes first. While raging, the rage rider has AC 27 and their spear Strikes deal 2d6+15 damage plus 2d6 persistent bleed damage. While raging, the rage rider can't use actions that have the concentrate trait, except for [[Actions/Seek|Seek]]. After they've stopped raging, a rage rider can't use Rage again for 1 minute."
 
```

```encounter-table
name: Rage Rider
creatures:
  - 1: Rage Rider
```


Human barbarian


