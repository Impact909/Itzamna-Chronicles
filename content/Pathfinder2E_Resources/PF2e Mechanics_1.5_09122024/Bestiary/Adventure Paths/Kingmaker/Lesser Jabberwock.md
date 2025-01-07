---
title: "Lesser Jabberwock"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ILWvzfLXaQlMnjho" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/tane
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Lesser Jabberwock"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Lesser Jabberwock"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[tane]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Darkvision, Scent (Imprecise) 120 Feet, Truesight"
languages: "Aklo, Common, Draconic, Fey, Gnomish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Athletics: +41, Intimidation: +38, Nature: +34, Survival: +37"
abilityMods: [10, 6, 7, 2, 7, 6]
speed: 35 feet,  fly 60 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +38, __Ref__ +33, __Will__ +36"
hp: 430
health:
  - name: ""
  - name: HP
    desc: "430, regeneration 20 (deactivated by vorpal weapons); __Immunities__  paralyzed,  sleep; __Weaknesses__ vorpal 20; __Resistances__ fire 20"
abilities_top:
  - name: ""

  - name: "Planar Acclimation"
    desc: "  The jabberwock always treats the plane it is currently located on as its home plane."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Vorpal Weapons)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Claws That Catch"
    desc: "`pf2:r`  **Trigger** A creature within the jabberwock's reach uses a manipulate action or a move action, leaves a square during a move action, makes a ranged attack, or uses a concentrate action\n* * *\n\n**Effect** The jabberwock makes a claw Strike against the triggering creature. If the Strike hits, the jabberwock disrupts the triggering action."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 100 feet. DC 41 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Vorpal Fear"
    desc: "  A jabberwock damaged by a vorpal weapon becomes [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 4]] on a critical hit)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (deadly 2d10, magical, reach 15 feet)\n__Damage__  4d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 15 feet)\n__Damage__  4d6 + 18 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+38 (magical, reach 15 feet)\n__Damage__  4d8 + 18 bludgeoning plus improved-knockdown"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+36 (agile, magical, reach 15 feet)\n__Damage__  4d6 + 18 bludgeoning"

  - name: "**Ranged** `pf2:1` Eyes Of Flame"
    desc: "+38 (fire, magical, range increment 60 feet)\n__Damage__  8d6 fire 2d6 fire"

  - name: "Primal Innate Spells"
    desc: "DC 44, attack +36\n__Constant__  __(10th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Burble"
    desc: "`pf2:2` (aura,emotion,mental,primal,sonic) The jabberwock creates a blast of strange noises and shouted nonsense in the various languages it knows (and invariably some languages it doesn't know), creating one of two effects.\n\nThe jabberwock can't Burble again for 1d4 rounds.\n\n*   **Confusion** 60-foot emanation. Each creature in the emanation must succeed at a DC 44 Will check save or become [[Conditions/Confused|Confused]] for 1d4 rounds.\n*   **Sonic Beam** The jabberwock focuses its Burbling into a 60-foot line of sonic energy that deals 22d6 sonic damage to creatures in the area (DC 44 Reflex check save)."

  - name: "Jaws That Bite"
    desc: "  If the jabberwock makes a jaws attack and rolls a natural 19 on the d20 roll, the attack is a critical hit. This has no effect if the 19 would be a failure."

  - name: "Whiffling"
    desc: "`pf2:r` (aura) **Trigger** The jabberwock Flies or makes a wing Strike\n* * *\n\n**Effect** The jabberwock's wings whiffle, creating severe winds within a 30-foot emanation. These winds move outward from the jabberwock, and they persist until the start of the jabberwock's next turn. During this time, flight of any kind in the emanation requires a successful Acrobatics check to [[Actions/Maneuver in Flight|Maneuver in Flight]], and creatures flying toward the jabberwock are moving through greater difficult terrain. Creatures on the ground in the emanation must succeed at a DC 41 Athletics check check to approach the jabberwock."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Lesser Jabberwock
creatures:
  - 1: Lesser Jabberwock
```


Variant jabberwock

Few beasts have inspired as many legends, poems, songs, and myths in as many cultures, as this bizarre draconic creature. The jabberwock hails from the fey realm of the First World and is part of a group of powerful First World creatures known collectively as the Tane.

Like all members of the Tane, jabberwocks are living creatures that age, eat, drink, and sleep, but do not reproduce normally. Instead, they are created directly by the godlike Eldest who rule the First World, and they serve at the pleasure of these capricious and mysterious entities. Believed to be the most powerful of all the Tane, jabberwocks are typically only ever created with one purpose: to wreak destruction and havoc upon the Material Plane. One of the Eldest might send a jabberwock to devastate a country, continent, or even entire world in order to get revenge for some slight made against them by a single mortal. Sometimes, no specific insult or injury is required, as some of the Eldest resent the very existence of the Material Plane and periodically create jabberwocks simply to express the wrath of the First World against its younger and less chaotic sibling.

Once a jabberwock arrives on the Material Plane, its first order of business is to seek out a lair. It prefers dwelling in remote forest locations about a day's flight from civilization-the more dangerous the woodland is to those who might eventually come hunting it, the better!

The relationship between jabberwocks and vorpal weapons is the subject of much debate and speculation among scholars, and the various poems, songs, and legends about the jabberwock do little to clarify the issue, conflicting and diverging on this point. Some believe that vorpal weapons were first created specifically to combat jabberwocks, but others take the story one step further. They cite evidence in certain ancient myths that there may once have been only a single, unique jabberwock, so powerful that nothing could so much as scratch it-nothing, that is, except for the first vorpal sword, crafted for that very purpose. So epic was the resulting battle that it created strange echoes throughout reality, and as a result, these echoes, in the form of vorpal weapons, can now be found on many worlds. Those who subscribe to this belief claim that the jabberwocks seen today are but pale imitations of this proto-jabberwock, and they speculate that only the combined efforts of several Eldest would be sufficient to create such a creature again.

Variant JabberwocksThe Eldest have sometimes altered certain aspects of the jabberwocks they create. Some of the more notorious or legendary variant jabberwocks include the following.

Frumious Jabberwock: Frumious jabberwocks have two heads. They are level 24 and gain an extra action on each of their turns they can use only to make a jaws Strike.

Mimsy Jabberwock: Typically hailing from wintry regions of the First World, mimsy jabberwocks have glowing blue-white scales, resist cold instead of fire, and have eyes that burn with blue flames that deal cold damage instead of fire damage.

Slithy Jabberwock: Wreaking destruction beneath the waves, these sinuous and slimy jabberwocks are amphibious, have a swim Speed of 80 feet instead of the normal fly Speed, and do not have a wing Strike. A slithy jabberwock's whiffling aura is activated whenever it swims, makes a tail Strike, or Burbles.
