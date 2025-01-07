---
title: "Fortune Dragon (Ancient)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9FxhLqVRHCR6nAuw" 
tags:
  - pf2e/creature/type/arcane
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/19
  - remaster
statblock: inline
name: "Fortune Dragon (Ancient)"
level: 19
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Fortune Dragon (Ancient)"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[arcane]]
trait_02: [[dragon]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Arcana: +37, Athletics: +34, Crafting: +37, Diplomacy: +32, Thievery: +36, Accounting Lore: +37, Mercantile Lore: +37"
abilityMods: [9, 9, 8, 10, 5, 5]
speed: 80 feet,  fly 180 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +31, __Ref__ +34, __Will__ +32; +2 status to all saves vs. arcane"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  drained,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Aura of Disruption"
    desc: " (arcane,aura) 120 feet.\n\nThe dragon radiates disruptive energies that allow them to feed on magic. When a spell is counteracted or disrupted within the aura, the dragon regains one expended spontaneous spell slot and gains 35 temporary Hit Points that last for 1 minute."

  - name: "Capture Spell"
    desc: "`pf2:r` (arcane) **Trigger** The dragon succeeds or critically succeeds on a saving throw against a spell\n* * *\n\n**Effect** The dragon attempts to capture a portion of the spell's magic to feed themself. They attempt to counteract the spell (counteract rank 10, counteract modifier +37). If successful, the dragon is unaffected by the spell and regains one expended spontaneous spell slot; other subjects are affected by the spell normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 20 feet)\n__Damage__  4d10 + 15 piercing 1d6 force"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 15 feet)\n__Damage__  1d6 force 4d6 + 15 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (magical, reach 25 feet)\n__Damage__  1d6 force 4d10 + 15 bludgeoning"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 45, attack +37; __10th __ (3 slots) _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Implosion|Implosion]]_, _[[Spells/Quandary|Quandary]]_, _[[Spells/Slither|Slither]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_, _[[Spells/Warp Mind|Warp Mind]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Disruptive Breath"
    desc: "`pf2:2` (arcane,force) The dragon unleashes a spray of magic-disrupting energies that deals 18d6 force damage in a 60-foot cone (DC 45 Reflex check save). Creatures that fail become [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Stupefied|Stupefied 2]] on a critical failure) for 1 minute.\n\nThe dragon can't use Disruptive Breath again for 1d4 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  Whenever they score a critical hit with a Strike, the dragon chooses to either recharge Disruptive Breath or regain one expended spontaneous spell slot."

  - name: "Drain Hoard"
    desc: "`pf2:1`  **Requirements** The dragon is within 60 feet of their hoard\n\n**Frequency** once per day\n* * *\n\n**Effect** The dragon draws power out of the magic items in their hoard, regaining all their expended spontaneous spell slots."

  - name: "Share the Wealth"
    desc: "`pf2:2`  **Requirements** The dragon's body is covered in riches (this is typically the case when the dragon is first encountered)\n* * *\n\n**Effect** The dragon shakes their body aggressively, sending coins and other riches flying in every direction, dealing 18d10 bludgeoning damage with a DC 40 Reflex check save to all creatures in a 50-foot emanation. The dragon's body is then no longer covered in riches."

  - name: "Treasure Dive"
    desc: "`pf2:2`  **Requirements** The dragon's body isn't covered in riches and the dragon is adjacent to their hoard\n* * *\n\n**Effect** The dragon Strides or Burrows through their hoard using their land Speed. They coat themself in coins, magic items, and other treasures. This contact with magical items revitalizes the dragon, causing them to regain one expended spontaneous spell slot.\n\nThe dragon can move through other creatures while moving in this way. Creatures in the dragon's path, or above it if the dragon Burrows, must succeed at a DC 38 Reflex check save or be pushed 10 feet (or pushed 20 feet and knocked [[Conditions/Prone|Prone]] on a critical failure)."
 
```

```encounter-table
name: Fortune Dragon (Ancient)
creatures:
  - 1: Fortune Dragon (Ancient)
```



Fortune dragons have the innate ability to draw upon the raw magical energies that surround them. They constantly use these magical energies to empower their magical abilities and even their bodies, as the energy can heal wounds. A fortune dragon has a typical build for an arcane dragon, but their bodies sport a striking feature: their treasure. The dragon's nature of drawing upon magic causes coins, gems, and, most notably, magical items to cling to their body like iron drawn to magnets. A dragon constantly pulls magical energies from the items attached to their body and makes use of these energies to cast spells. The magical energies that flow through a fortune dragon constantly flow through the dragon's items as well, and in many cases, the items melt from the heat produced in this process. Fortune dragons are seekers of novel experiences. This desire for originality leads fortune dragons to approach visitors of other ancestries with curiosity, though this initial interest quickly wanes if a visitor lacks exciting qualities.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
