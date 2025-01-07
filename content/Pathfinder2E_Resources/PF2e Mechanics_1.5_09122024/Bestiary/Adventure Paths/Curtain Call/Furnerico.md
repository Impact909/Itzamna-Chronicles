---
title: "Furnerico"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.22pV3IddDeB89RAI" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Furnerico"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Furnerico"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +28, Stealth: +25"
abilityMods: [8, 5, 8, -4, 4, -3]
speed: 15 feet,  climb 30 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +28, __Ref__ +23, __Will__ +24"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Immunities__  acid,  disease; __Weaknesses__ slashing 15; __Resistances__ bludgeoning 15, piercing 15, poison 15"
abilities_top:
  - name: ""

  - name: "Fetid Aura"
    desc: " (aura,olfactory) 80 feet. A creature entering or beginning its turn in a furnerico's fetid aura must succeed at a DC 31 Fortitude check or be [[Conditions/Sickened|Sickened 1]]; the creature also becomes [[Conditions/Enfeebled|Enfeebled 1]] until the end of their next turn. A creature that succeeds at its save is temporarily immune to all furnerico fetid auras for 1 minute."

  - name: "Hydrophobic"
    desc: "  A furnerico avoids water and won't willingly approach within five feet of a body of water. It won't initiate an attack against any creature that's soaking wet with water or that has the water trait. A furnerico takes a –2 circumstance penalty to its attack rolls against such creatures who attack it."

  - name: "Susceptible to Water"
    desc: "  A furnerico cleansed of filth becomes sluggish. If ever immersed fully in pure, clean water, or if it ever fails a saving throw against a water effect, the furnerico becomes [[Conditions/Slowed|Slowed 1]] until it starts its turn in an area of filth or contaminated water."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+28 (reach 10 feet)\n__Damage__  3d12 + 14 bludgeoning"

  - name: "**Ranged** `pf2:1` Acidic Slime"
    desc: "+25 (range 60 feet)\n__Damage__  3d6 acid 4d6 acid"

  - name: "Feast on Illness"
    desc: "`pf2:1` (occult) **Requirements** The furnerico's last action was a successful pseudopod Strike against a creature with the [[Conditions/Sickened|Sickened]] condition\n* * *\n\n**Effect** The furnerico feeds off the sweet sickness of the creature, gaining 30 temporary hit points for 1 minute."

  - name: "Sticky Slime"
    desc: "  A creature that's critically hit by a furnerico's acidic slime becomes [[Conditions/Immobilized|Immobilized]] until they [[Actions/Escape|Escape]] (DC 34) or 1 minute passes, after which the slime dissolves."
 
```

```encounter-table
name: Furnerico
creatures:
  - 1: Furnerico
```



A mass of undulating tendrils and nerves, furnericos stalk sewer systems below large cities, reveling in the filth and rotting detritus created by those who dwell above the middens and sumps they call home. Fortunately for sanitation workers and other civil servants who ply their trade in sewer tunnels, furnericos are exceedingly rare and solitary. Their power is such that once one moves into a sewer system, it's often easier for urban planners to simply abandon that section to the monster and rebuild around it. A furnerico left to its domain like this is generally content to remain—as long as the filth keeps flowing.

Furnericos are asexual, spawning a single offspring as they expire from natural causes. One that dies by violence does not perpetuate its kind, presenting a vexing question to sages: where do these creatures come from, and why haven't they gone extinct over the ages?

## Cultist Creations

The answer to "where are furnericos from?" is known by only a few, for it lies with the faithful of the parasite god Ghlaunder. These cultists use obscure rites to create furnericos from the very filth the monsters wallow in. Ghlaunder worshippers often do so to create powerful guardians for their hidden temples; furnericos created in this manner instinctively treat worshippers of Ghlaunder as allies... a trait not shared by those born from a prior furnerico, and a lesson many Ghlaunder cultists only learn moments before their death after assuming otherwise from a furnerico found in the wild.
