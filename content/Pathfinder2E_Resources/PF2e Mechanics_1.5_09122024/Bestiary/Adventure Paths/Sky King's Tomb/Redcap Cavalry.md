---
title: "Redcap Cavalry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mq9RZK4cPQNz31vF" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Redcap Cavalry"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Redcap Cavalry"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fey]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision"
languages: "Common, Fey, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +17, Intimidation: +13, Nature: +13, Performance: +11"
abilityMods: [5, 4, 2, 1, 3, 1]
speed: 50 feet
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +14, __Will__ +11"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, fast healing 10; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scythe|Scythe]], Iron Boots, Red Cap"
  - name: "Not My Cap!"
    desc: " (auditory) **Trigger** Their bloodseeker mount fails their blood-crazed flat check\n\n**Requirements** the redcap is mounted on a giant bloodseeker\n* * *\n\n**Effect** The bloodseeker may reroll the flat check."

  - name: "Red Cap"
    desc: " (primal) A redcap's woolen hat is dyed with the blood of its victims. If the redcap loses its cap, it no longer benefits from fast healing and takes a –4 status penalty to its damage rolls. It can create a new cap in 10 minutes, but that cap doesn't grant its powers until the redcap has turned it red with Blood Soak. A cap has no benefit for creatures other than the redcap who made it.\n\n[[Bestiary Effects/Effect_ Lost Red Cap|Effect: Lost Red Cap]]"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Divine Revulsion"
    desc: " (emotion,fear,mental) If a redcap sees a creature brandish a religious symbol of a good deity (which requires an interact action by that creature) or use one to cast a divine spell, the redcap must attempt a DC 19 Will check save. It then becomes temporarily immune to all brandished religious symbols for 10 minutes.\n* * *\n\n**Critical Success** The redcap is unaffected\n\n**Success** The redcap is [[Conditions/Frightened|Frightened 2]]\n\n**Failure** The redcap gains the [[Conditions/Fleeing|Fleeing]] condition for 1 round and is [[Conditions/Frightened|Frightened 4]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scythe"
    desc: "+17 (deadly d10, trip)\n__Damage__  1d10 + 11 slashing"

  - name: "**Melee** `pf2:1` Boot"
    desc: "+15 (agile, versatile b)\n__Damage__  1d6 + 9 piercing"

  - name: "Blood Soak"
    desc: "`pf2:1` (manipulate) The redcap dips its cap in the blood of a slain foe. The foe must have died in the last minute, and the redcap must have helped kill it. The redcap gains a +4 status bonus to damage rolls for 1 minute.\n\n[[Bestiary Effects/Effect_ Blood Soak|Effect: Blood Soak]]"

  - name: "Flyby Swing"
    desc: "`pf2:r`  **Trigger** The recap's bloodseeker mount moves away from a creature within the redcap's reach\n\n**Requirements** The redcap is mounted on a giant bloodseeker\n* * *\n\n**Effect** The redcap Strikes the creature with their scythe."
 
```

```encounter-table
name: Redcap Cavalry
creatures:
  - 1: Redcap Cavalry
```



Whomever first imagined putting a fey with a bloodsoaked hat on a giant blood-crazed insect certainly had a sense of humor, but that didn't stop the redcaps from trying to domesticate and train giant bloodseekers. Although a flying cavalry was Queen Frilogarma's goal, her court ended up accidentally inventing redcap racing. In this sport, one redcap with a freshly soaked cap is swung around a racetrack by a giant arm while several other redcaps on giant bloodseekers fly after them. The "bait" redcap doesn't usually survive, but they are the center of attention for about two minutes.

* * *

In the Ether Court, redcaps train to ride giant bloodseeker specially bred to be mounts. While their fey cousins outside the court see this as folly, redcap courtiers consider riding bloodseekers a noble sport.

## That Bloody Hat

Even when a redcap isn't taking persistent bleed damage, their red caps drip crimson, soaked in the blood of their enemies. This is more than enough to provoke creatures who react strongly to the scent of blood. Creatures with scent treat a redcap as a creature taking persistent bleed damage.
