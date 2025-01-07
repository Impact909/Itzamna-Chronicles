---
title: "Ximtal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7cA6dpK5uQmiOHYY" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/sahkil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Ximtal"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Ximtal"
level: "Creature 17"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[sahkil]]
trait_04: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Deception: +33, Intimidation: +33, Occultism: +27, Religion: +30, Stealth: +28"
abilityMods: [9, 3, 9, 2, 5, 8]
speed: 40 feet,  climb 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +32, __Ref__ +26, __Will__ +28"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380; __Immunities__  fear effects; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Easy to Call"
    desc: "  A ximtal's level is considered 2 lower for the purpose of being conjured by the [[Spells/Binding Circle|Binding Circle]] ritual (and potentially other rituals, at the GM's discretion), but it is always free to attack or leave instead of negotiate unless the primary caster's check is a critical success."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Despoiler"
    desc: " (aura,divine) 1000 feet. Creatures within the aura take a -2 circumstance penalty to all saving throws against poisons, diseases, and drugs.\n\n[[Bestiary Effects/Effect_ Despoiler|Effect: Despoiler]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 10 feet, unholy)\n__Damage__  3d12 + 17 piercing plus sensory-fever 2d6 spirit plus sensory-fever"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 17 slashing plus sensory-fever 2d6 spirit plus sensory-fever"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __8th __  _[[Spells/Fear|Fear (At Will)]]_, _[[Spells/Desiccate|Horrid Wilting (x3)]]_, _[[Spells/Quandary|Maze (x3)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(8th)__ _[[Spells/Fly|Fly]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Isolate Foes"
    desc: "`pf2:2` (curse,divine,emotion,incapacitation,mental) **Frequency** once per day\n* * *\n\n**Effect** The ximtal attempts to isolate its enemy's companions, forcing an impression that each creature's friends and allies have vanished and they are all alone against an insurmountable threat. The ximtal chooses up to four creatures, each of whom must be adjacent to one other target. Each target must attempt a DC 38 Will check save. On a failure, a target becomes out of phase with all allies. The affected creatures can't perceive their allies or interact with them in any way, and they can move into allies' spaces as if their allies simply weren't there. Allies similarly can't perceive or interact with the affected creatures with one exception: an ally can target an affected creature with [[Spells/Cleanse Affliction|Cleanse Affliction]] to remove the effects. Every 24 hours, an affected creature can attempt a new saving throw to end this effect."

  - name: "Sensory Fever"
    desc: " (disease) A ximtal's withering attacks cause a debilitating disease targeting the senses\n\n**Saving Throw** DC 36 Fortitude check\n* * *\n\n**Stage1** creature loses one sense determined randomly: taste, smell, hearing, or sight (1 day)\n\n**Stage 2** creature loses an additional sense from the stage 1 list (1 day)\n\n**Stage 3** creature loses an additional sense from the stage 1 list (1 day)\n\n**Stage 4** creature loses the last sense from the stage 1 list and any special senses, such as tremorsense or lifesense (1 day)\n\n**Stage 5** all lost senses are permanent unless restored via [[Spells/Sound Body|Sound Body]] or a similar effect."

  - name: "Skip Between"
    desc: "`pf2:1` (divine,teleportation) The ximtal moves from the Material Plane to the Ethereal Plane or vice-versa, with the effects of [[Spells/Ethereal Jaunt|Ethereal Jaunt]] except that the effect has an unlimited duration and can be [[Actions/Dismiss|Dismissed]].\n\nA summoned ximtal can't use Skip Between."
 
```

```encounter-table
name: Ximtal
creatures:
  - 1: Ximtal
```



The struggles of loneliness and the anxiety that accompanies that feeling plague many creatures, and ximtals delight in exploiting this fear for their own perverse gain. Appearing as hybrids of rats and crabs with grasping tentacles, these scheming fiends manipulate their victims over long spans of time, like pakalchis, to savor the most fear they can. Ximtals use subtlety to entrap their prey and often don't directly engage their targets. They use insecurities as a tool and force poor behavior in mortals they set their sights on. They prefer to focus their machinations on strong-willed and well-intentioned mortals, hoping to erode their pride and self-worth and ultimately lead them eschew altruistic efforts.

Rather than focusing on a single victim, a ximtal might instead seek out a particular cause of interest to the sahkil's appetites. These creatures often wander the multiverse seeking to sabotage societal crusades or suppress divergent ideologies.

While most ximtals work alone, they sometimes enlist the assistance of pakalchis, who share similar tastes in mortal fear. Together and focused, these two types of fiends can dissolve individual self-worth, relationships, and even entire organizations.

* * *

Ages ago, when this cycle of the multiverse was still adolescent, a cabal of psychopomps who already felt bored and restrained in their role of ushering souls to their ultimate resting place rebelled against their station. It was this corruption of the cycle of souls that spawned the first sahkils.

Ambivalent to the prescribed order of the multiverse and spiteful of mortals, sahkils delight in spreading fear and unease to all beings, clogging up the metaphysical cycle with anxiety-ridden mortals too scared to achieve their potential. These fiends have drastically changed from their dedicated psychopomp predecessors. They are creatures of spite and torment, fear and disgust. They exploit the most common and rare fears for their own perverse satisfaction, and they want nothing more than to frighten mortals and make them question their reason for existence.

Most sahkils lurk on the Ethereal Plane, but they frequently invade the Material Plane to torment mortals and spread terror. They use their innate ability to slip between the veils of the Ethereal and Material effortlessly, often stalking their targets for days or weeks before enacting their devious plots.
