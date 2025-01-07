---
title: "Piscodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RfdI43dQ7zXBrhGL" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Piscodaemon"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Piscodaemon"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[daemon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision, See the Unseen"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Intimidation: +19, Medicine: +17, Stealth: +22, Survival: +19"
abilityMods: [6, 4, 6, 2, 3, 3]
speed: 25 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +16, __Will__ +19; +1 status to all saves vs. magic"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  death effects,  poison; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Enhance Venom"
    desc: "`pf2:r` (divine,misfortune,poison) **Trigger** A creature within 30 feet attempts a saving throw against piscovenom\n* * *\n\n**Effect** The creature takes an additional 2d8 poison damage even if it succeeds at its save."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (magical, unholy)\n__Damage__  2d10 + 12 slashing plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+23 (agile, magical, unholy)\n__Damage__  2d6 + 12 bludgeoning plus piscovenom 1d6 spirit plus piscovenom"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +19; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_, _[[Spells/Stinking Cloud|Stinking Cloud (x3)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Good Only)]]_, _[[Spells/Detect Poison|Detect Poison (At will)]]_\n__Constant__  __(2nd)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+6 bludgeoning damage, DC 30 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Gory Rend"
    desc: "`pf2:2`  The piscodaemon makes two claw Strikes against the same creature. If both hit, the creature takes 2d10 bleed and is exposed to piscovenom."

  - name: "Piscovenom"
    desc: " (poison) **Saving Throw** DC 30 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d8 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d8 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 3** 4d8 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Piscodaemon
creatures:
  - 1: Piscodaemon
```



Scions of death by poisoning, piscodaemons are cruel even by daemonic standards, delighting in slow and painful suffering. To a piscodaemon, death is but the icing on a putrescent cake-its true pleasure comes from watching, hearing, smelling, and even tasting raw anguish. While poisons and venoms are piscodaemons' preferred tools, their cruel claws are more than capable of tearing enemies asunder if necessary.

Piscodaemons dwell in fetid swamps and noxious waterways, including the River Styx, the Bile Sluice, and the Drowning Court of Charon, Horseman of Death. They are often accompanied by cadres of hydrodaemons-representations of death by drowning. While they are cunning commanders, piscodaemons are apt to forget their station in the heat of battle and slice their way to the center of the fray.
