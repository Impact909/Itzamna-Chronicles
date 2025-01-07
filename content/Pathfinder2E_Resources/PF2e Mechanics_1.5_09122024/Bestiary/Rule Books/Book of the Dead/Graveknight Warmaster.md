---
title: "Graveknight Warmaster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kPUHdK56UNompTbL" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Graveknight Warmaster"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Graveknight Warmaster"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +28, Deception: +26, Intimidation: +28, Religion: +24, Society: +25, Warfare Lore: +27"
abilityMods: [8, 4, 5, 3, 4, 6]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +27, __Ref__ +24, __Will__ +24"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, void healing, rejuvenation; __Immunities__  death effects,  disease,  electricity,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/War Flail|War Flail]], [[Equipment/Full Plate|+1 Resilient Full Plate]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Hungry Armor"
    desc: "  A creature that Strikes a graveknight warmaster with a melee weapon must succeed at a DC 31 Reflex check save or be disarmed of that weapon. If the creature critically fails, the weapon ends up in the graveknight's space. A creature that hits a graveknight warmaster with an unarmed attack must succeed at a DC 31 Reflex check or become [[Conditions/Grabbed|Grabbed]] by the graveknight until the end of its next turn, it Escapes, or the graveknight moves, whichever comes first."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a graveknight is destroyed, its armor rebuilds its body over the course of 1d10 days-or more quickly if the armor is worn by a living host. If the body is destroyed before then, the process restarts.\n\nA graveknight can only be permanently destroyed by obliterating its armor (such as with [[Spells/Disintegrate|Disintegrate]]), transporting it to the Forge of Creation, or throwing it into the heart of a volcano."

  - name: "Sacrilegious Aura"
    desc: " (aura,divine) 30 feet. When a creature in the aura uses a vitality spell or ability, the graveknight automatically attempts to counteract it, with a +23 counteract modifier."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` War Flail"
    desc: "+29 (disarm, electricity, magical, sweep, trip)\n__Damage__  3d10 + 14 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (agile, electricity, magical, unarmed)\n__Damage__  3d6 + 14 bludgeoning"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+25 (electricity, magical, range increment 120 feet, reload 2)\n__Damage__  3d10 + 6 piercing"

  - name: "[[Creature Family Ability Glossary/(Graveknight) Devastating Blast|Devastating Blast]]"
    desc: "`pf2:2` (arcane,electricity) The graveknight unleashes a 30-foot cone of energy. Creatures in the area take 8d12 electricity damage (DC 34 Reflex check save).\n\nThe graveknight can use this ability once every 1d4 rounds."

  - name: "Exemplar of Violence"
    desc: "`pf2:2` (visual) **Frequency** once per round\n* * *\n\n**Effect** The graveknight attempts a Strike as their armor flashes with sinister power that spurs allies to violence. After the Strike, allies who can see the graveknight can use a reaction to Step or Stride, but they must end this movement in a space adjacent to an enemy. One ally of the graveknight's choice can instead use a reaction to Strike."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Graveknight's Curse|Graveknight's Curse]]"
    desc: " (arcane,curse) This curse affects anyone who wears a graveknight's armor for at least 1 hour.\n\n**Saving Throw** DC 39 Will check save\n* * *\n\n**Onset** 1 hour\n\n**Stage 1** [[Conditions/Doomed|Doomed 1]] and cannot remove the armor (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 2]], the creature's Speed is reduced by 10, and cannot remove the armor (1 day)\n\n**Stage 3** dies and transforms into the armor's graveknight.\n\n[[Bestiary Effects/Effect_ Graveknight's Curse|Effect: Graveknight's Curse]]"

  - name: "[[Creature Family Ability Glossary/(Graveknight) Phantom Mount|Phantom Mount]]"
    desc: "`pf2:3` (arcane,summon) HP 85; AC 34, Fort +23, Ref +20, Will +20\n* * *\n\nThe graveknight summons a supernatural mount as per [[Spells/Marvelous Mount|Marvelous Mount]], heightened to a level equal to half the graveknight's level.\n\nUnlike _phantom steed_, the steed's AC and saving throw bonuses are all 4 lower than the graveknight's, and the steed has one-third the graveknight's Hit Points (rounded down).\n\nIf the steed is destroyed, the graveknight must wait 1 hour before using this ability again."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Ruinous Weapons|Ruinous Weapons]]"
    desc: "  Any weapon or unarmed attack the graveknight uses gains the effects of the _+1 greater striking_ and _[[Equipment/Shock (Greater)|Greater Shock]]_ weapon runes."

  - name: "[[Creature Family Ability Glossary/(Graveknight) Weapon Master|Weapon Master]]"
    desc: "  The graveknight has access to the critical specialization effects of any weapons it wields."
 
```

```encounter-table
name: Graveknight Warmaster
creatures:
  - 1: Graveknight Warmaster
```




