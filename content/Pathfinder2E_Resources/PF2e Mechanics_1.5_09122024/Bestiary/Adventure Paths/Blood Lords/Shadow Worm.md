---
title: "Shadow Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NceJvID1d2gwTqlV" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Shadow Worm"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Shadow Worm"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[shadow]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +41, Stealth: +32"
abilityMods: [10, 2, 9, -4, 0, 0]
speed: 40 feet,  burrow 40 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +36, __Ref__ +32, __Will__ +30"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450, shadow healing; __Immunities__  immobilized; __Weaknesses__ light 20; __Resistances__ cold 20, void 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Inexorable"
    desc: "  The shadow worm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Shadow Healing"
    desc: "  As long as a shadow worm is in an area of dim light or darkness, it gains fast healing 20. When affected by a magical shadow effect from anything other than itself, a shadow worm becomes [[Conditions/Quickened|Quickened]] 1 for 1 round."

  - name: "Shrink from the Light"
    desc: "  A shadow worm takes an additional 20 damage from any spell or ability with the light trait and uses the outcome one degree worse for saving throws made against a spell or ability with the light trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (deadly 2d10, reach 15 feet)\n__Damage__  4d10 + 20 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Body"
    desc: "+38 (reach 15 feet)\n__Damage__  3d10 + 20 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2` (cold,occult,shadow,void) The shadow worm exhales a blast of clinging shadow, dealing 11d6 cold damage and 10d6 void damage to creatures in a 60-foot cone (DC 42 Reflex check). If the cone passes through an area of magical light or targets a creature affected by magical light, Breath Weapon attempts to counteract the light (+34 counteract modifier). The shadow worm can't use Breath Weapon again for 1d4 rounds."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The shadow worm Grabs a creature\n* * *\n\n**Effect** The worm uses Swallow Whole."

  - name: "Rock Tunneler"
    desc: "  A shadow worm can burrow through solid stone at a Speed of 20 feet. It can leave a tunnel if it desires, and it usually does."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+15 bludgeoning, Rupture 42\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2`  The worm makes a Strike once against each creature in its reach. It can Strike up to once with its jaws and any number of times with its body. Each attack counts toward the worm's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shadow Worm
creatures:
  - 1: Shadow Worm
```



Shadow worms are monstrous cave worms that dwell on the Shadow Plane. Larger and more cunning than most cave worms, shadow worms are fearsome predators that leave swaths of devastation in their wake. Most have glossy, black-armored hide, but those that burrow near velstrac lands are streaked with dark red, for the blood the velstracs spill has soaked into the very stones these shadow worms consume.
