---
title: "Shadowforged Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xzpzxqVUcAuwOF0m" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Shadowforged Guardian"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Shadowforged Guardian"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Greater Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23"
abilityMods: [7, 5, 3, -5, 0, -5]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +21, __Will__ +14"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ slashing 10; __Resistances__ cold 10, physical 10 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Eager Shadows"
    desc: "  The shadowforged guardian increases all of its Speeds by 30 feet during the first round of combat after rolling initiative."

abilities_mid:
  - name: ""
  - name: "Induction Word"
    desc: "  Each shadowforged guardian is activated during creation by a special word or short phrase spoken by its creator, and hearing this induction word resets its functions. If the guardian hears a creature within 30 feet utter its induction word, the guardian must succeed at a DC 26 Will check save or become [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 3]] on a critical failure). Regardless of the result of this save, it's immune to utterances of its induction word until the end of its next turn."

  - name: "Twilight Aura"
    desc: " (aura,illusion,occult,shadow) 30 feet. The shadowforged guardian's presence dims light and brightens shadows to a strange, twilit half-light. Light can't emanate brighter than dim light in this area while darkness is simultaneously illuminated to dim light. The shadowy aura automatically attempts to counteract any 5th-rank or lower magical light or darkness effect brought into this aura or created in this area (counteract check +21, 5th level). As long as the guardian is in dim light, it gains a fly Speed of 30 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, reach)\n__Damage__  2d8 + 11 slashing plus push 1d6 cold plus push"

  - name: "Shadow Breath"
    desc: "`pf2:2` (occult,shadow) The shadowforged guardian expels a 30-foot cone of twisting shadows from its mouth. All creatures in the area must attempt a DC 29 Fortitude check save. The guardian can't use Shadow Breath for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Enfeebled|Enfeebled 1]] until the end of its next turn.\n\n**Failure** The creature is enfeebled 1 for 1 hour and [[Conditions/Slowed|Slowed 1]] for 1 minute.\n\n**Critical Failure** The creature is [[Conditions/Enfeebled|Enfeebled 2]] for 24 hours and [[Conditions/Slowed|Slowed 2]] for 1 minute."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Shadowforged Guardian
creatures:
  - 1: Shadowforged Guardian
```



Shadowforged guardians are created through the intricate and dangerous process of siphoning penumbral energies and matter from the Shadow Plane and then binding them to a physical skeleton of wood and metal.

The first shadowforged guardians were created thousands of years ago in Nidal and were usually crafted in the likeness of that nation's patron deity, Zon-Kuthon. Shadowforged guardians are understandably in high demand; unfortunately, only the person who speaks a special word or phrase at the moment of the construct's creation can command it. Those who know the hidden formula to craft these constructs guard the secret well and only a few shadowcasters deign to create these guardians on another person's behalf-for a hefty price.
