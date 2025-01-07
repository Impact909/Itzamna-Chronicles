---
title: "Kargstaad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NaG7v7qT5sAe0tSK" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Kargstaad"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Kargstaad"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[evil]]
trait_04: [[giant]]
trait_05: [[humanoid]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Low-Light Vision"
languages: "Aklo, Common, Fey, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +39, Crafting: +33, Intimidation: +37, Stealth: +33"
abilityMods: [10, 6, 8, 4, 6, 8]
speed: 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +35, __Ref__ +31, __Will__ +33; juggernaut"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360, fast healing 20; __Immunities__  cold; __Weaknesses__ fire 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x [[Equipment/Hatchet|+2 Striking Hatchet]], [[Equipment/Hide Armor|+2 Greater Resilient Hide Armor]], 5x Rock, [[Equipment/Sack|Sack]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 20]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

  - name: "Juggernaut"
    desc: "  When Kargstaad rolls a success on a Fortitude save, he gets a critical success instead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+37 (agile, magical, sweep)\n__Damage__  3d6 + 18 slashing 2d6 cold"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+35 (brutal, range increment 120 feet)\n__Damage__  2d10 + 18 bludgeoning plus rock"

  - name: "Chill Breath"
    desc: "`pf2:1` (cold,primal) The frost giant breathes out a 15-foot cone of freezing moisture that quickly condenses into ice, dealing 9d6 cold damage. Each creature in the cone must attempt a DC 41 Reflex check save.\n\nA creature that fails its save is also [[Conditions/Immobilized|Immobilized]] and takes 2d6 cold damage at the end of each of its turns until it gets free (Escape DC 41).\n\nThe giant can't use Chill Breath again for 1d4 rounds."

  - name: "Hatchet Onslaught"
    desc: "`pf2:3`  **Requirements** Each of Kargstaad's four hands wields a hatchet.\n* * *\n\n**Effect** Kargstaad Strides up to half his speed, then makes four hatchet Strikes, applying his multiple attack penalty as normal."

  - name: "Ice Stride"
    desc: "  A frost giant isn't impeded by difficult terrain caused by snow or ice, nor does it need to attempt Acrobatics checks to keep from falling on slippery ice."

  - name: "Rage"
    desc: "`pf2:1`  **Requirements** Kargstaad isn't [[Conditions/Fatigued|Fatigued]] or raging.\n* * *\n\n**Effect** Kargstaad gains 25 temporary hit points, deals an extra 12 points of damage with thrown rocks, and deals an extra 6 points of damage with hatchets. He takes a -1 penalty to AC and can't use actions with the concentrate trait (except [[Actions/Seek|Seek]]) unless they also have the rage trait.\n\n[[Feat_Feature Effects/Effect_ Rage|Effect: Rage]]"

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "Wide Swing"
    desc: "`pf2:1`  The frost giant makes a single greataxe Strike and compares the attack roll result to the ACs of up to two foes within its reach. This counts as two attacks for the frost giant's multiple attack penalty."
 
```

```encounter-table
name: Kargstaad
creatures:
  - 1: Kargstaad
```


Variant frost giant

Frost giants are remorseless marauders who pillage and plunder from those who dare to live near them in desolate, frigid lands. Their clans range from extremely territorial hunters who claim an expanse of tundra and defend it at all costs to nomadic hordes that roam icy slopes in search of settlements to conquer. Frost giant clans are ruled by those who exhibit the greatest ferocity and prowess in battle-massive brutes who proclaim themselves jarl and demand absolute obedience from their followers. If at any time a frost giant wishes to be a jarl, all they must do is issue a challenge to the current jarl and face off in mortal combat, after which the reigning champion continues leading the clan or the victorious challenger assumes control.

Frost giants live in frostbitten realms, and their appearance is reflective of a people weathered and hardened by relentless snowstorms and freezing temperatures. They often wear metal armor adorned with the furs, skin, teeth, and tusks of slain beasts and heft weapons as long as dining tables. Their flesh ranges from pale blue to shale gray, and their hair is typically a dingy white or dirty yellow color.

A typical frost giant stands about 15 feet tall and weighs approximately 2,800 pounds.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They are divided into a number of subtypes.
