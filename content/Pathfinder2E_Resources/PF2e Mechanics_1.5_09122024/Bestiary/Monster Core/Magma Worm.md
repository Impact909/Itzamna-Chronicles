---
title: "Magma Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2PNB9zmgPAQMMIq2" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Magma Worm"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Magma Worm"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[fire]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +38"
abilityMods: [10, -1, 9, -3, -1, -1]
speed: 40 feet,  burrow 40 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +36, __Ref__ +25, __Will__ +27"
hp: 410
health:
  - name: ""
  - name: HP
    desc: "410, fire healing; __Immunities__  fire,  immobilized; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Fire Healing"
    desc: "  As long as a magma worm is in contact with a fire or body of magma at least as large as itself, it gains fast healing 20. When struck by a magical fire effect from anything other than itself, a magma worm regains Hit Points equal to half the fire damage the effect would otherwise deal."

  - name: "Inexorable"
    desc: "  The magma worm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Slough Skin"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The magma worm would be affected by a condition or adverse effect (such as [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]])\n* * *\n\n**Effect** The magma worm negates the triggering condition or effect by sloughing an outer layer of its skin. Effects from artifacts, deities, or a similarly powerful source can't be avoided in this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (deadly 3d10, fire, reach 20 feet)\n__Damage__  3d10 + 18 piercing plus improved-grab 2d6 fire plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+36 (agile, fire, poison, reach 20 feet)\n__Damage__  2d12 + 18 piercing plus magma-worm-venom 2d6 fire plus magma-worm-venom"

  - name: "**Melee** `pf2:1` Body"
    desc: "+34 (fire, reach 15 feet)\n__Damage__  2d10 + 16 bludgeoning 2d6 fire"

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The worm [[Conditions/Grabbed|Grabs]] a creature\n* * *\n\n**Effect** The worm uses Swallow Whole."

  - name: "Fire Breath"
    desc: "`pf2:2` (fire,primal) The magma worm breathes a blast of flame in a 60-foot cone that deals 18d6 fire damage to all creatures in the area (DC 41 Reflex check save).\n\nIt can't use Fire Breath again for 1d4 rounds."

  - name: "Magma Worm Venom"
    desc: " (poison) **Saving Throw** DC 41 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 2d6 poison damage and drained 1 (1 round)\n\n**Stage 3** 2d6 poison damage and [[Conditions/Drained|Drained 2]] (1 round)."

  - name: "Rock Tunneler"
    desc: "  A magma worm can burrow through solid stone at a Speed of 20 feet. It can leave a tunnel if it desires, and it usually does."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+10 bludgeoning + 2d6 fire, Rupture 36\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2`  The worm makes a Strike once against each creature in its reach. It can Strike up to once with its jaws, up to once with its stinger, and any number of times with its body. Each attack counts toward the worm's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Magma Worm
creatures:
  - 1: Magma Worm
```



Among the most dangerous of their kind are the fiery magma worms. In addition to being even larger than benthic worms, the magma worm has a penchant for burrowing through volcanic regions that, over the generations, have infused it with a supernatural link to the Elemental Plane of Fire. The fiery heart of an active volcano is an attractive lair for a magma worm, as are the sprawling fields of molten rock found in the deepest reaches of the Darklands. Legends of ancient dwarven societies and colonists of the Elemental Planes populating moats of lava with magma worms likely have some basis in truth, although the methods used to keep these "moat worms" contained—and prevented from chewing their way through fortress foundations—must have been significant.

Magma worms sometimes frequent areas on the surface where volcanism creates hot springs or other geothermal features, but even then they prefer to spend most of their time burrowing through the ground in their never-ending search for sustenance. Surface lands claimed by magma worms are notable for the mound-shaped burrows these creatures leave behind as they dig.

* * *

Cave worms are gigantic scavengers that bore through the depths of the world, eating whatever material they find. Named for their distinctive habitats, these worms are ravenous and display overwhelming destructive capabilities. Cave worms of different types and abilities lurk in the more remote corners of the world—tales speak of arctic worms that dwell within immense glaciers or icebergs and grave worms that burrow through the boneyards of long-forgotten ruins, to name a few.
