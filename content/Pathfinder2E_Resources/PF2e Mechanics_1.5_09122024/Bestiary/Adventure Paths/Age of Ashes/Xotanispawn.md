---
title: "Xotanispawn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vpWwSQIs00emjLVN" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Xotanispawn"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Xotanispawn"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fire]]
trait_05: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Tremorsense (Imprecise) 60 Feet, Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +34, Stealth: +31, Survival: +29"
abilityMods: [9, 6, 8, -5, 4, 5]
speed: 40 feet,  burrow 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +31, __Ref__ +29, __Will__ +23"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340; __Immunities__  fire; __Weaknesses__ cold 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

abilities_mid:
  - name: ""
  - name: "Explosion"
    desc: " (fire) When a Xotanispawn dies, it explodes, dealing 15d8 fire damage to creatures in a 30-foot emanation (DC 39 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 36 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Internal Furnace"
    desc: "`pf2:r` (fire) **Trigger** A creature adjacent to the Xotanispawn touches it or hits it with a physical attack\n* * *\n\n**Effect** The triggering creature takes 5d8 persistent fire damage (DC 37 Reflex check save to negate)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (reach 10 feet)\n__Damage__  4d8 + 9 piercing plus grab 2d8 fire plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, reach 10 feet)\n__Damage__  4d6 + 9 slashing 2d8 fire"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The Xotanispawn sprays a 60-foot cone of magma that deals 10d10 fire damage and 2d6 persistent fire damage to all creatures in the area (DC 39 Reflex check save).\n\nThe Xotanispawn can't use its Breath Weapon again for 1d4 rounds."

  - name: "Heat Surge"
    desc: "  When the Xotanispawn critically hits, its body surges with heat, increasing the damage of its Internal Furnace to 10d8 persistent fire damage until the start of its next turn."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Xotanispawn
creatures:
  - 1: Xotanispawn
```




