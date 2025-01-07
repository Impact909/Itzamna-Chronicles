---
title: "Crawling Hand Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tlsLOPmeASHCCA94" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/swarm
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Crawling Hand Swarm"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Crawling Hand Swarm"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[swarm]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Lifesense 30 Feet, Tremorsense (Imprecise) 30 Feet"
languages: "Common, Hallit; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +12"
abilityMods: [3, 5, 4, -4, 2, 0]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +15, __Will__ +9"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  swarm mind,  unconscious,  visual,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Stifle"
    desc: "`pf2:r`  **Trigger** A creature in the swarm's space attempts to Cast a Spell with a verbal component or attempts an action with the linguistic or vocal traits\n* * *\n\n**Effect** The swarming hands clamp over the triggering creature's mouth, preventing it from vocalizing. The affected creature must succeed at a DC 22 Reflex check save or the triggering action is disrupted."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Pummeling Grasp"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 3d6 slashing damage (DC 20 Reflex check). A creature that fails its save against Pummeling Grasp is also knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Crawling Hand Swarm
creatures:
  - 1: Crawling Hand Swarm
```




