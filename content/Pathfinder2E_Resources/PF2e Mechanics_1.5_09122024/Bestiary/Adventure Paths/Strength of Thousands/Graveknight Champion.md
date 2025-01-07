---
title: "Graveknight Champion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9zBgD1dfg7jpxHk0" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Graveknight Champion"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Graveknight Champion"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Intimidation: +29, Religion: +27, <Deity> Lore: +27"
abilityMods: [8, 4, 5, 2, 4, 6]
speed: 25 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +28, __Ref__ +26, __Will__ +25"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275, void healing, rejuvenation; __Immunities__  death effects,  disease,  fire,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|Greater Flaming Composite Shortbow]], [[Equipment/Greatpick|Greater Flaming Greatpick]], [[Equipment/Full Plate|+2 Resilient Full Plate]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Clutching Armor|Clutching Armor]]"
    desc: "`pf2:r` (arcane) **Trigger** A creature attempts to move away from the graveknight\n* * *\n\n**Effect** The graveknight's armor animates and attempts to Grab the triggering creature. It makes an Athletics check to [[Actions/Grapple|Grapple]] using the graveknight's Athletics modifier - 2. The armor can continue to Grapple the creature normally.\n\nSince the armor is grappling the creature, the graveknight doesn't need a free hand to do so."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a graveknight is destroyed, its armor rebuilds its body over the course of 1d10 days-or more quickly if the armor is worn by a living host. If the body is destroyed before then, the process restarts.\n\nA graveknight can only be permanently destroyed by obliterating its armor (such as with [[Spells/Disintegrate|Disintegrate]]), transporting it to the Forge of Creation, or throwing it into the heart of a volcano."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatpick"
    desc: "+31 (fatal d12, fire, magical)\n__Damage__  3d10 + 16 slashing 1d6 fire"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+30 (agile, fire, unarmed)\n__Damage__  3d6 + 16 bludgeoning 1d6 fire"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+28 (deadly d10, fire, magical, range increment 60 feet, reload 0)\n__Damage__  3d6 + 10 piercing 1d6 fire"

  - name: "Innate Divine Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Execute|Finger of Death]]_; __6th __ (2 slots) _[[Spells/Fireball|Fireball]]_, _[[Spells/Blazing Bolt|Scorching Ray]]_; __5th __ (2 slots) _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Flame Strike|Flame Strike]]_; __4th __ (1 slots) _[[Spells/Fireball|Fireball]]_\n__Cantrips__  __(8th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Light|Light]]_, _[[Spells/Shield|Shield]]_"

  - name: "[[Creature Family Ability Glossary/(Graveknight) Channel Magic|Channel Magic]]"
    desc: "`pf2:2`  The graveknight redirects magical energies through its armor, allowing it to deliver magic through an attack.\n\nThe graveknight Casts a Spell that takes 1 or 2 actions to cast and requires a spell attack roll. The effects of the spell don't occur immediately but are imbued into an attack instead. The graveknight then makes a melee Strike with a weapon or unarmed attack. The spell is coupled with the attack, using the attack roll result to determine the effects of both the Strike and the spell.\n\nThis counts as two attacks for the graveknight's multiple attack penalty but doesn't apply the penalty until after it's completed Channeling Magic.\n\nThe graveknight can't use Channel Magic again for 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Devastating Blast|Devastating Blast]]"
    desc: "`pf2:2` (arcane) The graveknight unleashes a 30-foot cone of energy. Creatures in the area take 8d12 fire damage (DC 36 Reflex check save).\n\nThe graveknight can use this ability once every 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Graveknight's Curse|Graveknight's Curse]]"
    desc: " (arcane,curse) This curse affects anyone who wears a graveknight's armor for at least 1 hour.\n* * *\n\n**Saving Throw** DC 36 Will check save\n\n**Onset** 1 hour\n\n**Stage 1** [[Conditions/Doomed|Doomed 1]] and cannot remove the armor (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 2]], speed penalty of -10 feet, and cannot remove the armor (1 day)\n\n**Stage 3** dies and transforms into the armor's graveknight."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Weapon Master|Weapon Master]]"
    desc: "  The graveknight has access to the critical specialization effects of any weapons it wields."
 
```

```encounter-table
name: Graveknight Champion
creatures:
  - 1: Graveknight Champion
```




