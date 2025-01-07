---
title: "Tombstone Troll"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0JkhF1Rkel9gACYK" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/troll
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Tombstone Troll"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Tombstone Troll"
level: "Creature 1"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[giant]]
trait_04: [[troll]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Stealth: +7"
abilityMods: [3, 2, 1, -3, 0, -2]
speed: 25 feet,  burrow 5 feet
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +6, __Ref__ +9, __Will__ +5"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25, regeneration 5 (deactivated by acid, fire, or vitality); __Immunities__  void; __Weaknesses__ fire 5, vitality 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 5 (Deactivated by Acid, Fire, or Vitality)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d6 + 3 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (agile)\n__Damage__  1d4 + 3 slashing"

  - name: "Death Feast"
    desc: "`pf2:1` (manipulate) **Requirements** The troll's last action was a jaws Strike that damaged a living creature or a corpse\n* * *\n\n**Effect** The troll deals 1d6 bleed damage to the target as it swallows a mouthful of meat and converts it into void energy. Its jaws and claw Strikes deal 1 additional void damage for 1 minute or until it uses its Grave Breath, whichever comes first."

  - name: "Grave Breath"
    desc: "`pf2:2` (death,occult,void) **Requirements** The troll is bloated with void energy from a Death Feast\n* * *\n\n**Effect** The troll breathes a 15-foot cone of putrid, soul-chilling gas. Each living creature in the area takes 2d6 void damage (DC 14 Fortitude check). On a failure, the creature also becomes [[Conditions/Sickened|Sickened 1]]. The troll can't use Grave Breath until it uses Death Feast again."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Tombstone Troll
creatures:
  - 1: Tombstone Troll
```



Sometimes, when a troll is regenerating from life-threatening wounds inflicted by necromancy or void energy, the vile energy takes hold in the troll's supernaturally resilient regeneration. The force that should have killed the troll instead becomes a part of the troll's strange physiology. These trolls are not undead, but the force inside them eats at their bodies and souls, turning them into shrunken mockeries of their former selves. These so-called "tombstone trolls" resemble withered, diminutive trolls, bloated with starvation and obviously sickly. Their teeth, hair, and fingernails rot, fall out, and regenerate every few days in an endless cycle that is both painful to experience and sickening to see.

Other trolls shun and despise tombstone trolls, who earn their name from their habit of digging up graves in their search for an easy meal that can't fight back. Tombstone trolls shun confrontation of any kind, especially in areas where their grave-robbing might put them at odds with powerful undead. They often lair underground, safe in their graveyard burrows for days at a time, gradually tunneling through the earth to devour nearby corpses. If the tombstone troll is clever, the surface might not bear any evidence of their presence except for a few divots or soft spots in the soil. Once a tombstone troll has run out of easy pickings in a cemetery, it moves on in the dead of night to find a new hunting ground. If their travel is lengthy or difficult, their hunger might drive them to attack the living.
