---
title: "Dread Roc"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2pWaonRyccZMwRQC" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Dread Roc"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Dread Roc"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +31"
abilityMods: [9, 3, 7, -4, 2, 0]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +25, __Will__ +24"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Wing Rebuff"
    desc: "`pf2:r`  **Trigger** A creature moves from beyond the reach of the roc's wing to within the reach of the roc's wing.\n* * *\n\n**Effect** The roc makes a wing Strike against the triggering creature. If the roc Pushes the creature, it disrupts the triggering move action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+30 (reach 15 feet)\n__Damage__  3d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+30 (agile, reach 15 feet)\n__Damage__  3d8 + 18 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+30 (agile, reach 30 feet)\n__Damage__  2d6 + 15 bludgeoning plus improved-push"

  - name: "Dreadful Screech"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The dread roc screeches terrifyingly. Each creature in a 120-foot emanation must attempt a DC 32 Will check save. Regardless of the result, creatures are temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is fleeing for 1 round and [[Conditions/Frightened|Frightened 3]]."

  - name: "Flying Strafe"
    desc: "`pf2:2`  The roc Flies up to its Speed and makes two talon Strikes at any point during that movement. Each Strike must target a different creature. Each attack takes the normal multiple attack penalty."

  - name: "Snack"
    desc: "  A roc gains a +2 circumstance bonus to hit with its beak Strike if the target is grabbed or restrained in its talon."

  - name: "Snatch"
    desc: "  A roc can Fly at half Speed while it has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in either or both of its talons, carrying that creature along with it."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "Improved Push 15ft"
    desc: "  **Requirements** The monster's last action was a success with a Strike that lists Push in its damage entry.\n* * *\n\n**Effect** The monster automatically knocks the target away from the monster. Unless otherwise noted in the ability description, the creature is pushed 15 feet. If the attack was a critical hit, this distance is doubled."
 
```

```encounter-table
name: Dread Roc
creatures:
  - 1: Dread Roc
```


Variant roc

Legendarily massive raptors capable of carrying off elephants as prey, rocs are typically about 30 feet long from beak to tail and have a wingspan of 80 feet or more. While their beaks are hooked to rip flesh from bone, their hunting strategy involves grabbing their prey in their powerful talons and then dropping it from great heights before feeding. This method creates a massive amount of carrion, which guarantees that rocs are followed by flocks of opportunistic scavengers, such as ravens and buzzards, who find it easy to steal bits of the larger birds' meals. Rocs, for the most part, don't mind these creatures, which sometimes get gobbled up along with the rest of the roc's food.

Rocs usually nest among mountaintops and cliffs inaccessible to all but the bravest of terrestrial dwellers. They are long-range predators that hunt both land and sea in search for massive prey to sustain them and their young. Rocs are antisocial and lone hunters who compete with each other in fierce aerial battles to protect territory. But about once a decade, a mating couple pairs up to raise their chicks. Once the chicks are old enough to hunt on their own, the parents separate to once again engage in lone hunting.

Particularly skilled druids or rangers might capture and train a roc to serve as a flying mount or hunting companion, though examples of such an incredible feat of domestication are few and far between. The easiest way to rear a roc is to do so from the moment it hatches, since the chick imprints on the first creature it sees. Acquiring a roc egg is by no means an easy feat, though, and is often a death sentence for the would-be egg-snatcher.
