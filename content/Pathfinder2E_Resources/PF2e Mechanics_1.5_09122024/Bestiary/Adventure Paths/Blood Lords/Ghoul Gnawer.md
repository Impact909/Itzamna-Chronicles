---
title: "Ghoul Gnawer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Uyt4JqJy7ItL7Lr0" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Ghoul Gnawer"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Ghoul Gnawer"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ghoul]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Chthonian, Common, Draconic, Kelish, Necril"
skills:
  - name: "Skills"
    desc: "Arcana: +21, Crafting: +21, Deception: +23, Diplomacy: +23, Intimidation: +23, Occultism: +21, Stealth: +19, Kabriri Lore: +21, Secret Eater Lore: +21"
abilityMods: [1, 3, 1, 5, 3, 7]
speed: 30 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +21, __Will__ +24"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Compendium.pf2e.equipment-srd.Item.c40Zn2TCRr3inIBA|Staff of Necromancy]], [[Equipment/Clothing (Ordinary)|Hooded Robe]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 (finesse)\n__Damage__  2d10 + 12 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile, finesse)\n__Damage__  2d8 + 10 slashing plus ghoul-paralysis"

  - name: "**Melee** `pf2:1` Staff"
    desc: "+19 (two-hand d8)\n__Damage__  2d8 + 10 bludgeoning"

  - name: "Occult Spontaneous Spells"
    desc: "DC 34, attack +26; __6th __ (3 slots) _[[Spells/Dominate|Dominate]]_, _[[Spells/Scrying|Scrying]]_, _[[Spells/Spirit Blast|Spirit Blast]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __5th __ (4 slots) _[[Spells/Abyssal Plague|Abyssal Plague]]_, _[[Spells/Invoke Spirits|Invoke Spirits]]_, _[[Spells/Rip the Spirit|Rip the Spirit]]_, _[[Spells/Wall of Flesh|Wall of Flesh]]_; __4th __ (4 slots) _[[Spells/Chroma Leach|Chroma Leach]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Talking Corpse|Talking Corpse]]_\n__Cantrips__  __(6th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Haunting Hymn|Haunting Hymn]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul gnawer is adjacent to the corpse of a creature that died within the last hour\n* * *\n\n**Effect** The ghoul gnawer devours a chunk of the corpse and regains 5d6 healing Hit Points. It can regain Hit Points from any given corpse only once."

  - name: "Drain Corpse"
    desc: "`pf2:r` (occult) **Frequency** once per day\n\n**Trigger** The ghoul gnawer uses Consume Flesh\n* * *\n\n**Effect** In addition to gaining Hit Points, using Consume Flesh refreshes one spell slot the cultist has already expended."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 29 Fortitude check\n\n**Stage 1** carrier with no effect (1 day)\n\n**Stage 2** 3d6 void damage and regains half as many hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a ghoul the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul gnawer's attack must succeed at a DC 27 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. The creature can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghoul Gnawer
creatures:
  - 1: Ghoul Gnawer
```




