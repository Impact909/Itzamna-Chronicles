---
title: "Polong"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aW5VKhdF8FakoXkg" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Polong"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Polong"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Lifesense 30 Feet"
languages: "any one language known by the polong&#x27;s creator"
skills:
  - name: "Skills"
    desc: "Deception: +18, Medicine: +15, Occultism: +13, Stealth: +18"
abilityMods: [-5, 6, 2, 1, 5, 6]
speed:  fly 35 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +18, __Will__ +19"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ holy 5; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Bottle Bound"
    desc: "  A polong is bound to the bottle from which they spawned. They can leave the bottle only at the will of their master and must return to it once every 24 hours to feed on their creator's blood. Otherwise, the polong withers and dies."

  - name: "Natural Invisibility"
    desc: "  A polong is naturally [[Conditions/Invisible|Invisible]] outside of their bottle. They become visible only when forced out of a possessed creature against their will. Shattering the polong's bottle also forces them to assume a visible form."

  - name: "Regenerating Bond"
    desc: " (occult) When a polong possesses a creature, the polong's master gains temporary Hit Points equal to the victim's level × the victim's drained value caused by the possession. These temporary Hit Points last as long as the possession lasts."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scythe Claw"
    desc: "+20 (finesse, magical)\n__Damage__  2d4 + 9 slashing 1d6 void"

  - name: "Polong Possession"
    desc: "`pf2:3` (incapacitation,mental,occult,possession) The polong attempts to possess an adjacent corporeal creature. This has the same effect as the [[Spells/Possession|Possession]] spell (DC 26 Will check), except the duration is 24 hours and, since the polong doesn't have a physical body, they're unaffected by that restriction of the spell. If the target has critically failed its save and become fully possessed by this polong before, it gets a save result one degree of success worse than it rolled.\n\nA creature possessed by a polong becomes [[Conditions/Drained|Drained 1]] and [[Conditions/Doomed|Doomed 1]]. These conditions don't reduce naturally unless the polong spends an entire day without possessing the creature. For each consecutive day the polong is able to return and possess the creature, the drained and doomed values each increase by 1, to a maximum of 4. If the polong possesses a different creature, the conditions end for any creature it previously possessed."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Scythe Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Polong
creatures:
  - 1: Polong
```



Polongs exist to serve their creators as loyal familiars, spies, and assassins. Their convenience makes them popular among the wicked, as each resides within a glass bottle which normally seems to contain only a small amount of red liquid. When addressed by their owner, a polong appears within their bottle as a tiny, beautiful humanoid drenched in blood. Forcing one to manifest outside the bottle reveals their true shape: a blood-soaked spirit with a hateful visage and sickle-shaped claws.

The ritual to create a polong originated in Minata and is known primarily by Tian-Sing spellcasters, but only those willing to practice such evil. The ritualist must collect the blood of a murdered humanoid in a small bottle and perform daily incantations, which can take up to 14 days. Once the polong forms, they drink the blood of their creator every day, most often taken from a finger inserted into their bottle. At the master's order, a polong will travel up to 10 miles away to locate a particular person, possess them, and either slowly whittle them down via possession until they die, or force them to attack anyone nearby until someone slays the victim in self-defense.
