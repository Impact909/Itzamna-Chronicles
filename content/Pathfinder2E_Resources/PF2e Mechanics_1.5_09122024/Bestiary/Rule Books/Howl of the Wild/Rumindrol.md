---
title: "Rumindrol"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Yl9CqB5FoB8sVkLA" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Rumindrol"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Rumindrol"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Motion Sense (Precise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30, Deception: +27, Survival: +25"
abilityMods: [9, 6, 7, -1, 5, -1]
speed: 20 feet,  burrow 60 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +30, __Ref__ +26, __Will__ +23"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  immobilized; __Weaknesses__ cold 10; __Resistances__ poison 15, sonic 15"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A rumindrol can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Dreadful Resonance"
    desc: " (auditory,aura,incapacitation) 60 feet. Each creature that enters or starts its turn in the emanation must succeed at a DC 36 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 1]] ([[Conditions/Enfeebled|Enfeebled 2]] on a critical failure) and take 3d8 sonic damage."

  - name: "Enthralling Call"
    desc: " (auditory,aura,emotion,mental) 1 mile. Each non-rumindrol creature that enters or starts its turn within the emanation must succeed at a DC 26 Will check save or become [[Conditions/Fascinated|Fascinated]]. The creature then becomes temporarily immune to this effect for 1 day (1 hour on a critical failure). Any creature fascinated in this way will attempt to find the source of the rumindrol's cry, mindlessly wandering towards it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (reach 15 feet)\n__Damage__  3d12 + 15 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+30 (agile, reach 15 feet)\n__Damage__  3d8 + 15 slashing"

  - name: "**Ranged** `pf2:1` Focused Resonance"
    desc: "+30 (range increment 120 feet)\n__Damage__  3d10 + 15 sonic"

  - name: "Entropic Cry"
    desc: "`pf2:1` (auditory,incapacitation) The rumindrol focuses its sonic emanations on a creature it's aware of within the area of its enthralling call aura. The target must attempt a DC 31 Fortitude check save.\n* * *\n\n**Critical Success** The creature becomes temporarily immune to Entropic Cry for 1 hour.\n\n**Success** The target is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The target is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The target is sickened 2, [[Conditions/Enfeebled|Enfeebled 1]], and [[Conditions/Stupefied|Stupefied 1]]."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The rumindrol Grabs a creature\n* * *\n\n**Effect** The rumindrol uses Swallow Whole."

  - name: "Inexorable"
    desc: "  The rumindrol recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+9 bludgeoning, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2` (attack) The rumindrol attempts individual Strikes against each creature in its reach. It can attempt up to one jaws Strike and any number of leg Strikes. Each attack counts toward the rumindrol's multiple attack penalty, but the penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, leg, DC 36 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Rumindrol
creatures:
  - 1: Rumindrol
```




