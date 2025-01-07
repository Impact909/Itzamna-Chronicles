---
title: "Ulgrem-Lurann"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.u1qnMiikhl1JZUEk" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Ulgrem-Lurann"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Ulgrem-Lurann"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[beast]]
trait_03: [[chaotic]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Wildsong; can&#x27;t speak"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Deception: +8, Intimidation: +11, Stealth: +10"
abilityMods: [4, 3, 3, 1, -2, 2]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +10, __Will__ +5"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55; __Resistances__ electricity 5, piercing 5"
abilities_top:
  - name: ""

  - name: "Bump in the River"
    desc: "  An Ulgrem-Lurann can pretend to be a floating log while in water by attempting a Stealth check. It has a +2 circumstance bonus to its checks and DCs to do so. While using Stealth this way, creatures see the log but don't realize it's an Ulgrem-Lurann."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 (reach 10 feet)\n__Damage__  1d8 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+13 (agile, reach 10 feet)\n__Damage__  1d6 + 6 bludgeoning plus grab"

  - name: "Nurtured Loathing"
    desc: "  An Ulgrem-Lurann gains a +1 circumstance bonus to attack and damage rolls against creatures with the undead trait."

  - name: "Sparking Bite"
    desc: "`pf2:2` (attack,electricity) **Requirements** The Ulgrem-Lurann has a creature [[Conditions/Grabbed|Grabbed]] with its jaws\n* * *\n\n**Effect** Electricity courses through its body and mouth, dealing an additional 1d4+6 electricity damage to the grabbed target with a DC 20 Fortitude check save."

  - name: "Swallow Whole"
    desc: "`pf2:1` (attack) Small, 1d6+6 bludgeoning, Rupture 9\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Voltaic Blow"
    desc: "`pf2:1` (electricity) **Requirements** The Ulgrem-Lurann has a creature [[Conditions/Grabbed|Grabbed]] with its jaws\n* * *\n\n**Effect** Electricity courses through its body and mouth, dealing an additional 1d4+6 electricity damage to the creature (DC 20 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ulgrem-Lurann
creatures:
  - 1: Ulgrem-Lurann
```




