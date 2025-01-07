---
title: "Venom Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.eEgl1h08Id2MxI2T" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Venom Mage"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Venom Mage"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Arcana: +16, Deception: +20, Nature: +17, Thievery: +17"
abilityMods: [2, 4, 1, 0, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +16, __Ref__ +19, __Will__ +17"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Resistances__ poison 12"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x Dagger, Studded Leather Armor, Poisoner's Staff"
abilities_mid:
  - name: ""
  - name: "Venom Explosion"
    desc: "`pf2:r` (poison) **Trigger** The venom mage is reduced to 0 Hit Points\n* * *\n\n**Effect** The venom mage explodes into a cloud of poison within a 20-foot burst. The venom mage then reforms at a point they choose within the burst, avoids being knocked out, and remains at 1 Hit Point. The venom mage's wounded value increases by 1 when they use this ability, and they can't use this ability when they're wounded 3 or more. Creatures other than the venom mage within the burst must attempt a Fortitude save.\n* * *\n\n**Critical Success** No effect.\n\n**Success** The creature is sickened 1.\n\n**Failure** The creature is sickened 2 and cannot recover from the sickened condition while within 20 feet of the venom mage.\n\n**Critical Failure** As failure, but sickened 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+17 (agile, finesse, versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "**Melee** `pf2:1` Poisoner&#x27;s Staff"
    desc: "+17 (magical, two-hand d8)\n__Damage__  1d6 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+19 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "Primal Spontaneous Spells"
    desc: "DC 28, attack +17; __5th __ (2 slots) _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Wyvern Sting|Wyvern Sting]]_; __4th __ (3 slots) _[[Spells/Heal|Heal]]_, _[[Spells/Summon Animal|Summon Animal]]_, _[[Spells/Swarming Wasp Stings|Swarming Wasp Stings]]_; __3rd __ (3 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __ (3 slots) _[[Spells/Animal Messenger|Animal Messenger]]_, _[[Spells/Faerie Fire|Faerie Fire]]_, _[[Spells/Imp Sting|Imp Sting]]_; __1st __ (3 slots) _[[Spells/Fleet Step|Fleet Step]]_, _[[Spells/Gust of Wind|Gust of Wind]]_, _[[Spells/Spider Sting|Spider Sting]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Light|Light]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Innate Primal Spells"
    desc: "DC 28, attack +18; __2nd __  _[[Spells/Detect Poison|Detect Poison (At Will)]]_"

  - name: "Steady Spellcasting"
    desc: "  If another creature's reaction would disrupt the venom mage's spellcasting action, the venom mage attempts a DC 15 Flat check check. If the venom mage succeeds, their action isn't disrupted."
 
```

```encounter-table
name: Venom Mage
creatures:
  - 1: Venom Mage
```




