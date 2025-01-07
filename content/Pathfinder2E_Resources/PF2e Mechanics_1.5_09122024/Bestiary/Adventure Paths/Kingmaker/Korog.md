---
title: "Korog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aCJ1NxUN8mVfrRSA" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Korog"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Korog"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision"
languages: "Hallit"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +33, Intimidation: +30, Religion: +29, Survival: +29"
abilityMods: [8, 5, 4, 2, 5, 4]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +27, __Will__ +27"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, void healing, rejuvenation; __Immunities__  death effects,  disease,  electricity,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Maul|+2 Greater Shock Maul]], [[Equipment/Full Plate|+2 Resilient Full Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a graveknight is destroyed, its armor rebuilds its body over the course of 1d10 days-or more quickly if the armor is worn by a living host. If the body is destroyed before then, the process restarts.\n\nA graveknight can only be permanently destroyed by obliterating its armor (such as with [[Spells/Disintegrate|Disintegrate]]), transporting it to the Forge of Creation, or throwing it into the heart of a volcano."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Sacrilegious Aura|Sacrilegious Aura]]"
    desc: " (aura,divine) 30 feet. When a creature in the aura uses a vitality spell or ability, the graveknight automatically attempts to counteract it, with a counteract modifier of +26."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greater Shock Maul"
    desc: "+30 (magical, shove)\n__Damage__  3d12 + 17 bludgeoning 1d6 electricity"

  - name: "Designate Blood Foe"
    desc: "`pf2:1`  Korog declares one creature he can see within 30 feet to be his blood-foe whom he swears to defeat. He can have up to three blood-foes designated at a time; any additional blood-foe removes another blood-foe of Korog's choice. Korog treats the results of Perception checks made against blood-foes as improved by one degree, and he has a +2 circumstance bonus to AC against his blood-foes' attacks."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Devastating Blast|Devastating Blast]]"
    desc: "`pf2:2` (arcane,electricity) The graveknight unleashes a 30-foot cone of energy. Creatures in the area take 9d12 electricity damage (DC 37 Reflex check save). The graveknight can use this ability once every 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Graveknight's Curse|Graveknight's Curse]]"
    desc: " (arcane,curse) This curse affects anyone who wears a graveknight's armor for at least 1 hour.\n\n**Saving Throw** DC 37 Will check save\n* * *\n\n**Onset** 1 hour\n\n**Stage 1** [[Conditions/Doomed|Doomed 1]] and cannot remove the armor (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 2]], the creature's Speed is reduced by 10, and cannot remove the armor (1 day)\n\n**Stage 3** dies and transforms into the armor's graveknight.\n\n[[Bestiary Effects/Effect_ Graveknight's Curse|Effect: Graveknight's Curse]]"

  - name: "Korog's Command"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Korog commands his allies to take an action. All allies who hear or see him are [[Conditions/Quickened|Quickened 1]] for 1 round and can use this extra action to Step, Stride, or make a Strike against one of Korog's blood-foes."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Weapon Master|Weapon Master]]"
    desc: "  The graveknight has access to the critical specialization effects of any weapons it wields."
 
```

```encounter-table
name: Korog
creatures:
  - 1: Korog
```


Variant graveknight

Graveknights are undead warriors granted unlife by a cursed suit of armor.
