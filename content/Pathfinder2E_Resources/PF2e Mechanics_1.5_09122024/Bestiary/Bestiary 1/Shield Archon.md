---
title: "Shield Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2ruC1wgzywjryAq1" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Shield Archon"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Shield Archon"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Diplomacy: +19, Intimidation: +19, Religion: +19, Survival: +17"
abilityMods: [5, 1, 7, 2, 3, 3]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +15, __Will__ +19; +1 status to all saves vs. magic"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125; __Weaknesses__ unholy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|+1 Striking Holy Spear]], [[Equipment/Sturdy Shield (Lesser)|Sturdy Shield (Lesser)]], [[Equipment/Full Plate|+1 Full Plate]]"
  - name: "Morphic Hands"
    desc: "`pf2:1` (divine) A shield archon's hands can change into a _+1 [[Equipment/Holy|Holy]] [[Equipment/Striking|Striking]] spear_ and a _[[Equipment/Sturdy Shield (Lesser)|Lesser Sturdy Shield]]_ or back into hands.\n\nTransforming does not restore any HP to the items, and if either the weapon or shield is fully destroyed, the archon loses that hand until it receives a [[Spells/Regenerate|Regenerate]] spell or similar magic.\n\nIf a shield archon is slain, its weapon and shield can be taken, but they fade into nothingness after 24 hours."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Living Shield"
    desc: "  A shield archon's shield is the focal point of its courage and soul. It always has its shield raised without needing to [[Action Macros/Raise a Shield|Raise a Shield]], and it can use [[Bestiary Ability Glossary/Shield Block|Shield Block]] as a free action instead of a reaction (Hardness 10, HP 80). A shield archon can trigger its Shield Block free action when an ally within 10 feet is the target of an attack, reducing damage to that ally instead of itself but otherwise following the normal rules of Shield Block."

  - name: "Menacing Guardian"
    desc: " (aura,divine) 30 feet. Enemies that start their turn in the area or enter it must attempt a DC 27 Will check save.\n\nOn a failure, they take a -1 status penalty to attack rolls, spell rolls, and damage rolls against any other target while in the aura for 24 hours or until they damage the archon, whichever comes first. On a critical failure, they can't use hostile actions against any other target while in the area for 24 hours or until they damage the archon, whichever comes first.\n\nRegardless of the result, a creature is then temporarily immune to further menacing guardian auras for 24 hours."

  - name: "Retributive Strike"
    desc: "`pf2:r`  **Damage Reduction** 12\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:0`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Holy Striking Spear"
    desc: "+22 (holy, magical, reach 10 feet)\n__Damage__  2d6 + 10 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +19; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __  _[[Spells/Share Life|Shield Other (x3)]]_; __1st __  _[[Spells/Sure Strike|True Strike (x3)]]_\n__Cantrips__  __(5th)__ _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast [[Spells/Translocate|Translocate]], it can cast an innate _dimension door_ (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's _dimension door_.\n\nIf the archon's _dimension door_ has enough distance, the archon appears the same distance and direction from the creature as before either used _dimension door_."

  - name: "Courageous Switch"
    desc: "  When a shield archon uses its [[Spells/Translocate|Translocate]] innate spell, it can choose to move into the space of a willing ally it can see within range. If it does so, the ally switches places with the archon, appearing in the space the archon just vacated, as if it too had cast Dimension Door."
 
```

```encounter-table
name: Shield Archon
creatures:
  - 1: Shield Archon
```



Shield archons defend the fortresses of Heaven against fiendish incursions. They wield their spears and shields in massive formations capable of withstanding any onslaught. Beneath their armor, they are sheathed in skin of steel. Given their tremendous strength and imposing stature, shield archons are ideal guardians of the meek and are sometimes summoned to the Material Plane to ward off the attacks of great numbers of evildoers.

* * *

Archons are guardians of Heaven and enemies of chaos and evil. They openly fight back the spread of fiends but also quietly nurture the seeds of virtue within mortals, teaching the denizens of the Material Plane how to act with honor and integrity, enact just laws, and cast off sin and temptation.

Archons live in the immense seven-tiered mountain of Heaven. They manifest in the Garden at the mountain's peak from mortal souls who answer a mysterious voice. There they swear to forever serve the cause of justice and transform into their new archon forms. Intensely orderly in their metamorphosis, new archons begin as lantern archons or other lesser forms, transforming into ever-greater archons as their virtue and achievements grow. Each archon represents a particular virtue, such as hope, charity, justice, or courage, and they gain strength in the presence of mortals who exemplify this virtue. Due to their extremely lawful nature, archons sometimes find themselves at odds with azatas.
