---
title: "Immense Mandragora"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mWS24jOEzujfDMHf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Immense Mandragora"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Immense Mandragora"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[plant]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Low-Light Vision"
languages: "Aklo, Chthonian, Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +35, Stealth: +38"
abilityMods: [10, 5, 6, 0, 7, 6]
speed: 40 feet,  burrow 10 feet,  climb 40 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +34, __Ref__ +31, __Will__ +35"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Weaknesses__ fire 20; __Resistances__ bludgeoning 20, electricity 20"
abilities_top:
  - name: ""

  - name: "Blood Scent"
    desc: " (fey) A mandragora can smell creatures with blood as an imprecise sense at a range of 30 feet, and it can smell demons, fey, and sorcerers with blood as a precise sense at a range of 30 feet."

abilities_mid:
  - name: ""
  - name: "Vulnerability to Supernatural Darkness"
    desc: "  Whenever a mandragora begins its turn in an area of magical darkness, it is [[Conditions/Slowed|Slowed 1]] on that turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (finesse)\n__Damage__  4d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Thorny Vine"
    desc: "+38 (agile, finesse, reach 10 feet)\n__Damage__  4d8 + 18 slashing plus immense-mandragora-venom"

  - name: "Apocalyptic Shriek"
    desc: "`pf2:1` (auditory,mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The immense mandragora emits a devastating shriek. Each non-mandragora creature within 30 feet must attempt a DC 42 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]] and takes 8d8 mental damage.\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]] and takes 16d8 mental damage.\n\n**Critical Failure** The creature is sickened 2, [[Conditions/Slowed|Slowed 1]], and takes 150 mental damage. As long as the creature remains sickened, this slowed condition value can't be reduced below 1."

  - name: "Blood Drain"
    desc: "`pf2:1`  **Requirements** The immense mandragora has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The immense mandragora drains blood from the creature it has grabbed, dealing 12d6 damage. If the creature is a demon, fey, or sorcerer, the mandragora gains temporary Hit Points equal to the damage dealt. A creature that has its blood drained by a mandragora is [[Conditions/Drained|Drained 2]] until it receives healing of any kind or amount."

  - name: "Immense Mandragora Venom"
    desc: " (poison) **Saving Throw** DC 42 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 4d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 4d6 poison damage, [[Conditions/Confused|Confused]], and stupefied 1 (1 round)\n\n**Stage 3** 6d6 poison damage, confused, and stupefied 1 (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Immense Mandragora
creatures:
  - 1: Immense Mandragora
```


Variant mandragora

A mandragora looks like a freshly pulled tuber that has grown into the malformed shape of a child with a grotesque face and hideously bloated body. These insidious little plants typically form when a mandrake root is watered with a demon's blood. Upon absorbing the otherworldly properties of the demon's blood, the root animates and is forced to seek out blood to feast from, lest it die of thirst.

Always famished and in search for sustenance, mandragoras live haunted, pained lives and perform vile and desperate acts to acquire the blood they crave. While they prefer magically infused blood such as that of unicorns, fey, or sorcerers, and they can also feed off of potions, alchemical bombs, and other magical elixirs, a mandragora can subsist on the blood of non-magical creatures. They find the flavor of mundane blood to be bland and bitter, and they do not blanch at voicing these complaints to the creatures from which they drink.

While the typical mandragora is the size of a human child, some of these evil plants continue to grow and grow, reaching sizes more comparable to those of giants. Sometimes as they grow, they form additional limbs or rudimentary faces, eventually transforming into truly hideous mockeries of the human form.
