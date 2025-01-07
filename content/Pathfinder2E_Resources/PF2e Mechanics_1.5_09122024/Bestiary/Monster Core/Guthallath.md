---
title: "Guthallath"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L5WJM3ryozO2QVzj" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/19
  - remaster
statblock: inline
name: "Guthallath"
level: 19
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Guthallath"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[construct]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Truesight"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +40"
abilityMods: [10, 2, 8, -4, 0, -1]
speed: 40 feet,  burrow 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +38, __Ref__ +32, __Will__ +30"
hp: 325
health:
  - name: ""
  - name: HP
    desc: "325; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ physical 15 (except adamantine), spells 15 (except cold, earth, or water)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Erosion Aura"
    desc: " (aura,primal) 120 feet.\n\nThe guthallath erodes away the physical integrity of all around it. Creatures and objects in the emanation other than the guthallath have their Hardness and resistances reduced by 10.\n\nAt the start of their turn, a creature in the erosion aura's area takes 6d6 bludgeoning damage with a DC 39 Fortitude check save."

  - name: "Immunity to Magic"
    desc: "  The guthallath is immune to spells of 6th rank or lower and activations of magic items of 13th level or lower."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+38 (deadly 3d12, magical, reach 20 feet)\n__Damage__  4d12 + 18 bludgeoning plus improved-grab,improved-push"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+38 (deadly 3d12, magical, reach 20 feet)\n__Damage__  4d8 + 18 bludgeoning plus improved-knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 37, attack +29\n__Constant__  __(8th)__ _[[Spells/Truesight|Truesight]]_ __(3rd)__ _[[Spells/Haste|Haste]]_"

  - name: "Annihilation Beams"
    desc: "`pf2:2`  A guthallath releases two beams of destruction from its eyes. Each beam is a 120-foot line. Everything in either line takes 13d10 untyped damage with a DC 41 Fortitude check save.\n\nA creature reduced to 0 HP is reduced to a fine powder as the [[Spells/Disintegrate|Disintegrate]] spell. There is no additional effect on creatures in any area where the beams overlap.\n\nThe guthallath can't use this ability again for 1d4 rounds."

  - name: "Deadly Throw"
    desc: "`pf2:1`  **Requirements** The guthallath has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The guthallath throws the creature into the air, 100 feet high and 50 feet away. If the flung creature lands on another creature, the creature it lands on takes the same amount of bludgeoning damage.\n\nThe creature being landed on can attempt a DC 41 Reflex check save."

  - name: "Powerful Blows"
    desc: "  If a guthallath hits with an attack and rolls a natural 19 on the d20 roll, the attack is a critical hit. This has no effect if the 19 would be a failure."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 45 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push 20 feet]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Guthallath
creatures:
  - 1: Guthallath
```



A guthallath is an enormous construct created long ago, probably as a war machine, by a long-forgotten empire. Nearly 100 feet tall, this massive stone statue typically resembles a stalwart warrior wearing only a loincloth and skullcap. Few have seen the entire body of a guthallath, though; most of the time, the relic is buried up to its neck, covered in moss, and stranded in a forgotten place. Yet every so often, one of these harbingers of destruction reactivates in response to some unknown stimulus or rallying call, and when this happens, woe to any who stand in its way.

While a guthallath's ancient enemies are likely gone, it's still an engine of pure destruction, designed to rampage for weeks, even months. It's not intelligent enough to enjoy or regret its acts and cannot be reasoned with—it's also unaffected by most magic and unpredictable in how it selects its targets (and the creatures it spares).
