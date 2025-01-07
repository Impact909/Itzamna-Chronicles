---
title: "Hooplamander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rMHyiNB17zfyww4w" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Hooplamander"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Hooplamander"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +12, Stealth: +10"
abilityMods: [5, 5, 3, -2, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +15, __Will__ +9"
hp: 78
health:
  - name: ""
  - name: HP
    desc: "78"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Flexible Dodge"
    desc: "`pf2:r`  **Requirements** The hooplamander is Unfurled\n\n**Trigger** The hooplamander is targeted by a Strike\n* * *\n\n**Effect** The hooplamander gains a +2 circumstance bonus to AC against the triggering attack and enters its Wheels Up stance."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hookclaw"
    desc: "+13 (agile, versatile p)\n__Damage__  3d6 bleed 1d4 + 5 slashing"

  - name: "**Melee** `pf2:1` Ridged Tail"
    desc: "+13 (sweep)\n__Damage__  2d6 + 5 bludgeoning"

  - name: "Rollout Trample"
    desc: "`pf2:3`  **Requirements** The hooplamander is Wheels Up\n* * *\n\n**Effect** As [[Bestiary Ability Glossary/Trample|Trample]] (Large or smaller, ridged tail, DC 22 Reflex check), except targets that critically fail their Reflex save are [[Conditions/Stunned|Stunned 1]], and the hooplamander Unfurls at the end of its movement."

  - name: "Unfurl"
    desc: "`pf2:1`  **Requirements** The hooplamander is Wheels Up\n* * *\n\n**Effect** The hooplamander releases its tail, [[Actions/Leap|Leaping]] up to 20 feet as it exits its wheeled shape and unfurls to land on its four legs."

  - name: "Wheels Up"
    desc: "`pf2:1` (stance) **Requirements** The hooplamander is Unfurled\n* * *\n\n**Effect** The hooplamander [[Actions/Leap|Leaps]] and then rolls into its wheeled form. Any creature within 5 feet must succeed at a DC 22 Reflex check save or be [[Conditions/Off-Guard|Off-Guard]] for one round. While it's Wheels Up, the hooplamander can't make Strikes and its Speed increases to 40 feet."
 
```

```encounter-table
name: Hooplamander
creatures:
  - 1: Hooplamander
```




