---
title: "Graveknight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.I0J5DTVSBxpnKqdY" 
tags:
  - pf2e/creature/type/graveknight
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Graveknight"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Graveknight"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[graveknight]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +22, Religion: +19, Warfare Lore: +20"
abilityMods: [7, 4, 4, 2, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +19, __Will__ +18"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, rejuvenation, void healing; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Greatsword|Greatsword]], [[Equipment/Full Plate|+1 Resilient Full Plate]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a graveknight is destroyed, their armor rebuilds their body over the course of 1d10 days—or more quickly if the armor is worn by a living host. If the body is destroyed before then, the process restarts.\n\nA graveknight can only be permanently destroyed by obliterating their armor (such as with [[Spells/Disintegrate|Disintegrate]]), transporting it to the Forge of Creation, or throwing it into the heart of a volcano."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Sacrilegious Aura|Sacrilegious Aura]]"
    desc: " (aura,divine,void) 30 feet.\n\nWhen a creature in the aura uses a vitality spell or ability, the graveknight automatically attempts to counteract it, with a counteract modifier of +17."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Frost Greatsword"
    desc: "+24 (cold, magical, versatile p)\n__Damage__  2d12 + 10 slashing 1d6 cold"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (agile, cold)\n__Damage__  2d6 + 10 bludgeoning 1d6 cold"

  - name: "**Ranged** `pf2:1` Frost Composite Longbow"
    desc: "+21 (cold, deadly d10, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  2d8 + 6 piercing 1d6 cold"

  - name: "[[Creature Family Ability Glossary/(Graveknight) Devastating Blast|Devastating Blast]]"
    desc: "`pf2:2` (arcane,cold) The graveknight unleashes a 30-foot cone of energy. Creatures in the area take 11d6 cold with a DC 29 Reflex check.\n\nThe graveknight can use this ability once every 1d4 rounds."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Graveknight's Curse|Graveknight's Curse]]"
    desc: " (arcane,curse) This curse affects anyone who wears a graveknight's armor for at least 1 hour\n\n**Saving Throw** DC 33 Will check save\n\n**Onset** 1 hour\n\n**Stage 1** [[Conditions/Doomed|Doomed 1]] and can't remove armor (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 2]], –10-foot status penalty to Speeds, and can't remove armor (1 day)\n\n**Stage 3** dies and transforms into the armor's graveknight."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Phantom Mount|Phantom Mount]]"
    desc: "`pf2:3` (arcane,summon) HP 58; AC 27, Fort +17, Ref +15, Will +14\n* * *\n\nThe graveknight summons a supernatural mount, as [[Spells/Marvelous Mount|Marvelous Mount]] heightened to a rank equal to half the graveknight's level. Unlike _marvelous mount_, the steed's AC and saving throw bonuses are all 4 lower than the graveknight's, and the steed has one-third the graveknight's Hit Points (rounded down).\n\nIf the steed is destroyed, the graveknight must wait 1 hour before using this ability again."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Weapon Master|Weapon Master]]"
    desc: "  The graveknight has access to the critical specialization effects of any weapons it wields."
 
```

```encounter-table
name: Graveknight
creatures:
  - 1: Graveknight
```



Graveknights are undead warriors granted unlife by a cursed suit of armor.
