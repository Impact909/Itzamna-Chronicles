---
title: "Totenmaske"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.D0MvM2aMCNqqE81d" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Totenmaske"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Totenmaske"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Deception: +17, Stealth: +17, Thievery: +15"
abilityMods: [4, 6, 2, 1, 2, 3]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +17, __Will__ +13"
hp: 128
health:
  - name: ""
  - name: HP
    desc: "128, (void healing); __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (finesse)\n__Damage__  2d6 + 7 piercing 2d6 void"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (agile, finesse)\n__Damage__  2d8 + 7 slashing"

  - name: "Drink Flesh"
    desc: "`pf2:1` (divine) **Requirements** The totenmaske hit the same enemy with two claw Strikes this turn and is still adjacent to it\n* * *\n\n**Effect** The totenmaske drains flesh from the creature's body. The creature becomes [[Conditions/Sickened|Sickened 2]] and [[Conditions/Drained|Drained 1]] unless it succeeds at a DC 25 Fortitude check save ([[Conditions/Sickened|Sickened 2]] and [[Conditions/Drained|Drained 2]] on a critical failure)."

  - name: "Living Form"
    desc: "`pf2:1` (concentrate,divine,polymorph) The totenmaske takes the appearance of a Medium or smaller humanoid creature. This is either its form from before it became undead, or the form of the last creature it successfully hit with Drink Flesh.\n\nThis doesn't change the totenmaske's Speed or the attack and damage bonuses for its Strikes, but might change the damage type its Strikes deal (typically to bludgeoning)."

  - name: "Shape Flesh"
    desc: " (curse,divine) After spending 1 minute in contact with a [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Unconscious|Unconscious]], or willing creature, a totenmaske can reshape the target's face, causing flesh to cover vital features.\n\nThe target can attempt a DC 25 Fortitude check save to resist; a critical success grants temporary immunity to Shape Flesh for 24 hours.\n\nEach time the totenmaske Shapes Flesh, it chooses one feature: ears (target becomes [[Conditions/Deafened|Deafened]]), eyes (target becomes [[Conditions/Blinded|Blinded]]), mouth (target can't speak or eat), or nose (target can't smell). A creature with both its nose and mouth sealed can't breathe and begins to suffocate.\n\nChanges are permanent until reversed by removing this curse, or the sealed flesh can be surgically opened with a DC 25 Medicine check check that takes 1d4 rounds and deals 1d6 slashing damage per round."
 
```

```encounter-table
name: Totenmaske
creatures:
  - 1: Totenmaske
```



Spawned by the same unnatural and self-destructive obsessions that drove them when they were alive, totenmaskes are the undead remnants of the most self-indulgent and sinful among us. Though unable to sate their perverse desires, these foul undead can drain the very flesh from their victims so as to wrap themselves in a perverse mockery of life that allows them to pursue their base wants. Totenmaskes' specific longings vary-one might be obsessed with food or drink, while another might be vain and desirous of an attractive form to marvel at in a mirror, while yet another could simply long for the scent of blood. Whatever the sensation the totenmaske seeks, it is always a vice taken to extreme, for this sin is what helped condemn it to unlife in the first place. A totenmaske obsessed with food, for example, might find itself assaulting bakeries or breweries, while a vain totenmaske obsessed with glamor could quickly grow bored of each new look and switch its victims out daily, or even hourly.
