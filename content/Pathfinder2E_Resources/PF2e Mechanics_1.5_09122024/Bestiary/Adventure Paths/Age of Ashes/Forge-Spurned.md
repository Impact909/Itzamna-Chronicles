---
title: "Forge-Spurned"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.krvWGym53LaE1uRP" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Forge-Spurned"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Forge-Spurned"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fire]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Crafting: +14, Droskar Lore: +12"
abilityMods: [5, 2, 4, 1, 2, 0]
speed: 20 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +9, __Will__ +11"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, eternal damnation, void healing; __Immunities__  death effects,  disease,  fire,  paralyzed,  poison,  unconscious; __Weaknesses__ cold 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|Warhammer]], [[Equipment/Soul Chain|Soul Chain]]"
abilities_mid:
  - name: ""
  - name: "Enternal Damnation"
    desc: " (divine) As long as its _soul chain_ remains intact, a forge-spurned can't be truly destroyed. It rises again fully healed at the next sundown, even if its physical body was destroyed."

  - name: "Searing Heat"
    desc: " (fire) A creature that touches the forge-spurned (including [[Actions/Grapple|Grappling]] it or hitting it with an unarmed attack) takes 2d6 fire damage (DC 21 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Soul Chain"
    desc: "+15 (disarm, trip)\n__Damage__  2d8 + 5 slashing 1d6 fire"

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+14 (shove)\n__Damage__  1d8 + 7 bludgeoning"

  - name: "Forge Breath"
    desc: "`pf2:2` (divine,fire) The forge-spurned breathes a cloud of stinging soot, ash, and glowing embers. This can affect either a 30-foot cone or a 20-foot burst centered on the forge-spurned and persists for 1d4 rounds.\n\nEach creature that moves into or starts their turn in the area takes 6d6 fire damage, with a DC 21 Reflex check save. A creature that fails its save is also [[Conditions/Blinded|Blinded]] for 1 minute.\n\nCreatures within the cloud are [[Conditions/Concealed|Concealed]], though not from the forge-spurned.\n\nThe forge-spurned can't use Forge Breath again until it has used Inflate Bellows."

  - name: "Inflate Bellows"
    desc: "`pf2:2`  **Requirements** The forge-spurned has used Forge Breath.\n* * *\n\n**Effect** The forge-spurned re-inflates its flaccid lungs, enabling it to use Forge Breath again."

  - name: "Soul Chain"
    desc: " (divine,fire) If a creature is slain by an attack from the _soul chain_ and the forge-spurned is able to retain the creature's corpse, it can bind the creature's soul into the soul chain (as [[Spells/Seize Soul|Seize Soul]]) with a day of work at a forge and a DC 20 Crafting check check.\n\nAn individual whose soul is bound in this way can't be resurrected unless the soul chain is destroyed (Hardness 10, 40 HP, BT 20)."
 
```

```encounter-table
name: Forge-Spurned
creatures:
  - 1: Forge-Spurned
```



Evil dwarves who die having failed to live up to the exacting standards of the duergar god Droskar are sometimes forced to return to the material world as undead abominations known as forge-spurned.
