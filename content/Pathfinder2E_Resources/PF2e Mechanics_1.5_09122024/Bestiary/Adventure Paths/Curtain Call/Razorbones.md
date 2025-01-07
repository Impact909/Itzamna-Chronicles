---
title: "Razorbones"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.j0jBpRfWngCdVMzE" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Razorbones"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Razorbones"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +38, Stealth: +36"
abilityMods: [10, 7, 6, 0, 6, 6]
speed: 25 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +33, __Ref__ +35, __Will__ +32"
hp: 430
health:
  - name: ""
  - name: HP
    desc: "430, void healing; __Immunities__  paralyzed,  unconscious,  poison,  death effects,  disease,  bleed; __Weaknesses__ bludgeoning 20"
abilities_top:
  - name: ""

  - name: "Ectoplasmic Filaments"
    desc: "  **Trigger** A creature within the razorbones' reach uses a manipulate action or a move action or leaves a square during a move action it's using\n* * *\n\n**Effect** A filament of black, oily ectoplasm lashes out at the triggering creature, dealing 4d8+18 slashing damage (DC 42 Reflex check save). If the filament deals damage, the razorbones gains 8d8 temporary Hit Points as blood flows back along its bones to sheathe them in glisten red fluid."

  - name: "Eerie Flexibility"
    desc: "  A razorbones can shift and adjust its mass to fit into smaller areas, allowing it to fit through tight spaces as if it were a Medium creature. While Squeezing, it can move at its full speed."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, reach 10 feet)\n__Damage__  1d6 bleed plus improved-grab 4d6 + 18 slashing plus improved-grab"

  - name: "**Ranged** `pf2:1` Hurled Bone"
    desc: "+38 (brutal, range increment 30 feet)\n__Damage__  4d4 + 18 piercing"

  - name: "Gnaw"
    desc: "`pf2:1`  **Requirements** The razorbones has [[Conditions/Grabbed|Grabbed]] a foe\n* * *\n\n**Effect** The razorbones gnaws and chews on the grabbed target with its many skulls, dealing 4d6+18 piercing damage (DC 42 Fortitude check save). On a critical failure, the creature is also [[Conditions/Drained|Drained 1]] (or increases an existing drained condition by 1, to a maximum of [[Conditions/Drained|Drained 4]]) from the grievous gnawing."

  - name: "Skeletal Storm"
    desc: "`pf2:2`  The razorbones makes a single claw Strike against every creature in reach. These attacks count toward the razorbones' multiple attack penalty, but the multiple attack penalty doesn't increase until after the razorbones makes all its attacks."

  - name: "Sprawled Bones"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the razorbones appears as a sprawling mass of bones. It has an automatic result of 56 on Deception checks and DCs to pass as a grisly but seemingly harmless mess."

  - name: "Improved Grab"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Razorbones
creatures:
  - 1: Razorbones
```


Variant tanglebones

Sometimes, when murderer buries a large number of victims in a mass grave, the vengeful spirits of the slain can become similarly tangled together. When these spirits can't untangle, they instead return to their physical remains, fusing into one horrific mass of bones and black, tar-like sludge-a tanglebones.

One awful tale speaks of a bitter old dowager who learned that, through a legal loophole, ownership of her estate would revert to her estranged daughter. She murdered her 13 servants, buried their bodies in the house's basement, and then played the gracious mother in handing over the manor keys at the appointed time. One night, the tanglebones that arose from the dowager's atrocity murdered the daughter and her family. By the time the authorities learned of what happened, the dowager had fled the nation, changed her identity, and (the story goes) wasted no time rebuilding her fortunes-this time becoming a queen.
