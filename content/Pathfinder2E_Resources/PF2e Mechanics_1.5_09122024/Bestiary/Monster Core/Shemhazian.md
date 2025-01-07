---
title: "Shemhazian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jajgEau9IhqseFru" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Shemhazian"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Shemhazian"
level: "Creature 16"

alignment: ""
size: "grg"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Chthonian, Draconic, Empyrean; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Deception: +25, Intimidation: +27, Medicine: +28, Religion: +30"
abilityMods: [9, 5, 7, 0, 6, 3]
speed: 35 feet,  climb 20 feet,  fly 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +32, __Ref__ +26, __Will__ +27; +1 status to all saves vs. magic"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Paralyzing Gaze"
    desc: " (aura,divine,unholy,visual) 30 feet.\n\nA non-demon creature that ends its turn in the aura must attempt a DC 35 Fortitude check save. If it fails, it's [[Conditions/Slowed|Slowed 1]] for 1 round, and if it critically fails, it is [[Conditions/Paralyzed|Paralyzed]] for 1 round."

  - name: "Succor Vulnerability"
    desc: "  A shemhazian's mutilation is a part of them, and they can't bear to see it reversed. The first time each round that a creature heals from damage the shemhazian dealt on their last turn, the demon takes 3d6 mental damage."

  - name: "Tail Whip"
    desc: "`pf2:r`  **Trigger** A creature within reach of the shemhazian's tail leaves a square during a move action it's using\n* * *\n\n**Effect** The shemhazian attempts to [[Actions/Trip|Trip]] the triggering creature. On a success, the creature also takes damage as if the shemhazian had hit with a tail Strike, and if the creature was flying, it falls 30 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 20 feet, unholy)\n__Damage__  3d12 + 17 piercing plus enfeebling-bite"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 20 feet, unholy)\n__Damage__  3d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+33 (magical, reach 20 feet, unholy)\n__Damage__  3d8 + 17 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (magical, reach 30 feet, unholy)\n__Damage__  3d6 + 17 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Divine Decree|Divine Decree]]_; __5th __  _[[Spells/Scouting Eye|Scouting Eye (x3)]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance (x3)]]_, _[[Spells/Translocate|Translocate (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Enfeebling Bite"
    desc: " (divine) If the shemhazian's jaws Strike damages a creature, the target is [[Conditions/Enfeebled|Enfeebled 3]] for 24 hours. The target can attempt a DC 37 Fortitude check save to reduce this to [[Conditions/Enfeebled|Enfeebled 1]] (or be unaffected on a critical success)."

  - name: "Focused Gaze"
    desc: "`pf2:1` (concentrate,divine,incapacitation,visual) The shemhazian focuses their gaze on a non-demon creature they can see within 30 feet. If that creature isn't already [[Conditions/Slowed|Slowed]] by the shemhazian's paralyzing gaze, it must attempt a save against the shemhazian's paralyzing gaze. If that creature is slowed, it must succeed at a DC 35 Fortitude check save or be [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\nA shemhazian can't use this ability against the same creature more than once per round."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shemhazian
creatures:
  - 1: Shemhazian
```



Shemhazians rise from the souls of torturers and those who reveled in mutilating the physical bodies of their victims. Standing 35 feet tall, a shemhazian is well equipped with a wide range of claws, pincers, and fangs to continue inflicting such torments on those they encounter.

Shemhazians delight in tormenting mortals, of course, but more than most demons, they revel in sharing the pain with their own kind. Other demons fear and hate shemhazians for this reason, with only the most powerful willing to work with a shemhazian to achieve a shared goal. Even then, the shemhazian is always on the watch for an opportunity to bring pain and suffering to their allies along with any foe.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
