---
title: "Spellscar Sky Marauder"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.T3gZukHdGeh2pK2B" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mutant
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Spellscar Sky Marauder"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #179: Cradle of Quartz"
name: "Spellscar Sky Marauder"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[mutant]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Sphinx"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Arcana: +11, Athletics: +13, Intimidation: +10, Stealth: +13, Spellscar Desert Lore: +13"
abilityMods: [4, 4, 5, 0, 3, -1]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder #179: Cradle of Quartz_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +12, __Ref__ +13, __Will__ +10"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85; __Immunities__  disease; __Resistances__ acid 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Scimitar|Scimitar]]"
abilities_mid:
  - name: ""
  - name: "Acidic Pustules"
    desc: "  The marauder's skin is covered with necrotic boils that burst when struck. Whenever a creature deals slashing or piercing damage to the marauder, each creature within 5 feet takes 2d6 acid damage (DC 22 Reflex check). On a critically failed save, a creature also takes 1d4 persistent acid damage."

  - name: "Runic Resistance"
    desc: "`pf2:r` (arcane) **Trigger** The marauder takes damage from a Strike or spell effect\n* * *\n\n**Effect** The marauder's protective runic tattoos glow, granting them resistance 5 to one damage type dealt by the triggering attack.\n\nThis resistance applies against the triggering effect and lasts for 1 minute or until the marauder uses this ability again, whichever comes first. If the triggering effect deals multiple damage types, the marauder chooses which type to resist.\n\n[[Bestiary Effects/Effect_ Runic Resistance|Effect: Runic Resistance]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+15 (forceful, magical, sweep)\n__Damage__  2d6 + 6 slashing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+15 (agile, finesse)\n__Damage__  2d4 + 6 slashing plus mana-fever"

  - name: "Arcane Innate Spells"
    desc: "DC 22, attack +14; __1st __  _[[Spells/Sanctuary|Sanctuary (x3)]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(3rd)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Mana Fever"
    desc: " (disease) A creature can't remove the fatigued condition while infected\n\n**Saving Throw** DC 22 Fortitude check\n* * *\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Fatigued|Fatigued]] and [[Conditions/Stupefied|Stupefied 1]] (1 day)\n\n**Stage 2** fatigued and [[Conditions/Stupefied|Stupefied 2]] (1 day)\n\n**Stage 3** fatigued and [[Conditions/Stupefied|Stupefied 3]] (1 day)\n\n**Stage 4** gain immunity to mana fever and become a Mana Wastes mutant"

  - name: "Paired Strike"
    desc: "`pf2:2`  **Requirements** The maftet is wielding two scimitars\n* * *\n\n**Effect** The maftet makes two Strikes against the same target, one with each of their scimitars. The maftet combines the damage of any attacks that hit and applies resistances and weaknesses only once. This counts as one attack when calculating the maftet's multiple attack penalty."

  - name: "Powerful Scimitars"
    desc: " (arcane) Any non-magical scimitar becomes a +1 striking scimitar while a spellscar sky marauder wields it."

  - name: "Raptor Dive"
    desc: "`pf2:3`  **Requirements** The marauder is flying at least 10 feet above the target\n* * *\n\n**Effect** The marauder Flies up to twice their fly Speed and makes a Paired Strike at the end of the movement. If both Strikes hit, the target is also knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Spellscar Sky Marauder
creatures:
  - 1: Spellscar Sky Marauder
```


Mana Wastes mutant maftet bandits


