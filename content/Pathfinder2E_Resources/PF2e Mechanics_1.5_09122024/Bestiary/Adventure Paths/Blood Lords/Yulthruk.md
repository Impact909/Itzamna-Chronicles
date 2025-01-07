---
title: "Yulthruk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9DbszZWqpq6bRs1L" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Yulthruk"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Yulthruk"
level: "Creature 11"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Arcana: +22, Deception: +18, Society: +20, Stealth: +21, Thievery: +19"
abilityMods: [5, 5, 1, 7, 3, 3]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +23, __Will__ +19"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Wand of Shardstorm (3rd-Rank Spell)|Wand of Manifold Missiles (3rd-Rank Spell)]]"
abilities_mid:
  - name: ""
  - name: "Consume Arcana"
    desc: "`pf2:r`  **Trigger** Yulthruk succeeds at a saving throw against an arcane spell cast by another creature\n* * *\n\n**Effect** Yulthruk inhales some of the averted energy and becomes [[Conditions/Quickened|Quickened]] until the start of his next turn. He can use this extra action to Cast a Spell or Sustain a Spell"

  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 28 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (finesse)\n__Damage__  3d8 + 10 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, finesse)\n__Damage__  3d6 + 10 slashing plus ghast-paralysis"

  - name: "Arcane Prepared Spells"
    desc: "DC 33, attack +25; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Shadow Siphon|Shadow Siphon]]_; __4th __  _[[Spells/Flicker|Blink]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Weapon Storm|Weapon Storm]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Invisibility|Invisibility]]_, _[[Spells/See the Unseen|See Invisibility]]_, _[[Spells/Ghostly Carrier|Spectral Hand]]_; __1st __  _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(6th)__ _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Shield|Shield]]_"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghast is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghast devours a chunk of the corpse and regains 6d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "Drain Wand"
    desc: "  **Frequency** once per day\n\n**Requirements** Yulthruk hasn't acted yet on his turn\n* * *\n\n**Effect** On his turn Yulthruk can Cast a Spell he's prepared and already cast this day without spending a spell slot. Yulthruk must still meet the spell's other requirements."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease) **Saving Throw** DC 28 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 28 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Swift Leap"
    desc: "`pf2:1`  Yulthruk jumps up to half his Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Yulthruk
creatures:
  - 1: Yulthruk
```


Male ghast wizard


