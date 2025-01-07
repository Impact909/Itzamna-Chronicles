---
title: "Blustering Gale"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yz5Njnzl42WcCP20" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Blustering Gale"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Blustering Gale"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[air]]
trait_02: [[elemental]]
trait_03: [[troop]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +22, Intimidation: +22, Stealth: +18"
abilityMods: [7, 5, 3, 0, 1, 5]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +24, __Will__ +18"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (16 squares); Thresholds 100 (12 squares), 50 (8 squares); __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Bullying Bluster"
    desc: " (auditory,aura,emotion,linguistic,mental) 30 feet. The blustering gale constantly unleashes a tirade of insults and aggressive taunts. Each enemy who enters or starts their turn in the aura must succeed at a DC 30 Will check save or become [[Conditions/Stupefied|Stupefied 1]] for as long as they remain within the aura ([[Conditions/Stupefied|Stupefied 2]] on a critical failure). The troop's members are collectively able to mimic a few curse words or insults in every language, allowing their Bullying Bluster to affect any creature who understands a language. A creature who succeeds at its save is temporarily immune for 1 hour. The blustering gale can activate or deactivate the aura with a free action, which has the concentrate trait."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Pummeling Winds"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The blustering gale bashes, batters, and pummels each adjacent enemy (DC 27 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 bludgeoning damage\n\n`pf2:2` 2d8+12 bludgeoning damage\n\n`pf2:3` 3d8+15 bludgeoning damage"

  - name: "Troop Movement"
    desc: "  Whenever a troop Flies or Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Windstorm"
    desc: "`pf2:2` (air) The blustering gale exhales as a unit, creating a powerful windstorm. This windstorm is a 10-foot burst within 100 feet that deals 3d8+10 bludgeoning damage (DC 30 Reflex check save). Creatures that fail their saving throw are pushed 10 feet in any direction (plus knocked [[Conditions/Prone|Prone]] on a critical failure). When the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst and the distance pushed decreases to 5 feet."
 
```

```encounter-table
name: Blustering Gale
creatures:
  - 1: Blustering Gale
```



Blustering gales are among the least of air elementals: spirits of the small breezes who sometimes arise in the wake of mightier creatures, like the downdraft of a swallow's wing or the sharp expulsion of a vigorous cough. Unwilling or unable to act effectively alone, they form into "gales," collections of weak elementals that use their combined power to hurl insults and pummel those who defy them in a misguided attempt to rise above their humble origins.

Together, they force other creatures to do their bidding, then move on when they grow bored. While most gales claim their abandoned minions were useless, in truth, blustering gales lack the commanding presence and confidence to retain vassals for long.

## Lackeys

Blustering gales sometimes serve as heralds or enforcers for other creatures (including cloud dragons, jaathooms, and other powerful air elementals), bullying and intimidating others at the behest of a more influential overlord. While blustering gales often feel secure and confident in these roles, they rankle at subservience, and rarely feel content with such an arrangement for long.
