---
title: "Voidglutton"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TmK1n5CaG6KqXsMn" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Voidglutton"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Voidglutton"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[air]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Deception: +15, Intimidation: +15, Occultism: +18, Stealth: +18"
abilityMods: [0, 6, 3, 6, 4, 3]
speed:  fly 40 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +13, __Ref__ +18, __Will__ +16"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  magic"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Glow"
    desc: " (aura,light) 30 feet. The tips of a voidglutton's fingers and its seven eyes glow, casting bright light in the area and making it visible if it was [[Conditions/Invisible|Invisible]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile, finesse)\n__Damage__  1d6 + 2 piercing plus fearful-strike 4d6 force plus fearful-strike"

  - name: "**Ranged** `pf2:1` Ectoplasmic Web"
    desc: "+20 (range increment 10 feet)\n__Damage__ "

  - name: "Occult Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Consume Light"
    desc: " (darkness,occult) **Trigger** The voidglutton casts [[Spells/Darkness|Darkness]]\n* * *\n\n**Effect** The voidglutton extinguishes its Glow as part of Casting the Spell. It becomes [[Conditions/Invisible|Invisible]] as long as it remains in the area of darkness. If the voidglutton uses a hostile action, its invisibility ends as soon as the hostile action is completed."

  - name: "Ectoplasmic Web Trap"
    desc: " (occult) A creature hit by the voidglutton's ectoplasmic web trap is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface until it succeeds at a DC 26 check to [[Actions/Escape|Escape]]. Ectoplasmic Web Trap can immobilize incorporeal creatures."

  - name: "Fearful Strike"
    desc: " (emotion,fear,mental,occult) When the voidglutton damages a creature with its claw Strike, the creature must succeed at a DC 26 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure)."

  - name: "Feed on Fear"
    desc: "`pf2:1` (concentrate) **Frequency** once per round\n\n**Requirement** An enemy is affected by a fear effect or has the frightened or dying condition, and is within 25 feet of the voidglutton\n* * *\n\n**Effect** The voidglutton feeds on the creature's terror. It regains 3d4 healing Hit Points and its Glow reignites if it had been extinguished.\n\nIt cannot use Consume Light again for 1d4 rounds, as it is too glutted on fear to suppress its Glow."

  - name: "Magic Immunity"
    desc: "  A voidglutton is immune to all spells except [[Spells/Faerie Fire|Faerie Fire]], [[Spells/Revealing Light|Revealing Light]], [[Spells/Force Barrage|Force Barrage]], [[Spells/Quandary|Quandary]], and spells with the light trait."
 
```

```encounter-table
name: Voidglutton
creatures:
  - 1: Voidglutton
```



A voidglutton is a powerful type of will-o'-wisp that haunts a site where misery dwells-such as a graveyard, prison camp, or recent battlefield. A voidglutton appears as a seething sphere of glowing eyes swirling around an empty black vortex 4 feet wide. From within this vortex extend long, semi-transparent tendrils that end in seven-fingered, needled hands.
