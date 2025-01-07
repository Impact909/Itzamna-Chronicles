---
title: "Picture-in-Clouds"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FaYVsep2bl6Fh1NM" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Picture-in-Clouds"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Picture-in-Clouds"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Stealth: +24"
abilityMods: [4, 8, 5, 4, 4, 4]
speed:  fly 100 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +21, __Ref__ +26, __Will__ +19"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Disperse"
    desc: "`pf2:r`  **Trigger** The picture-in-clouds takes damage from a hostile action\n* * *\n\n**Effect** The picture-in-clouds disperses. Until the end of the current turn, they can't be attacked or targeted, they don't take up space, and any auras or emanations they have are suppressed. At the end of the turn, the picture-in-clouds re-forms in any sufficient space within 150 feet of where they dispersed; any auras or emanations they have are restored as long as the duration didn't run out while the elemental was dispersed."

  - name: "High Winds"
    desc: " (air,aura) 60 feet. Air within the emanation is difficult terrain for Flying creatures that don't have the air trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+26 (finesse, reach 20 feet)\n__Damage__  3d10 + 10 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Lightning Lash"
    desc: "+26 (range increment 100 feet)\n__Damage__  3d12 electricity"

  - name: "Cloudgaze"
    desc: "`pf2:1`  The picture-in-clouds shifts into their choice of an eagle shape, elephant shape, or sword shape."

  - name: "Elephant Blast"
    desc: "`pf2:2`  **Requirements** The picture-in-clouds is in elephant shape\n* * *\n\n**Effect** The picture-in-clouds breathes out a 30-foot cone of air from their cloudy trunk. Creatures in the area must attempt a DC 30 Fortitude check save to stand their ground. A creature pushed into a solid object stops moving and takes 4d10 bludgeoning damage.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is pushed 20 feet.\n\n**Failure** The creature is pushed 40 feet.\n\n**Critical Failure** The creature is pushed 40 feet and knocked [[Conditions/Prone|Prone]]."

  - name: "Feather Storm"
    desc: "`pf2:2` (move) **Requirements** The picture-in-clouds is in eagle shape\n* * *\n\n**Effect** The picture-in-clouds Flies 125 feet, flapping their wings and creating a barrier along their path. This barrier has the effects of [[Spells/Wall of Wind|Wall of Wind]] (DC 30 Fortitude check) and lasts until the end of the picture-in-clouds's next turn."

  - name: "Slicing Wind"
    desc: "`pf2:1`  **Requirements** The picture-in-clouds is in sword shape\n* * *\n\n**Effect** The picture-in-clouds spins, forming a whirlwind that deals 5d8 slashing damage in a 15-foot emanation (DC 30 Reflex check save)."

  - name: "Swiftness"
    desc: "  The picture-in-clouds's movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Push|Push 15 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Picture-in-Clouds
creatures:
  - 1: Picture-in-Clouds
```



The shifting shapes of clouds in the sky have captivated the imaginations of mortal children for centuries. Pictures-in-clouds represent this pure possibility of air, transforming into anything the Universe imagines them to be.

* * *

Many elementals that roam the Plane of Air embody the mercurial formlessness and chaos of tumultuous storms.

## Tempestuous Spirits

Air elementals are often flighty contrarians, often more concerned with bringing about change than with the specific changes they enact. Art and writing created by such elementals is exceptionally rare, as they usually destroy their projects once the challenge and excitement of completing them fades.

## Invisible Courtiers

Formless and invisible elementals are the favored children of Hshurha, the air elementals' mother goddess. They receive favorable treatment in her realm, Verglas Precessional, where they serve as trusted advisors, emissaries to other planes, and members of her personal retinue, in addition to performing clandestine tasks the goddess wishes to keep hidden.
