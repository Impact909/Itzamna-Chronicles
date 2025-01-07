---
title: "Glorkus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6kAx0PNsLlWIcwmT" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Glorkus"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Glorkus"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Goblin, Necril"
skills:
  - name: "Skills"
    desc: "Occultism: +9, Religion: +10, Society: +7, Stealth: +10, Survival: +10"
abilityMods: [2, 4, 2, 1, 4, 3]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +10, __Will__ +12"
hp: 59
health:
  - name: ""
  - name: HP
    desc: "59, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Leather Armor|Leather Armor]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol (Bone)]], [[Equipment/Magic Wand (1st-Rank Spell)|Wand of Fear (Rank 1)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (finesse)\n__Damage__  1d6 + 2 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile, finesse)\n__Damage__  1d4 + 2 slashing plus ghoul-paralysis"

  - name: "Divine Prepared Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Noise Blast|Noise Blast]]_, _[[Spells/Spiritual Weapon|Spiritual Weapon]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Sanctuary|Sanctuary]]_\n__Cantrips__  __(2nd)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Cleric Domain Spells"
    desc: "1 Focus Point, DC 21, attack +13; __2nd __  _[[Spells/Touch of Undeath|Touch of Undeath]]_"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 3d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 21 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 21 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Glorkus
creatures:
  - 1: Glorkus
```


Male goblin ghoul cleric of Kabriri

Ghouls are ravenous undead who haunt graveyards and eat corpses.

* * *

Few creatures are more ubiquitous to sinister locations such as lonely graveyards and ruined crypts than the flesh-eating undead known as ghouls.
