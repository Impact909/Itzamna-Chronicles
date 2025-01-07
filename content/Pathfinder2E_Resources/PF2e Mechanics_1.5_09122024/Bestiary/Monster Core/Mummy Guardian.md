---
title: "Mummy Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yGYI4O4P1EA2n5w1" 
tags:
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Mummy Guardian"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Mummy Guardian"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[mummy]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Necril; plus any one language they knew while alive"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Stealth: +11"
abilityMods: [4, 0, 2, -2, 4, 2]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +10, __Will__ +16"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 5, alchemical 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alchemical Weakness"
    desc: "  The guardian's weakness to alchemical items not only applies to damage from alchemical items, but the guardian also takes 5 damage when splashed with non-damaging alchemical items or dosed with alchemical poisons, even if they're immune to their other effects."

  - name: "Blighted Consumption"
    desc: "`pf2:r` (curse,divine,poison) **Trigger** A creature within 30 feet eats or drinks (including an alchemical item or potion)\n* * *\n\n**Effect** The food or drink burns like the caustic substances fed to the mummy before its death. If the creature fails a DC 24 Fortitude check save, they become [[Conditions/Sickened|Sickened 2]] after they finish the consumption and can't reduce their sickened condition while within 30 feet of any mummy."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+16 (agile)\n__Damage__  2d10 + 7 bludgeoning plus choking-pain"

  - name: "Choking Pain"
    desc: "`pf2:1` (divine,illusion,mental,void) **Requirements** The mummy's last action was a successful fist Strike\n* * *\n\n**Effect** The mummy shares the pain of its dying moments with the target of that Strike. That creature takes 3d8 void damage with a DC 24 Will check save. If the creature critically fails the saving throw, it can't speak for 1 round, including to Cast a Spell."
 
```

```encounter-table
name: Mummy Guardian
creatures:
  - 1: Mummy Guardian
```



The majority of mummy guardians were created by cruel and selfish masters to serve as guardians to protect their tombs from intruders. The traditional method of creating a mummy guardian is a laborious and sadistic process that begins well before the poor soul to be transformed is dead. The victim is ritualistically starved of nourishing food and instead fed strange spices, preservative agents, and toxins intended to quicken the desiccation of the flesh. The victim remains immobile but painfully aware during the final stages, as its now-useless entrails are extracted. The victim is then shrouded in funerary wrappings and entombed within a necromantically ensorcelled sarcophagus to await instructions in the potentially distant future. While it's certainly possible to use other methods to create a mummy guardian from an already-deceased body, those who seek to create these foul undead as their guardians in the afterlife often feel that such methods result in inferior undead—the pain and agony of death by mummification being an essential step in the process.

Regardless of the method of their creation, mummy guardians are more than just physical shells of flesh and bone. They retain fragmented, distorted versions of their minds, with only enough memories of their living personality remaining to fuel their undead anger and jealousy of those who yet live. This burning rage only intensifies over the centuries of waiting within a crypt for the chance to actually act, and thus, when most mummy guardians are awoken by tomb robbers or adventurers, they stop at nothing in pursuit of spiteful slaughter.

* * *

While many cultures practice mummification for benign reasons, undead mummies are created through grueling rituals, typically to provide eternally vigilant guardians. Much more rarely, a body mummified without those special rites can rise again due to its hatred of the living.
