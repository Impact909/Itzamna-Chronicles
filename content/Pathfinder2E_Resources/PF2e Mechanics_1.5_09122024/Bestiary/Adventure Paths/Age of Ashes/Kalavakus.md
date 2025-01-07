---
title: "Kalavakus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pWzhJ6f0nDLPZYFF" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Kalavakus"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Kalavakus"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +23, Intimidation: +22, Religion: +17, Stealth: +19"
abilityMods: [7, 1, 5, 2, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +17, __Will__ +19; +1 status to all saves vs. magic"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Horn Snare"
    desc: "`pf2:r`  **Trigger** A creature misses the slaver demon with a melee weapon Strike.\n* * *\n\n**Effect** The slaver demon attempts to [[Actions/Disarm|Disarm]] the weapon used in the triggering Strike with a -2 penalty. If it rolls a success, it gets a critical success instead. The demon doesn't need a free hand to use this ability."

  - name: "Liberation Vulnerability"
    desc: "  The first time each round that a creature escapes from the slaver demon's Enslave Soul or the slaver demon witnesses a creature being freed from captivity or mental enslavement, the demon takes 3d6 mental damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horns"
    desc: "+23 (deadly d8, unholy)\n__Damage__  2d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, unholy)\n__Damage__  2d8 + 13 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (unholy)\n__Damage__  2d6 + 13 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +19; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Air Walk|Air Walk (x2)]]_, _[[Spells/Translocate|Dimension Door (At Will)]]_; __3rd __  _[[Spells/Haste|Haste]]_; __1st __  _[[Spells/Command|Command (At Will)]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Enslave Soul"
    desc: "`pf2:2` (arcane,mental) The demon enslaves the soul of a living creature within 60 feet. The target can attempt to resist this enslavement with a DC 29 Will check save.\n\nA slaver demon can have only one living soul enslaved with this ability at a time, and no more than one slaver demon can enslave the same soul. If a slaver demon kills a creature whose soul it has enslaved, the demon regains 20 healing HP and the soul is consigned to an eternity of toil in the Abyss, adding to the slaver demon's tally of souls and allowing the demon to enslave another.\n* * *\n\n**Success** The target avoids being enslaved and is temporarily immune for 24 hours.\n\n**Failure** The target is enslaved and is [[Conditions/Enfeebled|Enfeebled 2]] for 24 hours or until the slaver demon is slain, whichever comes first.\n\n**Critical Failure** As failure, and the target also suffers the effects of a failed saving throw against [[Spells/Dominate|Dominate]]."
 
```

```encounter-table
name: Kalavakus
creatures:
  - 1: Kalavakus
```



Kalavakuses work as slavers in the Abyss, earning them the alternate moniker of "slaver demons"; these fiends round up captured victims and sell them to other fiends or unscrupulous mortals. Pleas for freedom or clemency fall on deaf ears, as slaver demons consider anyone they can catch and hold to be their rightful property and theirs to sell. Kalavakuses know more than just physical means of restraining slaves; they also know how to fetter a victim's soul. The most successful slaver demons have vast slave-pits in the Abyss where they keep stables of imprisoned souls.
