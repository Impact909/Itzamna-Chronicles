---
title: "Sparkeater"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CuO0pAtFasHZ65mo" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Sparkeater"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Sparkeater"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +28"
abilityMods: [8, 0, 6, -5, 4, 4]
speed: 60 feet,  fly 180 feet
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +28, __Ref__ +22, __Will__ +26"
hp: 325
health:
  - name: ""
  - name: HP
    desc: "325, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "Failed Ravener"
    desc: "  Sparkeater has the same statistics as a normal [[Bestiary 2/Ravener Husk|Ravener Husk]] but is Large instead of Gargantuan. His melee Strikes have a reach of only 5 feet, and he lacks the Ravenous Repast ability, as he was never a ravener in the first place."

  - name: "[[Creature Family Ability Glossary/(Ravener) Soulsense|Soulsense 60 feet]]"
    desc: "  Sparkeater senses the spiritual essence of living and undead creatures within the listed range. Creatures whose material bodies are one unit with their souls, like celestials and fiends, appear brighter to this sense."

abilities_mid:
  - name: ""
  - name: "Boneshatter"
    desc: "`pf2:r`  **Trigger** Sparkeater takes any amount of bludgeoning damage\n* * *\n\n**Effect** Sparkeater's brittle bones shatter, spraying bone shards everywhere. Every creature within a 10-foot emanation of Sparkeater takes 7d6 piercing damage (DC 31 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 31 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical)\n__Damage__  3d8 + 16 piercing 2d6 void"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical)\n__Damage__  3d4 + 16 slashing 2d6 void"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,void) Sparkeater breathes a torrent of void energy that deals 16d6 void damage in a 40-foot cone (DC 34 Reflex check save).\n\nHe can't use Breath Weapon again for 1d4 rounds."
 
```

```encounter-table
name: Sparkeater
creatures:
  - 1: Sparkeater
```


Variant ravener husk

Raveners require a steady diet of souls, and a ravener that's unable to feed for too long eventually cannibalizes their own soul. Should a ravener's soul ward ever be reduced to 0 Hit Points by hunger while the ravener has more than 1 Hit Point (see Soul Ward), they lose all traces of their former identity and descend into a feral, nearly mindless state. Even if a ravener husk later consumes soul energy, the transformation can be reversed only via Ravenous Repast.

* * *

Though their lifespans can measure in millennia, all dragons must eventually perish. While many do so on the blades or under the spells of dragonslayers, some manage to outlast their enemies and must, in time, face the truth that awaits all living creatures at the end of their natural lifespan. As with many other creatures, some dragons respond to such looming reminders of their own mortality poorly, and the particularly prideful or wrathful of their kind often lash out in anger when confronted by this grim truth. Peace and acceptance may find some dragons, but the most stubborn of their ilk (and invariably the most wicked) may pursue a different answer to the problem. These dragons seek out sinister rites that can transform them into undead creatures known as raveners.

A ravener's flesh is stripped away as part of the transformation, leaving only their skeleton. What they lose in flesh, however, the dragon gains in soul-rending power, as their raw spiritual energy forms a protective barrier around their skeleton, keeping it intact and allowing flight with now-skeletal wings. This new existence is not so easy to maintain as other forms of undeath, however, and the ravener must feed regularly on the souls of living creatures to power their profane metabolism. This hunger is much greater than that of a living dragon, so raveners are forced to relocate regularly, traveling to fresh hunting grounds each time they strip their current home of prey. A ravener may depopulate whole regions at a time in order to sate their endless hunger for souls, lest they lose much of their power and become a ravener husk.
