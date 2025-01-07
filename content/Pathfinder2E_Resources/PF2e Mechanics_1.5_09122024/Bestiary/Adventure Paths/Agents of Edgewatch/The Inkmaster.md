---
title: "The Inkmaster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i4nwO1dFQBf8hOqt" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "The Inkmaster"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "The Inkmaster"
level: "Creature 16"

alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Deception: +25, Intimidation: +27, Medicine: +28, Religion: +30"
abilityMods: [9, 5, 7, 0, 6, 3]
speed: 35 feet,  climb 20 feet,  fly 35 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
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
  - name: "Items"
    desc: "Gearblade"
abilities_mid:
  - name: ""
  - name: "Clockwork Brain"
    desc: "  A second brain, made of clockwork, is implanted in the Inkmaster's skull. Any time he makes a Will save, he rolls twice and takes the higher result."

  - name: "Paralyzing Gaze"
    desc: " (aura,divine,visual) 30 feet. A non-evil creature that ends its turn in the aura must attempt a DC 35 Fortitude check save. If it fails, it's slowed 1 for 1 round, and if it critically fails, it is instead paralyzed for 1 round."

  - name: "Succor Vulnerability"
    desc: "  A shemhazian's mutilation is a part of them, and they can't bear to see it reversed. The first time each round that a creature heals from damage the shemhazian dealt on their last turn, the demon takes 3d6 mental damage."

  - name: "Tail Whip"
    desc: "`pf2:r`  **Trigger** A creature within reach of the shemhazian's tail leaves a square during a move action it's using.\n* * *\n\n**Effect** The shemhazian attempts to Trip the triggering creature. On a success, the creature also takes damage as if the shemhazian had hit with a tail Strike, and if the creature was flying, it falls 30 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 20 feet, unholy)\n__Damage__  3d12 + 17 piercing plus enfeebling-bite 1d6 spirit plus enfeebling-bite"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 20 feet, unholy)\n__Damage__  3d8 + 17 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+33 (magical, reach 20 feet, unholy)\n__Damage__  3d8 + 17 bludgeoning plus improved-grab 1d6 spirit plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (magical, reach 20 feet, unholy)\n__Damage__  3d6 + 17 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Gearblade"
    desc: "+33 (disarm, magical, unholy, versatile b)\n__Damage__  3d12 + 17 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +27; __8th __  _[[Spells/Divine Decree|Divine Decree]]_; __7th __  _[[Spells/Fly|Fly]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Translocate|Dimension Door (x2)]]_, _[[Spells/Scouting Eye|Prying Eye (x3)]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance (x3)]]_; __2nd __  _[[Spells/Invisibility|Invisibility]]_"

  - name: "Divine Rituals"
    desc: "DC 36, attack +26"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Enfeebling Bite"
    desc: " (divine) If the shemhazian's jaws Strike damages a creature, the target is [[Conditions/Enfeebled|Enfeebled 3]]. The target can attempt a DC 37 Fortitude check save to reduce this to [[Conditions/Enfeebled|Enfeebled 1]] (or be unaffected on a critical success)."

  - name: "Focused Gaze"
    desc: "`pf2:1` (concentrate,divine,incapacitation,visual) The shemhazian focuses their gaze on a non-evil creature they can see within 30 feet. If that creature isn't already slowed by the shemhazian's paralyzing gaze, it must attempt a save against the shemhazian's paralyzing gaze. If that creature is [[Conditions/Slowed|Slowed]], it must succeed at a DC 35 Fortitude check save or be [[Conditions/Paralyzed|Paralyzed]] for 1 round. A shemhazian can't use this ability against the same creature more than once per round."

  - name: "Rend"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Improved Grab"
    desc: "  **Requirements** The monster's last action was a success with a Strike that lists Improved Grab in its damage entry, or it has a creature grabbed using this action.\n* * *\n\n**Effect** The monster automatically Grabs the target until the end of the monster's next turn. The creature is grabbed by whichever body part the monster attacked with, and that body part can't be used to Strike creatures until the grab is ended. Using Improved Grab extends the duration of the monster's Improved Grab until the end of its next turn for all creatures grabbed by it, but this costs an action. A grabbed creature can use the Escape action to get out of the grab, and the Grab ends for a grabbed creatures if the monster moves away from it."
 
```

```encounter-table
name: The Inkmaster
creatures:
  - 1: The Inkmaster
```


Male variant shemhazian

Shemhazians rise from the souls of torturers and those who reveled in mutilating the physical bodies of their victims. Standing 35 feet tall, a shemhazian is well equipped with a wide range of talons, claws, and fangs to continue inflicting such torments on those it encounters.

Shemhazians delight in visiting torment upon mortals, of course, but more than most demons, these fiends revel in sharing the pain with their own kind. Other demons fear and hate shemhazians for this reason, with only the most powerful willing to work with a shemhazian to achieve a shared goal. Even then, the shemhazian is always on the watch for an opportunity to bring pain and suffering to its allies along with any foe.
