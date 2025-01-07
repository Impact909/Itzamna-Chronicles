---
title: "Xulgath Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.A0W5fFxOtUSFoJcq" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Xulgath Mage"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #152: Legacy of the Lost God"
name: "Xulgath Mage"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Arcana: +12, Athletics: +13, Deception: +15, Intimidation: +17, Society: +9, Survival: +12"
abilityMods: [1, 2, 1, 0, 1, 5]
speed: 25 feet
sourcebook: "_Pathfinder #152: Legacy of the Lost God_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +13, __Will__ +14"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Light Mace|+1 Light Mace]]"
abilities_mid:
  - name: ""
  - name: "Counterspell"
    desc: "`pf2:r`  **Trigger** A creature Casts a Spell the xulgath mage has in its repertoire\n* * *\n\n**Effect** The xulgath mage expends one of its spell slots to counter the triggering creature's casting of the spell in its repertoire. The xulgath mage loses the spell slot as if it had cast the triggering spell and attempts to counteract the triggering spell."

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature entering the aura must attempt a DC 25 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, the creature also takes a -5-foot status penalty to its Speeds for 1 round. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stench for 1 minute.\n\n[[Bestiary Effects/Effect_ Xulgath Stench|Effect: Xulgath Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Light Mace"
    desc: "+15 (agile, magical, shove)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  1d8 + 2 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile)\n__Damage__  2d6 + 2 slashing"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 26, attack +18; __4th __ (3 slots) _[[Spells/Acid Arrow|Acid Arrow]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_; __3rd __ (4 slots) _[[Spells/Fireball|Fireball]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Force Barrage|Magic Missile]]_; __2nd __ (4 slots) _[[Spells/Create Food|Create Food]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Floating Flame|Flaming Sphere]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __ (4 slots) _[[Spells/Breathe Fire|Burning Hands]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(4th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Bloodline Spells"
    desc: "3 Focus Points, DC 26, attack +16; __4th __ (2 slots) _[[Spells/Ancestral Memories|Ancestral Memories]]_, _[[Spells/Extend Spell|Extend Spell]]_"
 
```

```encounter-table
name: Xulgath Mage
creatures:
  - 1: Xulgath Mage
```




