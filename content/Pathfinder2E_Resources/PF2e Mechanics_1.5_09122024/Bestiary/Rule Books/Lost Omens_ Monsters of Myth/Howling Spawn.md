---
title: "Howling Spawn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lEGBS62QoKHa4XSk" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Howling Spawn"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Howling Spawn"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Deception: +19, Intimidation: +23, Stealth: +21, Survival: +19"
abilityMods: [7, 6, 7, 3, 4, 3]
speed: 35 feet,  climb 20 feet,  fly 15 feet,  swim 30 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +21, __Will__ +18"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, regeneration 20 (deactivated by cold); __Immunities__  emotion,  fear effects; __Weaknesses__ cold 10; __Resistances__ fire 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Fear Scent (Precise) 60 feet"
    desc: "  Howling spawn can sense frightened creatures within 60 feet, using an incredibly accurate sense of psychic smell as a precise sense."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 27 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Putrid Evanescence"
    desc: "`pf2:r`  **Frequency** once per hour\n\n**Trigger** The howling spawn is damaged by another creature\n* * *\n\n**Effect** The howling spawn bursts into a cloud of putrid smoke, ash, and nightmares, becoming [[Conditions/Invisible|Invisible]] and teleporting up to 30 feet away to an unoccupied space it can see. It remains invisible until the end of its next turn or until it uses a hostile action, whichever comes first."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, reach 10 feet)\n__Damage__  2d10 + 13 slashing plus grab"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+23 (range 30 feet)\n__Damage__  1d6 fire plus paralytic-secretion 1d6 mental plus paralytic-secretion"

  - name: "Innate Occult Spells"
    desc: "DC 27, attack +19; __5th __  _[[Spells/Hallucination|Hallucination]]_; __4th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_; __2nd __  _[[Spells/Invisibility|Invisibility (Self Only)]]_, _[[Spells/Mirror Image|Mirror Image]]_"

  - name: "Illusory Ambush"
    desc: "`pf2:2`  The howling spawn shimmers with illusions and devastates a foe who lost track of its position. It Strides up to twice its Speed. If it ends its movement within its melee reach of at least one enemy to which it is undetected, it can attempt two claw Strikes against that enemy. The howling spawn remains undetected to the creature it's attacking until after resolving both of the claw attacks."

  - name: "Paralytic Secretion"
    desc: "  The howling spawn's saliva is a potent paralytic substance that drains the energy from its prey. A creature hit by its spit Strike must succeed at a DC 30 Fortitude check save or become [[Conditions/Drained|Drained 1]] as well as [[Conditions/Paralyzed|Paralyzed]] for 1 round. If the target was already drained, it instead increases the condition's value by 1, to a maximum of drained 4."

  - name: "Profane Feast"
    desc: "`pf2:1`  **Requirements** The howling spawn has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The howling spawn begins to consume the creature, dealing 2d12+5 piercing damage (DC 30 Fortitude check save) and exposing the creature to its paralytic secretion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Howling Spawn
creatures:
  - 1: Howling Spawn
```



While Desert's Howl is presumed to be unique, given its inexplicable origin, there have been reports of creatures resembling Desert's Howl that stalk the sands of Thuvia. Though quite similar to the descriptions of Desert's Howl, they seem to be individuals who haven't yet fully completed their transformation into the terrifying beast. Whether these unfortunate people met a cruel fate similar to that which spawned Desert's Howl or are spawn of the nightmarish creature itself is unclear. Some reports of encounters with these creatures note that it's possible to revert the creature back to its humanoid form by cleansing its mind of nightmarish visions, though there's no solid evidence of such an event ever occurring.
