---
title: "Marguk Cleftneck"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PM85wZ3F0jUmVQEB" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/troll
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Marguk Cleftneck"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Marguk Cleftneck"
level: "Creature 7"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[troll]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Jotun, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Intimidation: +16"
abilityMods: [5, 1, 6, 0, 3, 3]
speed: 30 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +17, __Will__ +12"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, regeneration 20 (deactivated by electricity or fire); __Weaknesses__ fire 10, electricity 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|+1 Warhammer]], [[Equipment/Grim Trophy|Grim Trophy]]"
  - name: "Independent Brains"
    desc: "  Each of Marguk's heads rolls its own initiative and has its own turn. Neither head can Delay. At the start of a head's turn, that head gets 2 actions and 1 reaction. Each brain controls one of Marguk's arms, but both can move the legs. Any ability that would sever one of the heads (such as the vorpal weapon property) doesn't cause Marguk to die if she still has her other head, but it does cause her to lose the turns, actions, and reactions of the severed head. Mental effects that target a single creature affect only one of Marguk's heads."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Electricity or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Head Regrowth"
    desc: "  Marguk's regeneration can regrow a severed head. After regaining Hit Points from regeneration, she attempts a DC 10 Flat check. On a success, the missing head is fully restored. If Marguk loses her last remaining head, she dies immediately."

  - name: "Partial Armor"
    desc: "  Marguk's armor primarily protects her abdomen and legs, leaving her shoulders and head exposed. Strikes made with ranged or reach weapons gain a +1 circumstance bonus to attack rolls against Marguk. At the GM's discretion, other attacks that can easily reach her head level (such as attacks made from high ground) also gain this bonus."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (reach 10 feet)\n__Damage__  2d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, reach 10 feet)\n__Damage__  2d8 + 8 slashing"

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+18 (magical, shove)\n__Damage__  1d8 + 12 bludgeoning"

  - name: "Sweeping Hammer"
    desc: "`pf2:2`  **Requirements** Marguk is wielding a warhammer\n* * *\n\n**Effect** Marguk makes a warhammer Strike against each creature in a 15-foot cone."

  - name: "Tenderized Feast"
    desc: "`pf2:r`  **Trigger** Marguk successfully Strikes a creature with her warhammer\n* * *\n\n**Effect** One of Marguk's heads takes advantage of the disoriented foe and makes a jaws Strike against that creature with a –2 penalty."
 
```

```encounter-table
name: Marguk Cleftneck
creatures:
  - 1: Marguk Cleftneck
```




