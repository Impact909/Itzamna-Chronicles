---
title: "Clockwork Amalgam"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zFZjtjh96AUSFOnC" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Clockwork Amalgam"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Clockwork Amalgam"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +38"
abilityMods: [10, 7, 6, -5, 0, -5]
speed: 30 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +34, __Ref__ +35, __Will__ +28"
hp: 455
health:
  - name: ""
  - name: HP
    desc: "455; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 20, orichalcum 20; __Resistances__ physical 15 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Efficient Winding"
    desc: "  For the clockwork amalgam to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for 7 days, after which time it becomes unaware of its surroundings and can't act until it's wound again.\n\nThe amalgam can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt a DC 33 Thievery check check to Disable a Device to wind the amalgam down. For each success, the assassin loses 1 hour of operational time. This can be done even if the amalgam is in standby mode."

  - name: "Recalibrate"
    desc: "`pf2:2`  The clockwork amalgam can recalibrate its internal structure to shed damaged components and replace them with new ones, restoring 125 HP to the construct. Each time it uses this ability, the clockwork amalgam permanently deactivates one of its five melee attacks as the components from that arm reassemble within the core of the machine."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blade"
    desc: "+38 (magical, reach 10 feet)\n__Damage__  4d12 + 18 slashing"

  - name: "**Melee** `pf2:1` Blowtorch"
    desc: "+38 (magical, reach 10 feet)\n__Damage__  10d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (magical, reach 10 feet)\n__Damage__  4d8 + 18 slashing plus push"

  - name: "**Melee** `pf2:1` Hose"
    desc: "+38 (magical, reach 15 feet)\n__Damage__  4d8 + 18 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Stamper"
    desc: "+38 (magical, reach 10 feet)\n__Damage__  4d8 + 18 bludgeoning plus knockdown"

  - name: "**Ranged** `pf2:1` Spike"
    desc: "+35 (magical, range increment 40 feet)\n__Damage__  4d12 + 8 piercing"

  - name: "Whirring Doom"
    desc: "`pf2:3`  **Frequency** once per round\n* * *\n\nThe clockwork amalgam becomes a blur of spinning weaponry. It makes up to five melee Strikes (one for each active melee attack it has available), taking a -4 penalty to the attack roll for each attack, but ignoring the multiple attack penalty until it has made all of its attacks. It can use each melee attack only once and it can target each creature in reach only once. If the clockwork amalgam used Whirring Doom in the previous round, it can use it again this round using only 1 action instead of 3. The amalgam's movement Speed is halved until the end of its next turn."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "Push"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Clockwork Amalgam
creatures:
  - 1: Clockwork Amalgam
```




