---
title: "Urbulinex"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uGGaQcidFwZzfzsa" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Urbulinex"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Urbulinex"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[evil]]
trait_03: [[shadow]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Necril, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +35, Deception: +31, Intimidation: +31, Nature: +28, Religion: +31, Stealth: +30"
abilityMods: [9, 5, 6, 5, 6, 5]
speed: 50 feet,  fly 180 feet
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +31, __Ref__ +29, __Will__ +31; +1 status to all saves vs. magic"
hp: 345
health:
  - name: ""
  - name: HP
    desc: "345, Soul Ward; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep,  unconscious; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Soulsense 60 feet"
    desc: "  A ravener senses the spiritual essence of living and undead creatures within the listed range. Creatures whose material bodies are one unit with their souls, like celestials and fiends, appear brighter to this sense."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Ravener) Cowering Fear|Cowering Fear]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 37 Will check\n\nA ravener's frightful presence causes creatures to cower in fear as well. As long as a creature is at least [[Conditions/Frightened|Frightened 2]] or more as a result of the ravener's frightful presence, it is also [[Conditions/Immobilized|Immobilized]] from the fear.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Creature Family Ability Glossary/(Ravener) Discorporate|Discorporate]]"
    desc: "`pf2:0` (divine) **Trigger** The ravener takes excess damage to their soul ward but still has at least 51 Hit Points in their soul ward\n* * *\n\n**Effect** The ravener draws deeply into their soul ward, discorporating their body into soul energy in order to escape. They take 50 damage to their soul ward and their physical body vanishes, reappearing 1d4 hours later in a random location within 1 mile from the location where they used Discorporate."

  - name: "[[Creature Family Ability Glossary/(Ravener) Soul Ward|Soul Ward]]"
    desc: "  An intangible field of necromantic energy protects a ravener from total destruction. A soul ward has 150 maximum Hit Points.\n\nWhenever a ravener would be reduced below 1 Hit Point, all damage in excess of what would reduce them to 1 Hit Point is instead dealt to their soul ward. If this damage reduces the soul ward to fewer than 0 Hit Points, the ravener is destroyed.\n\nA soul ward's Hit Points can be restored only via specific ravener abilities such as Consume Soul, ravenous breath, or vicious criticals. A ravener who goes more than a week without successfully using Consume Soul to feed on a dying creature starves, and their soul ward loses 1d4 Hit Points each day until they feed. If the ravener's soul ward loses all its Hit Points while the ravener still has more than 1 HP, they become a [[Bestiary 2/Ravener Husk|Ravener Husk]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 15 feet)\n__Damage__  3d10 + 15 piercing 5d6 void"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 15 slashing 2d6 void"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (magical, reach 20 feet)\n__Damage__  3d12 + 15 slashing 2d6 void"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+32 (agile, magical, reach 15 feet)\n__Damage__  2d10 + 15 slashing 2d6 void"

  - name: "Primal Innate Spells"
    desc: "DC 39, attack +31; __8th __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Umbral Journey|Shadow Walk]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Creature Family Ability Glossary/(Ravener) Consume Soul|Consume Soul]]"
    desc: " (death,divine) **Trigger** A living creature within 30 feet of the ravener dies\n* * *\n\n**Effect** The ravener tears the creature's soul from its body with their maw and gulps it down. The dying creature must attempt a DC 44 Fortitude check save with the same DC as the ravener's Breath Weapon.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The ravener tears off a small chunk of the creature's soul. If the victim is restored to life, they are [[Conditions/Drained|Drained 1]] in addition to any other side effects of returning to life. The ravener adds a number of Hit Points to their soul ward equal to half the creature's level.\n\n**Failure** As success, but the creature's soul is ravaged. The creature is [[Conditions/Drained|Drained 3]] and the ravener adds a number of Hit Points to their soul ward equal to the creature's level.\n\n**Critical Failure** As failure, but the ravener devours the entire soul. The victim can't be restored to life as long as the ravener exists except via a 10th-rank effect such as [[Spells/Miracle|Miracle]] or [[Spells/Wish|Wish]], and the ravener adds a number of Hit Points to their soul ward equal to twice the creature's level."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The ravener makes two claw Strikes and one wing Strike in any order."

  - name: "Draconic Momentum"
    desc: "  The ravener recharges their Breath Weapon whenever they score a critical hit with a Strike."

  - name: "Ghost Bane"
    desc: "  The ravener's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune, and the ravener's jaws deal an additional 6d6 force damage to undead."

  - name: "Ravenous Breath Weapon"
    desc: "`pf2:2`  The ravener breathes in one of two ways. With either option, a creature that fails its save is also [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] on a critical failure). If at least one creature is drained by the ravener's Ravenous Breath Weapon, the ravener's soul ward gains 5 healing HP. The ravener can't use Breath Weapon again for 1d4 rounds.\n\n*   **Void** (necromancy, primal, void) The ravener breathes a blast of darkness in a 40-foot cone that deals 17d6 void damage plus 4d6 persistent void damage (DC 39 Reflex check save). Undead creatures take 22d6 force damage instead of the void damage.\n*   **Shadows** (necromancy, primal, shadow) The ravener breathes a blast of shadows in a 40-foot cone. Each creature within the cone must attempt a DC 39 Fortitude check save.\n    \n    **Critical Success** The creature is unaffected.\n    \n    **Success** The creature is [[Conditions/Enfeebled|Enfeebled 2]] for 1 round.\n    \n    **Failure** The creature is enfeebled 2 for 1 minute.\n    \n    **Critical Failure** The creature is enfeebled 2 for 1 minute and [[Conditions/Blinded|Blinded]] for 1 round."

  - name: "[[Creature Family Ability Glossary/(Ravener) Vicious Criticals|Vicious Criticals]]"
    desc: "  The ravener treats an attack roll as a critical hit on a roll of 19 or 20, as long as the attack roll was a success. Additionally, whenever the ravener makes a critical hit with one of their Strikes, the target must succeed at a DC 37 Fortitude check save or gain the [[Conditions/Drained|Drained 1]] condition. If the target already has a drained value of greater than 0, their drained value instead increases by 1, to a maximum of [[Conditions/Drained|Drained 4]]. Whenever the ravener applies drain to a creature in this way, their soul ward gains 5 Hit Points.\n* * *\n\n_Note: A DC was not provided for this ability by Paizo. The DC present here is a moderate DC for the creature level according to the Gamemastery Guide creature building Tables._"
 
```

```encounter-table
name: Urbulinex
creatures:
  - 1: Urbulinex
```


Female adult umbral dragon ravener


