---
title: "Interlocutor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nnChJcxBG8ul7DKk" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Interlocutor"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Interlocutor"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Greater Darkvision"
languages: "Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Crafting: +22, Intimidation: +25, Medicine: +26, Religion: +22, Stealth: +19, Torture Lore: +20"
abilityMods: [7, 3, 5, 2, 6, 5]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +21, __Will__ +26; +1 status to all saves vs. magic"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215, regeneration 20 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 15, silver 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Glimpse of Stolen Flesh"
    desc: " (aura,divine,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it sees pieces of its own body amid the interlocutor's form. The creature must succeed at a DC 29 Will check save or become [[Conditions/Stunned|Stunned 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (deadly 2d10, magical, reach 10 feet, unholy)\n__Damage__  3d10 + 13 slashing 2d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 33, attack +23; __7th __ (1 slots) _[[Spells/Interplanar Teleport|Plane Shift (Self only) (To the Universe or Netherworld only)]]_; __5th __ (1 slots) _[[Spells/Breath of Life|Breath of Life]]_; __4th __ (4 slots) _[[Spells/Heal|Heal (x2)]]_, _[[Spells/Restoration|Restoration (x2)]]_\n__Cantrips__  __(6th)__ _[[Spells/Stabilize|Stabilize]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The interlocutor stares at a creature they can see within 30 feet. The creature must immediately attempt a Will save against glimpse of stolen flesh. In addition, if the creature was already [[Conditions/Stunned|Stunned]], on a failed save, it feels its internal organs twist and writhe, and is [[Conditions/Clumsy|Clumsy 2]] for 1 minute.\n\nAfter attempting this save, the creature is then temporarily immune until the start of the interlocutor's next turn."

  - name: "Surgical Rend"
    desc: "`pf2:1`  This functions as the [[Bestiary Ability Glossary/Rend|Rend]] ability, dealing claw damage. In addition, if the target is a living creature with organs and muscle, the interlocutor opens a precise wound. Until the creature is restored to its maximum Hit Points, thus closing the wound, Strikes against the creature deal 1d6 extra precision damage.\n\n[[Bestiary Effects/Effect_ Surgical Rend|Effect: Surgical Rend]]"
 
```

```encounter-table
name: Interlocutor
creatures:
  - 1: Interlocutor
```



Interlocutors are the most talented surgeon-sculptors of the velstracs, carving away flesh and replacing it with new body parts of muscle, sinew, and metal. Each interlocutor structures their individual appearance carefully, but all are towering, multi-limbed amalgamations of the strongest limbs, densest bone, and sharpest metal they can find. They continually search for new material to graft to their forms, and their slain foes are rarely found intact, as little is more valuable to interlocutors than a powerful opponent's legs, eyes, or even brain. Interlocutors average 9 feet tall and weigh approximately 800 pounds.

* * *

The search for ultimate sensation through self-mutilation is the horrifying preoccupation of the shadow-dwelling fiends known as velstracs. They transcend their stoic detachment only when inflicting pain and terror upon their victims, practicing new forms of torture, or when turning their agonizing practices back on themselves. Velstracs consider themselves enlightened beings, transcending such limitations as morality or mortal taboos, but their victims know them as emotionless tormentors who inflict sadistic suffering. These fiends claim to seek perfection in thought, form, and action, although they don't recognize any refinement that doesn't require the painful excision of the flesh or spirit.

Velstracs manifest from the souls of the most extreme masochistic or sadistic mortals who are judged and sent on to the Shadow Plane. They take on forms that suit their vile predilections, ranging from the low-ranking augurs to the maestros of suffering and mutilation called eremites. The process of transformation warps the soul step by step, with other velstracs conveying their new members through untold chambers of pain among the dark reaches of the Shadow Plane.
