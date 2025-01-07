---
title: "Onryo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oLUHpWpJ2ksESJpQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Onryo"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Onryo"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +20, Stealth: +25, Survival: +23"
abilityMods: [2, 7, 5, 2, 5, 6]
speed: 35 feet,  climb 35 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +21, __Ref__ +23, __Will__ +23; +1 status to all saves vs. magic"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ all damage 8 (except force)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile, finesse)\n__Damage__  3d8 + 8 slashing 2d6 mental"

  - name: "Occult Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Nightmare|Nightmare]]_\n__Constant__  __(4th)__ _[[Spells/Flicker|Blink]]_, _[[Spells/Gecko Grip|Spider Climb]]_, _[[Spells/Water Walk|Water Walk]]_"

  - name: "Flicker"
    desc: "  An onryo's erratic movement makes them difficult to target. If an onryo moves at least 10 feet during a move action, they gain [[Conditions/Concealed|Concealment]] until the start of their next turn."

  - name: "Onryo's Rancor"
    desc: "`pf2:1` (curse,mental,occult) **Requirements** The onryo's last action was a successful claw Strike\n* * *\n\n**Effect** The onryo attempts to instill its need for vengeance into the creature. The onryo, with their touch, casts a 5th-rank [[Spells/Geas|Geas]] on the creature they hit (DC 30 Will check). On a failure, it's forced to seek and slay loved ones of the onryo's wrongdoer and anyone who attempts to defend them for up to one week. On a critical failure, the duration is 1 month and the creature gains Onryo's Rancor, which it's also compelled to use by the geas. Regardless of the outcome, the creature is temporarily immune to Onryo's Rancor from this individual for 1 year."

  - name: "Vengeful Suffocation"
    desc: "`pf2:2` (incapacitation,occult) **Frequency** once per hour\n* * *\n\n**Effect** The onryo channels their boundless resentment, manifesting it as a tangled clump of wet hair, a clot of rancid swamp mud, or other disgusting mass of matter in the throat of a creature within 30 feet. The creature must attempt a DC 32 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature becomes [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature becomes [[Conditions/Sickened|Sickened 3]] and the mass fully blocks the creature's airway. The creature begins suffocating."
 
```

```encounter-table
name: Onryo
creatures:
  - 1: Onryo
```



Onryos are created when a person dies violently in the grip of extreme emotion, such as unbridled rage or overwhelming sorrow. These twisted undead return as beings of pure vengeance, seeking to endlessly spread suffering. Onryos torment those who killed them, but not by directly attacking their murderer. Instead, an onryo hunts down the friends, family members, and anyone connected to their foe. In doing so, the onryo inflicts as much torment as possible on the person responsible for their demise. An onryo's vengeful nature persists indefinitely; not even the death of their killer sates their lust for destruction. Vengeance is just a way for them to spread their pain to others, and they quickly find new targets for their ire. Onryos always wear funeral clothing, often dripping wet or covered in filth. Most of them also display wounds or signs indicating how they died. As they move, onryos seem to pop in and out of existence, making them difficult to track in combat.
