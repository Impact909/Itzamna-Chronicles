---
title: "Water Elemental Vessel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8DsnCVb5lfGx85DV" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Water Elemental Vessel"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Water Elemental Vessel"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Aklo, Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Stealth: +32"
abilityMods: [8, 8, 8, 0, 0, 0]
speed: 35 feet,  swim 100 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +30, __Ref__ +28, __Will__ +22"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 15"
abilities_top:
  - name: ""

  - name: "Spell Circle"
    desc: " (mental) By performing an hour-long ritual, an elemental vessel can form a spell circle with an arcane or primal spellcaster. After the spell circle is formed, other spellcasters can join the spell circle by performing the same hour-long ritual while assisted by at least one spellcaster already in the spell circle. Each member of the spell circle must contribute at least one spell to the elemental vessel. The spellcaster permanently loses access to a spell slot equal to the spell's rank and the elemental vessel adds the contributed spell to its list of arcane innate spells (regardless of the spell's original type). An elemental vessel can be imbued with no more than three spells per spell rank. If the elemental vessel is destroyed, all members of the spell circle regain the spell slots they contributed to the creature. The arcane innate spells shown below represent a typical spell list for an elemental vessel, but each elemental vessel is likely to have different spells depending on what its spell circle has contributed."

abilities_mid:
  - name: ""
  - name: "Dispel Vulnerability"
    desc: "  Whenever a creature successfully counteracts one of its spells, the vessel permanently loses access to that spell and takes damage equal to 4 × the spell's rank. The spell circle member who contributed that spell regains access to their contributed spell slot."

  - name: "Inhabit Vessel"
    desc: " (mental) Any member of the elemental vessel's spell circle can spend 3 actions to mentally inhabit the vessel for 1 round. While they inhabit the vessel, the inhabiter controls the vessel's actions, and the vessel uses the inhabiter's Intelligence, Wisdom, and Charisma modifiers for all checks. Only one creature can inhabit an elemental vessel at a time."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+30 (reach 10 feet)\n__Damage__  3d12 + 12 bludgeoning plus push"

  - name: "Innate Arcane Spells"
    desc: "DC 38, attack +30; __8th __  _[[Spells/Polar Ray|Polar Ray]]_; __7th __  _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/Volcanic Eruption|Volcanic Eruption]]_; __6th __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Purple Worm Sting|Purple Worm Sting]]_; __5th __  _[[Spells/Mariner's Curse|Mariner's Curse]]_, _[[Spells/Wall of Ice|Wall of Ice]]_; __4th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Wall of Fire|Wall of Fire]]_; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Mist|Obscuring Mist]]_, _[[Spells/Stupefy|Touch of Idiocy]]_; __1st __  _[[Spells/Hydraulic Push|Hydraulic Push]]_, _[[Spells/Shocking Grasp|Shocking Grasp]]_, _[[Spells/Spider Sting|Spider Sting]]_"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 35 Reflex check save, no damage, [[Actions/Escape|Escape]] DC 35, Rupture 28\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Internal Spell Strike"
    desc: "`pf2:1`  The elemental vessel targets an engulfed creature with one of its spells. The spell must have a range of touch."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Water Elemental Vessel
creatures:
  - 1: Water Elemental Vessel
```



Spellcasters create elemental vessels by harvesting raw elemental energy and then binding it within a specially enchanted magic circle to grant it life.
