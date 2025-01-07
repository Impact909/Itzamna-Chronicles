---
title: "Vargouille"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.g7kIuXWoiaxSOBIH" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Vargouille"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Vargouille"
level: "Creature 2"
rare_03: [[Rare]]
alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Daemonic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +4, Intimidation: +6, Stealth: +8"
abilityMods: [0, 4, 2, -3, 2, 0]
speed:  fly 25 feet
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +10, __Will__ +8"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+10 (agile, finesse, unholy)\n__Damage__  1d8 piercing 1d6 poison"

  - name: "Tenacious Wounds"
    desc: " (curse,occult) A creature who takes poison damage from a vargouille must succeed at a DC 18 Fortitude check save or be cursed. The cursed creature can't regain HP except via magic, and anyone Casting a Spell to heal the creature must succeed at a DC 18 counteract check or the healing has no effect. The vargouille's counteract rank is equal to its creature level. A creature can attempt a new DC 18 Fortitude check save once per day (typically when it makes its daily preparations) to end this curse. The curse ends automatically if the creature is healed to maximum HP."

  - name: "Vargouille's Kiss"
    desc: "`pf2:3` (disease,occult) **Requirements** The vargouille is adjacent to a [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Unconscious|Unconscious]], or willing humanoid creature\n\n**Effect** The vargouille nuzzles up against a helpless or willing humanoid creature in a parody of a lover's kiss-the creature must then attempt a saving throw or begin an unsettling transformation into a vargouille. The sickened, stupefied, and unconscious conditions from Vargouille's Kiss don't improve on their own until the disease is cured. This disease can't progress in stage as long as the victim is in sunlight or in the area of a 3rd-rank or higher light effect.\n\n**Saving Throw** DC 18 Fortitude check\n\n**Stage 1** no ill effect (2 hours)\n\n**Stage 2** victim's hair falls out, [[Conditions/Sickened|Sickened 1]] (2 hours)\n\n**Stage 3** victim's ears elongate into winglike shapes and their teeth grow tangled and sharp, [[Conditions/Stupefied|Stupefied 1]] (2 hours)\n\n**Stage 4** as Stage 3, but the victim falls unconscious (2 hours)\n\n**Stage 5** death, and the victim's head transforms into a new vargouille that detaches from the body and flies off to spread evil on its own."

  - name: "Vargouille's Shriek"
    desc: "`pf2:2` (auditory,incapacitation,occult,visual) The vargouille distends its jaw awfully and emits an unnerving shriek. All creatures within 60 feet who can see and hear the vargouille must attempt a DC 15 Fortitude check save.\n\n**Success** The creature is unaffected and is temporarily immune to Vargouille's Shriek for 24 hours.\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]] until the end of its next turn.\n\n**Critical Failure** The creature is paralyzed. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."
 
```

```encounter-table
name: Vargouille
creatures:
  - 1: Vargouille
```



Vargouilles are scavengers from the swamps of Abaddon, where they flop and flap through strange and haunted skies in constant search of fresh souls to torment. In this daemonic nightmare realm, vargouilles play a role similar to that of a raven or vulture, although they augment these roles with a malevolent delight in causing pain and anguish that no scavenger bird could ever hope to match. A vargouille is larger than a human head, typically between 12 and 20 inches high with a 15- to 35-inch wingspan. While vargouilles aren't natives of the Material Plane, they can be found there nevertheless, occupying graveyards, ancient battlefields, or anywhere one can find remnants of death and decay.
