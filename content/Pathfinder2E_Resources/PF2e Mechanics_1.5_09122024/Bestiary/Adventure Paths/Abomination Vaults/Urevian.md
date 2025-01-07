---
title: "Urevian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VH2KBJSd4SJuc3CN" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Urevian"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Urevian"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Greater Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Empyrean, Necril, Sakvroth; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Deception: +21, Diplomacy: +19, Intimidation: +19, Religion: +19, Society: +19, Thievery: +18, Legal Lore: +23"
abilityMods: [3, 4, 3, 6, 4, 6]
speed: 25 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +17, __Will__ +22; +1 status to all saves vs. magic"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  fire; __Weaknesses__ holy 10; __Resistances__ physical 10 (except silver), poison 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Distracting Declaration"
    desc: "  Urevian keeps a few sly words at the ready to distract enemies. He always uses Deception for initiative."

  - name: "Ward Contract"
    desc: "  Any signed contract Urevian carries (including any draped over his horns) is immune to damage from creatures other than Urevian. In addition, Urevian is immune to mental effects that would make him alter, nullify, or destroy a contract."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Diabolic Quill"
    desc: "+21 (agile, fatal d12, finesse, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 9 piercing plus infernal-wound 1d6 spirit plus infernal-wound"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+20 (magical, unholy)\n__Damage__  3d10 + 9 piercing plus infernal-wound"

  - name: "Divine Innate Spells"
    desc: "DC 30, attack +22; __6th __  _[[Spells/Scrying|Scrying (At Will) (See Right of Inspection)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Flame Strike|Flame Strike]]_, _[[Spells/Locate|Locate (At Will)]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Sending|Sending (x3)]]_, _[[Spells/Wall of Force|Wall of Force]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_, _[[Spells/Peaceful Bubble|Private Sanctum]]_, _[[Spells/Silence|Silence]]_; __3rd __  _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Rituals"
    desc: "_Call Spirit_, _Infernal Pact_, _Inveigle_"

  - name: "Draft Contract"
    desc: "`pf2:3` (divine,manipulate) Urevian produces an infernal contract for a single living mortal. This contract can grant a wide range of abilities and effects, akin to the power of a [[Spells/Wish|Wish]] spell but fulfilled to the letter by Urevian. To receive any of those benefits, the mortal must willingly sign its true name to the contract. At that point, the mortal's soul is bound to Urevian and to Hell.\n\nWhile the contract is in effect, the mortal can't be restored to life except by wish or similar magic. If the mortal is restored to life by those means, Urevian knows which mortal came to life and can locate the creature or creatures who restored the mortal to life for 1 year, gaining the effects of a [[Spells/Locate|Locate]] spell with unlimited range. Avoiding the terms of an infernal contract is difficult and often dangerous."

  - name: "Infernal Wound"
    desc: " (divine) Urevian's Strikes also deal 2d6 bleed that resists attempts to heal them.\n\nThe flat check to stop the bleeding starts at DC 20 Flat check. The DC is reduced to DC 15 Flat check only if the bleeding creature or an ally successfully assists with the recovery. The DC to [[Actions/Administer First Aid|Administer First Aid]] to a creature with an infernal wound is increased by 5.\n\nA spellcaster or item attempting to use healing magic on a creature suffering from an infernal wound must succeed at a DC 28 counteract check or the magic fails to heal the creature.\n\n[[Bestiary Effects/Effect_ Infernal Wound|Effect: Infernal Wound]]"

  - name: "Right of Inspection"
    desc: "  Urevian can cast his innate [[Spells/Scrying|Scrying]] spell at will, but only to target a creature with which he has a contract, a specific creature named in a contract he has, or a descendant of any of those creatures. The outcome of the target's saving throw is one step worse than the result it rolled."
 
```

```encounter-table
name: Urevian
creatures:
  - 1: Urevian
```


Male phistophilus field commander


