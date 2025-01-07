---
title: "Berberoka"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.H7gqBEivcYZqoGvE" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Berberoka"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Berberoka"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[giant]]
trait_03: [[humanoid]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Deception: +27, Intimidation: +25, Nature: +26, Stealth: +25, Survival: +26"
abilityMods: [8, 4, 6, -1, 3, 4]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +23, __Will__ +24"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  A berberoka can hold their breath for 2 hours"

  - name: "Fear of Crabs"
    desc: " (emotion,fear,mental) If a berberoka sees a crab or crab-like creature, the berberoka must attempt a DC 33 Will check save. They then becomes immune to the sight of that creature for 10 minutes.\n* * *\n\n**Critical Success** The berberoka is unaffected.\n\n**Success** The berberoka becomes [[Conditions/Frightened|Frightened 2]].\n\n**Failure** The berberoka gains the [[Conditions/Fleeing|Fleeing]] condition for 1 round and is [[Conditions/Frightened|Frightened 4]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+31 (reach 15 feet)\n__Damage__  3d12 + 16 bludgeoning plus grab"

  - name: "Consume Lake"
    desc: " (manipulate) The berberoka drinks a prolific amount from an adjacent water source. If the water source is equal to or greater in volume than themself, the berberoka consumes up to 1,500 gallons of water per minute and becomes waterlogged. They can release water at the same rate. While waterlogged, the berberoka can use Spray Water, their size grows to Gargantuan, and their Speed is reduced to 15 feet.\n\n[[Bestiary Effects/Effect_ Waterlogged|Effect: Waterlogged]]"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d12+12 bludgeoning damage, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Spray Water"
    desc: "`pf2:2`  **Requirements** The berberoka is waterlogged.\n* * *\n\n**Effect** The berberoka sprays a blast of water in a 60-foot line. All creatures in the line take 6d8 bludgeoning damage (DC 35 Reflex check save). On a failed save, a creature is knocked [[Conditions/Prone|Prone]] and pushed back 5 feet (10 feet on a critically failed save)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Berberoka
creatures:
  - 1: Berberoka
```



Berberokas are giant humanoids who live among forests and swamps, where they use their ability to swallow massive amounts of water to drain small ponds and lakes. Creatures who visit their favorite watering hole and find only an empty mud basin become prey for the berberoka, who hides in the brush and overwhelm their prey with a massive torrent of regurgitated water.

A berberoka's mottled backside-which resembles a bundle of local plants, small trees, and large rocks-grants them natural camouflage that allows them to hide in plain sight. Berberokas tend to disguise themselves as rock formations in the center of a dried-up waterbed while they lie in wait for passersby. In the tropical regions where berberokas are most common, locals know to give empty ponds a wide berth, regardless of the enticing fish flopping about. Hungry travelers, on the other hand, might see such bounty as a blessing from the gods, only to be swept up in the berberoka's deadly deluge.
