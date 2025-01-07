---
title: "Shadefield Spirit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vubErgvrGZqsvZLu" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Shadefield Spirit"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Shadefield Spirit"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: "Common, Orcish, Shoanti, Varisian"
skills:
  - name: "Skills"
    desc: "Intimidation: +13, Occultism: +12, Stealth: +10"
abilityMods: [5, 5, 0, 3, 4, 4]
speed:  fly 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +12, __Will__ +14"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70, rejuvenation, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  The Shadefield spirit is bound to the Shadefields.\n* * *\n\nA typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Putting Diskah Night Watcher's spirit to rest allows the Shadefield spirit to return to its original role as a guardian haunt.\n* * *\n\nWhen a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fiery Hand"
    desc: "+15 (agile, finesse, magical)\n__Damage__  1d6 fire 2d6 void"

  - name: "Cindery Assault"
    desc: "`pf2:2` (divine) The Shadefield spirit cries out in pain and anguish as flaming objects and debris fly about in a 30-foot emanation. Creatures in this area take 3d6 bludgeoning damage plus 1d6 persistent fire damage (DC 20 Reflex check save)."

  - name: "[[Creature Family Ability Glossary/(Ghost) Corrupting Gaze|Corrupting Gaze]]"
    desc: "`pf2:2`  The Shadefield spirit stares at a creature it can see within 30 feet. The target takes 3d6 void damage (DC 20 Will check save). A creature that fails its save is also [[Conditions/Stupefied|Stupefied 1]] for 1 minute."

  - name: "Sworn to the Storm"
    desc: "  The Shadefield spirit gains a +1 circumstance bonus to attacks against creatures that have attempted to Disable the Shoanti ancestor storm."
 
```

```encounter-table
name: Shadefield Spirit
creatures:
  - 1: Shadefield Spirit
```


Variant ghost

The ghost commoner is an ordinary person who believes they died unjustly.

* * *

When some mortals die through tragic circumstances or without closure, their souls can linger and haunt a locale significant to them in life.
