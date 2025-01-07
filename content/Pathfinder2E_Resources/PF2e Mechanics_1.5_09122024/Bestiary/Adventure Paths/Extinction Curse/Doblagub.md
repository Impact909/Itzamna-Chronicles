---
title: "Doblagub"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DkL3qvK1fcq8RDo1" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Doblagub"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Doblagub"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fey]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Truesight"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Deception: +28, Intimidation: +28, Nature: +26, Survival: +24"
abilityMods: [8, 3, 6, 2, 5, 7]
speed: 10 feet,  swim 10 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +23, __Ref__ +18, __Will__ +26"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Etheric Fibers"
    desc: " (aura,mental) 40 feet. **Requirements** A doblagub has bonded with their current location by being called there via a ritual or by remaining in one place for 10 years\n* * *\n\n**Effect** The doblagub grows etheric fibers that they can use to psychically keep prey close. Any time a creature tries to move within this aura, it must succeed at a DC 30 Will check save or the movement fails and the action is wasted."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 10 feet)\n__Damage__  4d8 + 14 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+27 (reach 15 feet)\n__Damage__ "

  - name: "Primal Innate Spells"
    desc: "DC 33, attack +27; __6th __  _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Enthrall|Enthrall (x2)]]_, _[[Spells/Illusory Scene|Illusory Scene (At Will)]]_, _[[Spells/Wall of Stone|Wall of Stone]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Lightning Bolt|Lightning Bolt (x2)]]_, _[[Spells/Paralyze|Paralyze (x3)]]_; __3rd __  _[[Spells/Faerie Fire|Faerie Fire (x2)]]_, _[[Spells/Fear|Fear (At Will)]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Produce Flame|Produce Flame]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Etheric Tug"
    desc: "`pf2:1`  **Requirements** The doblagub's etheric fibers aura is active\n\n**Frequency** once per round\n* * *\n\n**Effect** All non-brughadatch creatures within the aura must succeed at a DC 30 Fortitude check save or be pulled 10 feet toward the doblagub."

  - name: "Magical Tongue"
    desc: "  A doblagub can use their tongue to make spell attacks with spells that have a range of touch."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 4d10+8 bludgeoning, Rupture 24\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Doblagub
creatures:
  - 1: Doblagub
```



Elder brughadatches command groups of fellow brughadatches, who placate the doblagub with fresh meals and trophies of the group's grisly catches.

* * *

Brughadatches are malevolent fey tricksters with distinct stages of life: they spawn from the First World's primal energies as esurient tadpoles, grow into humanoids capable of creating enticing illusions, then finally evolve into huge, slothful toads that warp their environs with mere thoughts.
