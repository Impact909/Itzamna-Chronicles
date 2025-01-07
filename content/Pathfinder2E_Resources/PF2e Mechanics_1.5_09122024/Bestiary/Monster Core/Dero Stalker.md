---
title: "Dero Stalker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1EwDrgPbEIuDcTe6" 
tags:
  - pf2e/creature/type/dero
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Dero Stalker"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dero Stalker"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[dero]]
trait_02: [[humanoid]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Aklo, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Medicine: +5, Stealth: +8, Thievery: +8"
abilityMods: [2, 4, 3, 0, -1, 1]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +10, __Will__ +3"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30; __Immunities__  confused"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Club|Club]], [[Equipment/Rope|Rope]], [[Equipment/Healer's Toolkit|Cytillesh Toolkit]], 20x [[Equipment/Bolts|Bolts]], 2x [[Equipment/Lethargy Poison|Lethargy Poison]]"
abilities_mid:
  - name: ""
  - name: "Vulnerable to Sunlight"
    desc: "  A dero stalker takes 4 damage for every hour they're exposed to sunlight."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+8 ()\n__Damage__  1d6 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Club"
    desc: "+10 (thrown 10 ft.)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+10 (range increment 60 feet, reload 1)\n__Damage__  1d6 piercing plus lethargy-poison"

  - name: "Occult Innate Spells"
    desc: "DC 17, attack +9\n__Cantrips__  __(1st)__ _[[Spells/Daze|Daze]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Dero Medicine"
    desc: "`pf2:1` (healing,manipulate) **Requirements** The dero is wearing a cytillesh toolkit and has a hand free\n* * *\n\n**Effect** The dero excises damaged flesh and crudely stitches wounds shut, healing themself or an ally in reach for 2d8 Hit Points. For 1 hour, the target has slashing weakness 2 and is immune to Dero Medicine.\n\n[[Bestiary Effects/Effect_ Dero Medicine|Effect: Dero Medicine]]"

  - name: "Exploit Lethargy"
    desc: "  A creature afflicted with [[Equipment/Lethargy Poison|Lethargy Poison]] is [[Conditions/Off-Guard|Off-Guard]] to the dero stalker, and the stalker can choose to add the nonlethal trait to their attacks against the creature without taking the normal penalty."

  - name: "Sneak Attack"
    desc: "  A dero stalker deals 1d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."
 
```

```encounter-table
name: Dero Stalker
creatures:
  - 1: Dero Stalker
```



Dero stalkers explore the surface world by night, seeking out victims to abduct. While hiding from the burning light of day, stalkers often assist with magisters' experiments.

* * *

Deros are short, wiry humanoids with milky white eyes, gray-blue skin, and wild shocks of off-white or gray hair. The descendants of a mysterious type of fey abandoned in the deepest, darkest caverns of Golarion, deros are the subject of fearful legends and folk tales to most of the world's surface races. They skulk beneath major metropolitan areas, performing cruel and twisted experiments on unwilling subjects.

Deros, particularly the leading magisters, are fixated with curing their allergy to sunlight. To understand how the surface dwellers can withstand the light of the sun, deros conduct late-night raids on surface cities, abducting victims and performing terrible experiments on them. Those who survive are often returned with much of their memory erased and their bodies bearing mysterious scars.

The largest dero settlements are built around esoteric machines of floating crystals. As these crystals grind against each other and hum with sickening blue energy, crystal flakes and powdery residue collect beneath the machinery. Dero magisters gather these products, creating tools and repurposing the crystals to power magical items.
