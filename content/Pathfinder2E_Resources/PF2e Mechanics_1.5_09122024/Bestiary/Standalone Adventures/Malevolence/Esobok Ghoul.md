---
title: "Esobok Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mbaSA115XVStcVcS" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Esobok Ghoul"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Esobok Ghoul"
level: "Creature 5"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Lifesense 60 Feet, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +12, Intimidation: +11, Religion: +6, Stealth: +13, Survival: +12"
abilityMods: [3, 4, 4, -3, 3, 2]
speed: 30 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +13, __Will__ +10"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  paralyzed,  unconscious,  poison,  death effects,  disease"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (magical)\n__Damage__  1d10 + 7 piercing plus corrupted-touch,ghoul-fever,paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile, magical)\n__Damage__  1d6 + 7 slashing plus corrupted-touch,paralysis"

  - name: "Innate Divine Spells"
    desc: "DC 22, attack +12; __2nd __ (3 slots) _[[Spells/Invisibility|Invisibility (Self Only)]]_"

  - name: "Consume Flesh"
    desc: "`pf2:1` (manipulate) **Requirements** The esobok ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 3d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "Corrupted Touch"
    desc: "  An esobok ghoul's Strikes deal 1d6 void damage to living creatures. A creature critically hit by an esobok ghoul's Strike must attempt a DC 18 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure) as rot spreads throughout their flesh."

  - name: "Ghoul Fever"
    desc: " (disease) **Saving Throw** DC 22 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a ghoul the next midnight."

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 22 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]].\n\nIt can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Pounce"
    desc: "`pf2:1`  The esobok ghoul Strides and then makes a claw Strike. If it began this action hidden, it remains hidden until after the Strike."
 
```

```encounter-table
name: Esobok Ghoul
creatures:
  - 1: Esobok Ghoul
```




