---
title: "Barded Manticore"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2tsXgS3oZ39avuQc" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Barded Manticore"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Barded Manticore"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Mwangi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +35, Crafting: +29, Deception: +32, Intimidation: +32, Nature: +31"
abilityMods: [9, 5, 6, 1, 5, 6]
speed: 40 feet,  fly 45 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +32, __Ref__ +30, __Will__ +29"
hp: 440
health:
  - name: ""
  - name: HP
    desc: "440; __Weaknesses__ electricity 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
  - name: "Spell Reflection"
    desc: "`pf2:r`  **Trigger** An opponent casts a spell that targets the manticore and requires a saving throw\n* * *\n\n**Effect** The manticore gains a +4 circumstance bonus to the saving throw. If they critically succeed at the save, they can choose a creature within 30 feet that was not originally targeted by the spell. That creature becomes a new target of the spell, who must attempt its own save against the same DC."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (magical, reach 10 feet)\n__Damage__  3d10 + 15 piercing 1d12 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical)\n__Damage__  3d8 + 15 slashing 1d12 electricity"

  - name: "**Ranged** `pf2:1` Spike"
    desc: "+31 (magical, range increment 40 feet)\n__Damage__  3d8 + 15 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +35; __9th __  _[[Spells/Wrathful Storm|Wrathful Storm]]_; __8th __  _[[Spells/Chain Lightning|Chain Lightning]]_; __6th __  _[[Spells/Field of Razors|Field of Razors]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Impaling Spike|Impaling Spike (At-Will)]]_, _[[Spells/Lightning Bolt|Lightning Bolt (At-Will)]]_; __3rd __  _[[Spells/One with Stone|One with Stone (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Metal|Detect Metal]]_, _[[Spells/Needle Darts|Needle Darts]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Arrange Scales"
    desc: "`pf2:1`  The barded manticore flexes the muscles under their scales to temporarily gain better protection. The manticore gains a +2 circumstance bonus to AC and resistance 15 to their choice of bludgeoning, piercing, or slashing damage. These benefits last until the beginning of the manticore's next turn or they use Arrange Scales again."

  - name: "Metallic Coating"
    desc: "  A barded manticore's unarmed attacks (including spikes) count as adamantine, cold iron, dawnsilver, and silver."

  - name: "Paired Spikes"
    desc: "`pf2:1`  The barded manticore flings two spikes from their tail, targeting up to two creatures within 20 feet of each other. They make a separate ranged Strike against each creature, which counts as a single Strike for the barded manticore's multiple attack penalty, and the penalty doesn't increase until they've made both Strikes. If the manticore targeted only one creature and hits, that creature takes normal damage for a single spike, but also gains weakness 15 to electricity damage until the spikes are removed with an Interact action.\n\n[[Bestiary Effects/Effect_ Paired Spikes|Effect: Paired Spikes]]"
 
```

```encounter-table
name: Barded Manticore
creatures:
  - 1: Barded Manticore
```




