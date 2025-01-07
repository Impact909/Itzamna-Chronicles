---
title: "Cassisian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.B7TEmgHJzHXNGK3Y" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Cassisian"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cassisian"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[holy]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Diplomacy: +6, Religion: +6, Stealth: +6"
abilityMods: [-1, 1, 2, -1, 1, 1]
speed:  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16 +1 status vs. unholy creatures; __Fort__ +7, __Ref__ +6, __Will__ +4; +1 status to all saves vs. unholy creatures"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Weaknesses__ unholy 3; __Resistances__ cold 3, fire 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Transfer Protection"
    desc: " (holy) A creature can wear a willing cassisian as a helmet. While it does, the cassisian can't act, but the cassisian extends their +1 status bonus to AC and saves against unholy creatures to their wearer. At any time, the cassisian can detach themself from their wearer as a single action.\n\n[[Bestiary Effects/Effect_ Transfer Protection|Effect: Transfer Protection]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Headbutt"
    desc: "+6 (agile, finesse, holy, magical, reach 0 feet)\n__Damage__  1d6 - 1 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 16, attack +8; __4th __  _[[Spells/Read Omens|Read Omens]]_; __1st __  _[[Spells/Heal|Heal]]_\n__Cantrips__  __(1st)__ _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Light|Light]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) A cassisian can take the appearance of a dove, a winged humanoid, a dog, or a fish. Normally, this doesn't change their Speed or the attack and damage bonuses for their Strikes, but it might change the damage type Strikes deal (typically to bludgeoning). Any further changes for specific forms are noted below.\n\n*   **Dog**\n    *   **Size** Small;\n    *   [[Bestiary Ability Glossary/Scent|Scent (Imprecise) 30 feet]],\n    *   **Speed** 40 feet;\n    *   **Skills** Athletics +6;\n    *   **Melee** jaws +7, **Damage** 1d6+2 piercing plus [[Bestiary Ability Glossary/Knockdown|Knockdown]]\n*   **Fish**\n    *   **Speed** Swim 30 feet\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Eye Beams"
    desc: "`pf2:2` (concentrate,divine,holy) The cassisian releases beams of heat or cold from their eyes, dealing 2d6 cold or fire damage (DC 17 Reflex check save) to all creatures in a 15-foot line. They can't use Eye Beams again for 1d4 rounds."

  - name: "Repository of Lore"
    desc: "  While the cassisian isn't particularly intelligent, they have perfect memory and can remember everything they see or hear. This allows them to attempt Lore checks on any topic, provided (at the GM's discretion) they've encountered the topic in question before. The cassisian's limited intellect often prevents them from acting upon their knowledge, making them a better resource than agent in using information."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Cassisian
creatures:
  - 1: Cassisian
```



The weakest of angels, cassisians usually serve as lackey messengers for more powerful angels or as spiritual guides for mortals. Despite their limited intellect, cassisians have a knack for precise recollection, particularly with scripture. Most cassisians are formed from the souls of trustworthy mortals, but some arise from fragments of greater angels destroyed in service to the celestial realms.

* * *

The celestial hosts of angels are messengers and warriors, divided into choirs based on their abilities and purviews. Angels were one of the first creations of the gods, and many still assist their righteous creators throughout the cosmos. Most angels in modern times are not direct creations of the divine, however, instead consisting of ascended mortal souls drawn from the celestial planes.

The majority of unaffiliated angels live in Nirvana, the plane of virtue and enlightenment. Angels who are affiliated with deities dwell in those deities' domains or other areas where that god holds influence. Regardless of residence or service, angels remain benevolent messengers possessed with magical auras to aid their allies.
