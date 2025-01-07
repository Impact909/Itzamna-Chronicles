---
title: "Putrifer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nK2ROT4Y5lksnnjB" 
tags:
  - pf2e/creature/type/plant
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Putrifer"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Putrifer"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[plant]]
trait_02: [[undead]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision"
languages: "Arboreal, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Intimidation: +15, Nature: +16, Stealth: +18, Survival: +16"
abilityMods: [6, 5, 4, -2, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +17, __Ref__ +20, __Will__ +14"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep,  unconscious; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Emotional Vulnerability"
    desc: "  A putrifer is easily overwhelmed by confusing thoughts, complex emotions, and resurfacing memories. A putrifer takes a –2 circumstance penalty to saving throws against emotion effects and treats the result of its saves against emotion effects as one degree worse."

  - name: "Stench"
    desc: " (aura,olfactory) 15 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 25 Fortitude check save or become [[Conditions/Sickened|Sickened 2]] (plus [[Conditions/Off-Guard|Off-Guard]] as long as it's sickened on a critical failure). A creature that succeeds at its save is temporarily immune for 1 minute."

  - name: "Vengeful Exhalation"
    desc: "`pf2:r` (inhaled,poison) **Trigger** An adjacent creature damages the putrifer\n* * *\n\n**Effect** The putrifer exhales, exposing the triggering creature to noxious putrescence"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rotting Fist"
    desc: "+21 (magical)\n__Damage__  2d8 + 12 bludgeoning 1d8 poison"

  - name: "**Ranged** `pf2:1` Bursting Seedpod"
    desc: "+20 (range increment 30 feet)\n__Damage__  2d6 + 6 bludgeoning plus noxious-putrescence"

  - name: "Primal Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Entangling Flora|Entangling Flora (At Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Puff of Poison|Puff of Poison]]_, _[[Spells/Tangle Vine|Tangle Vine]]_\n__Constant__  __(5th)__ _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Noxious Putrescence"
    desc: " (inhaled,poison) **Saving Throw** DC 28 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** 2d8 poison damage and [[Conditions/Sickened|Sickened 2]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Sickened|Sickened 4]] (1 round)"

  - name: "Woodland Stride"
    desc: "  The putrifer ignores difficult terrain and greater difficult terrain from non-magical foliage."
 
```

```encounter-table
name: Putrifer
creatures:
  - 1: Putrifer
```



A putrifer is a decaying plant creature that refuses to die, even as its body rots away. Similar in shape and appearance to a rotting ghoran, the flowers, leaves, bark, and rinds that compose a putrifer's body weep toxic black fluids. These disgusting secretions emit a foul-smelling miasma that surrounds the putrifer.

Most putrifers arise spontaneously when a gathlain, ghoran, leshy, or other intelligent plant dies traumatically from an effect that causes swift rot and decay. Others are created, either purposefully by necromancers or incidentally during magical experiments. Regardless of origin, a putrifer loses much of its intelligence during the transformation, becoming aggressive, erratic, and easily confused. Putrifers act instinctively, often lingering around the places they frequented in life. They find comfort in patterns and usually form simple daily routines that they loathe to deviate from. Often, these routines echo those they performed in life. A putrifer's memories are distant and faded, returning only periodically in short, confusing bursts that drive the putrifer to reenact moments from their past lives. Their inability to reconcile these memories with the present sometimes causes putrifers to destroy the locations they revisit and harm the people they once knew.

## Returning Memories

Over time, a putrifer's memories return, with each bout of remembrance lasting longer and resulting in more vivid, accurate memories. Putrifers that survive this confusing process sometimes regain a semblance of their former, living selves.
