---
title: "Gimmerling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WRDn7WwLeJY75SQo" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Gimmerling"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gimmerling"
level: "Creature 12"

alignment: ""
size: "Small"
trait_01: [[fey]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Crafting: +23, Deception: +25, Nature: +21, Stealth: +25, Thievery: +25"
abilityMods: [4, 7, 4, 5, 3, 4]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +22, __Ref__ +25, __Will__ +19"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|+1 Striking Hand Crossbow]], 20x [[Equipment/Bolts|Bolts]]"
  - name: "Hungersense (Imprecise) 30 feet"
    desc: "  Hungersense allows the gimmerling to sense creatures that require food to live."

abilities_mid:
  - name: ""
  - name: "Treacherous Aura"
    desc: " (aura,primal) 15 feet.\n\nTangled roots, jagged divots, sharp rocks and other hazards appear on surfaces in the aura, creating difficult terrain."

  - name: "Trip Up"
    desc: "`pf2:r`  **Trigger** A creature critically fails a melee attack to hit the gimmerling or moves into a space within the gimmerling's treacherous aura\n* * *\n\n**Effect** The triggering creature must attempt a DC 32 Reflex check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Off-Guard|Off-Guard]] until the start of its next turn.\n\n**Failure** The target takes 2d10 bludgeoning damage and is off-guard until the start of its next turn.\n\n**Critical Failure** As failure, and the target is knocked [[Conditions/Prone|Prone]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile, finesse)\n__Damage__  2d8 + 7 slashing plus disarm"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (finesse)\n__Damage__  3d8 + 7 piercing 2d6 poison"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+28 (range increment 60 feet, reload 1)\n__Damage__  2d6 + 3 piercing 2d6 poison"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The gimmerling takes on the appearance of any humanoid. In humanoid form, They lose their treacherous aura, and their equipment appears to be trinkets or toys. If the chosen form lacks claws or fangs, they lose the matching Strike. If they lose their claw Strike, they gain a fist Strike that is identical except that it deals bludgeoning damage.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Sly Disarm"
    desc: "`pf2:1`  **Requirements** The gimmerling's last action was a successful claw Strike\n* * *\n\n**Effect** The gimmerling attempts to [[Actions/Disarm|Disarm]] the creature they hit. They gain a +4 status bonus on the Athletics check. This attempt neither applies nor counts toward the gimmerling's multiple attack penalty."

  - name: "Sneak Attack"
    desc: "  The gimmerling deals 2d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Trickster's Step"
    desc: "  The gimmerling ignores difficult terrain and doesn't trigger traps with its movement."
 
```

```encounter-table
name: Gimmerling
creatures:
  - 1: Gimmerling
```



Gimmerlings are small, shapeshifting fey who stage ambushes to sate their endless hunger and childish greed. These cruelly curious fey obsess over finding and making unusual traps and sadistic weapons, and their favorite amusement is seeing these traps sprung or the weapons wielded. When residing on Golarion, they're frequently found in urban areas, particularly slums or other parts of town, where they can either go unnoticed or be easily forgotten—and have plenty of victims to choose from.

A typical gimmerling disguises themself as an endangered child, hoping to draw creatures close enough to rob. The gimmerling puts themself in apparent danger using a trap, construct, a bribed ally, or even a coerced monster.

Because gimmerlings sometimes trade obscure smithing or trapping techniques in exchange for gifts that sate their curiosity, their greed, or their hunger, they have at times been worshipped as minor gods of the forge. Some disciplined gimmerlings work as honored artisans, elite guards, or spies for the demigods known as the Eldest, who dwell in the depths of the First World.
