---
title: "Raskus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rfRNK1DRwPDLfYrc" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/tengu
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Raskus"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #190: The Choosing"
name: "Raskus"
level: "Creature 10"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[tengu]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision"
languages: "Chthonian, Razatlani, Tengu"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +19, Intimidation: +19, Religion: +18, Stealth: +21"
abilityMods: [3, 5, 2, 0, 2, 3]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #190: The Choosing_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +16, __Ref__ +21, __Will__ +18"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spike Launcher|Spike Launcher]], [[Equipment/Rapier|+1 Striking Rapier]], [[Equipment/Leather Armor|+1 Leather Armor]], [[Equipment/Manacles (Simple)|Manacles (Simple)]], 20x [[Item.247H5qGAteycBdAe|Spikes]]"
abilities_mid:
  - name: ""
  - name: "Snap Shot"
    desc: "`pf2:r`  **Requirements** Raskus holds a loaded spike launcher\n\n**Trigger** A creature within 30 feet of Raskus uses a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** Raskus attempts a spike launcher Strike against the triggering creature. This Strike doesn't contribute to his multiple attack penalty, and his multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+22 (deadly d8, disarm, finesse, magical)\n__Damage__  2d6 + 11 slashing"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+21 (finesse)\n__Damage__  2d4 + 11 piercing"

  - name: "**Ranged** `pf2:1` Spike Launcher"
    desc: "+22 (backstabber, fatal d12, kickback, magical, range increment 120 feet, reload 1)\n__Damage__  2d8 + 9 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Earthbind|Earthbind]]_"

  - name: "Go For the Eyes"
    desc: "`pf2:r`  **Trigger** Raskus critically hits with a beak Strike\n* * *\n\n**Effect** Raskus attempts to peck out his victim's eyes. The target must attempt a DC 29 Fortitude check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Critical Failure** The target is blinded until healed to its maximum Hit Points."

  - name: "Opportunistic Attack"
    desc: "  Raskus's Strikes deal an additional 3d6 damage to any foe that has a reduction to its Speed, is [[Conditions/Blinded|Blinded]], or is [[Conditions/Immobilized|Immobilized]]."

  - name: "Quick Spiker"
    desc: "  Raskus requires only 1 action, rather than 2 actions, to reload a spike launcher. He can change his grip on a spike launcher easily, improving its fatal aim d12 trait to fatal d12."
 
```

```encounter-table
name: Raskus
creatures:
  - 1: Raskus
```


Male tengu commander


