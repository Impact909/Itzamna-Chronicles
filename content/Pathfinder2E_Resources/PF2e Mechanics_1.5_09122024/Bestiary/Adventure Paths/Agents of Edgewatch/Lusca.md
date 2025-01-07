---
title: "Lusca"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NcEgx6957WRY1n5G" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Lusca"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Lusca"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[aquatic]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Scent (Imprecise) 100 Feet"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +34, Intimidation: +30, Survival: +31"
abilityMods: [9, 5, 9, 0, 6, 5]
speed: 10 feet,  swim 50 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, __Will__ +29"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Immunities__  electricity"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Attack of Opportunity"
    desc: "`pf2:r`  The lusca gains 2 extra reactions at the start of each of its turns that it can use only to make an Attack of Opportunity with its jaws. It can't use more than one Attack of Opportunity triggered by the same action.\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Blood Scent"
    desc: "  The lusca can smell blood in the water up to 1 mile away."

  - name: "Storm Bringer"
    desc: " (aura,primal) When the lusca is near the surface for more than 1 hour, clouds appear and deliver a thunderstorm with a 2-mile radius centered on its location. The weather returns to normal 1 hour after the lusca departs."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (magical, reach 20 feet)\n__Damage__  3d12 + 17 piercing plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+35 (magical, reach 40 feet)\n__Damage__  3d10 + 17 bludgeoning plus lusca-venom"

  - name: "Innate Primal Spells"
    desc: "DC 38, attack +0; __9th __  _[[Spells/Chain Lightning|Chain Lightning (x3)]]_; __8th __  _[[Spells/Punishing Winds|Punishing Winds (x3)]]_"

  - name: "Capsize"
    desc: "`pf2:1` (attack) The lusca tries to capsize an adjacent aquatic vessel of its size or smaller. It must succeed at an Athletics check with a DC of 35 (reduced by 5 for each size smaller the vessel is than the lusca) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Lusca Venom"
    desc: " (poison) **Saving Throw** DC 38 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 4d6 poison damage and clumsy 1 (1 round)\n\n**Stage 2** 6d6 poison damage and clumsy 2 (1 round)"

  - name: "Ravenous Jaws"
    desc: "`pf2:2`  The lusca makes three jaws Strikes, each against a different target. These attacks count toward the lusca's multiple attack penalty, but the penalty doesn't increase until after the lusca makes all of these attacks. If the lusca subsequently uses the Grab action, it Grabs any number of creatures it hit with Ravenous Jaws."

  - name: "Rend (jaws)"
    desc: "`pf2:1`  Jaws\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Swallow Whole"
    desc: "`pf2:1` (attack) Huge, 4d12+9 bludgeoning, Rupture 38\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Lusca
creatures:
  - 1: Lusca
```



A lusca is a predatory sea monster that resembles a three-headed shark with the body of an octopus. Ferocious electrical storms usually herald a lusca's arrival; such violent bursts of electricity result from the creature's superconductive flesh, which allows the lusca to store energy from lightning strikes that it can then discharge at foes.
