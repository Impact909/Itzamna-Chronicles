---
title: "Ironclad Annihilator Beetle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.f9EUVQvR4JByrmwg" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Ironclad Annihilator Beetle"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Ironclad Annihilator Beetle"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Athletics: +42"
abilityMods: [10, 6, 10, -5, 5, -1]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 49
armorclass:
  - name: AC
    desc: "49; __Fort__ +38, __Ref__ +32, __Will__ +35"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Carapace Deflection"
    desc: "`pf2:r`  **Trigger** The ironclad annihilator beetle is targeted with an attack from an attacker it can see\n* * *\n\n**Effect** The ironclad annihilator pivots to place its tough carapace in the way of the attack, gaining a +2 circumstance bonus to its AC against the triggering attack. If the attack misses, the ironclad annihilator can Step after the attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandible"
    desc: "+39 (magical, reach 20 feet)\n__Damage__  4d12 + 20 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+37 (magical, reach 15 feet)\n__Damage__  4d8 + 20 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  4d6+20 bludgeoning damage, DC 44 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Earthquake Stomp"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The ironclad annihilator beetle stomps the ground. All creatures within a 30-foot emanation must succeed at a DC 44 Fortitude check saving throw or fall [[Conditions/Prone|Prone]] and become [[Conditions/Stunned|Stunned 1]] (stunned for 1 round on a critical failure)."

  - name: "Oviposit"
    desc: "`pf2:2`  **Requirements** The ironclad annihilator beetle has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The ironclad annihilator injects its ovipositor under the grabbed creature's skin. The creature takes 4d6+20 bludgeoning damage (DC 44 Fortitude check). On a failed save, the beetle implants an egg, and the target creature takes 4d6 bleed that is unusually tenacious. The DC to stop the bleeding using Administer First Aid is DC 40 Medicine check, and healing the creature to full Hit Points doesn't automatically stop the bleeding. If the target creature dies from this bleed damage, its body is destroyed and unrecoverable except with powerful magic such as [[Spells/Miracle|Miracle]] or [[Spells/Wish|Wish]], and an immature ironclad annihilator beetle (with statistics as a [[Monster Core/Giant Stag Beetle|Giant Stag Beetle]]) bursts forth."

  - name: "Sunder Objects"
    desc: "  When an ironclad annihilator damages an item or structure, it deals an additional 2d10 damage to that item or structure."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 44 Reflex check save\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ironclad Annihilator Beetle
creatures:
  - 1: Ironclad Annihilator Beetle
```




