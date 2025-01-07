---
title: "Elder Outcrop"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JQZ30pmnGU6BNn6o" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Elder Outcrop"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Elder Outcrop"
level: "Creature 13"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: "Common, Fey, Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +29, Diplomacy: +25, Nature: +26, Survival: +26"
abilityMods: [8, -2, 8, 1, 5, 4]
speed: 30 feet,  burrow 30 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +29, __Ref__ +19, __Will__ +26"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Dust Eternal"
    desc: " (aura,earth) 30 feet. Dust swirls about the outcrop, rendering everything within its aura (including the outcrop) [[Conditions/Concealed|Concealed]]. In addition, the dust at the outcrop's base creates difficult terrain on the ground within the aura. The outcrop can activate or deactivate this aura using a single action, which has the concentrate trait."

  - name: "Unstoppable"
    desc: "  The elder outcrop's slowed condition can't exceed [[Conditions/Slowed|Slowed 1]], and it ignores penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Column"
    desc: "+27 (reach 15 feet)\n__Damage__  3d10 + 14 bludgeoning plus knockdown"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+27 (brutal, range increment 120 feet)\n__Damage__  3d6 + 14 bludgeoning plus call-of-earth"

  - name: "Call of Earth"
    desc: " (primal) A flying creature hit by the elder outcrop's rock ranged strike is affected by a 7th-rank [[Spells/Earthbind|Earthbind]] spell (DC 33 Fortitude check)."

  - name: "Earth Glide"
    desc: "  The elder outcrop can Burrow through any earthen matter, including rock. When it does so, the elder outcrop moves at its full burrow Speed, leaving no tunnels or signs of its passing."

  - name: "Natural Formation"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the elder outcrop appears to be a natural terrain feature. It has an automatic result of 47 on Deception checks and DCs to pass as a natural outcropping of rock. The outcrop's dust eternal aura is deactivated while Natural Formation is being used."

  - name: "Stone Grip"
    desc: "`pf2:1` (earth,incapacitation,primal) Great fingers of stone arise to grasp up to two Medium or smaller creatures on the ground in the outcrop's aura. Each target must succeed at a DC 33 Reflex check save or be [[Conditions/Grabbed|Grabbed]] by the stone hand (or [[Conditions/Restrained|Restrained]] on a critical failure; [[Actions/Escape|Escape]] DC 33). A creature grabbed or restrained by a stone hand at the end of its turn becomes [[Conditions/Slowed|Slowed 1]] or increases its existing slowed condition by 1. When a creature is unable to act due to the slowed condition from this effect, the creature is permanently petrified."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Elder Outcrop
creatures:
  - 1: Elder Outcrop
```



An outcrop of dense stone that spends ages eroding can gain sapience and slowly awaken with the wisdom of nature. Such elemental beings are slow to action and difficult to anger, spurred only by immediate threats.

* * *

The vast ranks of earth elementals have been slow to respond to the return of the elemental lords and the Planes of Metal and Wood. These events have not broken the mountains, nor have they blown away the sands.

## Earthy Emotions

Earth elementals talk even less than most elementals. They're ponderous, weighing decisions so slowly they can crush the energy from a discussion. Their foremost concern is whether a situation can be endured. Though a rare or resplendent treasure might entice an earth elemental, it's difficult to spur any sense of urgency in them without the presence of an immediate threat.

## Wisdom Of Stone

Elder outcrops learn a lesson for every grain of rock eroded away, every squall and freeze that has shaped their craggy bodies. As wizened advisors and tutors, they have the respect and affection of other elementals, as well as from natural creatures. Druids of the stone order revere the wisdom of elder outcrops, always happy to receive their wide perspective, literal and philosophical.
