---
title: "Wordsmith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0vFU2MmzbJroAAfo" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Wordsmith"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Paizo Blog: It&#x27;s Foolish To Go Alone"
name: "Wordsmith"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; "
languages: "Common, Dwarven; truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Crafting: +14, Occultism: +10, Scribing Lore: +12"
abilityMods: [4, 3, 4, 6, 2, 2]
speed: 25 feet
sourcebook: "_Paizo Blog: It&#x27;s Foolish To Go Alone_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +13, __Ref__ +8, __Will__ +11"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Resistances__ sonic 7"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Artisan's Toolkit (Sterling)|Anvil and Hammer]]"
abilities_mid:
  - name: ""
  - name: "Word Warp"
    desc: "`pf2:r` (auditory,occult) **Trigger** The wordsmith is the target of a linguistic effect\n* * *\n\n**Effect** The wordsmith twists the words and attempts to counter their foe's utterances with their hammer (counteract [[/gmr 1d20+16 #Councteract]]{+16}, 3rd rank)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hammer"
    desc: "+14 (forceful, occult, sonic)\n__Damage__  1d6 sonic plus forge-onomatopoeia 2d6 + 4 bludgeoning plus forge-onomatopoeia"

  - name: "**Ranged** `pf2:1` TWANG!"
    desc: "+13 (occult, range 60 feet, sonic)\n__Damage__  2d4 + 4 sonic"

  - name: "Occult Innate Spells"
    desc: "DC 24, attack +14; __2nd __  _[[Spells/Noise Blast|Noise Blast]]_, _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_; __1st __  _[[Spells/Command|Command]]_\n__Cantrips__  __(2nd)__ _[[Spells/Figment|Figment]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Forge Onomatopoeia"
    desc: " (occult,visual) The wordsmith slams their hammer against a creature, creating a visual onomatopoeia like CRACK! or SMASH! that flies off at the site of impact. The target of the strike must attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** The creature is stupefied 1 for 1 minute.\n\n**Critical Failure** The creature is [[Conditions/Stupefied|Stupefied 2]] and gains weakness 1 to sonic damage for 1 minute."

  - name: "Mightier than the Sword"
    desc: " (occult) Any hammer gains the forceful trait, can't be disarmed, and becomes a +1 striking hammer while the Wordsmith wields it."
 
```

```encounter-table
name: Wordsmith
creatures:
  - 1: Wordsmith
```



With every strike of a wordsmith's hammer, a new onomatopoeia is formed. They swiftly grab the word as it flies off the anvil before nailing it to the pages of our favorite comics. POW! WHAM! SPLAT! The hammer crafts each and every sound. The humble wordsmith is often overlooked by their artisan peers, whose pictures are the primary focus of readers. However, many don't realize that while pictures can be sent to the printing press, sounds are not captured so easily on the page and must be hammered into place by a skilled wordsmith.

While most wordsmiths are content to forge their words out of sight of the public, they are fierce defenders of their work and are quick to fight anyone who belittles it. They know the pen is mightier than the sword, but the hammer is mightiest of all, and they use it mercilessly to SMASH! through their foes.

Though many wordsmiths are dwarves, they come from all kinds of backgrounds, each bringing their own unique sounds and noises from their culture. Tengu wordsmiths particularly favor onomatopoeias similar to bird calls like caw for crows or okalee for red-winged blackbirds. Meanwhile, leshy wordsmiths favor sounds inaudible to most non-plant creatures, such as the tr-tr-tr that reflects the sound of a plant growing.
