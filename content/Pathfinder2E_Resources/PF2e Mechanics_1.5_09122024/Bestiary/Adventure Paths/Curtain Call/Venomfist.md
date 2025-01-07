---
title: "Venomfist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JbNOtpAiBMJhMq1j" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/elemental
  - pf2e/creature/type/unholy
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/22
  - remaster
statblock: inline
name: "Venomfist"
level: 22
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Venomfist"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[elemental]]
trait_03: [[unholy]]
trait_04: [[water]]
modifier: 40
perception:
  - name: "Perception"
    desc: "+40; Greater Darkvision"
languages: "Common, Muan, Petran, Pyric, Sussuran, Talican, Thalassic; Telepathy 100 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +43, Crafting: +39, Diplomacy: +36, Intimidation: +38, Nature: +38, Religion: +40, Stealth: +38, Norgorber Lore: +41"
abilityMods: [11, 8, 10, 9, 8, 6]
speed: 40 feet,  swim 120 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +42, __Ref__ +34, __Will__ +36"
hp: 430
health:
  - name: ""
  - name: HP
    desc: "430; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ acid 20, bludgeoning 20, fire 20"
abilities_top:
  - name: ""

  - name: "Constant Spells"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Toxic Downpour"
    desc: " (aura,primal) Venomfist's presence alters the weather within 2 miles to heavy rainfall as long as they're located in a sizable body of water. When they become hostile, the rain in a 120-foot emanation from them becomes highly toxic and deals 8d8 poison damage (DC 42 basic Fortitude half) to all creatures in the area."

  - name: "Vortex"
    desc: " (aura,water) 120 feet. Water in the area that is in the same body of water as Venomfist is difficult terrain for Swimming creatures that don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+42 (magical, reach 20 feet)\n__Damage__  4d6 + 21 bludgeoning plus improved-grab 4d6 poison plus improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 45, attack +37; __10th __  _[[Spells/Cataclysm|Cataclysm]]_; __9th __  _[[Spells/Toxic Cloud|Toxic Cloud]]_, _[[Spells/Wrathful Storm|Wrathful Storm]]_; __8th __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Caustic Blast|Caustic Blast]]_\n__Constant__  __(10th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Constrict"
    desc: "`pf2:1`  4d6 bludgeoning + 4d6 poison, DC 45 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Create Poison"
    desc: "`pf2:1`  **Frequency** once per day\n* * *\n\n**Effect** Venomfist transforms a portion of their watery body into a single dose of any type of common poison of 20th level or lower—tears of death is their favorite. If they're holding a container, they can create the poison within that container, at which point the poison remains viable for 24 hours before it reverts to water. Alternatively, they can apply a contact or injury-created poison to their fist."

  - name: "Surge"
    desc: "`pf2:2`  Venomfist expands their space to fill the area of their vortex. Creatures within the aura take 6d12+6 bludgeoning and 6d12+6 poison damage with a DC 45 Fortitude check save. A creature that fails this save is pushed 40 feet. Venomfist then retracts to their former space and cannot use Surge again for 1d4 rounds."

  - name: "Improved Grab"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Venomfist
creatures:
  - 1: Venomfist
```




