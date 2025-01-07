---
title: "Ijhyeojin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xx04n2GPIHlpp0FK" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/sahkil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Ijhyeojin"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Ijhyeojin"
level: "Creature 14"

alignment: ""
size: "Medium"
trait_01: [[fiend]]
trait_02: [[sahkil]]
trait_03: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet, truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Deception: +28, Intimidation: +28, Religion: +28, Stealth: +25, Boneyard Lore: +28"
abilityMods: [6, 5, 4, 4, 8, 8]
speed: 30 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +22, __Ref__ +25, __Will__ +28"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310; __Immunities__  fear effects; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Easy to Call"
    desc: "  An ijhyeojin's level is considered 2 lower for the purpose of being conjured by the [[Spells/Planar Servitor|Planar Servitor]] ritual (and potentially other rituals, at the GM's discretion), but they're always free to attack or leave instead of negotiate unless the primary caster's check is a critical success."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense (Imprecise) 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Forgotten Presence"
    desc: "`pf2:r`  **Trigger** The ijhyeojin critically succeeds at a saving throw against a spell\n* * *\n\n**Effect** The ijhyeojin redirects the triggering spell to a new target other than its caster. If the ijhyeojin is wearing that target's face, the new target takes a –2 circumstance penalty to this saving throw."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile)\n__Damage__  3d8 + 14 slashing plus swipe-countenance"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __4th __  _[[Spells/Rewrite Memory|Rewrite Memory (At Will) (x99)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only) (x99)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech (x99)]]_"

  - name: "Overwrite Memory"
    desc: "`pf2:2` (emotion,fear,mental) The ijhyeojin alters the memories of a target within 30 feet, insinuating their faceless visage in the place of others. The target must attempt a DC 34 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Frightened|Frightened 1]] and treats no one as an ally for as long as it's frightened.\n\n**Failure** The target is [[Conditions/Frightened|Frightened 2]] and is [[Conditions/Confused|Confused]] for as long as it's frightened.\n\n**Critical Failure** The target is [[Conditions/Frightened|Frightened 4]] and confused for as long as it's frightened. If the target is a joseung saja, they instead realize the fear of being forgotten and become an ijhyeojin."

  - name: "Swipe Countenance"
    desc: "`pf2:1` (mental,visual) **Requirements** The ijhyeojin's previous action was a successful claw Strike against the target\n* * *\n\n**Effect** The ijhyeojin copies the countenance of the target, imprinting it perfectly onto their own blank face. While only their face changes, creatures must [[Actions/Seek|Seek]] them and succeed at a DC 34 Will check save to distinguish them visually from the original creature. The sakhil keeps the same visage for 24 hours or until they steal another."
 
```

```encounter-table
name: Ijhyeojin
creatures:
  - 1: Ijhyeojin
```



Ijhyeojins (ee-jyuh-jeens) were once joseung sajas, psychopomps who guided the dead to the Boneyard as divine punishment for their sins. Over time, they rejected their roles and became sakhils. Some did this due to a sense of injustice over having to atone for their sins in the afterlife, but all do so partially out of a desperate desire to reclaim their memories—for ijhyeojins are named for the fear they manifest, the fear of being forgotten. They prey on people who are socially isolated by circumstances or those obsessed with their legacy, slowly cutting their victims off from friends, professional contacts, and family. Ijhyeojins particularly enjoy infiltrating medical facilities to prey on patients who fear about being forgotten in their deaths, snatching away crucial memories from them or their visiting loved ones. Hunting in this way also grants the sahkils ideal positioning to lure joseung sajas to their demise.

Ijhyeojins resemble the pale-skinned psychopomps they used to be, except their faces have no distinguishable features, like a skull with a smooth layer of skin pulled over it. Their bodies continue to twist and grow the longer they live.
