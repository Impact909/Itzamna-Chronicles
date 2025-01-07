---
title: "Canopy Elder"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jvFntwYVF095x281" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Canopy Elder"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Canopy Elder"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[plant]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Low-Light Vision, Tremorsense (Imprecise) 120 Feet"
languages: "Arboreal, Common, Fey; speak with animals, speak with plants"
skills:
  - name: "Skills"
    desc: "Athletics: +37, Deception: +35, Intimidation: +35, Nature: +40, Stealth: +31, Forest Lore: +35"
abilityMods: [10, 4, 9, 6, 8, 5]
speed: 40 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +36, __Ref__ +28, __Will__ +33"
hp: 445
health:
  - name: ""
  - name: HP
    desc: "445; __Weaknesses__ fire 15; __Resistances__ bludgeoning 15, piercing 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Axe Vulnerability 15"
    desc: "  A canopy elder has a weakness to axes."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Vine Splint"
    desc: "`pf2:1` (healing) The canopy elder grows a mesh of vines around its broken branches, repairing the damage and restoring 40 HP to itself. The canopy elder can't use Vine Splint again for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Branch"
    desc: "+37 (reach 15 feet)\n__Damage__  4d12 + 18 bludgeoning plus improved-push"

  - name: "**Melee** `pf2:1` Root"
    desc: "+37 (reach 30 feet)\n__Damage__  4d8 + 18 bludgeoning plus trip"

  - name: "**Melee** `pf2:1` Vine"
    desc: "+37 (agile, reach 40 feet)\n__Damage__  4d6 + 18 bludgeoning plus improved-grab"

  - name: "Innate Primal Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Nature's Enmity|Nature's Enmity (x4)]]_\n__Constant__  __(9th)__ _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Fungal Web"
    desc: "`pf2:1`  The canopy elder launches a rapidly growing net of fungus from the mushrooms growing on its body at a single creature within 80 feet. The target must attempt a DC 39 Reflex check save or become restrained by the fungal web (Escape DC 39). While restrained, the creature takes 4d6 poison damage at the end of each of their turns."

  - name: "Pollen Cloud"
    desc: "`pf2:2`  The canopy elder releases a dense cloud of pollen from the epiphytes living in its branches. The cloud emanates from the canopy elder in a 40-foot emanation. The cloud doesn't move with the canopy elder and remains in place for 1d6 rounds before dissipating. Creatures inside the cloud become [[Conditions/Concealed|Concealed]], and all creatures outside the cloud become concealed to creatures within it. Non-plant and non-fungus creatures within the cloud must attempt a DC 38 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 3]], and on a critical failure the creature is also [[Conditions/Blinded|Blinded]] for 1 minute. Regardless of the result, a creature is then temporarily immune to the sickening and blinding effects of the canopy elder's pollen for 24 hours."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Canopy Elder
creatures:
  - 1: Canopy Elder
```



In the densest and oldest jungles, arboreals can reach heights of 200 feet or more. Given thousands of undisturbed years, these massive creatures enter into a symbiotic relationship with a myriad of plants, fungi, and animals to achieve the esteemed status of canopy elder. They provide a safe home for the creatures they host and develop a variety of powers that help them defend their forest realms.
