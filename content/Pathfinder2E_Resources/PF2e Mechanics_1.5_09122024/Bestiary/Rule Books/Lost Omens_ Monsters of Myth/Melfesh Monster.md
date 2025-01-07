---
title: "Melfesh Monster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0HgT2LQ6bnqD9pfh" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Melfesh Monster"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Melfesh Monster"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fungus]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Aklo, Fey; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +13, Nature: +13, Survival: +13"
abilityMods: [4, 3, 4, 1, 2, 1]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +16, __Ref__ +14, __Will__ +12"
hp: 78
health:
  - name: ""
  - name: HP
    desc: "78; __Resistances__ fire 5, poison 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Reactive Growth"
    desc: "`pf2:r`  **Trigger** The Melfesh Monster takes physical damage\n* * *\n\n**Effect** The Melfesh Monster shifts plant matter to blunt the attack. It gains resistance 5 against the triggering physical damage."

  - name: "Sporesight"
    desc: "  If a creature has inhaled any of the Melfesh Monster's spores, the Melfesh Monster can sense the creature at the listed range."

  - name: "Terrorspores"
    desc: " (aura,emotion,fear,inhaled,mental,poison) 60 feet. A creature that enters the emanation must attempt a DC 21 Will check save. Regardless of outcome, the creature is temporarily immune to terrorspores for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]] and inhales spores that remain in its body for 1 minute.\n\n**Failure** As success, but [[Conditions/Frightened|Frightened 2]] and the spores remain for 1 hour.\n\n**Critical Failure** As success, but [[Conditions/Frightened|Frightened 3]], the spores remain for 1 hour, and the creature's frightened condition can't be reduced below 1 as long as spores remain in its body."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Limb"
    desc: "+16 (versatile p, versatile s)\n__Damage__  2d12 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Fungal Limb"
    desc: "+16 (agile)\n__Damage__  2d8 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Firelance"
    desc: "+15 (fire, magical, range increment 30 feet)\n__Damage__  2d8 + 2 fire"

  - name: "Envelop"
    desc: "`pf2:3`  The Melfesh Monster attempts to [[Actions/Grapple|Grapple]] a creature within reach. On a success, the creature is pulled into the Monster's body. The Melfesh Monster is [[Conditions/Slowed|Slowed 1]] while it envelops a creature, and this otherwise has the effects of [[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]] (the Melfesh Monster's size or smaller, 1d10 bludgeoning and 1d12 poison, Rupture 15)."

  - name: "Fulminate"
    desc: "`pf2:2` (fire) **Requirements** The Melfesh Monster has created a spore cloud, and the cloud is within range of one of the Melfesh Monster's fire abilities\n* * *\n\n**Effect** The Melfesh Monster targets the cloud with one of its abilities with the fire trait. The spore cloud explodes, dealing 4d10 fire damage and 4 persistent fire damage in a 40-foot burst originating from a single square within the cloud (DC 24 Reflex check save)."

  - name: "Spore Cloud"
    desc: "`pf2:2` (inhaled,poison) **Frequency** once per minute\n* * *\n\n**Effect** The Melfesh Monster conjures a cloud of spores within 60 feet in a 20-foot burst. The cloud lasts 1 minute. Creatures that enter or begin their turn within the cloud must succeed at a DC 21 Fortitude check save or take 3d8 poison damage, be [[Conditions/Sickened|Sickened 2]], and inhale spores that remain in their bodies for 1 minute (on a critical failure, [[Conditions/Sickened|Sickened 3]] and an additional 4 persistent poison damage)."
 
```

```encounter-table
name: Melfesh Monster
creatures:
  - 1: Melfesh Monster
```



Each Melfesh Monster is unique at any given time since the parent fungus only gives birth to a single monster at once, and each of these creations works a little differently and looks a little different from the last. However, their forms all bear similarities. A twisting mass of creeping vines creates the bulk of a Melfesh Monster's body, sculpted into a towering figure that can glide effortlessly across the ground. Mossy growths and trumpeting fungi cover the creature like matted fur, dripping from its back and shoulders in excess. A hood of dampened bark and thick moss covers its face, revealing only a crusty wooden jaw and a pair of gleaming red eyes. An acrid stench of burning manure follows the creature, often serving as the only warning that anyone gets before it attacks.

Despite their fungal nature, Melfesh Monsters are undamaged by their own jets of flame and resistant to fires set by others, often surprising hunters who paid too little attention to the legends before encountering the creature. Their terrifying spores also mean that most survivors of their attacks tend to be disoriented and delirious, relating accounts of the monster that are distorted by confusion and fear. This, along with the natural variance between different Melfesh Monsters, means that even the most diligent of researchers will come across contradictory evidence. Even if they learn from all the prior information collected over the years, they're still often caught off guard when trying to hunt down and fell the threat since the new Melfesh Monster might have an ability never seen before. The canniest researchers, when faced with the seemingly contradictory evidence, speculate that the creature might evolve or change over time, which is closer to the truth but still falls short.
