---
title: "Ammut"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rSF4b9EI3bx25sWm" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Ammut"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Ammut"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Scent (Imprecise) 30 Feet, Truesight"
languages: "Diabolic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +34, Intimidation: +33, Occultism: +29, Religion: +32, Stealth: +35"
abilityMods: [8, 7, 9, 3, 6, 7]
speed: 50 feet,  burrow 30 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +35, __Ref__ +27, __Will__ +28"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Weaknesses__ holy 20; __Resistances__ fire 20, poison 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, reach 10 feet, unholy)\n__Damage__  3d8 + 16 slashing plus wasting-wound"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+30 (deadly d10, unholy)\n__Damage__  4d8 + 12 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (reach 15 feet, unholy)\n__Damage__  3d12 + 16 piercing plus improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __6th __ (1 slots) _[[Spells/Dominate|Dominate]]_\n__Constant__  __(6th)__ _[[Spells/Detect Alignment|Detect Alignment(Evil Only)]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (curse,divine,fire) The ammut exhales a blast of flame that deals 18d6 fire damage to all creatures in a 30-foot cone (DC 37 Reflex check save). The ammut can't use their Breath Weapon again for 1d4 rounds."

  - name: "Devour Soul"
    desc: " (curse,death,divine) A creature whose HP drops to 0 while swallowed by an ammut has its soul consumed, as well as its body. The creature dies instantly and cannot be brought back to life except by [[Spells/Miracle|Miracle]], [[Spells/Wish|Wish]], or similar magic."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The ammut [[Conditions/Grabbed|Grabs]] a creature\n* * *\n\n**Effect** The ammut uses Swallow Whole."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d12+8 bludgeoning damage, Rupture 32\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Wasting Wound"
    desc: " (curse,divine) A creature dealt damage by an ammut's claw Strike must succeed at a DC 37 Will check save or become [[Conditions/Enfeebled|Enfeebled 1]] and [[Conditions/Drained|Drained 1]] (or [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Drained|Drained 2]] on a critical failed save). The conditions cannot be mitigated until the curse is removed, and the curse cannot be removed until all damage dealt by the claw Strike is healed. Each day, a creature afflicted with wasting wound must attempt another saving throw; on a failed save, the values of its enfeebled and drained conditions each increase by 1. If the victim dies while cursed, its soul is destroyed, as per the ammut's devour soul ability."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ammut
creatures:
  - 1: Ammut
```



These chimeric, desert-dwelling fiends have massive bodies that are part hippopotamus, part large cat, and part crocodile. Though they devour souls for sustenance, ammuts are infamously picky eaters; most will only eat experienced adventurers or, for a special treat, particularly evil creatures, passing over common folk or those whose mettle has never been tested.

Only a few ammuts are known to exist, and most dwell in Osirion. However, recent expeditions into Orv's Vault of the Black Desert have uncovered the existence of ammuts in this region, as well.
