---
title: "Phasmadaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AZ6kYmbJwX9xxW97" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Phasmadaemon"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #192: Worst of All Possible Worlds"
name: "Phasmadaemon"
level: "Creature 17"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Truesight"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Deception: +31, Intimidation: +33, Religion: +29"
abilityMods: [8, 8, 6, 3, 4, 6]
speed: 25 feet,  fly 35 feet
sourcebook: "_Pathfinder #192: Worst of All Possible Worlds_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +31, __Ref__ +26, __Will__ +31"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340; __Immunities__  death effects,  fear effects; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet DC 35 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Unending Terror"
    desc: "  Escaping fear near a phasmadaemon is no simple task. Creatures don't automatically reduce their [[Conditions/Frightened|Frightened]] condition while they are within the phasmadaemon's Frightful Presence aura. Instead, they must attempt a Will save at the end of their turn against the DC of the effect that caused the condition. On a success, the creature's frightened condition is reduced by 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 10 feet, unholy)\n__Damage__  1d6 spirit plus grab 3d10 + 16 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d8 + 16 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Duplicate Foe|Duplicate Foe]]_, _[[Spells/Weird|Weird]]_; __8th __  _[[Spells/Mask of Terror|Mask of Terror]]_; __7th __  _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Shadow Blast|Shadow Blast]]_; __6th __  _[[Spells/Shadow Blast|Shadow Blast (x2)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Shadow Siphon|Shadow Siphon (x2)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_, _[[Spells/Nightmare|Nightmare (At Will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will, Good Only)]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d10+6 bludgeoning, DC 35 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Consume Fear"
    desc: "`pf2:1` (emotion,fear,mental) **Requirements** The phasmadaemon has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The phasmadaemon feeds on the creature's mortality and innate terror, dealing 6d8 mental damage. The creature must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The creature takes no damage and manages to break free from the phasmadaemon's grab.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and increases their frightened conditioned by 1, to a maximum of [[Conditions/Frightened|Frightened 4]].\n\n**Critical Failure** The creature takes double damage and increases their frightened condition by 2, to a maximum of frightened 4. If the creature is already frightened 4, it must attempt a DC 38 Fortitude check saving throw. If it fails, it is reduced to 0 Hit Points and dies. This effect has the death and incapacitation traits."

  - name: "Inescapable Form"
    desc: "  The phasmadaemon can Squeeze through tight spaces as if it were a Small creature. While Squeezing, it can move at its full Speed. The phasmadaemon can even Squeeze through spaces that typically fit only a Tiny creature, but does so at the standard speed for Squeezing."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Phasmadaemon
creatures:
  - 1: Phasmadaemon
```



Known also as terror daemons, the horrifying phasmadaemons make use of illusions and their own frightening appearance (that of a serpent with a bony tail, a horned crocodilian skull for a head, and several insectile pincers) to strike fear into the hearts of others. They represent deaths brought about by fright.

## Fearful Machinations

While daemons don't typically require food, phasmadaemons seem intent on feeding on the emotions, and especially the fears, of mortals. Some believe that the life force and emotions of creatures serves as the fuel for a phasmadaemon's magic, while others believe that phasmadaemons simply enjoy facing a mortal eye-to-eye while feeding, delighting in the fear in their prey's final moments.
