---
title: "Sykever"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.T0hIvYWcaavgJyiq" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/darvakka
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Sykever"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Sykever"
level: "Creature 15"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[darvakka]]
trait_03: [[evil]]
trait_04: [[shadow]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common, Diabolic, Necril; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Athletics: +29, Intimidation: +28, Religion: +27, Stealth: +27, Shadow Plane Lore: +27, The Void Lore: +27, Warfare Lore: +27"
abilityMods: [8, 4, 6, 6, 6, 7]
speed: 40 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +25, __Ref__ +25, __Will__ +31"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 10, silver 10; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Entropy's Shadow"
    desc: " (aura,divine,void) 40 feet. Sykevers leak entropy and corruption from their very being. A living creature entering or starting its turn in the aura takes 4d6 void damage with a DC 33 Fortitude check. If it fails, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute and pulled 10 feet toward the sykever."

  - name: "Sunlight Powerlessness"
    desc: "  A sykever caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+31 (magical, reach 10 feet)\n__Damage__  3d8 + 12 bludgeoning 1d10 cold 2d8 bleed"

  - name: "**Melee** `pf2:1` Arm Spike"
    desc: "+31 (agile, magical, reach 10 feet)\n__Damage__  3d8 + 12 piercing 1d10 cold"

  - name: "Divine Innate Spells"
    desc: "DC 36, attack +28; __7th __  _[[Spells/Harm|Harm (x3)]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Interplanar Teleport|Plane Shift (to the Universe, Void, or Netherworld only)]]_; __6th __  _[[Spells/Truesight|True Seeing]]_; __4th __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Invisibility|Invisibility (x3)]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(8th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Change Posture"
    desc: "`pf2:1`  The sykever changes between their bipedal and quadrupedal stance. In their bipedal stance, the sykever can use all the abilities in their stat block except Horned Rush. In their quadrupedal stance, the sykever has a Speed of 80 feet but can't make arm spike Strikes, Disarm, cast spells, or use Crush Item."

  - name: "Crush Item"
    desc: "`pf2:r`  **Trigger** The sykever gets a critical success to [[Actions/Disarm|Disarm]]\n\n**Requirements** The sykever is in their bipedal stance\n* * *\n\n**Effect** The sykever snatches the item and pierces it with their arm spikes. The item becomes broken and falls to the ground in the sykever's space. Items that are already broken aren't further damaged, and an item with 14 or higher Hardness is unaffected."

  - name: "Draining Gaze"
    desc: "`pf2:1` (concentrate,divine,visual) The sykever fixes their nightmarish gaze on one creature they can see, who must attempt a DC 36 Will check save. Regardless of the result, the target is temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Enfeebled|Enfeebled 2]] for 1 round if the sykever is in bipedal stance, or [[Conditions/Clumsy|Clumsy 2]] for 1 round if the sykever is in quadrupedal stance.\n\n**Failure** As success, but the effect lasts 1 minute.\n\n**Critical Failure** As success, but [[Conditions/Enfeebled|Enfeebled 3]] or [[Conditions/Clumsy|Clumsy 3]], and the effect lasts 10 minutes."

  - name: "Horned Rush"
    desc: "`pf2:1`  **Requirements** The sykever is in their quadrupedal stance\n* * *\n\n**Effect** The sykever Strides and then makes a horn Strike."
 
```

```encounter-table
name: Sykever
creatures:
  - 1: Sykever
```



The most common darvakkas are sykevers, walkers in the night. Bloodthirsty but calculating, they lead legions of dead into battle on the Material Plane, working toward the simple goal of ending all life.

* * *

Darvakkas, also called nightshades, are a ravenous evil made up of equal parts darkness and malice. Originally creatures of the Outer Planes who travel to the convergence of the Shadow Plane and the Void—where the power of nothingness obliterates them—these undead abominations are the physical embodiment of entropy. They burn with an intense hatred for all life, working to bring a final, dark night to the Material Plane where nothing but ash and ice remain.

As creatures twisted by darkness and shadow, darvakkas have a great aversion to sunlight and all sources of vitality energy. On the Material Plane, they spend the hours of daylight hidden below ground, amid ruins, or submerged deep in the ocean's darkest chasms beyond the reach of the sun's rays, emerging when darkness shelters them overhead.

Darvakkas have an aura of entropy that attracts undead thralls to serve as warriors and heralds. They rarely seek alliances with each other or other creatures, existing in solitude as the heads of individual armies of the dead.
