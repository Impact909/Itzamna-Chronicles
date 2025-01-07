---
title: "Xulgath Stoneliege"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.F7p86q2tsNzXmNhu" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Xulgath Stoneliege"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Xulgath Stoneliege"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Intimidation: +18, Survival: +18, Cave Lore: +15, Geology Lore: +15"
abilityMods: [5, 2, 6, 1, 2, 2]
speed: 20 feet,  burrow 10 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +20, __Ref__ +12, __Will__ +14"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Resistances__ physical 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature entering the aura must attempt a DC 24 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, the creature also takes a -5-foot status penalty to its Speeds for 1 round. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stench for 1 minute.\n\n[[Bestiary Effects/Effect_ Xulgath Stench|Effect: Xulgath Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Digging Bar"
    desc: "+18 (fatal d12, forceful, versatile b)\n__Damage__  2d10 + 9 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 ()\n__Damage__  2d8 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile)\n__Damage__  2d6 + 9 slashing plus grab"

  - name: "Primal Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Shape Stone|Shape Stone (x3)]]_"

  - name: "Earthen Blow"
    desc: "`pf2:1` (earth) **Frequency** once per round\n* * *\n\n**Effect** The stoneliege commands nearby earth to attack a foe. The stoneliege makes a claw Strike against a creature that is within 60 feet of the stoneliege and 10 feet of an earthen surface, such as dirt, mud, stone, or sand. The Strike originates from the surface's square and has a reach of 10 feet. On a critical hit, the target is also knocked [[Conditions/Prone|Prone]]."

  - name: "Earthen Torrent"
    desc: "`pf2:2` (earth) **Frequency** once per minute\n\n**Requirements** The stoneliege is standing on or next to at least 10 cubic feet of dirt, stone, or other earthen material\n* * *\n\n**Effect** The stoneliege creates a violent wave of roiling earth. Creatures in a 15-foot cone take 7d8 bludgeoning damage (DC 26 Reflex check save; on a critical failure, creatures are also knocked [[Conditions/Prone|Prone]])."

  - name: "Stone Throes"
    desc: "`pf2:1` (earth) The stoneliege turns their own body into solid stone like a statue and immediately becomes [[Conditions/Petrified|Petrified]]. Any creature grappled or restrained by the stoneliege becomes [[Conditions/Immobilized|Immobilized]]; to get free, the creature must damage the statue enough to break it or succeed at a DC 28 Acrobatics check check to [[Actions/Escape|Escape]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Xulgath Stoneliege
creatures:
  - 1: Xulgath Stoneliege
```



Stonelieges are xulgaths magically infused with living earth—the very bones of the world. They are created through a process xulgaths call stone-binding, which can be performed with complex alchemy, powerful psychic magic, or Abyssal rituals. Their scales are like stone slabs, and their bones are as dense as bedrock, so they are among the hardiest and longest-lived xulgaths. To stonelieges, earth is as mutable as water, and their innate power to shape the soil and stone beneath their feet makes them integral members of xulgath society (as well as formidable combatants).
