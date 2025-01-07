---
title: "Gritblight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lPdGTj9t6wWqjaOV" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Gritblight"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Gritblight"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +27"
abilityMods: [8, 4, 5, 0, 4, 1]
speed: 30 feet,  burrow 30 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +19, __Will__ +23; +1 status vs. earth effects"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235; __Immunities__  bleed,  disease,  paralyzed,  poison,  sickened,  sleep; __Resistances__ acid 15, physical 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Blight Sense"
    desc: "  A gritblight can detect the location of nearby creatures afflicted with Ayrzul's Blight as a precise sense at the listed range."

abilities_mid:
  - name: ""
  - name: "Blight Cloud"
    desc: " (aura,poison,radiation) 30 feet.\n\nA gritblight continually sheds tiny fragments of radioactive earth in a cloud around it. This cloud conceals the gritblight as a light fog and sheds dim light in the area. Any creature that begins its turn in the aura takes 2d6 poison damage with a DC 30 Fortitude check save. A creature that fails its save is exposed to Ayrzul's Blight and a creature that critically fails is additionally [[Conditions/Sickened|Sickened 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (reach 10 feet)\n__Damage__  3d6 + 14 slashing 2d6 acid"

  - name: "**Ranged** `pf2:1` Caustic Shard"
    desc: "+23 (range increment 60 feet)\n__Damage__  3d6 + 10 piercing 2d6 acid"

  - name: "Ayrzul's Blight"
    desc: " (disease,earth,primal) Radioactive elemental energy courses through sap and blood, petrifies bark and bone, withers flesh, and mutates life. Creatures with the wood or plant trait treat critical successes against the disease as successes. The drained condition caused by Ayrzul's Blight can't be healed until the disease is removed. Ayrzul's Blight presents with obvious but varying symptoms, from coughing up black dust to suddenly becoming covered in itchy patches of flaky stone.\n\n**Saving Throw** DC 33 Fortitude check\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 3]] (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 4]] (1 day)\n\n**Stage 5** mutation (on a failure) or death (on a critical failure)"

  - name: "Earth Glide"
    desc: "  The gritblight can Burrow through any earthen matter, including rock. When it does so, the gritblight moves at its full burrow Speed, leaving no tunnels or signs of its passing."

  - name: "Grit Vision"
    desc: "  A gritblight's vision is unaffected by clouds of sand, dirt, grit, or other earth materials in air or water."

  - name: "Labyrinthine Vision"
    desc: "`pf2:3` (mental,primal) The gritblight forces disorienting visions of Ayrzul's Blistering Labyrinth into the minds of nearby creatures. All creatures in a 60-foot cone take 7d12 mental damage with a DC 33 Will check save. Creatures [[Conditions/Blinded|Blinded]] by a gritblight's Labyrinthine Vision see only endless earthen tunnels in every direction.\n\nThe gritblight can't use this ability again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is blinded for 1 minute.\n\n**Critical Failure** The creature takes double damage and is blinded permanently."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, claw, DC 33 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Gritblight
creatures:
  - 1: Gritblight
```



Resembling twisted lumps of fused gravel with oddly angled crystal limbs, gritblights are shock troops commonly used by Ayrzul to spread terror and disease to his enemies. These creatures are the gruesome result of experiments on crystalline elementals who were once the allies or servants of Ayrzul's rival lord of elemental earth, Sairazul. Their crystalline body parts appear cracked and deformed, only their single "eye" left intact.
