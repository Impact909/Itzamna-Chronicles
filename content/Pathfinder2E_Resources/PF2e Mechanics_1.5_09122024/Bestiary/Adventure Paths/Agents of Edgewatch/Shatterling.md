---
title: "Shatterling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FrfqrvMEopaIbtC1" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Shatterling"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Shatterling"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fey]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +25, Intimidation: +25, Society: +20, Stealth: +32, Thievery: +30"
abilityMods: [5, 8, 4, 0, 4, 3]
speed: 40 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +30, __Will__ +26"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305; __Immunities__  bleed; __Weaknesses__ bludgeoning 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Attack of Opportunity"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Divert Strike"
    desc: "`pf2:r`  **Trigger** A shatterling takes non-bludgeoning damage and there's an unbroken mirror at least 1 foot wide within 100 feet of the shatterling\n* * *\n\n**Effect** The nearest mirror to the shatterling at least 1 foot wide breaks, and the damage to the shatterling is reduced to 0."

  - name: "Extra Reaction"
    desc: "  A shatterling gains an additional reaction each turn, but can use this extra reaction only for Divert Strike."

  - name: "Mirror Senses"
    desc: "  A shatterling can see and hear through any unbroken mirror within 100 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mirror Hand"
    desc: "+27 (agile, finesse, magical)\n__Damage__  3d6 + 11 slashing 2d6 bleed"

  - name: "**Ranged** `pf2:1` Mirror Dart"
    desc: "+27 (magical, range increment 30 feet)\n__Damage__  3d6 + 11 piercing"

  - name: "Blood-Fueled Titter"
    desc: "  If the shatterling attempts an Intimidation check to [[Actions/Demoralize|Demoralize]] a target within 30 feet of a creature with persistent bleed damage, the shatterling has +4 circumstance bonus to the Intimidation check. In addition, the shatterling takes no penalty to the check for not speaking a language the target can hear, and the target isn't temporarily immune to the shatterling's attempts to Demoralize it unless the shatterling critically fails its Intimidation check."

  - name: "Mirror Jump"
    desc: "`pf2:1` (move) During this Stride, the shatterling can move into any unbroken mirror at least 1 foot wide and out of another unbroken mirror at least 1 foot wide within 100 feet of the first mirror, treating the mirrors as connected. The shatterling can move through any number of pairs of foot-wide mirrors during its mirror jump, requiring each pair to be within 100 feet of each other while doing so."

  - name: "Vanish in Reflections"
    desc: "  The shatterling doesn't appear in reflective surfaces if it doesn't want to. When it's within 100 feet of an unbroken mirror at least 1 foot wide, a shatterling can Hide and Sneak even without cover or without being concealed."

  - name: "Wipe Away Cracks"
    desc: "`pf2:3` (manipulate) The shatterling touches a broken mirror, instantly repairing it."
 
```

```encounter-table
name: Shatterling
creatures:
  - 1: Shatterling
```




