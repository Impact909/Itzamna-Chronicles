---
title: "Carrion Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.koisb5JjIQZA6sSk" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Carrion Golem"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Carrion Golem"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +14"
abilityMods: [4, -2, 3, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +13, __Ref__ +8, __Will__ +10"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  electricity,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 5 (except adamantine or slashing)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Golem Antimagic"
    desc: "  harmed by fire (4d6, 1d8 from areas or persistent damage); healed by electricity (area 1d6 HP); slowed by cold\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Stench"
    desc: " (aura,disease,olfactory) 40 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 19 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as it's sickened on a critical failure). While within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

  - name: "Vulnerable to Gentle Repose"
    desc: "  Casting a [[Spells/Peaceful Rest|Peaceful Rest]] spell on a carrion golem causes it to grow stiff. The golem attempts a DC 19 Fortitude check save. It's unaffected on a critical success, [[Conditions/Slowed|Slowed 1]] for 1d4 rounds on a success, and on a failure is [[Conditions/Immobilized|Immobilized]] and slowed for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (magical)\n__Damage__  2d10 + 4 piercing plus filth-fever"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile, magical)\n__Damage__  2d6 + 4 slashing plus filth-fever"

  - name: "Filth Fever"
    desc: " (disease) The [[Conditions/Sickened|Sickened]] and [[Conditions/Unconscious|Unconscious]] conditions from filth fever can't end or be reduced until the disease is cured.\n\n**Saving Throw** DC 19 Fortitude check\n\n**Stage 1** carrier with no ill effect (1d4 hours)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Sickened|Sickened 1]] and [[Conditions/Slowed|Slowed 1]] as long as it remains sickened (1 day)\n\n**Stage 4** unconscious (1 day)\n\n**Stage 5** dead"
 
```

```encounter-table
name: Carrion Golem
creatures:
  - 1: Carrion Golem
```



Carrion golems are foul-smelling and fly-swarmed amalgams of putrefied parts stitched together from many different creatures. Unlike most golems, carrion golems only rarely are given a humanoid form, instead appearing more twisted and bestial in frame. As a result, some students of golem crafting claim that the carrion golem isn't a "true golem," but regardless of those claims these foul constructs certainly share other golem-like traits, including their significant immunities. What is true is that most who craft carrion golems don't do so out of true interest in the technique of golem crafting, but for the golem's ability to spread disease. The crafters of carrion golems send their mindless minions to cause immediate destruction and leave wakes of illness and death behind them.
