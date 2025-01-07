---
title: "Fjord Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OjSkWOVl0NLoKE6m" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Fjord Linnorm"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Fjord Linnorm"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
trait_04: [[evil]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +33, Stealth: +29"
abilityMods: [9, 5, 8, -3, 6, 7]
speed: 35 feet,  fly 75 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +30, __Ref__ +28, __Will__ +24; +1 status to all saves vs. magic"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315, regeneration 10 (deactivated by cold iron); __Immunities__  cold,  curse,  paralyzed,  sleep; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Curse of Stolen Breath"
    desc: " (curse,primal,water) When a creature slays a fjord linnorm, it must succeed at a DC 41 Will check save or become unable to ever breathe underwater (either via a natural ability or a spell such as water breathing). In addition, the victim can hold its breath only half as long as normal, and whenever it holds its breath it becomes [[Conditions/Sickened|Sickened 2]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 20 feet)\n__Damage__  3d12 + 17 piercing plus fjord-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 20 feet)\n__Damage__  3d10 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (agile, magical, reach 25 feet)\n__Damage__  3d6 + 15 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 37, attack +27\n__Constant__  __(7th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_ __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (cold,primal) The fjord linnorm expels a 120-foot line of icy bile, dealing 17d6 cold damage to creatures within the area (DC 37 Reflex check save). Any creature that fails its save is covered by the ice, which freezes and fuses with the creature's skin, giving it a -10-foot penalty to Speed. A creature can [[Actions/Escape|Escape]] or [[Actions/Force Open|Force Open]] the ice (DC 34) to free itself; otherwise, the ice remains for 1 minute.\n\nThe fjord linnorm can't use Breath Weapon again for 1d4 rounds."

  - name: "Fjord Linnorm Venom"
    desc: " (cold,poison) **Saving Throw** DC 37 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 4d6 cold damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 6d6 cold damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Fjord Linnorm
creatures:
  - 1: Fjord Linnorm
```



Fjord linnorms make their homes in damp caves behind ice-cold waterfalls in the river-veined coastal reaches of the north. While they may appear graceful as they swim up the fjords for which they're named, they are as vile as any other of their species and take pleasures in capsizing river boats before gobbling up their terrified crews.
