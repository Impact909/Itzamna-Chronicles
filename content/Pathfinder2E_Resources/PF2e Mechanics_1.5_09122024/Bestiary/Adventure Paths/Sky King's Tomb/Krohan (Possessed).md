---
title: "Krohan (Possessed)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VN9qsToErC2EclHr" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/good
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Krohan (Possessed)"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Krohan (Possessed)"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[good]]
trait_03: [[humanoid]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Medicine: +8, Occultism: +8, Society: +6, Stealth: +5, Dwarf Lore: +8"
abilityMods: [2, 0, 2, 1, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 18
armorclass:
  - name: AC
    desc: "18 (19 with shield raised); __Fort__ +9, __Ref__ +7, __Will__ +10"
hp: 52
health:
  - name: ""
  - name: HP
    desc: "52, Void Healing; __Resistances__ poison 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Pick|Pick]], [[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Buckler|Buckler]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Rope|Rope]], [[Equipment/Waterskin|Waterskin]], [[Equipment/Flint and Steel|Flint and Steel]], 5x [[Equipment/Torch|Torch]], [[Equipment/Bedroll|Bedroll]], [[Equipment/Soap|Soap]], 20x [[Equipment/Arrows|Arrows]], 10x [[Equipment/Chalk|Chalk]], 2x [[Equipment/Rations|Rations]], [[Equipment/Healing Potion (Lesser)|Healing Potion (Lesser)]], [[Equipment/Antidote (Lesser)|Antidote (Lesser)]], [[Equipment/Backpack|Backpack]]"
  - name: "Possessed"
    desc: "  A hostile spirit controls Krohan, which gives him the void healing ability and otherwise has the same effect as the [[Spells/Possession|Possession]] spell. Krohan attempts a DC 20 Flat check at the end of his turn; this is reduced to DC 15 Flat check if the corrupted blade spirit is destroyed. If he succeeds, the possession effect is suppressed and he is [[Conditions/Slowed|Slowed 1]] until the end of his next turn, allowing him to act normally. If he critically succeeds, the possession effect ends."

abilities_mid:
  - name: ""
  - name: "Occult Catharsis"
    desc: " (emotion,healing,occult) Krohan's magic converts his pain into spellpower. After he casts an innate occult spell, he attempts a DC 5 Flat check, increasing the DC by twice the spell's rank if it was not a cantrip. On a success, Krohan's Spirits Drawn to Suffering effect ends; he can reduce the value of one condition affecting him by 1, and he regains 2d6 healing Hit Points."

  - name: "Spirits Drawn to Suffering"
    desc: "`pf2:0` (occult) **Frequency** once per 10 minutes\n\n**Trigger** Krohan critically fails a saving throw, takes mental damage, takes damage from a critical hit, or gains a harmful condition with a numerical value (such as frightened or sickened). This effect does not trigger due to self-harm or similarly engineered circumstances.\n* * *\n\n**Effect** Krohan gains the ability to cast his innate occult spells for 1 minute."

  - name: "Unwitting Rivethun"
    desc: "  Krohan has very limited access to Rivethun magic, able to cast spells only when experiencing pain or distress."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Phantom Pick"
    desc: "+14 (fatal d10)\n__Damage__  1d6 + 3 piercing 1d12 mental"

  - name: "**Ranged** `pf2:1` Phantom Hand Crossbow"
    desc: "+14 (range increment 60 feet)\n__Damage__  1d6 + 3 piercing 1d12 mental"

  - name: "Occult Innate Spells"
    desc: "DC 20, attack +12; __2nd __  _[[Spells/Soothe|Soothe]]_, _[[Spells/Noise Blast|Sound Burst (x2)]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_; __1st __  _[[Spells/Fear|Fear]]_, _[[Spells/Runic Weapon|Magic Weapon]]_, _[[Spells/Spirit Link|Spirit Link]]_\n__Cantrips__  __(2nd)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_"

  - name: "Righthand Man"
    desc: "  Krohan gains a +2 circumstance bonus to attack rolls and skill checks attempted to Aid others. He can attempt a Dwarf Lore check in place of any other attack roll or skill check to Aid a dwarf."
 
```

```encounter-table
name: Krohan (Possessed)
creatures:
  - 1: Krohan (Possessed)
```




