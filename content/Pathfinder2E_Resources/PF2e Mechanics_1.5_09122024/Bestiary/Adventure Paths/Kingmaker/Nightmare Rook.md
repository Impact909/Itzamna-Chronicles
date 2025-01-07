---
title: "Nightmare Rook"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gBPPIYf5Xre6ex5J" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Nightmare Rook"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Nightmare Rook"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 38
perception:
  - name: "Perception"
    desc: "+38; Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +38, Deception: +35, Intimidation: +35"
abilityMods: [10, 6, 6, 5, 8, 5]
speed: 20 feet,  fly 80 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +34, __Ref__ +34, __Will__ +38"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380, regeneration 20 (deactivated by cold iron or lawful); __Resistances__ physical 20 (except cold iron)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold Iron or Lawful)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 42 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 39 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Wing Rebuff"
    desc: "`pf2:r`  **Trigger** A creature moves from beyond the reach of the roc's wing to within the reach of the roc's wing.\n* * *\n\n**Effect** The roc makes a wing Strike against the triggering creature. If the roc Pushes the creature, it disrupts the triggering move action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+38 (reach 15 feet)\n__Damage__  4d12 + 18 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+38 (agile, reach 15 feet)\n__Damage__  4d8 + 18 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+38 (agile, reach 30 feet)\n__Damage__  4d8 + 18 bludgeoning plus improved-push"

  - name: "Occult Innate Spells"
    desc: "DC 42, attack +34; __10th __  _[[Spells/Alter Reality|Alter Reality]]_; __9th __  _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Weird|Weird]]_; __8th __  _[[Spells/Phantasmal Killer|Phantasmal Killer (x3)]]_"

  - name: "Flying Strafe"
    desc: "`pf2:2`  The roc Flies up to its Speed and makes two talon Strikes at any point during that movement. Each Strike must target a different creature. Each attack takes the normal multiple attack penalty."

  - name: "Snack"
    desc: "  A roc gains a +2 circumstance bonus to hit with its beak Strike if the target is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its talon."

  - name: "Snatch"
    desc: "  A roc can Fly at half Speed while it has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in either or both of its talons, carrying that creature along with it."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push 10 feet]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Nightmare Rook
creatures:
  - 1: Nightmare Rook
```


Variant roc

Legendarily massive raptors capable of carrying off elephants as prey, rocs are typically about 30 feet long from beak to tail and have a wingspan of 80 feet or more. While their beaks are hooked to rip flesh from bone, their hunting strategy involves grabbing their prey in their powerful talons and then dropping it from great heights before feeding. This method creates a massive amount of carrion, which guarantees that rocs are followed by flocks of opportunistic scavengers, such as ravens and buzzards, who find it easy to steal bits of the larger birds' meals. Rocs, for the most part, don't mind these creatures, which sometimes get gobbled up along with the rest of the roc's food.

Rocs usually nest among mountaintops and cliffs inaccessible to all but the bravest of terrestrial dwellers. They are long-range predators that hunt both land and sea in search for massive prey to sustain them and their young. Rocs are antisocial and lone hunters who compete with each other in fierce aerial battles to protect territory. But about once a decade, a mating couple pairs up to raise their chicks. Once the chicks are old enough to hunt on their own, the parents separate to once again engage in lone hunting.

Particularly skilled druids or rangers might capture and train a roc to serve as a flying mount or hunting companion, though examples of such an incredible feat of domestication are few and far between. The easiest way to rear a roc is to do so from the moment it hatches, since the chick imprints on the first creature it sees. Acquiring a roc egg is by no means an easy feat, though, and is often a death sentence for the would-be egg-snatcher.
