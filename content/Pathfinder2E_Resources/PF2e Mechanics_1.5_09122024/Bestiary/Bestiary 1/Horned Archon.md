---
title: "Horned Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.v1E4kH8tofvJf7fk" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Horned Archon"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Horned Archon"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Nature: +11, Religion: +9, Stealth: +10, Survival: +11"
abilityMods: [3, 4, 3, 1, 3, 1]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +10, __Will__ +11; +1 status to all saves vs. magic"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Weaknesses__ unholy 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Menacing Guardian"
    desc: " (aura,divine) 30 feet. Enemies that start their turn in the area or enter it must attempt a DC 19 Will check save.\n\nOn a failure, they take a -1 status penalty to attack rolls, spell rolls, and damage rolls against any other target while in the aura for 24 hours or until they damage the archon, whichever comes first. On a critical failure, they can't use hostile actions against any other target while in the area for 24 hours or until they damage the archon, whichever comes first.\n\nRegardless of the result, a creature is then temporarily immune to further menacing guardian auras for 24 hours."

  - name: "Retributive Strike"
    desc: "`pf2:r`  **Damage Reduction** 6\n\nA horned archon can also make a Retributive Strike with its composite longbow\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+11 (holy, magical)\n__Damage__  2d8 + 3 piercing plus push 1d6 spirit plus push"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+14 (deadly d10, holy, magical, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 4 piercing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 21, attack +13; __4th __  _[[Spells/Translocate|Dimension Door (x3)]]_; __2nd __  _[[Spells/Animal Messenger|Animal Messenger (x3)]]_; __1st __  _[[Spells/Charm|Charm (Animals Only) (x3)]]_, _[[Spells/Sure Strike|True Strike (x3)]]_\n__Cantrips__  __(2nd)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast [[Spells/Translocate|Translocate]], it can cast an innate _dimension door_ (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's _dimension door_.\n\nIf the archon's _dimension door_ has enough distance, the archon appears the same distance and direction from the creature as before either used _dimension door_."

  - name: "Touch of Charity"
    desc: "`pf2:1` (healing,manipulate) A horned archon can touch another creature to take on that creature's wounds, transferring up to 30 of the horned archon's HP to the touched creature. The horned archon can't transfer more HP than it currently has."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Horned Archon
creatures:
  - 1: Horned Archon
```



Horned archons are secretive and tireless sentinels and scouts, patrolling the Outer Sphere's untamed wilds for evil to eliminate and keeping small communities safe from demons, devils, and worse. They resemble muscular humans with the head, horns, and legs of a stag. When requested to do so by their patrons, especially Erastil, they journey to the Material Plane and patrol dangerous frontier areas, secretly performing acts of kindness such as leading hunters to food, helping lost children, and driving off evil creatures. Because they roam the wilds of Nirvana and Elysium, horned archons are among the best at understanding the perspectives of other celestials.

* * *

Archons are guardians of Heaven and enemies of chaos and evil. They openly fight back the spread of fiends but also quietly nurture the seeds of virtue within mortals, teaching the denizens of the Material Plane how to act with honor and integrity, enact just laws, and cast off sin and temptation.

Archons live in the immense seven-tiered mountain of Heaven. They manifest in the Garden at the mountain's peak from mortal souls who answer a mysterious voice. There they swear to forever serve the cause of justice and transform into their new archon forms. Intensely orderly in their metamorphosis, new archons begin as lantern archons or other lesser forms, transforming into ever-greater archons as their virtue and achievements grow. Each archon represents a particular virtue, such as hope, charity, justice, or courage, and they gain strength in the presence of mortals who exemplify this virtue. Due to their extremely lawful nature, archons sometimes find themselves at odds with azatas.
