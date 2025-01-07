---
title: "Ferrugon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EDeU1mJ6jbtzruys" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Ferrugon"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #190: The Choosing"
name: "Ferrugon"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Greater Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean, Petran; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Crafting: +22, Deception: +21, Intimidation: +23, Religion: +22, Stealth: +23, Thievery: +25"
abilityMods: [7, 5, 6, 4, 4, 5]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder #190: The Choosing_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +20, __Will__ +21; +1 status to all saves vs. magic"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  fire; __Weaknesses__ holy 10; __Resistances__ physical 10 (except silver)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Metallic"
    desc: "  A ferrugon is a metallic creature and thus affected by effects such as [[Spells/Rusting Grasp|Rusting Grasp]]."

  - name: "Vainglorious Whispers"
    desc: "`pf2:r` (divine,linguistic,mental) **Trigger** A non-devil creature within 30 feet of the ferrugon succeeds (but doesn't critically succeed) at an attack roll, skill check, or saving throw\n* * *\n\n**Effect** The ferrugon whispers subversive messages to the triggering creature, causing it to become overly confident in its abilities, while in fact it becomes less accomplished overall. The target must attempt a DC 32 Will check save. On a failure, the target gains a +2 status bonus to saving throws against fear effects but also takes a –2 penalty to all attack rolls and skill checks for 1 hour. During this time, the victim can't benefit from [[Actions/Aid|Aid]] reactions, use healing effects on themselves, or use [[Actions/Take Cover|Take Cover]] or Raise a Shield actions, as these actions seem unnecessary to the creature at this time. Similar defensive actions might not be available to the victim as well, at the GM's discretion. The target is then temporarily immune to Vainglorious Whispers for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+25 (cold iron, magical, shove, unholy)\n__Damage__  3d8 + 13 bludgeoning 1d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile, cold iron, magical, unholy)\n__Damage__  1d6 spirit plus ferrugon-tetanus 3d4 + 13 slashing plus ferrugon-tetanus"

  - name: "**Ranged** `pf2:1` Iron Feather"
    desc: "+23 (cold iron, magical, range increment 40 feet, unholy)\n__Damage__  3d4 + 13 piercing plus ferrugon-tetanus"

  - name: "Divine Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Petrify|Flesh to Stone]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Shatter|Shatter]]_, _[[Spells/Wall of Stone|Wall of Stone (x3)]]_; __4th __  _[[Spells/Creation|Creation]]_, _[[Spells/Translocate|Dimension Door (At Will)]]_, _[[Spells/Rusting Grasp|Rusting Grasp (x3)]]_, _[[Spells/Suggestion|Suggestion]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Ferrugon Tetanus"
    desc: " (disease) **Saving Throw** DC 32 Fortitude check\n\n**Onset** 1d4 days\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 week)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and can't speak (1 day)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] (1 day)\n\n**Stage 4** death"

  - name: "Sunder Objects"
    desc: "  When a ferrugon damages an item or structure, they deal an additional 2d8 damage to that item or structure."
 
```

```encounter-table
name: Ferrugon
creatures:
  - 1: Ferrugon
```




