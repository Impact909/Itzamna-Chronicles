---
title: "Choker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SRr8N3vcSaby0e9E" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Choker"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Choker"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Aklo, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Stealth: +9"
abilityMods: [3, 3, 1, -3, 1, -2]
speed: 20 feet,  climb 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +10, __Will__ +7"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Yank"
    desc: "`pf2:r` (manipulate) **Trigger** An enemy targets the choker with an attack\n* * *\n\n**Effect** The choker tries to pull a creature it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] into the path of the attack. The choker attempts an Athletics check, including its bonus to [[Actions/Grapple|Grapple]]. If it succeeds against the grabbed or restrained creature's Fortitude DC, the choker redirects the attack to that creature, and the attacker compares its attack roll result against the new target's AC. The choker must move the creature into a space adjacent to itself. The creature must also be moved within the attacker's reach against a melee attack or into a space between itself and the attacker against a ranged attack. The choker can't use this ability to make the attacker target itself, even if it's grabbing or restraining the attacker."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm"
    desc: "+11 (reach 10 feet)\n__Damage__  1d6 + 3 bludgeoning plus strangling-fingers"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6+3 bludgeoning, DC 19 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Hidden Movement"
    desc: "  If the choker starts its turn [[Conditions/Hidden|Hidden]] from or [[Conditions/Undetected|Undetected]] by a creature, that creature is [[Conditions/Off-Guard|Off-Guard]] against the choker's attacks until the end of the turn."

  - name: "Strangling Fingers"
    desc: "  Any creature hit by a choker's arm Strike is automatically [[Conditions/Grabbed|Grabbed]], and the choker begins to strangle the target. The creature is suffocating and can't speak as long as it's strangled. This prevents it from casting spells with a verbal component or activating items with a command component."
 
```

```encounter-table
name: Choker
creatures:
  - 1: Choker
```



With long, cartilaginous limbs and gray skin, chokers easily hide in stony alcoves, rocky fissures, and darkened staircases to ambush their prey. The strange little aberrations prefer to pick off weak and solitary creatures, especially those that wander off from their packs or communities. A choker's long, spongy arms are flexible but deceptively strong. The fingers can tighten rapidly and are ridged with spiky, tooth-like structures that provide an incredible grip. A choker typically strangles its prey to death, then drags the body off or dismembers it using crude tools if the body is too big to carry. If confronted or outnumbered, a choker tries to escape, often compressing into a tight passage to get away. Chokers that encounter humanoids exhibit intense curiosity about their culture, society, and the products of art and industry. This interest isn't very deep-it just results in chokers that like killing people and collecting any of their items that seem sophisticated, such as jewelry, nice clothing, or written texts.

Chokers sometimes gather in settlements, usually sticking to slums or abandoned structures. These chokers stalk at night, flopping across rooftops, tapping at windows, and scuttling through sewers, gutters, and chimneys to get at prey. An urban choker that finds prey early on its hunt-a wandering pet, a person who is out alone-might spend the rest of the night indulging its curiosity about the products of society. A curious choker might abscond with all sorts of odd items, from tavern signs to library books to roof tiles. A choker usually pilfers only one item at a time, but as its collection grows, it might need to find a larger nest to accommodate its collection, then move its pieces one by one to the new home.
