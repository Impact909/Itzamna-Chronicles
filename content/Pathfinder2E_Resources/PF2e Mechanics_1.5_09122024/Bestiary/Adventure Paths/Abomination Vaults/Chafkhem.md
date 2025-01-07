---
title: "Chafkhem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wUEPQVPbez0a2foB" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Chafkhem"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Chafkhem"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[mummy]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Aklo, Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +19, Athletics: +15, Diplomacy: +16, Intimidation: +16, Occultism: +17, Religion: +15"
abilityMods: [3, 4, 3, 7, 3, 4]
speed: 20 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +15, __Ref__ +16, __Will__ +17; +1 status to all saves vs. vitality"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Compendium.pf2e.equipment-srd.Item.EYRrABqjUYPrhrZr|Staff of Abjuration]]"
abilities_mid:
  - name: ""
  - name: "Despair"
    desc: " (aura,divine,emotion,fear,incapacitation,mental) 30 feet. Living creatures are [[Conditions/Frightened|Frightened 1]] while in Chafkhem's despair aura. They can't naturally recover from this fear while in the area but recover instantly once they leave it. When a creature first enters the area, it must succeed at a DC 24 Will check save (after taking the penalty from being frightened) or be [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\nThe creature is then temporarily immune for 24 hours.\n\n[[Bestiary Effects/Effect_ Despair|Effect: Despair]]"

  - name: "Rejuvenation"
    desc: " (divine) When Chafkhem is destroyed, necromantic energies rebuild his body in the magic circle in his room over 1d10 days. If the re-forming body is destroyed during that time, the process starts anew. Chafkhem can be destroyed for good with a [[Spells/Consecrate|Consecrate]] ritual, or if the magic circle is destroyed."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Warding Script"
    desc: "`pf2:r` (arcane) **Trigger** A creature Chafkhem can see makes a melee Strike against Chafkhem\n* * *\n\n**Effect** Chafkhem traces a magical glyph in the air that glows and fades. The triggering creature must attempt a DC 25 Fortitude check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Blinded|Blinded]] until the start of its next turn.\n\n**Critical Failure** The target is blinded for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+19 (agile, finesse)\n__Damage__  2d6 + 7 bludgeoning plus mummy-rot"

  - name: "**Melee** `pf2:1` Staff"
    desc: "+18 (two-hand d8)\n__Damage__  1d4 + 7 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Spell Immunity|Spell Immunity]]_; __3rd __  _[[Spells/Rune Trap|Glyph of Warding]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Mind Reading|Mind Reading]]_; __2nd __  _[[Spells/Blur|Blur]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Mending|Mending]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Phantasmal Minion|Unseen Servant]]_\n__Cantrips__  __(4th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Rituals"
    desc: "_Awaken Portal_, _Create Undead_, _Inveigle_"

  - name: "Mummy Rot"
    desc: " (curse,disease,divine,void) This disease and any damage from it can't be healed until this curse is removed. A creature killed by mummy rot turns to dust and can't be resurrected except by a 7th-rank [[Spells/Resurrect|Resurrect]] ritual or similar magic.\n\n**Saving Throw** DC 24 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 minute)\n\n**Stage 2** 6d6 void damage and [[Conditions/Stupefied|Stupefied 1]] (1 day)"
 
```

```encounter-table
name: Chafkhem
creatures:
  - 1: Chafkhem
```


Male mummy ritualist


