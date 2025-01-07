---
title: "Accursed Forge-Spurned"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GJvzas3dF7mQyo89" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Accursed Forge-Spurned"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Accursed Forge-Spurned"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fire]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +29, Crafting: +30, Droskar Lore: +26"
abilityMods: [8, 4, 6, 3, 5, 2]
speed: 20 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +28, __Ref__ +24, __Will__ +25"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285, eternal damnation, void healing; __Immunities__  death effects,  disease,  fire,  paralyzed,  poison,  unconscious; __Weaknesses__ cold 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Soul Chain|Soul Chain]], [[Equipment/Warhammer|+2 Striking Adamantine Warhammer]], [[Equipment/Full Plate|+2 Resilient Full Plate]]"
abilities_mid:
  - name: ""
  - name: "Eternal Damnation"
    desc: " (divine) As long as its _soul chain_ remains intact, the accursed forge-spurned can't be truly destroyed and rises again fully healed at the next sundown, even if its physical body was destroyed."

  - name: "Searing Heat"
    desc: " (fire) A creature that touches the accursed forge-spurned (including [[Actions/Grapple|Grappling]] it or hitting it with an unarmed attack) takes 4d6 fire damage (DC 33 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Soul Chain"
    desc: "+31 (disarm, finesse, reach, trip)\n__Damage__  3d8 + 14 slashing plus soul-siphon 1d6 fire plus soul-siphon"

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+31 (shove)\n__Damage__  2d8 + 14 bludgeoning"

  - name: "Forge Breath"
    desc: "`pf2:2` (divine,fire) The accursed forge-spurned breathes a cloud of stinging soot, ash, and glowing embers. This can affect either a 30-foot cone or a 20-foot burst centered on the accursed forge-spurned and persists for 1d4 rounds.\n\nCreatures that move into or start their turn in the area take 12d6 fire damage (DC 36 Reflex check save).\n\nA creature that fails its save is also [[Conditions/Blinded|Blinded]] for 1 minute. Creatures within the cloud are [[Conditions/Concealed|Concealed]], though not from the accursed forge-spurned.\n\nThe accursed forge-spurned can't use Forge Breath again until it has used Inflate Bellows."

  - name: "Inflate Bellows"
    desc: "`pf2:2`  **Requirements** The accursed forge-spurned has used Forge Breath.\n* * *\n\n**Effect** The accursed forge-spurned re-inflates its flaccid lungs, enabling it to use Forge Breath again."

  - name: "Soul Chain"
    desc: " (divine,fire) If a creature is slain by an attack from the _soul chain_ and the accursed forge-spurned is able to retain the creature's corpse, it can bind the creature's soul into the soul chain (as [[Spells/Seize Soul|Seize Soul]]) with a day of work at a forge and a DC 20 Crafting check check.\n\nAn individual whose soul is bound in this way can't be resurrected unless the soul chain is destroyed (Hardness 10, 40 HP, BT 20)."

  - name: "Soul Siphon"
    desc: " (divine) When the accursed forge-spurned critically hits a target with its _soul chain_, the chain leeches away a portion of the target's soul. The target must attempt a DC 36 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Drained|Drained 1]].\n\n**Failure** The target is [[Conditions/Drained|Drained 2]].\n\n**Critical Failure** The target is drained 2 and [[Conditions/Stunned|Stunned 2]] from the pain."
 
```

```encounter-table
name: Accursed Forge-Spurned
creatures:
  - 1: Accursed Forge-Spurned
```



This undead dwarf has gorged on suffering over the centuries, and in that time has grown immense himself, so that he is proportioned more like a giant than a dwarf.
