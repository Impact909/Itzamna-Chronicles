---
title: "Clockwork Serpent"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nt1DtbIVpSb2ja25" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Clockwork Serpent"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Clockwork Serpent"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [6, 3, 3, -5, 4, -5]
speed: 30 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +15, __Ref__ +17, __Will__ +16"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 10, orichalcum 10; __Resistances__ physical 10 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 26 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Activate Serpent Mode"
    desc: "`pf2:r`  **Trigger** The clockwork serpent begins its turn\n* * *\n\n**Effect** The clockwork serpent transforms into a different mode. Roll 1d3 and consult the options below. If it rolls a mode it can't currently activate, the clockwork serpent becomes [[Conditions/Clumsy|Clumsy 1]] until the start of its next turn. At the end of its turn, it automatically deactivates its serpent mode.\n\n**1 Cobra Mode** The clockwork serpent can use Intimidating Hood.\n\n**2 Constrictor Mode** The clockwork serpent can use its coils Strike and can Constrict.\n\n**3 Rattlesnake Mode** The clockwork serpent can use Shattering Rattle."

  - name: "Critical Deactivation"
    desc: "  If a clockwork serpent takes any precision damage or takes a critical hit and it has a serpent mode active, it must attempt a DC 16 Flat check. On a failure, it takes the damage from the critical hit as normal, is [[Conditions/Stunned|Stunned 1]], and its serpent mode deactivates."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (magical, reach 10 feet)\n__Damage__  2d10 + 9 piercing plus clockwork-serpent-venom"

  - name: "**Melee** `pf2:1` Coils"
    desc: "+20 (magical)\n__Damage__  2d12 + 9 bludgeoning plus grab"

  - name: "Clockwork Serpent Venom"
    desc: " (arcane,magical,poison) **Saving Throw** DC 26 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 2d6 poison damage, [[Conditions/Enfeebled|Enfeebled 1]], and off-guard (1 round)"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+6 bludgeoning, DC 26 Fortitude check\n\n**Requirements** The clockwork serpent is in constrictor mode\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Intimidating Hood"
    desc: "`pf2:2` (arcane,emotion,fear,mental) **Requirements** The clockwork serpent is in cobra mode\n* * *\n\n**Effect** The clockwork serpent flares out a cobra hood. All creatures within a 15-foot emanation must succeed at a DC 26 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure)."

  - name: "Shattering Rattle"
    desc: "`pf2:2` (arcane,sonic) **Requirements** The clockwork serpent is in rattlesnake mode\n* * *\n\n**Effect** The clockwork serpent rattles its tail, then snaps it like a whip to create a devastating blast of sonic energy in a 30-foot cone. Creatures in the area take 9d6 sonic damage (DC 26 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Clockwork Serpent
creatures:
  - 1: Clockwork Serpent
```



Clockwork serpents are often found serving as guardians in serpentfolk laboratories or temples.

## Experimental Serpents

Even stranger clockwork serpents are rumored to exist in the heart of serpentfolk enclaves. These constructs supposedly can repair damage to themselves when they change serpent modes, activate additional forms that allow swimming or flight, or even break apart into a seething swarm of smaller clockwork serpents.
