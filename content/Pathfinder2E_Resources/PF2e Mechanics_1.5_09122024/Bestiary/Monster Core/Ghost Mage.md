---
title: "Ghost Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gIb33fYs0PQlukkS" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Ghost Mage"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ghost Mage"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Draconic"
skills:
  - name: "Skills"
    desc: "Arcana: +22, Intimidation: +22, Stealth: +21"
abilityMods: [-5, 3, 0, 6, 3, 6]
speed:  fly 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +19, __Will__ +22"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, rejuvenation, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 10 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  A typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Completing the ghost mage's project allows it to move on to the afterlife.\n* * *\n\nWhen a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+21 (agile, finesse, magical)\n__Damage__  2d8 + 12 void"

  - name: "Arcane Innate Spells"
    desc: "DC 29, attack +23; __5th __  _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Howling Blizzard|Howling Blizzard]]_; __4th __  _[[Spells/Suggestion|Suggestion]]_, _[[Spells/Vision of Death|Vision of Death]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Veil of Privacy|Veil of Privacy]]_; __2nd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_; __1st __  _[[Spells/Enfeeble|Enfeeble]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "[[Creature Family Ability Glossary/(Ghost) Frightful Moan|Frightful Moan]]"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The ghost laments its fate, forcing each living creature within 30 feet to attempt a DC 29 Will check save. On a failure, a creature becomes [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). On a success, a creature is temporarily immune to this ghost's frightful moan for 1 minute."

  - name: "[[Creature Family Ability Glossary/(Ghost) Telekinetic Assault|Telekinetic Assault]]"
    desc: "`pf2:2` (divine) The ghost cries out in pain and anguish as small objects and debris fly about in a 30-foot emanation. Creatures in this area take 6d6 bludgeoning damage, subject to a DC 29 Reflex check save."
 
```

```encounter-table
name: Ghost Mage
creatures:
  - 1: Ghost Mage
```



A wizard who died with work incomplete might become a ghost mage.

* * *

When some mortals die through tragic circumstances or without closure, their souls can linger and haunt a locale significant to them in life.
