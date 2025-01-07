---
title: "Eremite"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2c9vmEttqF4eOnQR" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Eremite"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Eremite"
level: "Creature 20"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Greater Darkvision, Truesight"
languages: "Common, Diabolic, Shadowtongue; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Deception: +38, Diplomacy: +36, Intimidation: +40, Medicine: +36, Religion: +34, Stealth: +36, Torture Lore: +36"
abilityMods: [9, 6, 7, 6, 6, 10]
speed: 30 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +37, __Ref__ +32, __Will__ +34; +1 status to all saves vs. magic"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375, regeneration 25 (deactivated by holy or silver); __Immunities__  cold,  fear effects,  nonlethal attacks; __Weaknesses__ holy 20, silver 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Ignore Pain"
    desc: "  An eremite's actions can't be disrupted due to damage or Strikes (such as [[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]])."

  - name: "Paralytic Perfection"
    desc: " (aura,divine,fear,incapacitation,mental,visual) 30 feet. When a creature ends its turn in the aura, it feels compelled to offer pieces of its own flesh to the eremite. The creature must succeed at a DC 40 Will check save or become [[Conditions/Paralyzed|Paralyzed]] for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (magical, unholy)\n__Damage__  4d8 + 19 piercing plus exquisite-pain 2d6 bleed plus exquisite-pain"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+39 (agile, magical, unholy)\n__Damage__  3d6 + 19 slashing plus exquisite-pain,improved-grab 2d6 bleed plus exquisite-pain,improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +32; __9th __ (1 slots) _[[Spells/Seize Soul|Bind Soul]]_, _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Harm|Harm (x2)]]_, _[[Spells/Heal|Heal (x2)]]_, _[[Spells/Shadow Blast|Shadow Blast]]_, _[[Spells/Umbral Journey|Shadow Walk (At will)]]_; __7th __ (5 slots) _[[Spells/Translocate|Dimension Door (At will)]]_, _[[Spells/Planar Seal|Dimensional Lock]]_, _[[Spells/Interplanar Teleport|Plane Shift (to the Universe or Netherworld only)]]_, _[[Spells/Shadow Siphon|Shadow Siphon (At will)]]_, _[[Spells/Warp Mind|Warp Mind]]_\n__Cantrips__  __(10th)__ _[[Spells/Stabilize|Stabilize]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Imprisonment_"

  - name: "Evisceration"
    desc: "`pf2:1` (attack) **Requirements** The eremite has a creature grabbed\n* * *\n\n**Effect** The eremite excises flesh or bone from a creature it has grabbed. The target takes 6d10 bleed."

  - name: "Exquisite Pain"
    desc: "  An eremite's knowledge of pressure points and pain centers is unsurpassed. A creature hit by an eremite's melee Strikes must succeed at a DC 40 Fortitude check save or be [[Conditions/Stunned|Stunned 2]] ([[Conditions/Stunned|Stunned 4]] on a critical failure).\n\nA creature that critically succeeds is temporarily immune for 24 hours."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The eremite stares at a creature they can see within 30 feet. The creature must immediately attempt a Will save against paralytic perfection.\n\nIn addition, if the creature was already paralyzed, on a failed save, its unnatural longing causes it to become [[Conditions/Doomed|Doomed 1]].\n\nAfter attempting this save, the creature is then temporarily immune until the start of the eremite's next turn."

  - name: "Graft Flesh"
    desc: "`pf2:1`  **Requirements** The eremite holds a piece of flesh they collected via Evisceration\n* * *\n\n**Effect** The eremite attaches the stolen flesh to themself. They either regain 100 healing Hit Points; reduce the value of their clumsy, drained, enfeebled, or stupefied condition by 3; or reduce the stage of any affliction affecting them by 3."

  - name: "Shadow Traveler"
    desc: " (divine) When an eremite uses [[Spells/Interplanar Teleport|Interplanar Teleport]] or [[Spells/Umbral Journey|Umbral Journey]], they arrive at exactly their intended destination."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Eremite
creatures:
  - 1: Eremite
```



Eremites roam the planes to seek out ideal portions of other creatures, such as a hero's sword-arm or an angel's pinions. Eremites capture these specimens to clinically test their true limits, then harvest specimens and add them to their own bodies. An eremite might attach tongues to their hand as extra fingers or a fist to the back of their neck in a horrid "improvement." Eremites average 7 feet tall and weigh approximately 200 pounds.

* * *

The search for ultimate sensation through self-mutilation is the horrifying preoccupation of the shadow-dwelling fiends known as velstracs. They transcend their stoic detachment only when inflicting pain and terror upon their victims, practicing new forms of torture, or when turning their agonizing practices back on themselves. Velstracs consider themselves enlightened beings, transcending such limitations as morality or mortal taboos, but their victims know them as emotionless tormentors who inflict sadistic suffering. These fiends claim to seek perfection in thought, form, and action, although they don't recognize any refinement that doesn't require the painful excision of the flesh or spirit.

Velstracs manifest from the souls of the most extreme masochistic or sadistic mortals who are judged and sent on to the Shadow Plane. They take on forms that suit their vile predilections, ranging from the low-ranking augurs to the maestros of suffering and mutilation called eremites. The process of transformation warps the soul step by step, with other velstracs conveying their new members through untold chambers of pain among the dark reaches of the Shadow Plane.
