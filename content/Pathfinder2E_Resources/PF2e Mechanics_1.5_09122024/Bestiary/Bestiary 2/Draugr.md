---
title: "Draugr"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3HewsikT3mGWbKKT" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Draugr"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Draugr"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[water]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +8"
abilityMods: [4, 2, 3, -1, 1, 1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +6, __Will__ +7"
hp: 35
health:
  - name: ""
  - name: HP
    desc: "35, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 5; __Resistances__ fire 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]], [[Equipment/Leather Armor|Leather Armor]]"
abilities_mid:
  - name: ""
  - name: "The Sea's Revenge"
    desc: " (curse,divine) A creature that slays a draugr is subjected to a [[Spells/Mariner's Curse|Mariner's Curse]] spell with a DC 17 Will check save. The curse ends if the draugr is buried in a calm sea or after 1 week passes."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+10 (sweep)\n__Damage__  1d12 + 4 slashing plus grotesque-gift"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+10 (agile)\n__Damage__  1d4 + 4 slashing plus grotesque-gift"

  - name: "Grotesque Gift"
    desc: " (olfactory) A draugr's attacks spatter their targets with rancid flesh and rotting seaweed. A creature damaged by a draugr's Strike must succeed at a DC 15 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."

  - name: "Swipe"
    desc: "`pf2:2`  The draugr makes a melee Strike and compares the attack roll result to the AC of up to two foes, each of whom must be within its melee reach and adjacent to each other. Roll damage only once and apply it to each creature hit. A Swipe counts as two attacks for the draugr's multiple attack penalty."
 
```

```encounter-table
name: Draugr
creatures:
  - 1: Draugr
```



Risen corpses of sailors who died at sea, draugr reek of the rot and decay of the briny deep. Their eyes glow with ghastly green light, and rotting seaweed, barnacles, and dead sea creatures cling to their bodies. Draugr can't speak, but expresses their malicious emotions with gurgles, as though they were eternally drowning with lungs full of water. They desire little more than to attack living creatures, especially those who sail the sea. Even when they go upon land, draugrs often drag the corpses of those they strike down back to the water, populating the depths with even more dead.

Draugr rise in the haunted places of the sea, where restless spirits, swells of void energy, or supernatural storms deliver death. A corpse might rest at the bottom of the sea for some time before awakening as a draugr. Collecting detritus and organisms, a corpse becomes increasingly disgusting before it finally rises. Proximity to intelligent life can expedite this process, and an underwater explorer who happens upon a shipwreck might cause a body to snap to unlife as a draugr suddenly. The creatures don't take intrusions lightly, especially upon their place of death.

Though steeped in evil, draugr are susceptible to reminders of their lives as mariners. In particular, a well-performed sea shanty or call-and-response work song might cause a draugr to become lost in reverie for a moment. The creatures have even been witnessed moaning along, unable to sing the words but providing haunting accompaniment. The lull rarely lasts long, though, as the beauty of the song quickly becomes a reminder of the tragedy that befell the draugr, reaffirming their desire for blood and death.

More powerful draugr with burning red eyes are called draugr captains. They're 3rd-level creatures with elite adjustments that can cast obscuring mist as an innate divine spell three times per day.
