---
title: "Diabolic Dragon (Adult)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pBka4CgtJ6zBa5Cz" 
tags:
  - pf2e/creature/type/divine
  - pf2e/creature/type/dragon
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Diabolic Dragon (Adult)"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Diabolic Dragon (Adult)"
level: "Creature 15"

alignment: ""
size: "huge"
trait_01: [[divine]]
trait_02: [[dragon]]
trait_03: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Pyric, Empyrean, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +30, Deception: +26, Diplomacy: +28, Intimidation: +26, Religion: +26, Society: +24, Thievery: +27, Hell Lore: +24, Legal Lore: +26"
abilityMods: [8, 4, 6, 3, 5, 5]
speed: 60 feet,  fly 150 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +25, __Will__ +26; +2 status to all saves vs. divine"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair the dragon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Hell's Sting"
    desc: "`pf2:r` (divine,mental,unholy) **Trigger** The dragon is critically hit with a melee attack\n* * *\n\n**Effect** The dragon channels the rancor of Hell back through the body of their foe, overwhelming it with an infernal assault on the mind. The triggering creature takes 8d6 mental damage with a DC 36 Will check save. Holy creatures use an outcome one degree of success worse than they roll on their saving throw."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (fire, magical, reach 10 feet, unholy)\n__Damage__  2d6 fire 3d12 + 11 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+30 (agile, fire, magical, unholy)\n__Damage__  2d6 fire plus grab 3d8 + 11 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+28 (fire, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 11 bludgeoning plus knockdown 2d6 fire plus knockdown"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Divine Immolation|Divine Immolation]]_, _[[Spells/Interplanar Teleport|Interplanar Teleport (At Will, Self Only)]]_, _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Ignition|Ignition]]_"

  - name: "Diabolic Fire"
    desc: "  Any fire damage that a diabolic dragon deals, including fire damage from spells, is imbued with the unholy power of Hell to scorch the spirit as well. A creature takes spirit damage instead of fire damage if that would be more detrimental to the creature (as determined by the GM). A diabolic dragon is immune to the diabolic fire of other diabolic dragons, the fire from divine immolation, and similar effects."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Hellfire Breath whenever they score a critical hit with a Strike."

  - name: "Hellfire Breath"
    desc: "`pf2:2` (divine,fire,unholy) The dragon unleashes a blast of infernal fire that deals 16d6 fire damage in a 50-foot cone (DC 36 Reflex check save).\n\nThe dragon can't use Hellfire Breath again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Diabolic Dragon (Adult)
creatures:
  - 1: Diabolic Dragon (Adult)
```



Hell, according to some theologians, is a living entity in and of itself. Diabolic dragons, these scholars argue, are just extensions of the plane, living creatures that break off from Hell to enact its will. Whether this is true or whether diabolical dragons are simply the reborn souls of dragons sent to Hell, the fact remains that these dragons are powerful, cunning, and tyrannical. Every diabolic dragon's goal is to further Hell's will, though how this happens can vary. Regardless of their goals, these dragons always approach newcomers with an unsettling calmness.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
