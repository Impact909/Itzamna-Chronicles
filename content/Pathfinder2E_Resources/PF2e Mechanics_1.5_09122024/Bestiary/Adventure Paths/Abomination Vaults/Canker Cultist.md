---
title: "Canker Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JnIXF6zXZC8x7b3U" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Canker Cultist"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Canker Cultist"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Aklo, Common, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +10, Intimidation: +10, Occultism: +8, Religion: +8, Stealth: +9"
abilityMods: [4, 3, 1, 1, 3, 3]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +9, __Will__ +12"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x Lump of Decayed Flesh Strung on a Necklace"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  1d8 + 6 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile)\n__Damage__  1d4 + 6 slashing plus ghoul-paralysis"

  - name: "Occult Prepared Spells"
    desc: "DC 20, attack +12; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Phantom Pain|Phantom Pain]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(2nd)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The Canker cultist is adjacent to the corpse of a creature that died within the last hour, or is carrying a specially prepared lump of decaying flesh.\n* * *\n\n**Effect** The Canker cultist devours a chunk of the corpse or the lump of decaying flesh and regains Hit Points. They regain 1d6 healing Hit Points from consuming the flesh of a creature that died within the last hour, and 2d6 healing Hit Points from the lump.\n\nThe cultist can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 20 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a Canker cultist's attack must succeed at a DC 20 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The cultist jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Canker Cultist
creatures:
  - 1: Canker Cultist
```


Ghoul zealot


