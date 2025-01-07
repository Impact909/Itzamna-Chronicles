---
title: "Ghast Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tjNuN0a6HcyJxDQw" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Ghast Cultist"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Ghast Cultist"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Chthonian, Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +15, Intimidation: +17, Religion: +18"
abilityMods: [4, 4, 2, 2, 5, 4]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +11, __Ref__ +15, __Will__ +18"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Flail|+1 Striking Flail]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol of Kabriri]]"
abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 22 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (finesse)\n__Damage__  2d8 + 10 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile, finesse)\n__Damage__  2d6 + 10 slashing plus ghast-paralysis"

  - name: "**Melee** `pf2:1` Flail"
    desc: "+18 (disarm, magical, sweep, trip)\n__Damage__  2d6 + 10 bludgeoning"

  - name: "Divine Prepared Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Crisis of Faith|Crisis of Faith]]_; __2nd __  _[[Spells/Silence|Silence]]_, _[[Spells/Spiritual Weapon|Spiritual Weapon]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Harm|Harm]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghast is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghast devours a chunk of the corpse and regains 5d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once.\n\nA ghast cultist can also scoop up a handful of maggots to feed upon if they're adjacent to the large bowl in the middle of area **J1**."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease) **Saving Throw** DC 25 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 25 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghast jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghast Cultist
creatures:
  - 1: Ghast Cultist
```


Ghast priest of Kabriri


