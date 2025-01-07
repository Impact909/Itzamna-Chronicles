---
title: "Blackfrost Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RI8qMXJNFUmLX8p9" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Blackfrost Zombie"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #189: Dreamers of the Nameless Spires"
name: "Blackfrost Zombie"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[cold]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[zombie]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [5, 2, 4, -5, 0, 0]
speed: 20 feet
sourcebook: "_Pathfinder #189: Dreamers of the Nameless Spires_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +16, __Ref__ +12, __Will__ +8"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, void healing; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Blackfrost Dead) Ice Climb|Ice Climb 20 feet]]"
    desc: "  The blackfrost dead can climb on ice as though it had the listed climb Speed. It ignores difficult terrain and greater difficult terrain from ice and snow and doesn't risk falling when crossing ice."

abilities_mid:
  - name: ""
  - name: "Opportune Bite"
    desc: "`pf2:r`  **Trigger** A creature critically fails a Strike within 10 feet of the blackfrost zombie\n* * *\n\n**Effect** The blackfrost zombie Steps toward the triggering creature, then makes a jaws Strike against that creature."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+15 ()\n__Damage__  2d6 + 5 bludgeoning 1d6 cold"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 ()\n__Damage__  2d4 + 5 piercing plus blackfrost 1d6 cold plus blackfrost"

  - name: "[[Creature Family Ability Glossary/(Blackfrost Dead) Blackfrost|Blackfrost]]"
    desc: " (cold,curse,disease,occult) This affliction can't be reduced below stage 1, nor the damage from it healed, until successfully treated with [[Spells/Cleanse Affliction|Cleanse Affliction]] or a similar effect; the affliction can then be removed as a normal disease. A creature that dies from cold damage while cursed with blackfrost rises as a blackfrost dead after 24 hours. Blackfrost has a counteract rank of 10.\n\n**Saving Throw** DC 27 Fortitude check\n\n**Stage 1** 4d6 cold (1 minute)\n\n**Stage 2** weakness to cold 5 and [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** weakness to cold 10 and [[Conditions/Drained|Drained 2]] (1 day)"

  - name: "[[Creature Family Ability Glossary/(Blackfrost Dead) Blackfrost Breath|Blackfrost Breath]]"
    desc: "`pf2:2` (occult) The blackfrost dead gasps sharply, then exhales a mist of dark-blue blackfrost particles in a 5-foot emanation. All creatures within the mist become [[Conditions/Concealed|Concealed]], and all creatures outside the mist become concealed to creatures within it. The mist persists for 1 minute. A creature that ends its turn in the mist is exposed to blackfrost. The blackfrost dead can't use Blackfrost Breath again for 1d4 rounds."
 
```

```encounter-table
name: Blackfrost Zombie
creatures:
  - 1: Blackfrost Zombie
```



Most creatures who perish from the cold while cursed with blackfrost rise as zombies. Though mindless, blackfrost zombies are driven by the [[Conditions/Invisible|Invisible]] will of blackfrost to spread their foul curse.

* * *

These shambling arctic horrors are dead in name alone. Creatures who succumb to the frigid elements while cursed by blackfrost don't become mere corpses entombed in ice but rather vicious undead capable of spreading the curse of blackfrost even further. Cracked, frostbitten flesh that emits a freezing vapor like steam; inexorable, unhindered strides through feet of ash-blackened snow; a vacant, icy-blue gaze devoid of humanity—the descriptions of blackfrost dead vary by the teller, but none can deny the supernatural dread these monsters evoke.

Blackfrost dead take a variety of forms. Most are mindless, lumbering brutes, largely indiscernible from mundane zombies except for the curse they can inflict. Others not only maintain their presence of mind but wield powers of psychic corruption not unlike those of blackfrost's originator, Osoyo, the Blackfrost Whale. What form a blackfrost dead takes depends primarily on the victim's psychic fortitude and its aptitude for occult magic.

### Creating Blackfrost Dead

The simplest way to create a blackfrost dead is to use an existing undead, such as a zombie or a mummy, as your base creature. Replace the creature's abilities with abilities from the list on this page. All blackfrost dead gain the cold trait and have at least one way to inflict blackfrost, often using one of their Strikes.

### Curse of the Crown

Blackfrost dead are found only around the Nameless Spires, under which a massive alien being named Osoyo remains imprisoned. Only recently has this ancient being stirred from its slumber, causing blackfrost to foam out of fissures in the ice and afflict unfortunate explorers. The spread of the blackfrost curse has been mercifully slow thus far, but with each creature afflicted, Osoyo's reach expands ever outward.
