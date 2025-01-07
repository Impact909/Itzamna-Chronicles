---
title: "Herexen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.h3vZJi3mXcUoPVTH" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Herexen"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Herexen"
level: "Creature 2"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Deception: +7, Religion: +10, Stealth: +6"
abilityMods: [2, 2, 1, 0, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +5, __Ref__ +8, __Will__ +10"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Religious Symbol (Wooden)|Defiled Religious Symbol of Pharasma (Wooden)]]"
abilities_mid:
  - name: ""
  - name: "Final Blasphemy"
    desc: " (divine,void) When the herexen is destroyed, it explodes in a wave of void energy with the effects of a 3-action [[Spells/Harm|Harm]] spell (DC 18 Fortitude check).\n\nThe herexen is destroyed, so it doesn't gain any Hit Points from this use of _harm_, and it doesn't need to have any _harm_ spells remaining to use this ability"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+10 (agile, versatile s)\n__Damage__  1d6 + 4 piercing plus heretics-smite"

  - name: "Divine Prepared Spells"
    desc: "DC 18, attack +10; __1st __  _[[Spells/Harm|Harm]]_"

  - name: "Cleric Domain Spells"
    desc: "1 Focus Point, DC 18, attack +10; __1st __  _[[Spells/Death's Call|Death's Call]]_"

  - name: "Heretic's Smite"
    desc: " (divine) While wielding the favored weapon of its former deity (such as a dagger for an ex-Pharasmin herexen), the herexen's Strikes deal an additional 1d6 spirit damage to creatures with the holy trait."
 
```

```encounter-table
name: Herexen
creatures:
  - 1: Herexen
```



When a cleric rebels against their deity and dies in the grip of blasphemous rage, the heresies they committed in life may fuel their transformation into an undead herexen. Herexens seek vengeance against the deity they once worshipped, defiling temples, slaying the faithful, and rallying lesser undead and death cultists to aid them in their unholy quests. Though a herexen's divine gifts have mostly been corrupted into the vileness of undeath, they stubbornly cling to remnants of their former power, still wielding magic and armaments favored by the deity they so greatly despise.

Groups of herexens that blasphemed against the same deity sometimes combine to form a mockery of a congregation, conducting blasphemous rites with something approaching euphoria. These congregations are often formed from a blasphemous cult whose members practiced their heresy together in life and died together, though some gather independent herexens of the same former faith.
