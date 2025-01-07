---
title: "Mivanian Soldier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9adjxodUN5W15V6f" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/tengu
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Mivanian Soldier"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #190: The Choosing"
name: "Mivanian Soldier"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[tengu]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision"
languages: "Chthonian, Razatlani, Tengu"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Intimidation: +15, Stealth: +17, Survival: +15"
abilityMods: [4, 3, 4, -1, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder #190: The Choosing_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +15, __Will__ +13"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spike Launcher|Spike Launcher]], [[Equipment/Rapier|+1 Striking Rapier]], [[Equipment/Leather Armor|Leather Armor Bearing Mivanian Insignia]], [[Equipment/Manacles (Simple)|Manacles (Simple)]], 20x [[Item.247H5qGAteycBdAe|Spikes]]"
abilities_mid:
  - name: ""
  - name: "Snap Shot"
    desc: "`pf2:r`  **Requirements** The Mivanian soldier holds a loaded spike launcher\n\n**Trigger** A creature within 30 feet of the soldier uses a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The Mivanian soldier attempts a spike launcher Strike against the triggering creature. This Strike doesn't contribute to their multiple attack penalty, and their multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+19 (deadly d8, disarm, finesse, magical)\n__Damage__  2d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+18 (finesse)\n__Damage__  2d10 + 10 piercing"

  - name: "**Ranged** `pf2:1` Spike Launcher"
    desc: "+18 (backstabber, fatal d12, kickback, magical, range increment 120 feet, reload 1)\n__Damage__  2d8 + 7 piercing"

  - name: "Go For the Eyes"
    desc: "`pf2:r`  **Trigger** The Mivanian soldier critically hits with a beak Strike\n* * *\n\n**Effect** The soldier attempts to peck out his victim's eyes. The target must attempt a DC 26 Fortitude check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Critical Failure** The target is blinded until healed to its maximum Hit Points."

  - name: "Quick Spiker"
    desc: "  The soldier requires only 1 action, rather than 2 actions, to reload a spike launcher. He can change his grip on a spike launcher easily, improving its fatal aim d12 trait to fatal d12."
 
```

```encounter-table
name: Mivanian Soldier
creatures:
  - 1: Mivanian Soldier
```


Tengu soldier


