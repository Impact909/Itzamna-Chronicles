---
title: "Ghost Monk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.K3cDSFRBbMtTQPXl" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Ghost Monk"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Ghost Monk"
level: "Creature 9"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[lawful]]
trait_04: [[spirit]]
trait_05: [[undead]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Tien"
skills:
  - name: "Skills"
    desc: "Occultism: +17, Irori Lore: +17, Temple Lore: +17"
abilityMods: [-5, 4, 0, 2, 6, 6]
speed:  fly 40 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +19, __Will__ +21"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Site Bound"
    desc: "  A typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Putting the abbot in A8 to rest brings peace to the ghost monks, allowing them to move on to the Serene Circle in Axis.\n* * *\n\nWhen a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Fist"
    desc: "+21 (agile, finesse, magical)\n__Damage__  2d8 + 12 void"

  - name: "Flurry of Blows"
    desc: "`pf2:1` (flourish) The ghost monk makes two Strikes with their ghostly fist. If both hit the same creature, combine their damage for the purpose of resistances and weaknesses."

  - name: "[[Creature Family Ability Glossary/(Ghost) Frightful Moan|Frightful Moan]]"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The ghost laments its fate, forcing each living creature within 30 feet to attempt a DC 25 Will check save. On a failure, a creature becomes [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). On a success, a creature is temporarily immune to this ghost's frightful moan for 1 minute."

  - name: "[[Creature Family Ability Glossary/(Ghost) Telekinetic Assault|Telekinetic Assault]]"
    desc: "`pf2:2` (divine) The ghost cries out in pain and anguish as small objects and debris fly about in a 30-foot emanation. Creatures in this area take 5d6 bludgeoning damage + 1d6 per 2 levels, subject to a DC 25 Reflex check save."
 
```

```encounter-table
name: Ghost Monk
creatures:
  - 1: Ghost Monk
```


Ghost adherents of Irori


