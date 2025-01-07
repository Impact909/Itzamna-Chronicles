---
title: "Snapdrake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jpo2Ta159HaJbyHu" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Snapdrake"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Snapdrake"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Arboreal, Common, Muan; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +14, Performance: +16"
abilityMods: [4, 6, 3, -2, 3, 4]
speed: 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +11, __Will__ +19"
hp: 144
health:
  - name: ""
  - name: HP
    desc: "144; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ axe vulnerability 10, fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alluring Scent"
    desc: " (aura,olfactory,plant,primal) 30 feet.\n\nA creature that enters the emanation must attempt a DC 25 Will check save. On a failure, the target is [[Conditions/Fascinated|Fascinated]] by the snapdrake and must use at least 1 action on its next turn to Stride closer to the snapdrake. On a success, the target is immune to the snapdrake's alluring scent for 1 hour."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  Tail scythe only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+14 ()\n__Damage__  2d12 + 4 piercing plus grab,snapdrake-pollen"

  - name: "**Melee** `pf2:1` Tail Scythe"
    desc: "+16 (deadly d10, finesse, reach 10 feet)\n__Damage__  2d10 + 6 slashing"

  - name: "Greater Forest Passage"
    desc: "  The snapdrake ignores difficult terrain and greater difficult terrain from plants and fungi."

  - name: "Snapdrake Pollen"
    desc: " (plant,poison) **Saving Throw** DC 25 Fortitude check;\n\n**Maximum Duration** 8 rounds\n\n**Stage 1** 1d6 poison damage plus [[Conditions/Dazzled|Dazzled]] 1 (1 round)\n\n**Stage 2** 1d6 poison damage plus dazzled 1 and [[Conditions/Sickened|Sickened 1]] (2 rounds)\n\n**Stage 3** 2d6 poison damage plus [[Conditions/Confused|Confused]] and sickened 1 (2 rounds)"

  - name: "Speed Surge"
    desc: "`pf2:1` (move) **Frequency** 3 times per day\n* * *\n\n**Effect** The snapdrake moves up to twice its Speed."

  - name: "Spray Pollen"
    desc: "`pf2:2` (arcane,plant,poison) The snapdrake breathes a blast of pollen in a 40-foot cone. Creatures caught in the blast must succeed at a DC 25 Reflex check save or be exposed to snapdrake pollen.\n\nThe snapdrake can't use Spray Pollen again for 1d6 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Snapdrake
creatures:
  - 1: Snapdrake
```



Skilled kizidhar mages and gardeners handcraft these lovely creatures as much for their shuyookhs' aesthetic pleasure as for their protection. Creating a snapdrake requires first painstakingly constructing a frame of living wood in the shape of a drake before weaving thousands of colorful snapdragon flowers into intricate patterns to form its body and scales. Once complete, snapdrakes often serve kizidhars as a combination of guards, pets, and decorations for as long as they are well fed.
