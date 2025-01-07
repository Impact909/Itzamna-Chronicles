---
title: "Scarecrow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y44q2bVNDXGoZsOL" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Scarecrow"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Scarecrow"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[construct]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12"
abilityMods: [5, 2, 3, -4, 3, -2]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +13, __Ref__ +8, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ fire 5; __Resistances__ physical 5 (except slashing)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Scarecrow's Leer"
    desc: " (aura,emotion,fear,mental,occult,visual) 40 feet.\n\nThe scarecrow's eyes flicker with an unnerving glow. A creature can't reduce its [[Conditions/Frightened|Frightened]] condition below 1 as long as it is in the aura's emanation. When a creature enters or starts its turn in the aura, it must attempt a DC 18 Will check save. Birds and other avian creatures take a -2 circumstance penalty to this save.\n* * *\n\n**Critical Success** The creature is unaffected and is then temporarily immune for 24 hours.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]] and is [[Conditions/Fascinated|Fascinated]] by the scarecrow until the end of its next turn.\n\n**Critical Failure** As failure, but [[Conditions/Frightened|Frightened 3]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (versatile s)\n__Damage__  2d6 + 7 bludgeoning plus clawing-fear"

  - name: "Baleful Glow"
    desc: " (concentrate,light,mental,occult) The scarecrow's head bursts into ghostly, heatless flame that sheds bright light in a 20-foot emanation (and dim light to the next 20 feet). If the scarecrow uses this ability on the first round of combat, any creature that has not acted yet is startled and becomes [[Conditions/Off-Guard|Off-Guard]] against the scarecrow for 1 round. It can suppress the light by using this action again."

  - name: "Clawing Fear"
    desc: "  The scarecrow's strikes deal an additional 1d6 mental damage to [[Conditions/Frightened|Frightened]] creatures."

  - name: "Mundane Appearance"
    desc: "`pf2:1` (concentrate) Until it acts, the scarecrow resembles an ordinary scarecrow. It has an automatic result of 32 on Deception checks and DCs to pass as an ordinary scarecrow."
 
```

```encounter-table
name: Scarecrow
creatures:
  - 1: Scarecrow
```



A ramshackle collection of materials in a human shape, the scarecrow construct is indistinguishable from a normal scarecrow until it slowly creaks to life. As it animates, its carved pumpkin or sackcloth face bursts into eldritch flame, sending fear creeping into the air around it. Each scarecrow is handcrafted and unique in its appearance, though most are 5 to 6 feet tall and constructed of a combination of wood, cloth, rope, straw, sawdust, discarded husks and cobs, and similar materials, all dressed in ragged pastoral garments. This rudimentary construction makes a scarecrow somewhat fragile, prone to snapping limbs in the crush of battle. Yet its structure is adaptable, allowing it to reshape another piece of itself into a clawed limb or grip a severed portion of itself to swat at its foes.

When a scarecrow is created, it must be anointed with a drop of its creator's blood into each of its eyes. This blood soaks into the material and siphons a tiny sliver of the creator's soul away—not enough to harm the creator, but more than enough to imbue the scarecrow with an instinctive intellect that allows it to follow commands as eagerly as a well-trained (if ill-tempered) guard dog. When a scarecrow is destroyed, the blood leaks back out from its eyes, but the portion of the creator's soul never returns.
