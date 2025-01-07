---
title: "Mandragora Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.b6elc2D0LOHSl8Bc" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/plant
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Mandragora Swarm"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Mandragora Swarm"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[plant]]
trait_04: [[swarm]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Low-Light Vision"
languages: "Chthonian, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +29, Stealth: +34"
abilityMods: [5, 8, 6, -1, 6, 0]
speed: 30 feet,  burrow 10 feet,  climb 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +30, __Ref__ +34, __Will__ +28"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230, fast healing 15; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 15, fire 15, splash damage 15; __Resistances__ bludgeoning 15, electricity 15, piercing 15, slashing 7"
abilities_top:
  - name: ""

  - name: "Blood Scent"
    desc: " (fey) A mandragora can smell creatures with blood as an imprecise sense at a range of 30 feet, and it can smell demons, fey, and sorcerers with blood as a precise sense at a range of 30 feet."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 15]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Vulnerability to Supernatural Darkness"
    desc: "  Whenever a mandragora begins its turn in an area of magical darkness, it is [[Conditions/Slowed|Slowed 1]] on that turn."

attacks:
  - name: ""

  - name: "Blood Drain"
    desc: "  **Trigger** An enemy takes damage from the mandragora swarm's Swarming Bites action\n* * *\n\n**Effect** The mandragora swarm drains blood from the creature, dealing 9d6 damage. If the creature is a demon, fey, or sorcerer, the mandragora gains temporary Hit Points equal to the damage dealt. A creature that has its blood drained by a mandragora is [[Conditions/Drained|Drained 2]] until it receives healing of any kind or amount."

  - name: "Mandragora Swarm Venom"
    desc: " (poison) **Saving Throw** DC 40 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 4d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 4d6 poison damage, [[Conditions/Confused|Confused]], and stupefied 1 (1 round)\n\n**Stage 3** 6d6 poison damage, confused, and stupefied 1 (1 round)"

  - name: "Piercing Shriek"
    desc: "`pf2:1` (auditory,mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The mandragora emits an unsettling shriek. Each non-mandragora creature within 30 feet must attempt a DC 40 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 2]] and [[Conditions/Slowed|Slowed 1]]. As long as the creature remains sickened, this slowed condition value can't be reduced below 1."

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 7d8 piercing damage (DC 40 Reflex check) and is exposed to mandragora swarm venom. A successful save negates the poison exposure."
 
```

```encounter-table
name: Mandragora Swarm
creatures:
  - 1: Mandragora Swarm
```


Variant mandragora

A mandragora looks like a freshly pulled tuber that has grown into the malformed shape of a child with a grotesque face and hideously bloated body. These insidious little plants typically form when a mandrake root is watered with a demon's blood. Upon absorbing the otherworldly properties of the demon's blood, the root animates and is forced to seek out blood to feast from, lest it die of thirst.

Always famished and in search for sustenance, mandragoras live haunted, pained lives and perform vile and desperate acts to acquire the blood they crave. While they prefer magically infused blood such as that of unicorns, fey, or sorcerers, and they can also feed off of potions, alchemical bombs, and other magical elixirs, a mandragora can subsist on the blood of non-magical creatures. They find the flavor of mundane blood to be bland and bitter, and they do not blanch at voicing these complaints to the creatures from which they drink.

While the typical mandragora is the size of a human child, some of these evil plants continue to grow and grow, reaching sizes more comparable to those of giants. Sometimes as they grow, they form additional limbs or rudimentary faces, eventually transforming into truly hideous mockeries of the human form.
