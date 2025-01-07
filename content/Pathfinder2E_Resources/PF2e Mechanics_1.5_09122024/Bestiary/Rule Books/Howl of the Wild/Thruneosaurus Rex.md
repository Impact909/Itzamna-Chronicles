---
title: "Thruneosaurus Rex"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uAGhfDCnDbp5nJBM" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/devil
  - pf2e/creature/type/dinosaur
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Thruneosaurus Rex"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Thruneosaurus Rex"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[devil]]
trait_03: [[dinosaur]]
trait_04: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; "
languages: "Common, Diabolic; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +35, Intimidation: +30"
abilityMods: [10, 3, 6, -2, 6, 5]
speed: 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +31, __Ref__ +25, __Will__ +29"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  fire; __Weaknesses__ holy 15; __Resistances__ physical 15 (except silver)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,divine,emotion,fear,mental) 90 feet DC 38 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Instinctive Teleportation"
    desc: "`pf2:r` (divine,teleportation) **Trigger** The thruneosaurus takes damage from a holy effect\n* * *\n\n**Effect** The thruneosaurus teleports to an open space within 60 feet it can see, along with any creatures it has swallowed whole."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 20 feet)\n__Damage__  3d12 + 16 piercing plus grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+33 (magical, reach 15 feet)\n__Damage__  3d10 + 16 bludgeoning"

  - name: "Hellfire Blast"
    desc: "`pf2:2`  The thruneosaurus channels sulfurous hellfire in one of three ways. The thruneosaurus chooses the effect, but it can't make the same choice in two consecutive rounds.\n\n*   **Blistering Sun** (divine, fire, unholy) The thruneosaurus ignites an orb of hellfire between its horns that radiates heat in a 30-foot emanation, dealing 2d8 persistent fire damage.\n*   **Choking Fumes** (divine, poison, unholy) The thruneosaurus exhales a 60-foot cone of sulfurous smoke that deals 6d8 poison damage (DC 38 Fortitude check save). Creatures that fail their saves are [[Conditions/Sickened|Sickened 2]].\n*   **Fiery Beam** (divine, fire, unholy) A 120-foot line of hellish flame erupts from the thruneosaurus's eyes, dealing 6d10 fire damage (DC 38 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d12+10 bludgeoning, Rupture 40\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 38 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Thruneosaurus Rex
creatures:
  - 1: Thruneosaurus Rex
```



The unholy terror known as the thruneosaurus rex is not a natural beast. They were created by Chelaxian diabolists who sought to combine the ferocity of dinosaurs with the power of Hell, infusing a clutch of tyrannosaurus rex eggs from Mediogalti Island with devil ichor and naming the monstrous hatchlings after their patrons. Although few records and fewer survivors tell exactly how the experiment went awry, the experimental subjects escaped, and their descendants are now most often sighted in the Whisperwood in eastern Cheliax.
