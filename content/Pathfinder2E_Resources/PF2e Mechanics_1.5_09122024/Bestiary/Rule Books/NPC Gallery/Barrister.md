---
title: "Barrister"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iGfRnl3ctee04Flf" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Barrister"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Barrister"
level: "Creature -1"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Deception: +10, Diplomacy: +12, Performance: +10, Society: +9, Legal Lore: +13"
abilityMods: [0, 1, 1, 3, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +3, __Ref__ +3, __Will__ +12"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Clothing (Fine)|Court Garb]], [[Equipment/Scholarly Journal|Law Book]], [[Equipment/Writing Set|Writing Set]]"
  - name: "Sway the Judge and Jury"
    desc: "  A barrister gains a +2 circumstance bonus to Diplomacy checks to [[Actions/Make an Impression|Make an Impression]] or [[Actions/Request|Request]] something of the deciding members within a courtroom.\n\nIf the barrister successfully [[Actions/Perform|Performs]] against a DC 20 Performance check during the 20 minutes prior to the check, they increase the circumstance bonus to +4."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+4 (agile, nonlethal)\n__Damage__  1d4 bludgeoning"

  - name: "Cite Precedent"
    desc: "`pf2:1` (auditory,linguistic) The barrister uses existing case law to undermine their opposition. If they succeed at a Legal Lore check, they impose a -2 circumstance penalty on the next Diplomacy check an opponent attempts in a legal argument.\n\nAny further attempts to Cite Precedent fail until a new topic with different precedents is being argued.\n\n[[Bestiary Effects/Effect_ Cite Precedent|Effect: Cite Precedent]]"
 
```

```encounter-table
name: Barrister
creatures:
  - 1: Barrister
```



Barristers may serve as criminal prosecutors or as legal advocates, defending the rights of those accused of crimes or named as defendants in civil cases. In a court case or other legal proceeding, the barrister is a 4th-level challenge.

* * *

Larger societies rely on those with the authority and the ability to interpret and enforce laws. In good-aligned societies, these officials carry out their duties fairly. In neutral and evil ones, these officials can be harsh and cruel (with an altered alignment to reflect this), imposing severe punishments on those who can't pay for mercy.
