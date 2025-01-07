---
title: "Babau"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8werHuvJlgcvRYZA" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Babau"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Babau"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, See the Unseen"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +13, Intimidation: +14, Religion: +10, Stealth: +16, Thievery: +14"
abilityMods: [4, 4, 4, 2, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +16, __Will__ +11; +1 to all saves vs. magic"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130; __Weaknesses__ cold iron 5, holy 5; __Resistances__ acid 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|+1 Longspear]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Mercy Vulnerability"
    desc: " (mental) Babaus revel in gore, and when wounds are healed, they recoil in pain. When a creature heals from damage that the babau dealt on their last turn with Grievous Strike, sneak attack, or a critical hit, the demon takes 4d6 mental damage. The babau can take this mental damage only once per round."

  - name: "Reactive Slime"
    desc: "`pf2:r`  **Trigger** A creature within the babau's reach successfully hits the babau with a Strike\n* * *\n\n**Effect** The babau excretes a gout of acidic, bloodlike slime against the attacker and its weapon. The attacker must attempt a DC 24 Reflex check save.\n* * *\n\n**Critical Success** The attacker is unaffected.\n\n**Success** The attacker takes 1d6 acid damage.\n\n**Failure** The attacker takes 2d6 acid damage.\n\n**Critical Failure** As failure, except the weapon used to Strike the babau becomes [[Conditions/Broken|Broken]], unless the weapon is made of a material that is immune to acid."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+17 (magical, reach 10 feet, unholy)\n__Damage__  1d8 + 7 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 (magical, unholy)\n__Damage__  1d10 + 7 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, magical, unholy)\n__Damage__  1d4 + 7 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +14; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __2nd __  _[[Spells/Darkness|Darkness]]_\n__Constant__  __(5th)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Grievous Strike"
    desc: "`pf2:2`  The babau attacks with the intent of creating a particularly horrific and gory wound. The babau makes a melee Strike. This counts as two attacks when calculating the demon's multiple attack penalty. If this Strike hits, the babau deals an additional 2d6 damage of the same damage type, and the creature struck is [[Conditions/Frightened|Frightened 2]]."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The babau's Strikes deal an extra 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Babau
creatures:
  - 1: Babau
```



The babau is an assassin, a murderer, and a sadist-certainly not unusual traits, yet their penchant for stealth and surprise sets them apart from their kin. Babaus form from mortal souls of lone killers-those who took pleasure in more personal murders, and particularly those with grisly patterns to their killings.
