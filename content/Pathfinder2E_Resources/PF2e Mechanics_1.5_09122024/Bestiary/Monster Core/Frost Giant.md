---
title: "Frost Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vledTyPHE30r9AyV" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Frost Giant"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Frost Giant"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[cold]]
trait_02: [[giant]]
trait_03: [[humanoid]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Crafting: +18, Intimidation: +18, Nature: +17, Stealth: +17"
abilityMods: [6, 0, 5, 0, 2, 0]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +23, __Ref__ +16, __Will__ +16"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  cold; __Weaknesses__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|+1 Striking Greataxe]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+21 (magical, reach 10 feet, sweep)\n__Damage__  2d12 + 12 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+21 (agile, reach 10 feet)\n__Damage__  2d8 + 12 bludgeoning"

  - name: "**Ranged** `pf2:1` Icicle"
    desc: "+21 (cold, primal, range 120 feet)\n__Damage__  3d6 cold 2d8 piercing"

  - name: "Chill Breath"
    desc: "`pf2:1` (cold,primal) The frost giant breathes out a 15-foot cone of freezing moisture that quickly condenses into ice, dealing 4d6 cold damage. Each creature in the cone must attempt a DC 28 Reflex check save. A creature that fails its save is also [[Conditions/Immobilized|Immobilized]] and takes 2d6 cold damage at the end of each of its turns until it gets free ([[/act escape dc=28]]).\n\nThe giant can't use Chill Breath again for 1d4 rounds."

  - name: "Ice Stride"
    desc: "  A frost giant isn't impeded by difficult terrain caused by snow or ice, nor do they need to attempt Acrobatics checks to keep from falling on slippery ice."

  - name: "Wide Swing"
    desc: "`pf2:1`  The frost giant makes a single greataxe Strike and compares the attack roll result to the ACs of up to two foes within their reach. This counts as two attacks for the frost giant's multiple attack penalty."
 
```

```encounter-table
name: Frost Giant
creatures:
  - 1: Frost Giant
```



Frost giants are remorseless marauders who pillage and plunder from those who dare to live near them in desolate, frigid lands. Their clans range from extremely territorial hunters who ferociously defend their expanse of tundra to nomadic families that roam icy slopes in search of settlements to conquer. Frost giant clans are ruled by the family member who exhibits the greatest ferocity and prowess in battle—often a massive bully who demands absolute obedience from the rest.

Frost giants' appearance is reflective of their icy homes, with flesh ranging from a translucent glacial blue to a slushy gray. A typical frost giant stands about 15 feet tall and weighs approximately 2,800 pounds. They often wear metal armor adorned with the furs, skin, teeth, and tusks of slain beasts and heft weapons as long as dining tables. A well-stocked frost giant clan will raise mammoth mounts or press witchwargs into service as hunting companions, but consider their environment too hostile for a soft concept like pets.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
