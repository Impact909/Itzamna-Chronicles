---
title: "Danava Titan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gIx7dTGyyOiup1Za" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/titan
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/23
statblock: inline
name: "Danava Titan"
level: 23
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Danava Titan"
level: "Creature 23"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[humanoid]]
trait_02: [[lawful]]
trait_03: [[titan]]
trait_04: [[water]]
modifier: 41
perception:
  - name: "Perception"
    desc: "+41; Darkvision, Truesight, Wavesense (Imprecise) 100 Feet"
languages: "Chthonian, Empyrean, Thalassic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +39, Arcana: +43, Athletics: +46, Crafting: +43, Nature: +41, Occultism: +43, Religion: +41, Society: +43"
abilityMods: [11, 8, 10, 10, 8, 6]
speed: 50 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 49
armorclass:
  - name: AC
    desc: "49; __Fort__ +41, __Ref__ +37, __Will__ +37; +4 status to all saves vs. mental or divine"
hp: 470
health:
  - name: ""
  - name: HP
    desc: "470; __Immunities__  death effects,  disease"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|+3 Major Striking Greatclub]]"
  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 100 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Hadalic Presence"
    desc: " (divine,illusion,mental,water) Creatures that fail their Will save against the titan's Impossible Stature aura also experience the crushing depths and darkness of the ocean floor.\n\nSuch creatures see as if in an area of [[Spells/Darkness|Darkness]] (10th level), and the titan can use their wavesense to detect such creatures as a precise sense, even if neither are in water. On a critical failure, the creature is also [[Conditions/Immobilized|Immobilized]]."

  - name: "Impossible Stature"
    desc: " (aura,divine,illusion,mental) 100 feet. Titans warp perception and distance around them to seem even larger and more imposing. A creature that enters or begins its turn within the emanation must succeed at a DC 46 Will check save or its movement toward the titan is movement over difficult terrain (greater difficult terrain on a critical failure) for 1 round."

  - name: "Relentless"
    desc: "  The titan is as ever-moving as ocean waves. They're permanently [[Conditions/Quickened|Quickened 1]], and the extra action can only be used to Stride, Strike, or Sustain a Spell, or as one of the actions necessary to Cast [[Spells/Dispel Magic|Dispel Magic]]."

  - name: "Roiling Rebuke"
    desc: "`pf2:r`  **Trigger** A creature within 200 feet targets the titan with or includes the titan in the area of an attack, spell, or other effect\n* * *\n\n**Effect** The titan makes a benthic wave Strike against the triggering creature. If the Strike hits, the titan disrupts the triggering action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+43 (backswing, magical, reach 40 feet, shove)\n__Damage__  4d10 + 20 bludgeoning 2d12 cold"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+40 (agile, reach 30 feet)\n__Damage__  4d8 + 20 bludgeoning 2d12 cold"

  - name: "**Ranged** `pf2:1` Benthic Wave"
    desc: "+40 (brutal, magical, range 200 feet, water)\n__Damage__  4d6 + 20 bludgeoning 2d12 cold"

  - name: "Divine Innate Spells"
    desc: "DC 46, attack +38; __10th __  _[[Spells/Implosion|Implosion]]_; __9th __  _[[Spells/Control Water|Control Water (At Will)]]_, _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Eclipse Burst|Eclipse Burst (x3)]]_, _[[Spells/Heal|Heal (x3)]]_, _[[Spells/Hydraulic Push|Hydraulic Push (x3)]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent (x3)]]_\n__Constant__  __(10th)__ _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Truesight|True Seeing]]_, _[[Spells/Water Walk|Water Walk]]_"

  - name: "Rituals"
    desc: "_Control Weather (Doesn't Require Secondary Casters)_, _Planar Binding (Doesn't Require Secondary Casters)_, _Resurrect (Doesn't Require Secondary Casters)_"

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 46 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Wide Cleave"
    desc: "`pf2:2`  The titan makes a melee weapon Strike against each foe within their reach. This counts as three attacks for the titan's multiple attack penalty."
 
```

```encounter-table
name: Danava Titan
creatures:
  - 1: Danava Titan
```



Danava titans once regulated the foundational forces that shaped reality. Rebuked by the gods for being harsh and inflexible overseers, these spurned titans joined their siblings in their failed war against their creators. Defeated, the danavas were cast into the paralyzing depths of the cosmos's seas. The few danava titans who have escaped now wield the cold, darkness, and crushing pressure of their prisons in pursuit of their ancient visions of reality. Danavas split mountains, wake primordial beasts, or level whole civilizations in accordance with grand designs they forged at the dawn of time. Others hunt and harvest the balance-enforcing aeons, who they see as usurpers of their divine responsibility.

* * *

Created by ancient deities long before the rise of mortal ancestries, titans united and attempted to overthrow their deific progenitors. The resulting war still figures prominently throughout mortal myths, in which most titans were cast down and imprisoned for eons.
