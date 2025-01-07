---
title: "The Chewer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YAgDLBxrPjw9h2So" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "The Chewer"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #197: Let the Leaves Fall"
name: "The Chewer"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +15, Stealth: +14, Monastic Lore: +11"
abilityMods: [5, 4, 2, 1, 4, 2]
speed: 35 feet
sourcebook: "_Pathfinder #197: Let the Leaves Fall_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +16, __Will__ +14"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Temple Sword|+1 Striking Ghost Touch Temple Sword]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 (agile, magical)\n__Damage__  1d6 + 8 bludgeoning plus sagebane 1d4 void plus sagebane"

  - name: "**Melee** `pf2:1` Temple Sword"
    desc: "+18 (magical, monk, trip)\n__Damage__  2d8 + 8 slashing"

  - name: "Black Apoxia"
    desc: " (disease) The target can't recover from the fatigued condition caused by black apoxia until the disease is cured\n\n**Saving Throw** DC 24 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] and [[Conditions/Fatigued|Fatigued]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] and fatigued (1 day)\n\n**Stage 4** dead"

  - name: "Brawling Critical"
    desc: "  When the kurobozu scores a critical hit with an unarmed attack, the target must succeed at a DC 22 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] until the end of its next turn."

  - name: "Sagebane"
    desc: " (occult) When the kurobozu damages a living creature with an unarmed Strike, the target must succeed at a DC 24 Fortitude check save or become [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\nFurther damage dealt by the kurobozu resets the duration to 1 minute and increases the stupefied value by 1 on a failed save, to a maximum of stupefied 4."

  - name: "Steal Breath"
    desc: "`pf2:2` (incapacitation,occult) **Requirements** The kurobozu is adjacent to a living creature that is [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], [[Conditions/Stunned|Stunned]], or [[Conditions/Unconscious|Unconscious]]\n* * *\n\n**Effect** The kurobozu leans over and sucks the breath from the target, who must attempt a DC 22 Fortitude check save. Regardless of the result, the creature is exposed to black apoxia and its breath reeks of carrion for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature can't speak for 1 minute.\n\n**Failure** The creature becomes [[Conditions/Sickened|Sickened 2]] and can't speak for 1 minute.\n\n**Critical Failure** As failure, plus the creature falls [[Conditions/Unconscious|Unconscious]] and begins suffocating."

  - name: "Stunning Flurry"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The kurobozu makes two unarmed Strikes. If both hit the same creature, combine their damage for the purpose of resistances and weaknesses, and the target must succeed at a DC 22 Fortitude check save or be [[Conditions/Stunned|Stunned 1]] (or [[Conditions/Stunned|Stunned 3]] on a critical failure); this save has the incapacitation trait."
 
```

```encounter-table
name: The Chewer
creatures:
  - 1: The Chewer
```


Variant male kurobozu

A monk who violated their monastic vows in life might arise after death to become an undead horror known as a kurobozu. These predators feast upon the breath of mortals, creeping on twisted limbs into bedrooms to steal the life from sleeping victims. This act of feeding leaves its mark on the victim in the form of a vile scent of rot on the victim's breath and a debilitating disease that eventually results in exhaustion and finally death.

Kurobozus retain echoes of their ascetic training, enabling them to suck the breath from debilitated foes in the midst of battle. Their malevolent cunning combined with ascetic discipline helps them concoct elaborate and lengthy schemes to enact their jealous revenge. Few kurobozus are convincing enough to persuade their onetime allies to break their own oaths, but this doesn't stop them from making the attempt.
