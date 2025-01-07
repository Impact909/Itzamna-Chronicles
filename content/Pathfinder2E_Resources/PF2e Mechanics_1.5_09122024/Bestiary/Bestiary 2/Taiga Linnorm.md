---
title: "Taiga Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sn4Vsfn39ffaYc5I" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Taiga Linnorm"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Taiga Linnorm"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +37, Stealth: +35"
abilityMods: [10, 6, 8, -2, 6, 7]
speed: 40 feet,  fly 100 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +35, __Ref__ +31, __Will__ +29; +1 status to all saves vs. magic"
hp: 385
health:
  - name: ""
  - name: HP
    desc: "385, regeneration 15 (deactivated by cold iron); __Immunities__  curse,  electricity,  paralyzed,  sleep; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Curse of Endless Storms"
    desc: " (curse,electricity,primal) When a creature slays a taiga linnorm, it must succeed at a DC 46 Will check save or permanently gain weakness 20 to electricity."

  - name: "Spines"
    desc: "  Any creature that makes a melee attack against a taiga linnorm is stabbed by the taiga linnorm's spines and takes 1d6 piercing damage per attack. A melee weapon with reach protects the user against these spines."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (magical, reach 25 feet)\n__Damage__  4d12 + 18 piercing plus taiga-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+37 (agile, magical, reach 25 feet)\n__Damage__  4d8 + 18 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+37 (agile, magical, reach 30 feet)\n__Damage__  5d6 + 18 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 41, attack +31\n__Constant__  __(9th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_ __(8th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (electricity,primal) The taiga linnorm breathes a 60-foot cone of electrified vapor, dealing 20d6 electricity damage to creatures in the area (DC 41 Reflex check save). The electrified mist persists for 1d4 rounds, dealing 6d6 electricity damage (DC 41 Reflex check save) to each creature that ends its turn in the mist.\n\nThe taiga linnorm can't use Breath Weapon again for 1d4 rounds."

  - name: "Taiga Linnorm Venom"
    desc: " (electricity,poison) **Saving Throw** DC 42 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 7d6 electricity damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 10d6 electricity damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Taiga Linnorm
creatures:
  - 1: Taiga Linnorm
```



Taiga linnorms are covered in hundreds of quill-like black spines as sharp as spears. Wise hunters native to linnorm-infested lands know to watch for spines stuck in the bark of conifers-a sure sign that a taiga linnorm has recently passed through. Sometimes this means of tracking isn't enough to avoid an encounter, however; taiga linnorms, like their tarn and tor brethren, are skilled stalkers. They prefer to lurk in half-frozen bogs or swampy marshlands with their heads poking just above the water's surface, ever watchful for unwary prey.
