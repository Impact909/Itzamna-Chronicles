---
title: "Ainamuuren"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.m883bJLv8VOWk6IE" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Ainamuuren"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #189: Dreamers of the Nameless Spires"
name: "Ainamuuren"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[cold]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Elven, Erutaki, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Stealth: +22"
abilityMods: [7, 4, 5, 0, 5, 0]
speed: 35 feet
sourcebook: "_Pathfinder #189: Dreamers of the Nameless Spires_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +23, __Ref__ +22, __Will__ +23; +1 status bonus to saves against good and necromancy spells and effects"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  cold,  controlled,  disease; __Resistances__ fire 10, mental 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tentacle Only)]]"
    desc: "`pf2:r`  Tentacle only\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Blackfrost Evasion"
    desc: "`pf2:r`  **Trigger** Ainamuuren takes at least 35 physical damage from a single attack, and he isn't currently discorporated\n* * *\n\n**Effect** Ainamuuren discorporates into a whirling blizzard of blackfrost for 3 rounds. During this time, he gains resistance 10 to physical damage and weakness 10 to force damage. He gains a fly Speed of 40 feet, but the only action he can take is to Fly. While discorporated, the first time each round that Ainamuuren enters another creature's space or a creature enters Ainamuuren's space, that creature takes 4d8 cold and is exposed to blackfrost. At the start of his turn, Ainamuuren can end this effect as a free action."

  - name: "Reactive Tentacles"
    desc: "  At the start of his turn, when Ainamuuren regains his actions, he gains an additional reaction that can be used only to make an Attack of Opportunity."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+26 (reach 10 feet)\n__Damage__  3d6 + 10 bludgeoning plus blackfrost-dead-blackfrost"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+26 (agile, cold)\n__Damage__  3d8 + 10 bludgeoning plus knockdown 1d6 cold plus knockdown"

  - name: "Occult Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Synaptic Pulse|Synaptic Pulse]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_"

  - name: "Dreams of the Blackfrost Whale"
    desc: "`pf2:2` (incapacitation,mental) **Frequency** once per day\n* * *\n\n**Effect** Ainamuuren fixes his many-eyed gaze upon a single target he can see within 60 feet, then opens wide his maw to release a torrent of whispers channeled from Osoyo's slumbering mind. The targeted creature must attempt a DC 32 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature endures a brief moment where they believe they are imprisoned in the ice, as Osoyo has been for thousands of years, and is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The vision of being imprisoned in ice is more profound, and in the span of a few seconds, the creature endures what seems like a thousand years of imprisonment. The creature is [[Conditions/Paralyzed|Paralyzed]] until the end of its next turn, after which it emerges from its paralysis [[Conditions/Stupefied|Stupefied 1]].\n\n**Critical Failure** As failure, but the creature doesn't automatically recover from paralysis at the end of its turn. Instead, it can attempt a new DC 32 save. On a success, the paralysis ends and they are stupefied 1, but on a failure, the paralysis continues for another round."

  - name: "[[Creature Family Ability Glossary/(Blackfrost Dead) Blackfrost|Invasive Blackfrost]]"
    desc: " (cold,curse,disease,occult) Gatewalker characters are not immune to blackfrost effects inflicted by Ainamuuren\n\nThis affliction can't be reduced below stage 1, nor the damage from it healed, until successfully treated with [[Spells/Cleanse Affliction|Cleanse Affliction]] or a similar effect; the affliction can then be removed as a normal disease. A creature that dies from cold damage while cursed with blackfrost rises as a blackfrost dead after 24 hours. Blackfrost has a counteract rank of 10.\n\n**Saving Throw** DC 32 Fortitude check\n\n**Stage 1** 4d6 cold (1 minute)\n\n**Stage 2** weakness to cold 5 and [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** weakness to cold 10 and [[Conditions/Drained|Drained 2]] (1 day)"

  - name: "Twist Deviance"
    desc: "`pf2:2` (mental,occult) Ainamuuren reaches out, then clutches his fingers into a fist and twists his arm, as if he were wrenching and tugging. At the same moment, all gatewalkers in a 60-foot cone that Ainamuuren can see feel the signs they've worn on their bodies since they emerged from their Missing Moment spike with pain, as if Ainamuuren had [[Conditions/Grabbed|Grabbed]] that flesh and was twisting and tearing it. The targets must attempt a DC 32 Will check save. Ainamuuren can't use Twist Deviance again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature endures a brief moment of horrific pain and takes 4d8 mental.\n\n**Failure** The pain is much greater, and for a moment the creature is convinced that the portion of their flesh that was adorned with the sign of the gatewalker has been torn free. They take 8d8 mental and can't use their deviant abilities for 1 round.\n\n**Critical Failure** As failure, but 16d8 mental and they can't use their deviant abilities for 1 minute."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Ainamuuren
creatures:
  - 1: Ainamuuren
```


Male saumen kar last scion


