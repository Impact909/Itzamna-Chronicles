---
title: "Minchgorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.53WrK7FsN2Z3pAdC" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Minchgorm"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Minchgorm"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[fey]]
trait_04: [[water]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Wavesense (Imprecise) 100 Feet"
languages: "Aklo, Common, Thalassic; tongues (can speak only through simulacra)"
skills:
  - name: "Skills"
    desc: "Athletics: +34, Intimidation: +34, Performance: +36"
abilityMods: [8, 0, 6, 5, 2, 8]
speed: 5 feet,  swim 20 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +30, __Ref__ +27, __Will__ +33"
hp: 440
health:
  - name: ""
  - name: HP
    desc: "440; __Weaknesses__ cold iron 15; __Resistances__ fire 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (magical, reach 10 feet)\n__Damage__  3d10 + 16 piercing plus improved-grab"

  - name: "Innate Primal Spells"
    desc: "DC 40, attack +30; __9th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_; __5th __  _[[Spells/Control Water|Control Water (x3)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The minchgorm Grabs a creature in its jaws\n* * *\n\n**Effect** The minchgorm uses Swallow Whole."

  - name: "Riptide"
    desc: "`pf2:2` (primal,water) Tentacles of water rise up and attempt to [[Actions/Grapple|Grapple]] all enemies within 15 feet of the minchgorm. The minchgorm attempts an Athletics check check against the Fortitude DC of each creature in the area. On a success, the creature is [[Conditions/Grabbed|Grabbed]] (Escape DC 40). On a critical success, or a success against a creature that is already grabbed, the target begins to drown."

  - name: "Swallow Whole"
    desc: "`pf2:1` (attack) Large, 3d10+16 bludgeoning, Rupture 36\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Watery Simulacra"
    desc: "`pf2:2` (concentrate,primal,water) The minchgorm raises up to eight figures from nearby water, each appearing in an empty space within 60 feet of the minchgorm. A simulacrum can take any shape of size Medium or smaller that the minchgorm desires, including that of a specific individual or object, but is always plainly made of water. The minchgorm can speak, cast spells, and use its senses through its simulacra, spending actions for a simulacrum on a one-for-one basis. By using a single action with the concentrate trait, the minchgorm can cause any number of simulacra to Fly, Step, Stride, or Swim up to 60 feet. A simulacrum uses the minchgorm's AC and saving throws and has 30 Hit Points. A minchgorm can have up to eight simulacra in existence at once. Simulacra dissolve immediately when more than 60 feet from the minchgorm, or if the minchgorm dies or falls unconscious. The minchgorm can dismiss any number of its simulacra as a free action."

  - name: "Improved Grab"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Minchgorm
creatures:
  - 1: Minchgorm
```




