---
title: "Unrisen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wiLtpnKXn8Ed8G45" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Unrisen"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Unrisen"
level: "Creature 11"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Lifesense 30 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Stealth: +19"
abilityMods: [7, 4, 5, -2, 6, 3]
speed: 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +17, __Will__ +21"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, meant to live, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Meant to Live"
    desc: " (occult) Whenever an unrisen would take damage from vitality energy, it instead heals half that number of Hit Points."

  - name: "Resurrection Vulnerability"
    desc: "  A creature with a prepared or spontaneous spell that can restore the dead to life (such as [[Spells/Breath of Life|Breath of Life]] or [[Spells/Raise Dead|Raise Dead]]) can expend an appropriate spell slot as a 2-action activity to destroy an unrisen within 30 feet. The attempt fails if the unrisen succeeds at a Will save against the creature's spell DC."

  - name: "Rise Again"
    desc: " (occult) If the unrisen is reduced to 0 Hit Points by means other than fire damage, disintegration, or its resurrection vulnerability, it returns to unlife at the start of its next turn. It has 100 Hit Points and is [[Conditions/Prone|Prone]] in the space in which it was destroyed. The unrisen can't be returned by this ability again for 1 hour."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (deadly d10, magical)\n__Damage__  3d8 + 13 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, magical)\n__Damage__  2d8 + 13 slashing plus grab"

  - name: "Agonized Howl"
    desc: "`pf2:2` (auditory,mental,occult) The unrisen howls in pain at its cursed existence. Creatures within a 30-foot emanation take 9d8 mental damage (DC 30 Will check). The unrisen can't use Agonized Howl again for 1d4 rounds."

  - name: "Awful Approach"
    desc: "`pf2:1`  The unrisen reshapes its grotesque form to move swiftly. It Strides twice. Any living creature that can see the unrisen during this movement must succeed at a DC 28 Fortitude check save or be [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure). This is a mental and visual effect. The unrisen can't use Awful Approach again for 1d4 rounds."

  - name: "Death Grip"
    desc: "`pf2:1` (curse,occult) **Requirements** The unrisen has a living creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The unrisen attempts to destroy its victim's life force to share the unrisen's fate. The creature must succeed at a DC 30 Fortitude check save or become [[Conditions/Doomed|Doomed 1]]. While the curse lasts, the creature regains only half as many HP from vitality healing effects; if it dies, any attempt to raise it from the dead causes it to return as an unrisen. The curse ends automatically if the creature's doomed value is reduced to 0."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Unrisen
creatures:
  - 1: Unrisen
```



An unrisen is a mangled conglomeration of splintered bones, decaying organs, and rotting flesh, created when a ritual such as resurrect goes catastrophically wrong. Immense care must be taken, for if the ritual is a critical failure, an unrisen can be the result—as many a ritualist has learned to their horror.

Unrisen are barely intelligent, aware only of the agony constantly inflicted by their flawed creation and their resentment for the living. They tend to attack the casters involved in the botched ritual first before lashing out at everyone else around them. Though an unrisen's twisted form is unrecognizable as the intended target of the resurrection, its wordless howls are often disturbingly similar to the deceased's voice. If an unrisen is destroyed before it can rise again, it's reduced to a handful of metallic blue-green salts referred to as essential salts.
