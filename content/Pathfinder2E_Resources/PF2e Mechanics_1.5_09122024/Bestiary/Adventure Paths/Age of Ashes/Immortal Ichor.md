---
title: "Immortal Ichor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V49QwbKoyzSIGIYW" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Immortal Ichor"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Immortal Ichor"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ooze]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Motion Sense (Precise) 60 Feet"
languages: "Aklo, Chthonian, Diabolic, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +30, Religion: +29, Ancient History Lore: +30"
abilityMods: [6, 3, 9, 7, 6, 6]
speed: 20 feet,  fly 20 feet
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +30, __Ref__ +20, __Will__ +29"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350, regeneration 15 (deactivated by holy); __Immunities__  acid,  critical hits,  mental,  precision,  unconscious,  visual; __Resistances__ physical 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Holy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Immortality"
    desc: "  The immortal ichor doesn't age, nor does it need to eat or breathe. It can die only as a result of violence."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+27 ()\n__Damage__  3d8 + 12 bludgeoning plus mental-erosion"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +31; __7th __  _[[Spells/Charm|Charm (x3)]]_, _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Possession|Possession]]_, _[[Spells/Suggestion|Suggestion]]_; __6th __  _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Telekinetic Haul|Telekinetic Haul (At Will)]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_; __2nd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_; __1st __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Command|Command (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Cleric Domain Spells"
    desc: "3 Focus Points, DC 37, attack +31; __8th __  _[[Spells/Cry of Destruction|Cry of Destruction]]_, _[[Spells/Destructive Aura|Destructive Aura]]_"

  - name: "Corrupt Ally"
    desc: " (divine,mental) A creature that fails to save against an immortal ichor's charm spell becomes [[Conditions/Stupefied|Stupefied 1]]. The stupefied value reduces by 1 every 24 hours. The first time each day a creature stupefied by the ichor's charm fails to save against another casting of the ichor's charm, the value of the condition increases by 1d4. If the stupefied condition ever equals the creature's Wisdom score, it becomes controlled by the ichor permanently; if it dies, it rises the next round as a zombie (of the GM's choice) under the ichor's control. If the ichor is killed, these zombies are destroyed."

  - name: "Dead Spells"
    desc: "  An immortal ichor can cast an initial and advanced domain spell of a domain that belonged to the dead deity from which the ichor arose (the domain spells presented here are from the destruction domain)."

  - name: "Mental Erosion"
    desc: "  A creature hit by the ichor's pseudopod is [[Conditions/Stupefied|Stupefied 2]] for 1 day unless it succeeds at a DC 35 Will check save."

  - name: "Resanguinate"
    desc: "`pf2:3` (divine,healing) The immortal ichor draws blood from the pores of living creatures around it. Any living creature within 30 feet that has blood takes 4d6 damage (DC 33 Fortitude check save). The immortal ichor regains HP equal to the total damage dealt. A creature that fails its save is also [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] on a critical failure)."
 
```

```encounter-table
name: Immortal Ichor
creatures:
  - 1: Immortal Ichor
```



An immortal ichor is an intelligent mass of blood from a dead evil deity. The cultists who perform the ritual to create immortal ichor typically seal up the sentient ooze in an underground or remote chamber that blocks its magical abilities, but over time these seals break or weaken, freeing the unholy monster.
