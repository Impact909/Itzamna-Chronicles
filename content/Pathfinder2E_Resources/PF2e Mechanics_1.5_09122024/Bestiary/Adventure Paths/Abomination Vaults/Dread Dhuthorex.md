---
title: "Dread Dhuthorex"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.E22embjxblQiPibo" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Dread Dhuthorex"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Dread Dhuthorex"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[amphibious]]
trait_03: [[chaotic]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Occultism: +16, Stealth: +20, Survival: +21"
abilityMods: [8, 3, 5, -1, 4, 0]
speed: 20 feet,  swim 40 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 31
armorclass:
  - name: AC
    desc: "31 all-around vision; __Fort__ +24, __Ref__ +18, __Will__ +21"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  acid"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 27 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (deadly d12, reach 10 feet)\n__Damage__  3d10 + 12 piercing plus grab"

  - name: "**Melee** `pf2:1` Snout"
    desc: "+24 (reach 10 feet)\n__Damage__  3d8 + 12 bludgeoning plus push"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+22 (agile, reach 15 feet)\n__Damage__  3d6 + 12 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 27, attack +19; __5th __  _[[Spells/Mariner's Curse|Mariner's Curse]]_; __3rd __  _[[Spells/Hypnotize|Hypnotic Pattern]]_, _[[Spells/Mind Reading|Mind Reading]]_"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  50 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Overpowering Jaws"
    desc: "  A dread dhuthorex deals 8 piercing damage to its target if its jaws Strike is a failure (but not a critical failure)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d6+8 bludgeoning plus 2d6 acid damage, Rupture 23\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Dread Dhuthorex
creatures:
  - 1: Dread Dhuthorex
```



More intelligent than their lesser kin, dread dhuthorexes possess eerie, enchanting powers.

* * *

Strange things swim in sunless seas, but few as fierce as the shark-like dhuthorexes. These beasts chase prey fearlessly and tenaciously.
