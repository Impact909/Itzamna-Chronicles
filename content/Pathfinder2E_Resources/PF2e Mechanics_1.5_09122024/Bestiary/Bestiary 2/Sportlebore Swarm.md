---
title: "Sportlebore Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hoRAMRVgcbTHO1dI" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Sportlebore Swarm"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Sportlebore Swarm"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Stealth: +17"
abilityMods: [2, 6, 4, -4, 2, 4]
speed: 35 feet,  fly 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +17, __Will__ +13"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 7, splash damage 7; __Resistances__ bludgeoning 3, piercing 7, slashing 7"
abilities_top:
  - name: ""

  - name: "Sportlebore Infestation"
    desc: " (disease) **Saving Throw** DC 22 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 hour)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 2]] (1 hour)\n\n**Stage 4** 4d6 bludgeoning damage (DC 25 Fortitude check save) as the host painfully vomits out a sportlebore swarm and returns to stage 1"

abilities_mid:
  - name: ""
  - name: "Swarm Mind"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Pour Down Throat"
    desc: "`pf2:r`  **Trigger** A creature in the sportlebore swarm's area speaks, uses a verbal component, or opens its mouth\n* * *\n\n**Effect** A portion of the sportlebore swarm attempts to surge down the throat of the triggering creature, which must attempt a DC 25 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature gets a mouthful of sportlebores. It spits the insects out and avoids further damage, but it can't speak for 1 round, and if it was performing a verbal spellcasting action, the spell fails and the caster wastes the action.\n\n**Failure** The creature takes 4d6 piercing damage from sportlebore bites, can't speak for 1 round, and loses a spell as noted under Success.\n\n**Critical Failure** As failure, but the creature is also exposed to sportlebore infestation."

attacks:
  - name: ""

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each creature in the sportlebore swarm's area takes 4d6 piercing damage (DC 25 Reflex check save)."
 
```

```encounter-table
name: Sportlebore Swarm
creatures:
  - 1: Sportlebore Swarm
```



A swarm of sportlebores is a much more dangerous foe than a single insect.
