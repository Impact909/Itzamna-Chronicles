---
title: "Glitterspore"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tEFl4VedMA6mvDsz" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Glitterspore"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Glitterspore"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[fungus]]
trait_02: [[mindless]]
trait_03: [[swarm]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +18"
abilityMods: [4, 4, 5, -5, 3, -3]
speed: 20 feet,  fly 25 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +19, __Ref__ +16, __Will__ +13"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105; __Immunities__  bleed,  fatigued,  poison,  sleep,  unconscious,  visual,  mental,  grabbed,  prone,  restrained; __Weaknesses__ area damage 10, fire 10, splash damage 10; __Resistances__ bludgeoning 6, slashing 11, piercing 11"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Fascinating Mimicry"
    desc: " (aura,mental,visual) 30 feet. While a glitterspore mimics a plant, its glittering spores and vibrant colors make it unnaturally beautiful. A creature that starts its turn in the aura must succeed at a DC 23 Will check save or become [[Conditions/Fascinated|Fascinated]] by the glitterspore for 1 round. This aura activates automatically when a glitterspore uses Plant Mimicry, and it deactivates when the glitterspore reverts to its natural form."

attacks:
  - name: ""

  - name: "Burrowing Spores"
    desc: "`pf2:1`  Each enemy in the glitterspore's space takes 4d8 piercing damage (DC 26 Reflex check save) and is exposed to spore rot."

  - name: "Invade"
    desc: "`pf2:3`  The glitterspore enters the ears, mouth, and nostrils of a living non-fungus or non-plant creature, then bursts out through their flesh. One enemy in the glitterspore's space takes 7d8 piercing damage (DC 26 Reflex check save). On a failed save, the target also takes 1d8 persistent bleed damage and is [[Conditions/Drained|Drained 1]]."

  - name: "Plant Mimicry"
    desc: "`pf2:1`  The glitterspore reconfigures its component spores to assume the shape and appearance of another plant, such as a flower bed, shrubbery, tree, or topiary. This doesn't change the glitterspore's texture or overall size but does alter its coloration and appearance. The glitterspore has an automatic result of 29 (33 in gardens, forests, or swamps) on Deception checks and DCs to pass as a non-creature plant. The glitterspore stays in this shape until it takes an action."

  - name: "Spore Cloud"
    desc: "`pf2:2` (poison) A glitterspore unleashes a cloud of sparkling, hypnotic spores in a 60-foot-radius burst. Each creature in the area is exposed to spore rot and must succeed at a DC 26 Will check save or be [[Conditions/Fascinated|Fascinated]] for 1d4 rounds."

  - name: "Spore Rot"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage plus [[Conditions/Clumsy|Clumsy 1]] and –5-foot status penalty to Speed (1 round)\n\n**Stage 2** 2d6 poison damage plus [[Conditions/Clumsy|Clumsy 2]] and –10-foot status penalty to Speed (1 round)\n\n**Stage 3** 3d8 poison damage plus [[Conditions/Clumsy|Clumsy 3]] and [[Conditions/Paralyzed|Paralyzed]] (1d4 rounds)"
 
```

```encounter-table
name: Glitterspore
creatures:
  - 1: Glitterspore
```



A glitterspore is a colony of mold spores that function as a mindless yet cunning conglomerate. Composed of razor-sharp spores that glitter hypnotically, this insidious fungus adopts the appearance of plants to lure in prey, altering its form and coloration to perfectly impersonate a variety of flora.

Ghorus designed glitterspores to be pernicious and deadly. They can gain sustenance from a variety of sources, including sunlight and soil, but their preferred food source is blood. When possible, glitterspores enter their prey through open orifices or by burrowing directly into their flesh. They then consume their prey from within, cutting through muscle and bone to bathe in blood.

## Living Legacy

While Ghorus and his followers are long dead, many of Ghorus's creations live on, including deadly plant creatures like the glitterspore, dangerous weapons, and—of course—ghorans. From the heart of the Verduran Forest, these successful creations and half-finished experiments have spread across Golarion.
