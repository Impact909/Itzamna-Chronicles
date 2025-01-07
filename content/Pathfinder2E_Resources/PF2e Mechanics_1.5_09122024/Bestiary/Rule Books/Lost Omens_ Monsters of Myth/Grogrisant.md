---
title: "Grogrisant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pxwRC0Jff7QzcjHY" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/primal
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Grogrisant"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Grogrisant"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[primal]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +35, Intimidation: +32, Stealth: +28, Survival: +28"
abilityMods: [9, 6, 9, -2, 5, 5]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +30, __Ref__ +28, __Will__ +25"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  blinded,  disease; __Resistances__ fire 15, physical 15 (except bludgeoning), poison 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Blinding Light"
    desc: " (aura,incapacitation,light,primal,visual) 40 feet. Any creature that begins its turn in the aura must attempt a DC 34 Fortitude check save or be [[Conditions/Blinded|Blinded]] for 1 minute and become temporarily immune for 1 day. If the creature critically fails this save, it's permanently blinded."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 ()\n__Damage__  3d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile)\n__Damage__  3d10 + 15 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 34, attack +26; __8th __  _[[Spells/Fire Shield|Fire Shield]]_, _[[Spells/Holy Light|Searing Light]]_\n__Cantrips__  __(8th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_\n__Constant__  __(3rd)__ _[[Spells/Veil of Privacy|Nondetection]]_ __(1st)__ _[[Spells/Vanishing Tracks|Pass Without Trace]]_"

  - name: "Dual Pounce"
    desc: "`pf2:2`  Grogrisant Strides and makes two claw Strikes against the same creature at the end of that movement. Each attack counts against Grogrisant's multiple attack penalty, but the penalty doesn't increase until after Grogrisant makes both attacks. If both attacks hit, combine their damage for the purpose of resistances and weaknesses."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  claw.\n\nIf Grogrisant Rends after a successful Dual Pounce, combine the Rend's damage with that from the Dual Pounce for the purpose of resistances and weaknesses.\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Vicious Rend"
    desc: "`pf2:r`  **Trigger** Grogrisant uses Rend\n* * *\n\n**Effect** The target's armor takes damage equal to the damage from Rend. The target can attempt a DC 37 Reflex check save, negating the armor damage on a successful save."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Grogrisant
creatures:
  - 1: Grogrisant
```



Grogrisant is an enormous lion with multiple eyes and a golden, glowing mane. As it was originally slain by Taldor's founding emperor, the legendary hero Taldaris, Grogrisant's appearance marks both danger for the people of Taldor and the potential for Taldans to prove their might against a creature from their fabled past. How it continues to appear time and time again remains a mystery, one that Taldan scholars continuously attempt to decipher.
