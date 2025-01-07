---
title: "Venedaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VEMZAphHcoxTlw0Z" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Venedaemon"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Venedaemon"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[daemon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Aklo, Chthonian, Common, Daemonic, Diabolic, Draconic, Requian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Arcana: +16, Deception: +12, Occultism: +14, Religion: +13, Scribing Lore: +14"
abilityMods: [2, 4, 2, 5, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +11, __Will__ +14; +1 status to all saves vs. magic"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  death effects; __Weaknesses__ holy 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Smell Magic (Imprecise) 60 feet"
    desc: "  A venedaemon is aware of magical items and active spells as an imprecise sense. The subtle differences in these scents reveal the tradition and traits of the magic."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+13 (agile, finesse, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 5 bludgeoning"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 22, attack +14; __3rd __ (3 slots) _[[Spells/Fireball|Fireball]]_, _[[Spells/Levitate|Levitate]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __ (4 slots) _[[Spells/Blazing Bolt|Blazing Bolt]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Noise Blast|Noise Blast]]_; __1st __ (4 slots) _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_\n__Cantrips__  __(3rd)__ _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Sigil|Sigil]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +14; __4th __  _[[Spells/Translocate|Translocate]]_"

  - name: "Residual Force"
    desc: "`pf2:1` (arcane,force) **Requirements** The venedaemon's most recent action was to cast a spell\n* * *\n\n**Effect** Fading runes cling to the venedaemon's tentacles. The venedaemon makes a tentacle Strike that has a reach of 20 feet and deals 2d4 additional force damage."

  - name: "Soul Spell"
    desc: "  If a venedaemon ingest a soul gem from a cacodaemon, they can recover an expended spell slot instead of gaining fast healing. The spell slot's rank can be no higher than half the level of the creature whose soul was consumed, rounded up."

  - name: "Twisted Whispers"
    desc: "`pf2:1` (arcane,auditory,concentrate,linguistic,mental) The venedaemon whispers to a creature within 15 feet, which must succeed at a DC 22 Will check save or be [[Conditions/Stupefied|Stupefied 2]] for 1 minute (or [[Conditions/Stupefied|Stupefied 3]] on a critical failure).\n\nRegardless of the results of the save, the creature is immune to Twisted Whispers for 24 hours."
 
```

```encounter-table
name: Venedaemon
creatures:
  - 1: Venedaemon
```



Those killed by magic or killed in the pursuit of magic can arise as venedaemons. Although among the weaker daemons, these robed figures can often be seen serving as researchers or clerks throughout the plane. Even within the mortal Universe, scholars barter souls or arcane knowledge with venedaemons for their secrets and assistance.

* * *

Denizens of the bleak and terrible plane of Abaddon, daemons are shaped by and devoted to the destruction of life in all its forms. They seek the death of every mortal being by the most painful and horrible means possible, in service to the Apocalypse Riders. Each kind of daemon represents a different way to die, and their powers are nearly always aimed at spreading that particular form of death. Through the use of these powers, they seek to drag all existence down into a pit of hopelessness and despair, and to commit all souls to oblivion.

While mortals who summon daemons usually seek to use the creatures' destructive and corrupting powers for their own ends, daemons always look for ways to spread fear, doubt, and despair wherever they go. Often, daemons disguise their plots as the workings of other fiends, knowing that such confusion compounds mortals' fear and keeps those mortals from bringing the most effective weapons. As a result, learned mortals sometimes refer to daemons as "riders" after their leaders or "soul mongers" after their largest industry.

While many fiends seek to tempt mortals into lives of nihilistic evil to increase their own numbers and power on their native planes, daemons are further driven by a supernatural hunger for mortal souls and use a variety of methods—not least of which is the cacodaemons' soul gems—to entrap them. On Abaddon and in other forbidding places across the multiverse, souls are simultaneously a delicacy, a trade good, and a source of magical power, and the daemons are among the greatest gluttons, merchants, and abusers of this spiritual "resource."
