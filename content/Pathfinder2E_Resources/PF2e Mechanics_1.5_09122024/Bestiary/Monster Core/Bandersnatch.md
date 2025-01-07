---
title: "Bandersnatch"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4gZleMjunv8wCS7m" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/tane
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Bandersnatch"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Bandersnatch"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[tane]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Precise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +33, Intimidation: +32, Stealth: +32, Survival: +28"
abilityMods: [9, 6, 6, -4, 6, 6]
speed: 50 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +32, __Ref__ +30, __Will__ +27; +1 status to all saves vs. magic"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335, fast healing 15; __Immunities__  confused"
abilities_top:
  - name: ""

  - name: "Planar Acclimation"
    desc: "  The bandersnatch treats the plane it is on as its home plane."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 15]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Confusing Gaze"
    desc: " (aura,emotion,mental,primal,visual) 20 feet.\n\nWhen a creature ends its turn in the aura, it must succeed at a DC 35 Will check save or become [[Conditions/Confused|Confused]] for 1 round."

  - name: "Quick Recovery"
    desc: "  The bandersnatch recovers with frightening speed. At the end of its turn, it reduces the value of one debilitating condition it suffers (with the exception of dying) by 1. If it's [[Conditions/Blinded|Blinded]], [[Conditions/Dazzled|Dazzled]], [[Conditions/Deafened|Deafened]], [[Conditions/Fatigued|Fatigued]], [[Conditions/Fleeing|Fleeing]], or petrified, it can instead succeed at a DC 16 Flat check to end one of these conditions of its choice; it can't use quick recovery on other conditions that lack values."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 15 feet)\n__Damage__  3d12 + 19 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+34 (agile, magical, reach 15 feet)\n__Damage__  3d8 + 19 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+34 (fatal d8, magical, reach 20 feet)\n__Damage__  3d4 + 19 piercing plus pain"

  - name: "**Ranged** `pf2:1` Quill"
    desc: "+30 (range increment 100 feet)\n__Damage__  3d4 + 19 piercing plus pain"

  - name: "Focus Gaze"
    desc: "`pf2:1` (emotion,mental,primal,visual) The bandersnatch fixes its gaze at a creature it can see within 20 feet. The target must immediately attempt a Will save against the bandersnatch's Confusing Gaze. After attempting the save, the creature is temporarily immune to a bandersnatch's Confusing Gaze until the start of the bandersnatch's next turn."

  - name: "Frumious Charge"
    desc: "`pf2:2`  The bandersnatch Strides, ignoring difficult terrain, then makes two claw Strikes at the end of its movement."

  - name: "Lash Out"
    desc: "  At the start of its turn, the bandersnatch gains an additional reaction that can be used only to attempt an Attack of Opportunity."

  - name: "Pain"
    desc: "  A bandersnatch's quills create exceptionally painful wounds. The wounded creature must succeed at a DC 38 Fortitude check save to resist becoming [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure) by this pain. Further bandersnatch Strikes that cause pain increase the amount of drain by 1 for each failed save to a maximum of drained 4."

  - name: "Relentless Tracker"
    desc: "  The bandersnatch can [[Actions/Track|Track]] while moving at its full speed."
 
```

```encounter-table
name: Bandersnatch
creatures:
  - 1: Bandersnatch
```



Bandersnatches are great six-legged cats with wicked quills running down the length of their bodies down to the tips of their mighty tails. As with other legendary creatures from the First World, such as the jabberwock, bandersnatches belong to the infamous group of creatures known collectively as the "Tane." These terrifying hunters take great delight in taking down other deadly or intelligent predators by perfectly adapting to any environment they find themselves in. A bandersnatch stalks their quarry before lashing out with speed and ferocity. Those who survive a bandersnatch attack will confirm that while the cats' fangs and claws are deadly, their eyes are their greatest weapon of all. A bandersnatch's eyes are constantly shifting in color, intensity, and design, causing those they gaze upon to fall into a confused panic.
