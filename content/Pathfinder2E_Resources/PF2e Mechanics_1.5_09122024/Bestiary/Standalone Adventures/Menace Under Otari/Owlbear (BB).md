---
title: "Owlbear (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Pf7VUAFnDDr94wRM" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Owlbear (BB)"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Owlbear (BB)"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +14, Intimidation: +10"
abilityMods: [6, 1, 5, -4, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +7, __Will__ +11"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Talon"
    desc: "+14 (agile)\n__Damage__  1d10 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+14 ()\n__Damage__  1d12 + 6 piercing"

  - name: "Bloodcurdling Screech"
    desc: "`pf2:1` (fear,mental) Each creature within 80 feet who can hear the owlbear's screech must attempt a DC 20 Will check save. The creatures can't be affected by another screech for 1 minute. On a critical success, the creature is unaffected; on a success, the creature gains the [[Conditions/Frightened|Frightened 1]] condition; on a failure, the creature gains the [[Conditions/Frightened|Frightened 2]] condition; on a critical failure, the creature gains the [[Conditions/Frightened|Frightened 3]] condition and must spend its next turn running away from the owlbear."

  - name: "Screeching Advance"
    desc: "`pf2:2` (auditory,fear,mental) The owlbear makes a Bloodcurdling Screech and Strides twice. All creatures within 80 feet of the owlbear at any point during this movement are subjected to the effects of Bloodcurdling Screech."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  When the owlbear succeeds at its talon Strike, it can use this action immediately after to automatically give the target the [[Conditions/Grabbed|Grabbed]] condition until the end of its next turn."
 
```

```encounter-table
name: Owlbear (BB)
creatures:
  - 1: Owlbear (BB)
```



The owlbear is a territorial predator with the body of a brown bear but the head-and resultant keen senses-of an owl.
