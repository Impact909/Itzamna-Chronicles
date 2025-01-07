---
title: "Bralani"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dNrFXv72i44xGMKf" 
tags:
  - pf2e/creature/type/azata
  - pf2e/creature/type/celestial
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Bralani"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Bralani"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[azata]]
trait_02: [[celestial]]
trait_03: [[chaotic]]
trait_04: [[good]]
trait_05: [[holy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Deception: +15, Diplomacy: +15, Stealth: +15, Games Lore: +14"
abilityMods: [5, 5, 3, 2, 4, 5]
speed: 30 feet,  fly 80 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +13, __Ref__ +17, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Weaknesses__ cold iron 5, unholy 5; __Resistances__ electricity 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|+1 Composite Longbow]], [[Equipment/Scimitar|Scimitar]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+16 (forceful, holy, sweep)\n__Damage__  1d6 + 8 slashing 2d6 electricity 1d6 spirit"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+18 (deadly d10, holy, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 6 piercing 1d6 electricity 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +14; __4th __  _[[Spells/Vapor Form|Gaseous Form (At will)]]_; __3rd __  _[[Spells/Heal|Heal]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Calm|Calm Emotions]]_; __1st __  _[[Spells/Gust of Wind|Gust of Wind (At will)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Fair Competition"
    desc: " (divine,mental) Once per day, a bralani can spend 1 minute to bless willing creatures within 100 feet who are about to participate in a contest. This blessing lasts 24 hours. If a blessed creature cheats or uses the contest to harm another, the creature grows visibly ill, becoming [[Conditions/Sickened|Sickened 1]] and unable to remove this condition for the duration or until they withdraw from the competition. At the end of the contest, participants who competed fairly find it easier to negotiate and understand their opponent's perspective. For 1 hour, they gain a +2 status bonus to Diplomacy checks and [[Actions/Recall Knowledge|Recall Knowledge]] checks that directly pertain to their opponents."

  - name: "Whirlwind Blast"
    desc: "`pf2:2` (air,divine) The bralani generates a 20-foot line of scouring wind that deals 7d6 bludgeoning damage (DC 24 Reflex check save). It can't use this ability again for 1d4 rounds."

  - name: "Wind Form"
    desc: "  A bralani flies at full Speed in [[Spells/Vapor Form|Vapor Form]]."
 
```

```encounter-table
name: Bralani
creatures:
  - 1: Bralani
```



Bralanis embody the freedom of fair competition, embracing opportunities to test their skills against worthy foes and bring mortals together with the thrill of good-natured sports and contests. Their interest in constructive conflict also extends to higher stakes, such as diplomatic negotiations. In these cases, bralanis ensure that neither side's desires are crushed by the other's and work as mediators when needed. They believe in friendly contests to diffuse tension. When discussions are going well, bralanis step back, allowing the participants to shape their own futures. They delight in sailing through violent storms as wind, basking in the raw energy.
