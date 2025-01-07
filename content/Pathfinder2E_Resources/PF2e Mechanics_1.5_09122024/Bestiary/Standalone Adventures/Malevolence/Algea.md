---
title: "Algea"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.N1D96EQBipkiPqoi" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Algea"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Algea"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
trait_03: [[swarm]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Lifesense 60 Feet"
languages: "Aklo, Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Occultism: +21, Religion: +20, Stealth: +22, Boneyard Lore: +21"
abilityMods: [-1, 7, 5, 2, 5, 3]
speed: 15 feet,  fly 40 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +18, __Ref__ +24, __Will__ +22; +1 status bonus to all saves vs. magic"
hp: 144
health:
  - name: ""
  - name: HP
    desc: "144; __Immunities__  precision,  death effects,  disease,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 10, void 10, piercing 10, poison 10, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "See Magic"
    desc: "  An algea can see magic auras on creatures or objects that it can observe; it can't see magic auras on creatures or objects that are hidden from its view. It learns the schools of magic for all spells affecting creatures."

abilities_mid:
  - name: ""
  - name: "Grieving Aura"
    desc: " (aura,divine,emotion,mental) 30 feet. A creature that begins its turn in the aura must attempt a DC 27 Will check save. Undead take a -2 circumstance penalty to this saving throw. The creature is then temporarily immune to the grieving aura for 1 hour.\n\n**Success** The creature is unaffected.\n\n**Failure** For 1 round, the creature can't use reactions and is [[Conditions/Slowed|Slowed 1]] for that turn as it sobs uncontrollably.\n\n**Critical Failure** As failure, but the effects lasts while the creature remains in the aura plus 1 minute."

attacks:
  - name: ""

  - name: "Innate Divine Spells"
    desc: "DC 30, attack +22; __7th __ (1 slots) _[[Spells/Interplanar Teleport|Plane Shift (Self and soul caged creatures only, to the Boneyard only)]]_; __4th __ (2 slots) _[[Spells/Confusion|Confusion]]_, _[[Spells/Talking Corpse|Talking Corpse]]_; __2nd __ (1 slots) _[[Spells/Invisibility|Invisibility]]_"

  - name: "Rituals"
    desc: "_Call Spirit_"

  - name: "Drain Magic"
    desc: " (divine) Whenever a creature fails its save against Frenzied Beaks, the algea attempts to counter a spell effect active on that creature (6th level, counteract check +22). The algea can choose which effect to attempt to counteract for each creature."

  - name: "Frenzied Beaks"
    desc: "`pf2:1`  Each foe in the swarm's space takes 5d6 piercing damage (DC 30 Reflex check) and is exposed to drain magic. This damage affects incorporeal creatures as if it had the effects of a ghost touch property rune."

  - name: "Soul Cage"
    desc: " (divine,incapacitation) An incorporeal undead damaged by Frenzied Beaks must attempt a DC 30 Will check save.\n* * *\n\n**Critical Success** The undead is unaffected and is temporarily immune for 24 hours.\n\n**Success** The undead takes a -10-foot status penalty to Speeds for 1 round.\n\n**Failure** As success, but the undead is also [[Conditions/Immobilized|Immobilized]] for 1 round, although it can attempt to Escape (DC 30).\n\n**Critical Failure** The undead is restrained for 1 round. The algea can attempt to plane shift with the [[Conditions/Restrained|Restrained]] creature even if that creature isn't willing, but an unwilling creature can attempt a Will save to resist [[Spells/Interplanar Teleport|Interplanar Teleport]]. If it succeeds, the algea plane shifts and leaves the incorporeal creature behind, which is then no longer restrained."
 
```

```encounter-table
name: Algea
creatures:
  - 1: Algea
```



Algeas protect (and sometimes retrieve) souls at risk of being claimed by other entities, particularly spellcasters who dabbled with otherworldly forces but never officially pledged their souls.
