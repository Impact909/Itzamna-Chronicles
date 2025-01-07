---
title: "Ibrique"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.z6ovBf6GGIGIMC3t" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Ibrique"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Shadows at Sundown"
name: "Ibrique"
level: "Creature 13"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Aklo, Common, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Crafting: +25, Deception: +24, Occultism: +25, Performance: +24, Stealth: +27"
abilityMods: [4, 8, 5, 6, -1, 5]
speed: 25 feet,  burrow 10 feet
sourcebook: "_Pathfinder Adventure: Shadows at Sundown_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +25, __Ref__ +28, __Will__ +21"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Leather Armor|+1 Resilient Leather Armor]]"
abilities_mid:
  - name: ""
  - name: "Vulnerable to Sunlight"
    desc: "  Ibrique takes 20 damage for each hour she is exposed to sunlight."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (finesse)\n__Damage__  3d10 + 10 piercing plus ghoul-ghoul-fever,profane-paralysis 2d6 void plus ghoul-ghoul-fever,profane-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, finesse)\n__Damage__  3d6 + 10 slashing plus profane-paralysis 2d6 void plus profane-paralysis"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Noise Blast|Sound Burst]]_; __6th __  _[[Spells/Rewrite Memory|Modify Memory]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Teleport|Teleport]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Confusion|Confusion (x3)]]_; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Cytillesh Stare"
    desc: "`pf2:1` (concentrate,incapacitation,mental,visual) **Frequency** once per round\n* * *\n\n**Effect** Ibrique focuses her gaze on a creature she can see within 30 feet. The target is [[Conditions/Dazzled|Dazzled]] for 1 round and must succeed at a DC 33 Will check save or be [[Conditions/Confused|Confused]] for 1 round."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 33 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "Profane Paralysis"
    desc: "  Any living, non-elf creature hit by Ibrique's attack must attempt a DC 33 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]].\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."
 
```

```encounter-table
name: Ibrique
creatures:
  - 1: Ibrique
```


Female variant dero ghoul


