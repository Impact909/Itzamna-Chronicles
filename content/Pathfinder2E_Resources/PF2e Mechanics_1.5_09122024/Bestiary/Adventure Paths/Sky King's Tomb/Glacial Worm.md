---
title: "Glacial Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EoTTtaMuZ0iF0zx1" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Glacial Worm"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Glacial Worm"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +34"
abilityMods: [10, 0, 8, -5, 0, -1]
speed: 40 feet,  burrow 40 feet,  swim 20 feet
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +30, __Ref__ +22, __Will__ +22"
hp: 370
health:
  - name: ""
  - name: HP
    desc: "370, cold healing; __Immunities__  cold,  immobilized; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (imprecise) 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Cold Healing"
    desc: "  When a glacial worm is in extreme cold or surrounded by ice, it gains fast healing 10. When struck by a magical cold effect, a glacial worm regains Hit Points equal to half the cold damage the effect would otherwise deal."

  - name: "Inexorable"
    desc: "  The glacial worm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Leech Heat"
    desc: " (aura,cold) 30 feet. A glacial worm's intense cold absorbs heat. Creatures that start their turn within the area take 3d6 cold damage (DC 34 Fortitude check save)."

  - name: "Shake It Off"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The glacial worm would be affected by a condition or adverse effect (such as _baleful polymorph_)\n* * *\n\n**Effect** The glacial worm negates the triggering condition or effect. Effects from artifacts, deities, or a similarly powerful source can't be avoided in this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (deadly 2d12, reach 15 feet)\n__Damage__  3d12 + 13 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Body"
    desc: "+30 (reach 15 feet)\n__Damage__  2d8 + 12 bludgeoning 1d6 cold"

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The worm Grabs a creature\n* * *\n\n**Effect** The worm uses Swallow Whole."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d8+12 bludgeoning + 2d6 cold, Rupture 28\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2`  The worm makes a Strike once against each creature in its reach. It can Strike up to once with its jaws and any number of times with its body. Each attack counts toward the worm's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Glacial Worm
creatures:
  - 1: Glacial Worm
```



Cave worm eggs that lie dormant for a long period may experience significant climactic shift. If the temperature falls below freezing, the worms may hatch as glacial worms, also called white worms. These creatures immediately migrate as far north as possible, seeking the glaciers or icebergs that will nourish and house them. Glacial worms lack stingers, as liquid venom is less effective in cold temperatures. Occasionally, such creatures are carried far south on icebergs that have carved off the main ice sheets of the polar regions.
