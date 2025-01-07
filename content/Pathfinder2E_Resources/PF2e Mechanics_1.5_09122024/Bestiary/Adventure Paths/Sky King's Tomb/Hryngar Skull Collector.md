---
title: "Hryngar Skull Collector"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.n1MEoig22i2GxNYa" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/hryngar
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Hryngar Skull Collector"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Hryngar Skull Collector"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[hryngar]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Intimidation: +13, Medicine: +10"
abilityMods: [5, 2, 3, -1, 2, 2]
speed: 20 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +12, __Will__ +14"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|+1 Greataxe]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Clothing (Ordinary)|Hood]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+16 (magical, sweep)\n__Damage__  1d12 + 9 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(3rd)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Behead"
    desc: "`pf2:3`  **Requirements** The executioner is adjacent to a dying creature or a creature specifically prepared for a killing blow\n* * *\n\n**Effect** The executioner Strikes the creature with their greataxe. On a hit, in addition to taking damage, the target must attempt a DC 24 Fortitude check save or be reduced to 0 HP and become [[Conditions/Dying|Dying 1]]. If the creature was already dying (including if it was reduced to 0 HP by the Strike's damage), the creature's dying value increases by 1, in addition to any increase from the Strike. On a critical failure, the creature dies instantly.\n\nIf the executioner's Strike was a critical hit, the target uses the outcome for one degree of success worse than the result of their saving throw."

  - name: "Intimidating Strike"
    desc: "`pf2:2` (emotion,fear,fighter,mental) The executioner makes a melee Strike. If it hits and deals damage, the target is [[Conditions/Frightened|Frightened 1]], or [[Conditions/Frightened|Frightened 2]] on a critical hit."

  - name: "Mark for Death"
    desc: "`pf2:1` (concentrate) The executioner marks a single creature they can see for death. The first time each round the executioner Strikes that creature, the Strike deals 1d12 additional precision damage.\n\nThe creature remains marked for death until the executioner is knocked out, marks a different creature for death, or the encounter ends."
 
```

```encounter-table
name: Hryngar Skull Collector
creatures:
  - 1: Hryngar Skull Collector
```


Variant Executioner

Executioners carry out sentences from cruel tyrants and legitimate rulers alike. Most remain numb to the necessity of their duty, but some evil executioners grow to love the power of having someone else's life in their hands.

* * *

Larger societies rely on those with the authority and the ability to interpret and enforce laws. In good-aligned societies, these officials carry out their duties fairly. In neutral and evil ones, these officials can be harsh and cruel (with an altered alignment to reflect this), imposing severe punishments on those who can't pay for mercy.
