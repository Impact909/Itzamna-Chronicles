---
title: "Tormented (Starvation)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VSEcxkqPF0vrZsKL" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Tormented (Starvation)"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Tormented (Starvation)"
level: "Creature 14"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Lifesense 60 Feet"
languages: "Aklo, Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +26, Intimidation: +28, Stealth: +24"
abilityMods: [6, 4, 4, -1, 5, 8]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +22, __Ref__ +26, __Will__ +27"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250, void healing, regeneration 10 (deactivated by cold); __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Endless Suffering"
    desc: "  The tormented starved to death, denied food until the end."

  - name: "Tortured Gaze"
    desc: " (aura,divine,illusion,mental) 30 foot or 60 foot if the tormented is at 125 HP or lower.\n\nThe psychic agony of a tormented spills into the world around them, inflicting murderous hallucinations replicating the tormented's last moments. A non-undead creature that ends its turn in the aura must succeed at a DC 32 Will check save or for 1 minute, the creature is [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Fatigued|Fatigued]]. While it has a condition from Tortured Gaze, a creature can't gain a new condition from the aura but can take damage from it again."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Painful Touch"
    desc: "+28 (agile, finesse, magical)\n__Damage__  4d6 + 14 mental 2d6 mental"

  - name: "Scream in Agony"
    desc: "`pf2:2` (auditory,divine,mental) Each creature in the tormented's Tortured Gaze aura takes 14d6 mental damage (DC 34 Will check). A creature that fails is also [[Conditions/Sickened|Sickened 1]] (or [[Conditions/Sickened|Sickened 2]] on a critical failure).\n\nThe tormented can't Scream in Agony again for 1d4 rounds, but recharges the ability whenever they take damage from an attacker's critical hit or their own critical failure on a saving throw."
 
```

```encounter-table
name: Tormented (Starvation)
creatures:
  - 1: Tormented (Starvation)
```



Twisted caricatures of living beings, tormented arise from the remains of those who've been tortured to death. They appear as the mortals they were in life, horribly disfigured by acts of cruelty. Unable to rest, they haunt the sites of their deaths, doomed to relive their last moments of agony. The toxic psychic residue of their death is so great it spills over, afflicting anyone who meets the tormented's haunted gaze.
