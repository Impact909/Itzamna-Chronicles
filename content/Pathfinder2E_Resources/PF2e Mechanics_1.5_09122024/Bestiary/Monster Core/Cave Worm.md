---
title: "Cave Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PDuQi7kpXqL0B7I6" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Cave Worm"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cave Worm"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [9, -1, 7, -5, -1, -1]
speed: 40 feet,  burrow 40 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +28, __Ref__ +21, __Will__ +21"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  immobilized"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Inexorable"
    desc: "  The cave worm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Slough Skin"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The cave worm would be affected by a condition or adverse effect (such as [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]])\n* * *\n\n**Effect** The cave worm negates the triggering condition or effect by sloughing an outer layer of its skin. Effects from artifacts, deities, or a similarly powerful source can't be avoided in this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (deadly 2d10, reach 15 feet)\n__Damage__  3d10 + 15 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+28 (agile, poison, reach 15 feet)\n__Damage__  2d12 + 15 piercing plus purple-worm-venom"

  - name: "**Melee** `pf2:1` Body"
    desc: "+26 (reach 15 feet)\n__Damage__  1d10 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Regurgitate"
    desc: "+26 (brutal, range increment 60 feet)\n__Damage__ "

  - name: "Cave Worm Venom"
    desc: " (poison) **Saving Throw** DC 32 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 5d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 2** 6d6 poison damage, and enfeebled 2 (1 round)\n\n**Stage 3** 8d6 poison damage and enfeebled 2 (1 round)"

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The cave worm [[Conditions/Grabbed|Grabs]] a creature.\n* * *\n\n**Effect** The worm uses Swallow Whole."

  - name: "Regurgitate"
    desc: "  The purple worm can violently regurgitate a creature or boulder it has swallowed to make a ranged Strike. The Strike deals bludgeoning damage depending on the size of the projectile:\n\n*   Tiny 2d6+13\n*   Small 3d6+13\n*   Medium 4d6+13\n*   Large 5d6+13\n*   Huge 6d6+13\n\nA regurgitated creature takes falling damage from the height of the target or from 20 feet, whichever is greater.\n\nBoulders occupy space in the worm's stomach as a creature of equivalent size, and purple worms often have several boulders swallowed. A purple worm can use a single action to swallow a new boulder."

  - name: "Rock Tunneler"
    desc: "  A cave worm can burrow through solid stone at a Speed of 20 feet. It can leave a tunnel if it desires, and it usually does."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d6+9 bludgeoning, Rupture 24\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2`  The worm makes a Strike once against each creature in its reach. It can Strike up to once with its jaws, up to once with its stinger, and any number of times with its body. Each attack counts toward the worm's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cave Worm
creatures:
  - 1: Cave Worm
```



The most common and infamous of the cave worms gives its name to the entire family—a much-feared monster wandering the twisting tunnels of the Darklands that is capable of carving out entire cave systems. Tunnels bored by a cave worm don't always last long after these creature's passage, and areas where they nest are maddening mazes of passageways that lead nowhere, yet navigating the labyrinth to find the worm's central nest often yields amazing treasures left behind by the worm's prior victims.

* * *

Cave worms are gigantic scavengers that bore through the depths of the world, eating whatever material they find. Named for their distinctive habitats, these worms are ravenous and display overwhelming destructive capabilities. Cave worms of different types and abilities lurk in the more remote corners of the world—tales speak of arctic worms that dwell within immense glaciers or icebergs and grave worms that burrow through the boneyards of long-forgotten ruins, to name a few.
