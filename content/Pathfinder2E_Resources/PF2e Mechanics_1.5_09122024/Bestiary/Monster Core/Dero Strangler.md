---
title: "Dero Strangler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V759oZfwpNWOj09g" 
tags:
  - pf2e/creature/type/dero
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Dero Strangler"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dero Strangler"
level: "Creature 3"

alignment: ""
size: "Small"
trait_01: [[dero]]
trait_02: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Aklo, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +7, Medicine: +6, Stealth: +10"
abilityMods: [4, 3, 3, 0, -1, 2]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +10, __Ref__ +8, __Will__ +6"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  confused"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Spiked Chain|Spiked Chain]], [[Equipment/Rope|Rope]], [[Equipment/Healer's Toolkit|Cytillesh Toolkit]], 5x [[Equipment/Lethargy Poison|Lethargy Poison]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Ill Glow"
    desc: " (disease,light) A non-dero living creature that starts its turn [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the strangler is exposed to the sickly blue light from the strangler's cytillesh toolkit. It must succeed at a DC 19 Fortitude check save or become [[Conditions/Sickened|Sickened 1]]. This has no effect if the strangler isn't wearing the toolkit."

  - name: "Vulnerable to Sunlight"
    desc: "  A dero strangler takes 8 damage for every hour they're exposed to sunlight."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+11 (disarm, trip)\n__Damage__  1d8 + 6 bludgeoning"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+10 (range increment 60 feet, reload 1)\n__Damage__  1d6 + 2 piercing plus lethargy-poison"

  - name: "Occult Innate Spells"
    desc: "DC 19, attack +11; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Revealing Light|Revealing Light]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Dero Medicine"
    desc: "`pf2:1` (healing,manipulate) **Requirements** The dero is wearing a cytillesh toolkit and has a hand free\n* * *\n\n**Effect** The dero excises damaged flesh and crudely stitches wounds shut, healing themself or an ally in reach for 2d8 Hit Points. For 1 hour, the target has slashing weakness 2 and is immune to Dero Medicine.\n\n[[Bestiary Effects/Effect_ Dero Medicine|Effect: Dero Medicine]]"

  - name: "Strangle"
    desc: "`pf2:1` (attack,nonlethal) **Requirements** The dero must have two free hands or be wielding a spiked chain\n* * *\n\n**Effect** The dero attempts an Athletics check to [[Actions/Grapple|Grapple]] with a +2 circumstance bonus. On a success, the target also takes 1d6+6 bludgeoning damage and can't speak (including to Cast a Spell) as long as they're [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]."
 
```

```encounter-table
name: Dero Strangler
creatures:
  - 1: Dero Strangler
```



Dero stranglers specialize in capturing living victims, and they are often called upon to aid in abductions.

* * *

Deros are short, wiry humanoids with milky white eyes, gray-blue skin, and wild shocks of off-white or gray hair. The descendants of a mysterious type of fey abandoned in the deepest, darkest caverns of Golarion, deros are the subject of fearful legends and folk tales to most of the world's surface races. They skulk beneath major metropolitan areas, performing cruel and twisted experiments on unwilling subjects.

Deros, particularly the leading magisters, are fixated with curing their allergy to sunlight. To understand how the surface dwellers can withstand the light of the sun, deros conduct late-night raids on surface cities, abducting victims and performing terrible experiments on them. Those who survive are often returned with much of their memory erased and their bodies bearing mysterious scars.

The largest dero settlements are built around esoteric machines of floating crystals. As these crystals grind against each other and hum with sickening blue energy, crystal flakes and powdery residue collect beneath the machinery. Dero magisters gather these products, creating tools and repurposing the crystals to power magical items.
