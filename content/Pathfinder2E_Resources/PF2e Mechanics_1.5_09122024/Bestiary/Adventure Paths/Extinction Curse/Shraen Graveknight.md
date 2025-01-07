---
title: "Shraen Graveknight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xufU81MfwttWCI0R" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Shraen Graveknight"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Shraen Graveknight"
level: "Creature 15"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Elven, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Intimidation: +27, Religion: +24, Stealth: +27"
abilityMods: [4, 8, 4, 2, 3, 6]
speed: 30 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +25, __Ref__ +27, __Will__ +26; +1 status bonus to all saves vs. magic effects, +2 status bonus to all saves vs. mental effects"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, void healing, rejuvenation; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  sleep,  unconscious; __Resistances__ vitality 30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Main-Gauche|Main-Gauche]], [[Equipment/Rapier|Rapier]], [[Equipment/Elven Chain (Standard-Grade)|Elven Chain (Standard-Grade)]], 10x [[Equipment/Bolts|Bolts]], 2x [[Equipment/Cave Worm Venom|Purple Worm Venom]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a graveknight is destroyed, its armor rebuilds its body over the course of 1d10 days-or more quickly if the armor is worn by a living host. If the body is destroyed before then, the process restarts.\n\nA graveknight can only be permanently destroyed by obliterating its armor (such as with [[Spells/Disintegrate|Disintegrate]]), transporting it to the Forge of Creation, or throwing it into the heart of a volcano."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Sacrilegious Aura|Sacrilegious Aura]]"
    desc: " (aura,divine) 30 feet. When a creature in the aura uses a vitality spell or ability, the graveknight automatically attempts to counteract it, with a counteract modifier of +24."

  - name: "Status Bonus to Saves"
    desc: "  +1 status bonus to all saves vs. magic effects.\n\n+2 status bonus to all saves vs. mental effects."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greater Frost Rapier"
    desc: "+31 (cold, deadly 2d8, disarm, finesse, magical)\n__Damage__  3d6 + 14 piercing"

  - name: "**Melee** `pf2:1` Greater Frost Main-Gauche"
    desc: "+31 (agile, cold, disarm, finesse, magical, parry, versatile s)\n__Damage__  3d4 + 14 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (agile, cold, unarmed)\n__Damage__  3d6 + 10 piercing 1d6 cold"

  - name: "**Ranged** `pf2:1` Greater Frost Hand Crossbow"
    desc: "+31 (cold, magical, range increment 60 feet, reload 1)\n__Damage__  3d6 + 14 piercing plus purple-worm-venom"

  - name: "Divine Innate Spells"
    desc: "DC 36, attack +28; __4th __  _[[Spells/Darkness|Darkness (At Will)]]_; __2nd __  _[[Spells/Faerie Fire|Faerie Fire (At Will)]]_\n__Cantrips__  __(6th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "[[Creature Family Ability Glossary/(Graveknight) Devastating Blast|Devastating Blast]]"
    desc: "`pf2:2` (arcane,cold) The graveknight unleashes a 30-foot cone of energy. Creatures in the area take 8d12 cold damage (DC 36 Reflex check save).\n\nThe graveknight can use this ability once every 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Graveknight's Curse|Graveknight's Curse]]"
    desc: " (arcane,curse) This curse affects anyone who wears a graveknight's armor for at least 1 hour.\n\n**Saving Throw** DC 36 Will check save\n* * *\n\n**Onset** 1 hour\n\n**Stage 1** [[Conditions/Doomed|Doomed 1]] and cannot remove the armor (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 2]], the creature's Speed is reduced by 10, and cannot remove the armor (1 day)\n\n**Stage 3** dies and transforms into the armor's graveknight.\n\n[[Bestiary Effects/Effect_ Graveknight's Curse|Effect: Graveknight's Curse]]"

  - name: "Heart-Seeking Strike"
    desc: "`pf2:3`  The Shraen graveknight Steps once then Strikes with its rapier. A creature damaged by the attack must attempt a DC 36 Fortitude check save. On a failure, the creature takes 4d6 bleed. On a critical failure, the attack pierces the creature's heart, and the creature dies."

  - name: "Quick Draw"
    desc: "`pf2:1`  The Shraen graveknight draws a weapon, then Strikes with it."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Ruinous Weapons|Ruinous Weapons]]"
    desc: "  At the time of its creation, a graveknight chooses one of the following energy types that was relevant to its life or death: acid, cold, electricity, or fire.\n\nAny weapon the graveknight wields gains the effects of the _caustic_, _frost_, _shock_, or _flaming_ weapon rune, respectively, in addition to a _+1 striking weapon_ rune.\n\nIf the graveknight is 14th level or higher, its weapons instead gain the effects of the greater versions of both of these runes."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Weapon Master|Weapon Master]]"
    desc: "  The graveknight has access to the critical specialization effects of any weapons it wields."
 
```

```encounter-table
name: Shraen Graveknight
creatures:
  - 1: Shraen Graveknight
```


Drow graveknight


