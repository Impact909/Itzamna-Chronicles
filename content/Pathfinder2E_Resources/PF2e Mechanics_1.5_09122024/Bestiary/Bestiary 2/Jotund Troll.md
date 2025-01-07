---
title: "Jotund Troll"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jqjAN8rkHDzzEC7p" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/mutant
  - pf2e/creature/type/troll
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Jotund Troll"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Jotund Troll"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[giant]]
trait_04: [[mutant]]
trait_05: [[troll]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +29, Intimidation: +27"
abilityMods: [8, 4, 8, -1, 6, 4]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +31, __Ref__ +23, __Will__ +23"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360, regeneration 40 (deactivated by acid or fire); __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 40 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

  - name: "Head Regrowth"
    desc: "  A jotund troll ordinarily has nine heads, and they can use regeneration to regrow a head that is severed from an effect like a [[Equipment/Vorpal|Vorpal]] weapon. After regaining Hit Points from regeneration, the jotund troll attempts a DC 8 Flat check check. On a success, one missing head is fully restored; on a critical success, two missing heads are fully restored. If a jotund troll loses their last remaining head, they die immediately."

  - name: "Multiple Opportunities"
    desc: "  A jotund troll gains an extra reaction per round for each of their heads beyond the first, which they can use only to make Attacks of Opportunity with their jaws or to Fast Swallow. They can't use more than 1 reaction for the same triggering action, even if a creature leaves several squares within their reach, and the jotund troll must use a different head for each Attack of Opportunity they make. Whenever one of the jotund troll's heads is severed, the troll loses 1 of their extra reactions per round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (reach 15 feet)\n__Damage__  3d12 + 14 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, reach 15 feet)\n__Damage__  3d10 + 14 slashing"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+30 (brutal, range increment 120 feet)\n__Damage__  2d12 + 14 bludgeoning"

  - name: "Cacophonous Roar"
    desc: "`pf2:2` (auditory,emotion,incapacitation,mental,primal) The jotund troll emits a cacophonous roar from all their heads with a mystical power that distorts the listener's mind. Each non-troll creature within 100 feet must attempt a DC 34 Will check save.\n\nThe jotund troll can't use Cacophonous Roar for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Cacophonous Roar for 24 hours.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The creature is confused for 1d4 rounds."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The jotund troll [[Bestiary Ability Glossary/Grab|Grabs]] a creature with their jaws\n* * *\n\n**Effect** The troll uses Swallow Whole."

  - name: "Ravenous Jaws"
    desc: "`pf2:2`  The jotund troll makes a number of jaws Strikes up to their number of heads, each against a different target. These attacks count toward the troll's multiple attack penalty, but the penalty doesn't increase until after the jotund troll makes all of these attacks."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 3d12+8 bludgeoning damage, Rupture 36\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Jotund Troll
creatures:
  - 1: Jotund Troll
```



Jotund trolls are gigantic, nine-headed horrors who prowl frigid moors, marshes, and wastelands, always alone and always enraged. While each of the jotund troll's nine heads possess their own brains and senses, they work much more in tandem than the dual-minded nature of the two-headed troll. Despite this, the heads often argue and bicker, particularly over which head gets to eat. The fact that all nine maws lead to the same shared stomach makes little difference in such culinary disagreements.

Prevailing wisdom holds that the jotund troll represents a primordial, if not original, shape and design for the first trolls to plague the world, arising from a mythical realm in the Great Beyond known as Jotungard. This sprawling domain, said to be nestled in a remote reach of Elysium, is the legendary home of the deities of giant-kind. Whether the jotund troll was created in Jotungard to plague the Material Plane as punishment or challenge, or if it's merely an evocative legend told by scholars, is unknown. In any case, the jotund trolls themselves likely care little.
