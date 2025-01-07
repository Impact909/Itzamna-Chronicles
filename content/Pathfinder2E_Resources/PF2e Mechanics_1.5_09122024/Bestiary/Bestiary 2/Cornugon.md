---
title: "Cornugon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8XGPuVdK79BA9FIA" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Cornugon"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Cornugon"
level: "Creature 16"

alignment: ""
size: "Large"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Greater Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +32, Intimidation: +30, Religion: +28, Stealth: +26, Warfare Lore: +30"
abilityMods: [8, 6, 7, 4, 6, 6]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +31, __Ref__ +26, __Will__ +26; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  fire; __Weaknesses__ holy 15; __Resistances__ physical 15 (except silver), poison 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+2 Greater Striking Unholy Spiked Chain]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Circle of Protection"
    desc: " (aura,divine) 10 feet. A constant [[Spells/Circle of Protection|Circle of Protection]] against good is centered on the cornugon."

  - name: "Commander's Aura"
    desc: " (aura,divine) 100 feet. Allied evil creatures in the aura of lower level than the devil's gain a +1 circumstance bonus to attack rolls, damage rolls, AC, saves, and skill checks.\n\n[[Bestiary Effects/Effect_ Commander's Aura|Effect: Commander's Aura]]"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 10 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+34 (disarm, finesse, magical, reach 10 feet, trip, unholy)\n__Damage__  3d8 + 16 slashing plus stunning-chain 2d6 spirit plus stunning-chain"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d10 + 14 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (magical, reach 10 feet, unholy)\n__Damage__  3d8 + 14 slashing plus infernal-wound 1d6 spirit plus infernal-wound"

  - name: "Divine Innate Spells"
    desc: "DC 36, attack +28; __7th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Fireball|Fireball (x2)]]_, _[[Spells/Lightning Bolt|Lightning Bolt (x2)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Chain of Malebolge"
    desc: "`pf2:1`  **Requirements** The cornugon's last action was a success with a spiked chain Strike.\n* * *\n\n**Effect** The devil pulls the creature 5 feet closer and [[Conditions/Grabbed|Grabs]] it with the spiked chain ([[Actions/Escape|Escape]] DC 42). The creature is automatically freed if the devil makes another spiked chain attack or moves away."

  - name: "Infernal Wound"
    desc: " (divine) A cornugon's tail Strike deals 4d6 bleed.\n\nThe DC of the flat check to stop the bleeding starts at DC 20 Flat check and is reduced to DC 15 Flat check only if someone successfully assists. The DC to [[Actions/Administer First Aid|Administer First Aid]] to a creature with an infernal wound increases by 10.\n\nA spellcaster or item using healing magic on an infernally wounded creature must succeed at a DC 34 counteract check or the magic fails to heal the creature.\n\n[[Bestiary Effects/Effect_ Infernal Wound|Effect: Infernal Wound]]"

  - name: "Stunning Chain"
    desc: " (incapacitation) If the cornugon critically hits with its spiked chain Strike, the target must succeed at a DC 34 Fortitude check save or be [[Conditions/Stunned|Stunned]] for 1 round (1d4 rounds on a critical failure)."
 
```

```encounter-table
name: Cornugon
creatures:
  - 1: Cornugon
```



Hell's armies contain legions upon legions of different devils all suited precisely to their roles. But such an army needs able commanders, and it is this role that cornugons fill. Their mere presence inspires those under their command to improved performance- often through fear of the horrible torments that a cornugon can unleash as punishment for failure. Forged in the fires of Malebolge from the most renowned warriors among lesser devilkind, even the least cornugon is among the fiercest warriors of the multiverse. The greatest among them on occasion ascend further still, becoming those rare and feared legends of Hell called malebranche.

* * *

Each type of devil plays a particular role in Hell's bureaucracies and hierarchies, though some have far more specialized functions than others.
