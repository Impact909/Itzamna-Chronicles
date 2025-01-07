---
title: "Nightmarchers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dh8QLeERyt639nuq" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Nightmarchers"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Nightmarchers"
level: "Creature 14"

alignment: ""
size: "grg"
trait_01: [[incorporeal]]
trait_02: [[lawful]]
trait_03: [[spirit]]
trait_04: [[troop]]
trait_05: [[undead]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Religion: +27, Warfare Lore: +27"
abilityMods: [-5, 5, 4, 5, 5, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +19, __Will__ +25"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, troop defenses; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  sleep; __Weaknesses__ area damage 20, splash damage 10; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Kinsense"
    desc: " (detection,divine) Nightmarchers can detect creatures who are their kin, whether by blood or bond, as an imprecise sense. If they focus their senses on a creature by [[Actions/Seek|Seeking]], they learn whether they are related to that creature, and how."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (auditory,aura,emotion,fear,mental) 90 feet. DC 31 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 160 (12 squares), 80 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 31, attack +23\n__Constant__  __(4th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Blazing Admonition"
    desc: "`pf2:2` (divine,fire,visual) Heat scorches those who lay eyes on the nightmarchers. All creatures in a 60-foot cone take 15d6 fire damage (DC 34 Reflex check save).\n\n[[Conditions/Prone|Prone]] creatures and the nightmarchers' kin are unaffected as long as they have not taken a hostile action against the nightmarchers.\n\nThe nightmarchers can't use Blazing Admonition for 1d4 rounds."

  - name: "Missile Volley"
    desc: "`pf2:2`  The nightmarchers fling a hail of spears and stones, dealing 5d6+9 bludgeoning damage or 5d6+9 piercing damage to creatures in a 10-foot burst within 20 feet (DC 31 Reflex check save).\n\nWhen the nightmarchers are reduced to 8 or fewer squares, this decreases to a 5-foot burst."

  - name: "Striking Koa"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The troop attacks with spears, clubs, and leiomano against enemies within 5 feet (DC 33 Reflex check save) for their choice of bludgeoning, piercing, or slashing damage depending on the number of actions.\n\n`pf2:1` 2d6+2 bludgeoning damage, 2d6+2 piercing damage, or 2d6+2 slashing damage\n\n`pf2:2` 4d6+12 bludgeoning damage, 4d6+12 piercing damage, or 4d6+12 slashing damage\n\n`pf2:3` 6d6+12 bludgeoning damage, 6d6+12 piercing damage, or 6d6+12 slashing damage"

  - name: "Troop Movement"
    desc: "  Whenever the nightmarchers Stride, they first [[Bestiary Ability Glossary/Form Up|Form Up]] as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move. This works just like a Gargantuan creature moving; for instance, if any of the nightmarchers' squares enter difficult terrain, the extra movement cost applies to the whole group."
 
```

```encounter-table
name: Nightmarchers
creatures:
  - 1: Nightmarchers
```



While smooth roads remain a traveler's blessing, walking them after sunset risks nightmarcher attack. The ringing of conch shells and beating of drums herald the coming of these spirits as they walk the royal highways, unfettered by walls or barriers.

Nightmarchers react violently to those in their path. If a bystander is fortunate, an ancestor's spirit might call out to spare them. Those who refuse to show proper deference might be reduced to little more than ash on the wind come sunrise.
