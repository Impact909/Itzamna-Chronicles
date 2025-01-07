---
title: "Quoppopak Mummy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IlSjkfwJFqz0i0M6" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Quoppopak Mummy"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Quoppopak Mummy"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mummy]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27"
abilityMods: [8, 2, 6, -2, 5, 0]
speed: 10 feet,  swim 35 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +26, __Ref__ +21, __Will__ +24"
hp: 260
health:
  - name: ""
  - name: HP
    desc: "260; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tentacle Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Despair"
    desc: " (aura,divine,emotion,fear,incapacitation,mental) 30 feet. Living creatures are [[Conditions/Frightened|Frightened 1]] while in a mummy guardian's despair aura. They can't naturally recover from this fear while in the area but recover instantly once they leave the area. When a creature first enters the area, it must succeed at a DC 30 Will check save (after taking the penalty from being frightened) or be [[Conditions/Paralyzed|Paralyzed]] for 1 round. The creature is then temporarily immune for 24 hours.\n\n[[Bestiary Effects/Effect_ Despair|Effect: Despair]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+27 (reach 10 feet)\n__Damage__  3d10 + 14 piercing plus oil-rot"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+27 (agile, reach 15 feet)\n__Damage__  3d8 + 14 bludgeoning plus grab,oil-rot"

  - name: "**Melee** `pf2:1` Ventral Tube"
    desc: "+27 (reach 10 feet)\n__Damage__  1d6 bleed plus oil-rot 3d6 + 14 slashing plus oil-rot"

  - name: "Ignite Oil"
    desc: "  **Trigger** The quoppopak mummy takes fire damage while it is above water\n* * *\n\n**Effect** The oil coating the mummy ignites. This fire does no additional damage to the mummy but does cause its melee Strikes to inflict an additional 1d6 fire damage. At the end of its turn, the mummy attempts a DC 10 Flat check; on a success, the fire goes out. The fire also goes out immediately if the mummy submerges in water."

  - name: "Oil Rot"
    desc: " (curse,disease,divine) This disease and any damage from it can't be healed until this curse is removed. As the disease progresses, the creature's flesh grows leathery, while a foul-smelling oily layer spreads from painful splits in the dried skin. A creature killed by oil rot melts into a puddle of foul-smelling oil and can be resurrected only by a 7th-rank resurrect ritual or similar magic\n\n**Saving Throw** DC 33 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 minute)\n\n**Stage 2** 10d6 void damage and [[Conditions/Clumsy|Clumsy 2]] (1 day)"

  - name: "Tentacle Stab"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The quoppopak makes two tentacle Strikes against the same creature. These Strikes deal piercing damage instead of bludgeoning, and the quoppopak can't [[Bestiary Ability Glossary/Grab|Grab]] with them. Its multiple attack penalty doesn't increase until after both attacks."

  - name: "Water Glide"
    desc: "  The quoppopak can stand and move on the surface of water or other liquids without falling through. It can go underwater if it wishes, but it must [[Actions/Swim|Swim]] to do so."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Quoppopak Mummy
creatures:
  - 1: Quoppopak Mummy
```




