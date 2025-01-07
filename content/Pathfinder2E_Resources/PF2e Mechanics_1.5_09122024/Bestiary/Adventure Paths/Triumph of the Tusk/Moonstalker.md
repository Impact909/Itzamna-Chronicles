---
title: "Moonstalker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CeTYiTLFdbh1ORlr" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Moonstalker"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Moonstalker"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Orcish, Shoanti"
skills:
  - name: "Skills"
    desc: "Medicine: +15, Nature: +15, Stealth: +17, Survival: +17, Shadefields Lore: +130"
abilityMods: [-5, 6, 0, 2, 6, 2]
speed:  fly 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 25
armorclass:
  - name: AC
    desc: "25 (27 in moonlight); __Fort__ +10, __Ref__ +18, __Will__ +16"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, rejuvenation, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 9 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  The moonstalker can stray no more than 120 feet from the hunting grounds where it was slain."

abilities_mid:
  - name: ""
  - name: "Cover of Night"
    desc: "  A moonstalker in an area illuminated by moonlight gains a +2 status bonus to AC and Stealth checks. In the light of a full moon, they are [[Conditions/Concealed|Concealed]]."

  - name: "Lunar Shift"
    desc: "`pf2:r`  **Trigger** The moonstalker is hit by a Strike\n\n**Requirements** The moonstalker is in an area illuminated by moonlight\n* * *\n\n**Effect** The moonstalker teleports through a beam of moonlight to another moonlit space within 120 feet. This does not trigger reactions."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Slaying the moonstalker's prey from their final hunt allows them to move on to the afterlife.\n* * *\n\nWhen a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Shortsword"
    desc: "+18 (agile, finesse, magical)\n__Damage__  2d6 + 6 void"

  - name: "**Ranged** `pf2:1` Ghostly Composite Longbow"
    desc: "+18 (agile, deadly d10, finesse, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  2d8 + 11 void"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __2nd __  _[[Spells/Mist|Mist]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Fear|Fear]]_"

  - name: "[[Creature Family Ability Glossary/(Ghost) Corrupting Gaze|Corrupting Gaze]]"
    desc: "`pf2:2`  The moonstalker stares at a creature it can see within 30 feet. The target takes 4d6 void damage (DC 25 Will check save). A creature that fails its save is also [[Conditions/Stupefied|Stupefied 1]] for 1 minute."

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) The moonstalker designates a single creature they can see and hear, or one they're Tracking, as their prey. The moonstalker gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] the prey and to Survival checks to [[Actions/Track|Track]] the prey. The first time the moonstalker hits the designated prey in a round, they deal an additional 1d8 precision damage. The moonstalker also ignores the penalty for making ranged attacks within their second range increment. These effects last until the moonstalker uses Hunt Prey again."

  - name: "Soul Pierce"
    desc: "`pf2:2` (divine,void) The moonstalker infuses soul-rending energy into a spectral arrow, making a ghostly composite longbow Strike with a –2 circumstance penalty against each creature in a 100-foot line."
 
```

```encounter-table
name: Moonstalker
creatures:
  - 1: Moonstalker
```



The most tenacious hunters of the Lyrune-Quah track and kill nocturnal beasts under the light of the moon. When such a warrior perishes during the hunt, sometimes their spirit lingers and transforms into a specter of the night, refusing to move on until their prey is slain.

## Loyal in Death

Though moonstalkers retain few memories of life, their connections to their quah resonate with them even after their demise. Moonstalkers have been seen protecting living Shoanti warriors who make camp within their hunting grounds, especially warbands that show reverence for the hunt. Outsiders are rarely, if ever, extended the same courtesy.
