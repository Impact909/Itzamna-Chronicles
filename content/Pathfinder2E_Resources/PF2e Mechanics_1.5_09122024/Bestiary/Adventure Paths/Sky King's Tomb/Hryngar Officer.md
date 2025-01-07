---
title: "Hryngar Officer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Ibzo3guQQtzUyTYg" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/hryngar
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Hryngar Officer"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Hryngar Officer"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[hryngar]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Diplomacy: +11, Intimidation: +13, Society: +10, Legal Lore: +12, Warfare Lore: +8"
abilityMods: [5, 0, 2, 0, 3, 3]
speed: 15 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 24
armorclass:
  - name: AC
    desc: "24 (26 with shield raised); __Fort__ +14, __Ref__ +12, __Will__ +15"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Dagger|Dagger]], [[Equipment/Longsword|+1 Longsword]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Full Plate|Full Plate]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Aura of Command"
    desc: " (aura,emotion,mental) 30 feet. The captain of the guard bolsters lower-level guards under their command, granting them a +1 status bonus to their attack rolls and a +2 status bonus to their Will saves.\n\n[[Bestiary Effects/Effect_ Under Command|Effect: Under Command]]\n\n[[Bestiary Effects/Effect_ Aura of Command|Effect: Aura of Command]]"

  - name: "Bravery"
    desc: "  When the captain of the guard rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "Shield Warden"
    desc: "  When the captain has their shield raised, they can [[Bestiary Ability Glossary/Shield Block|Shield Block]] when an attack is made against an adjacent ally. If they do, the shield prevents that ally from taking damage instead of the captain."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+18 (magical, versatile p)\n__Damage__  1d8 + 11 slashing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+12 (range increment 120 feet, reload 1)\n__Damage__  1d8 + 6 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(3rd)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Shielded Advance"
    desc: "`pf2:1`  **Requirements** The captain of the guard has their shield raised\n* * *\n\n**Effect** The captain of the guard presses forward, using their shield to push back foes.\n\nThe captain Strides and [[Actions/Shove|Shoves]], in either order. The multiple attack penalty doesn't apply to this Shove, though the Shove does count toward the captain's multiple attack penalty."
 
```

```encounter-table
name: Hryngar Officer
creatures:
  - 1: Hryngar Officer
```


Variant Captain Of The Guard

The captain of the guard leads a troop of soldiers who serve as security forces for a powerful individual, most often a high-ranking noble or very rich merchant, though this stat block could also represent a lower-ranking captain of the guard for the leader of a nation. A formidable opponent in their own right, the captain of the guard skillfully employs their troops to protect the life and health of their ward.

* * *

Larger societies rely on those with the authority and the ability to interpret and enforce laws. In good-aligned societies, these officials carry out their duties fairly. In neutral and evil ones, these officials can be harsh and cruel (with an altered alignment to reflect this), imposing severe punishments on those who can't pay for mercy.
