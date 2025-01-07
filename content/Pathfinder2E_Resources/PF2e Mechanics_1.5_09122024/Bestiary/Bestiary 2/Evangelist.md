---
title: "Evangelist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7FO0d4SJVQSJVcSs" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Evangelist"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Evangelist"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Greater Darkvision"
languages: "Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +15, Crafting: +10, Intimidation: +15, Religion: +11, Torture Lore: +12"
abilityMods: [4, 3, 2, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +15, __Ref__ +14, __Will__ +11; +1 status to all saves vs. magic"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, regeneration 10 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 5, silver 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Unnerving Gaze"
    desc: " (aura,divine,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it sees the face of a departed loved one in place of the evangelist's face. The creature must succeed at a DC 21 Will check save or become [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 3]] on a critical failure)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Chain"
    desc: "+17 (disarm, magical, reach 10 feet, trip, unholy)\n__Damage__  2d8 + 7 piercing plus impaling-chain 1d6 bleed plus impaling-chain"

  - name: "Animate Chains"
    desc: " (divine) Chains in the evangelist's vicinity sprout barbs and writhe menacingly. The evangelist can make chain Strikes against any creature that is adjacent to an unattended chain within 20 feet, in addition to those within the reach of the evangelist's chain Strike."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The evangelist stares at a creature they can see within 30 feet. The target must immediately attempt a DC 21 Will check save against Unnerving gaze. In addition, if the creature was already [[Conditions/Frightened|Frightened]], on a failed save, the evangelist is [[Conditions/Concealed|Concealed]] from the creature for as long as the creature remains frightened.\n\nAfter attempting this save, the creature is then temporarily immune until the start of the evangelist's next turn."

  - name: "Impaling Chain"
    desc: "  When the evangelist critically hits with a chain Strike, the target is impaled and anchored in place, becoming [[Conditions/Grabbed|Grabbed]] by the chain. The creature is unable to recover from persistent bleed damage until it gets free ([[Actions/Escape|Escape]] DC 25).\n\n[[Bestiary Effects/Effect_ Impaling Chain|Effect: Impaling Chain]]"
 
```

```encounter-table
name: Evangelist
creatures:
  - 1: Evangelist
```



Evangelists, the velstracs' unofficial ambassadors, roam the farthest reaches of the planes to spread the word of their kind's abhorrent belief in perfection through pain. They are therefore the most frequently encountered velstracs on the Material Plane, leading covens of hedonistic mortal flesh-sculptors or serving as wardens of horrific dungeons. In regions ruled by infernal powers, evangelists may serve as lieutenants or advisors, whispering secret paths to power in exchange for mortal's souls or choice mortal flesh. Evangelists are the same size as humans, although with the heavy chains that always drape their forms, they often weigh 350 pounds or more.

* * *

The search for ultimate sensation through self-mutilation is the horrifying preoccupation of the shadow-dwelling fiends known as velstracs. They transcend their stoic detachment only when inflicting pain and terror upon their victims, practicing new forms of torture, or when turning their agonizing practices back on themselves. Velstracs consider themselves enlightened beings, transcending such limitations as morality or mortal taboos, but their victims know them as emotionless tormentors who inflict sadistic suffering. These fiends claim to seek perfection in thought, form, and action, although they don't recognize any refinement that doesn't require the painful excision of the flesh or spirit.

Velstracs manifest from the souls of the most extreme masochistic or sadistic mortals who are judged and sent on to the Shadow Plane. They take on forms that suit their vile predilections, ranging from the low-ranking augurs to the maestros of suffering and mutilation called eremites. The process of transformation warps the soul step by step, with other velstracs conveying their new members through untold chambers of pain among the dark reaches of the Shadow Plane.
