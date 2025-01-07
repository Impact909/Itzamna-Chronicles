---
title: "Rune Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fKOnu3k56yNdOEtp" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Rune Giant"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Rune Giant"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[giant]]
trait_02: [[humanoid]]
trait_03: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Low-Light Vision"
languages: "Common, Jotun, Petran"
skills:
  - name: "Skills"
    desc: "Arcana: +28, Athletics: +32, Crafting: +28, Intimidation: +28, Society: +27"
abilityMods: [9, 2, 7, 2, 6, 4]
speed: 45 feet,  fly 45 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +33, __Ref__ +26, __Will__ +28"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Immunities__  fire"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|+1 Striking Longspear]], [[Equipment/Greatsword|+2 Greater Striking Greatsword]], [[Equipment/Splint Mail|+1 Splint Mail]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Special)]]"
    desc: "`pf2:r`  The rune giant gains an additional reaction at the beginning of each of their turns that they can use only for a Reactive Strike.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+33 (magical, reach 20 feet, versatile p)\n__Damage__  3d12 + 17 slashing"

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+32 (magical, reach 25 feet)\n__Damage__  2d8 + 17 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+31 (agile, reach 20 feet, unarmed)\n__Damage__  3d8 + 17 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 35, attack +27; __8th __  _[[Spells/Charm|Charm]]_, _[[Spells/Suggestion|Suggestion]]_; __6th __  _[[Spells/Dominate|Dominate (x3)]]_, _[[Spells/Truesight|Truesight]]_; __5th __  _[[Spells/Sending|Sending]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/Fly|Fly]]_"

  - name: "Command Giants"
    desc: "  When a rune giant casts a mental spell against another giant, the DC is 39, rather than 35"

  - name: "Demand"
    desc: " (arcane,mental) When a rune giant casts their innate [[Spells/Sending|Sending]] spell, they can also cast [[Spells/Suggestion|Suggestion]] on the target."

  - name: "Flashing Runes"
    desc: " (arcane,light) **Trigger** The rune giant uses an arcane ability or casts an arcane spell\n* * *\n\n**Effect** The runes on the giant's body flash with magical energy. Each creature within a 10-foot emanation must attempt a DC 35 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Failure** The creature is [[Conditions/Blinded|Blinded]] for 1 round."

  - name: "Invoke Rune"
    desc: "`pf2:1` (arcane,concentrate,electricity) The rune giant invokes one of the runes on their body, causing the rune to spray forth a 30-foot cone of sparks that deals 6d12 electricity damage to all creatures in the cone (DC 37 Reflex check save).\n\nThe giant can't use Invoke Rune again for 1d4 rounds.\n\nA glowing copy of the invoked rune appears on a single weapon the giant holds, granting the weapon one effect listed below of the giant's choice. The effect on the weapon lasts for 1 minute. If the giant places a new rune on a weapon, any previously placed rune immediately vanishes, ending its effect.\n\n*   **Rune of Destruction** The weapon gains the deadly trait with three weapon damage dice of the same die size as for the base weapon, and a creature hit with the weapon is [[Conditions/Drained|Drained 1]] unless it succeeds at a DC 35 Fortitude check save.\n*   **Rune of Flames** The weapon deals an additional 3d6 fire damage on all attacks.\n*   **Rune of Smiting** When the weapon hits, the giant can Push the target back 10 feet, or 20 feet on a critical hit.\n*   **Rune of Space** During the rune giant's turn, the weapon's reach is increased to 60 feet."

  - name: "Wide Swing"
    desc: "`pf2:1`  The rune giant makes a single greatsword Strike and compares the attack roll result to the ACs of up to two foes within their reach. This counts as two attacks for the giant's multiple attack penalty."
 
```

```encounter-table
name: Rune Giant
creatures:
  - 1: Rune Giant
```



Rune giants are tyrants among their own kind, given power to command and magically control other giants. They once served even more powerful masters—potent wizards known as runelords—and in so doing, commanded entire armies of giants in service to the runelords' empires.

In the eons since these empires collapsed, rune giants have persisted, though to the outside world they're little more than fabled horrors. Rune giants usually dwell in the most remote and rugged of towering mountain ranges, but they can also be found in immense ruins atop lost islands, glacial valleys, or even more remote or magical regions.

Dozens of runes decorate rune giants' striking charcoal flesh. They are towering creatures, averaging at 40 feet in height and weighing 25,000 pounds.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
