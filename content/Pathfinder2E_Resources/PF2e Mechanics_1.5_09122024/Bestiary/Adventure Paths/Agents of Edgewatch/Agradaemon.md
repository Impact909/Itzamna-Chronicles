---
title: "Agradaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iEpvvieTOhWnOgup" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/fire
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Agradaemon"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Agradaemon"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[fire]]
trait_05: [[unholy]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; "
languages: "Common, Daemonic, Pyric; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Deception: +37, Diplomacy: +37, Intimidation: +39"
abilityMods: [6, 10, 5, 6, 5, 10]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +31, __Ref__ +36, __Will__ +31; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  death effects,  fire; __Weaknesses__ cold 20, holy 20"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair an agradaemon's vision; it ignores the concealed condition from smoke."

abilities_mid:
  - name: ""
  - name: "Choking Smog"
    desc: " (air,aura,fire) 100 feet. The agradaemon is surrounded by ashy smoke. Creatures within the aura are concealed, and creatures outside of it are concealed to creatures within it. Non-daemon creatures can't breathe in the aura and must hold their breath or suffocate."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, finesse, magical, reach 15 feet, unholy)\n__Damage__  2d12 + 14 slashing 2d6 fire 2d6 spirit"

  - name: "**Ranged** `pf2:1` Lava Bomb"
    desc: "+35 (range increment 100 feet, splash, unholy)\n__Damage__  4d8 fire 2d6 fire 8 fire"

  - name: "Divine Innate Spells"
    desc: "DC 41, attack +33; __10th __  _[[Spells/Massacre|Massacre]]_; __8th __  _[[Spells/Volcanic Eruption|Volcanic Eruption (x3)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Good Only)]]_"

  - name: "Daemonic Pledge"
    desc: "`pf2:3` (divine,healing) **Frequency** once per day\n* * *\n\n**Effect** The agradaemon designates a single willing mortal as a pledged fanatic. That creature gains resistance to fire equal to its level, immunity to the agradaemon's choking smog aura, and smoke vision.\n\nThe agradaemon can have up to 10 pledged fanatics at one time and can remove the status from any number of pledged fanatics as a free action with the concentrate trait. The status can also be removed with an [[Spells/Atone|Atone]] ritual."

  - name: "Proven Devotion"
    desc: "`pf2:1` (concentrate,fire) The agradaemon regains 15 untyped Hit Points, and a pledged fanatic of the agradaemon's choice that it can see loses 15 Hit Points (no effects apply that would decrease this Hit Point loss).\n\nA pledged creature that dies in this way explodes and deals 9d10 fire damage in a 20-foot emanation (DC 41 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Agradaemon
creatures:
  - 1: Agradaemon
```




