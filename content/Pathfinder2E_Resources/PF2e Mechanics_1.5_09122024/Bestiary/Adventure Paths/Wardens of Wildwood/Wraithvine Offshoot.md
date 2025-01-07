---
title: "Wraithvine Offshoot"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xL3EJouBQ6eAMUIt" 
tags:
  - pf2e/creature/type/plant
  - pf2e/creature/type/wraithvine
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Wraithvine Offshoot"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Wraithvine Offshoot"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[plant]]
trait_02: [[wraithvine]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Lifesense (Imprecise) 30 Feet, Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +10, Stealth: +12"
abilityMods: [2, 5, 3, -1, 2, 0]
speed: 30 feet,  burrow 10 feet,  climb 30 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +13, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Weaknesses__ fire 5; __Resistances__ bludgeoning 5, electricity 5"
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
    desc: "+14 (finesse)\n__Damage__  2d8 + 4 piercing plus grab"

  - name: "**Melee** `pf2:1` Thorny Vine"
    desc: "+14 (agile, finesse, reach 10 feet)\n__Damage__  2d4 + 4 slashing plus mandragora-venom"

  - name: "Piercing Shriek"
    desc: "`pf2:1` (auditory,mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The mandragora emits an unsettling shriek. Each non-mandragora creature within 30 feet must attempt a DC 25 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 2]] and [[Conditions/Slowed|Slowed 1]]. As long as the creature remains sickened, this slowed condition value can't be reduced below 1."

  - name: "Vitality Drain"
    desc: "`pf2:1`  **Requirements** The wraithvine offshoot has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The offshoot drains blood or ichor from the creature it has grabbed, dealing 2d6 untyped damage. If the creature has the plant trait, the offshoot gains temporary Hit Points equal to the damage dealt. A creature that has its vitality drained by an offshoot is [[Conditions/Drained|Drained 1]] until it receives healing of any kind or amount."

  - name: "Wraithvine Venom"
    desc: " (poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 1d6 poison damage, [[Conditions/Confused|Confused]], and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Confused|Confused]], and [[Conditions/Stupefied|Stupefied 1]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Wraithvine Offshoot
creatures:
  - 1: Wraithvine Offshoot
```


Variant mandragora

A mandragora looks like a freshly pulled tuber that has grown into the malformed shape of a child with a grotesque face and hideously bloated body. These insidious little plants typically form when a mandrake root is watered with a demon's blood. Upon absorbing the otherworldly properties of the demon's blood, the root animates and is forced to seek out blood to feast from, lest it die of thirst.

Always famished and in search for sustenance, mandragoras live haunted, pained lives and perform vile and desperate acts to acquire the blood they crave. While they prefer magically infused blood such as that of unicorns, fey, or sorcerers, and they can also feed off of potions, alchemical bombs, and other magical elixirs, a mandragora can subsist on the blood of non-magical creatures. They find the flavor of mundane blood to be bland and bitter, and they do not blanch at voicing these complaints to the creatures from which they drink.

While the typical mandragora is the size of a human child, some of these evil plants continue to grow and grow, reaching sizes more comparable to those of giants. Sometimes as they grow, they form additional limbs or rudimentary faces, eventually transforming into truly hideous mockeries of the human form.
