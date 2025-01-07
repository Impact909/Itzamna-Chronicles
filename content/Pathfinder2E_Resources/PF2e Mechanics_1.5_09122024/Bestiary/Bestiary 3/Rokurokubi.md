---
title: "Rokurokubi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZmgRAfKwfbeEvvaQ" 
tags:
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Rokurokubi"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Rokurokubi"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Deception: +8, Diplomacy: +8, Intimidation: +8, Society: +6, Stealth: +8"
abilityMods: [3, 4, 3, 2, 3, 4]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +8, __Will__ +9"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30; __Immunities__  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws Only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Drink Oil"
    desc: "`pf2:r`  **Trigger** The rokurokubi is the target of an alchemical bomb Strike\n\n**Requirements** The rokurokubi is aware of the attack, not [[Conditions/Off-Guard|Off-Guard]] against it, and doesn't have a creature [[Conditions/Grabbed|Grabbed]] with their jaws\n* * *\n\n**Effect** The rokurokubi attempts to catch the flung bomb in their mouth. They gain a +4 circumstance bonus to AC against the triggering attack. If the attack misses, they catch the bomb in their mouth and harmlessly drink its contents down, regaining Hit Points equal to the bomb's item level."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (finesse, reach 10 feet)\n__Damage__  1d8 + 3 piercing 1d6 bleed"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile, finesse)\n__Damage__  1d8 + 3 slashing"

  - name: "Extend Neck"
    desc: "`pf2:1`  The rokurokubi extends their neck, increasing the reach of their jaws Strike from 10 feet to 20 feet until the end of their next turn."

  - name: "Threatening Lunge"
    desc: "`pf2:2`  **Requirements** The rokurokubi's neck is not currently extended\n* * *\n\n**Effect** The rokurokubi's head comes within an inch of their target's face before striking. They Extend their Neck, attempt to [[Actions/Demoralize|Demoralize]] one opponent within 20 feet, and then make a jaws Strike against that opponent.\n\nTheir Demoralize check is a visual rather than auditory effect, and they don't take a penalty if the target doesn't understand their language."
 
```

```encounter-table
name: Rokurokubi
creatures:
  - 1: Rokurokubi
```



Rokurokubi come into being when mortals are cursed for some misdeed, though often the one who bears the curse is not the one who committed the offense, but instead their child or spouse. The curse slowly transforms the individual into a rokurokubi as they sleep. At first, their neck extends, or even detaches altogether, to let their head roam freely and engage in simple mischief like scaring neighbors or animals. The sleeper may awaken the next morning from a hazy dream of drinking the oil from nearby lanterns, only to find them indeed empty.

Over time, the bizarre acts progress to increasingly mischievous or even violent crimes. There's only a brief period during which the nascent rokurokubi might still be saved by dispelling the curse, but before long, they are fully consumed, never to sleep again.

Most rokurokubi despair at their state, seeking to drown their sorrows in drink or simply stay out of sight. A nefarious few rokurokubi embrace their fate and seek to enhance their power by completely giving in to the curse. This grants them the ability to cast potent occult spells but inevitably twists them even more toward evil.
