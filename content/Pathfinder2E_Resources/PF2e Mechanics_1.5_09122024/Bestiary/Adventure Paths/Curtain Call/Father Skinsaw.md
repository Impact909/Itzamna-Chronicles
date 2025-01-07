---
title: "Father Skinsaw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YZeLhLCmQPckYYNL" 
tags:
  - pf2e/creature/type/illusion
  - pf2e/creature/type/mental
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Father Skinsaw"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Father Skinsaw"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[illusion]]
trait_02: [[mental]]
trait_03: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Greater Darkvision"
languages: "Telepathy 100 feet, Universal language"
skills:
  - name: "Skills"
    desc: "Athletics: +37, Deception: +38, Intimidation: +40, Occultism: +34, Religion: +33, Society: +36, Stealth: +38, Norgorber Lore: +36"
abilityMods: [7, 8, 7, 6, 5, 10]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +33, __Ref__ +38, __Will__ +31"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380; __Immunities__  death effects,  disease,  doomed,  scrying,  detection; __Weaknesses__ mental 15; __Resistances__ physical 15 (except cold iron)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Retribution"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Universal Language"
    desc: "  Anything spoken by the brainchild is perceived by the listener in its native language."

  - name: "Urban Legend"
    desc: "  As brainchild except Father Skinsaw's abilities are determined by the collective memories of his worshippers and Norgorber himself. Instead of using [[Actions/Seek|Seek]] or [[Actions/Sense Motive|Sense Motive]] to disbelieve any of his abilities, a character who's discovered some of Norgorber's secrets can confront Father Skinsaw with these truths by using [[Actions/Demoralize|Demoralize]] (DC 41), or they can taunt him with these secrets by Creating a Diversion (DC 43). On a success, in addition to the normal effects, that person can disbelieve one of Father Skinsaw's following abilities: resistance to physical damage, the extra bleed damage caused by his Strikes, his occult innate spells, or his Grievous Cut ability.\n* * *\n\nA brainchild is sustained only by the reputation that precedes them. Mindless creatures are immune to a brainchild and can't perceive them.\n\nThe brainchild's size, features, and items, as well as the appearance of their attacks, match what the foes perceiving them expect. If foes expect to see different things, the brainchild chooses which to manifest. If any creature that can perceive the brainchild believes the brainchild has one of the abilities below, the brainchild has that ability.\n\nA creature can [[Actions/Seek|Seek]] or [[Actions/Sense Motive|Sense Motive]] (against the brainchild's Deception DC) to attempt to disbelieve an individual ability. If at any point no creature perceiving the brainchild believes in the ability, the brainchild loses that ability immediately. If foes expect different particulars, such as one believing the brainchild is immune to fire and another believing they're immune to divinations, the brainchild chooses one to have.\n\n*   **[[Bestiary Ability Glossary/Tremorsense|Tremorsense]]** (imprecise) 100 feet\n*   **Immunity** to one damage type, magic school, or condition\n*   **Weakness** 10 to one damage type other than mental\n*   **Resistance** 10 to physical damage, with an exception for either cold iron or silver\n*   **[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]** (aura, emotion, fear, mental) 100 feet, DC 28\n*   **1d6 Extra Damage** on Strikes, of a type one foe believes in\n*   **Additional Spells** [[Spells/Phantom Pain|Phantom Pain]] and [[Spells/Shadow Blast|Shadow Blast]] at 6th rank"

abilities_mid:
  - name: ""
  - name: "Persistence of Memory"
    desc: " (illusion,mental,occult) As brainchild, except the time is chosen by Norgorber.\n* * *\n\nWhen a brainchild is destroyed, it returns if anyone still fully believes it exists, re-forming within 100 feet of any believer after 2d4 days."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Retribution"
    desc: "+41 (agile, backstabber, deadly d8, finesse, magical)\n__Damage__  3d4 + 17 slashing 1d6 bleed"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __10th __  _[[Spells/Massacre|Massacre]]_; __9th __  _[[Spells/Phantasmagoria|Phantasmagoria]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_; __6th __  _[[Spells/Blood Vendetta|Blood Vendetta (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Bloodletting"
    desc: "  **Trigger** Father Skinsaw is adjacent to a creature that takes persistent bleed damage\n\n**Frequency** once per round\n* * *\n\n**Effect** Blood writhes from the bleeding creature to splash onto Father Skinsaw, granting him 40 temporary Hit Points for 1 minute.\n\n[[Bestiary Effects/Effect_ Bloodletting|Effect: Bloodletting]]"

  - name: "Cut Across Space"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Father Skinsaw makes a war razor Strike against a target within 120 feet."

  - name: "Grievous Cut"
    desc: "`pf2:2`  Father Skinsaw attempts a war razor Strike against an adjacent target. If he hits, the blade cuts deep and creates a grievous wound. In addition to the normal damage caused by the attack, the creature struck takes 4d6 bleed damage and becomes [[Conditions/Wounded|Wounded 1]] (or increases the value of an existing wounded condition by 1, to a maximum of [[Conditions/Wounded|Wounded 4]])."

  - name: "Sneak Attack"
    desc: "  Father Skinsaw deals 3d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."
 
```

```encounter-table
name: Father Skinsaw
creatures:
  - 1: Father Skinsaw
```


Male variant brainchild

A rumor can become so vivid and so persistent that it comes to life, creating a brainchild-a living illusion that hatches from an intense belief in a remorseless and implacable killer. Often, these rumors swirl around the victims of a [[Spells/Phantasmal Killer|Phantasmal Killer]] spell. A brainchild's capabilities grow when they pursue a believer but deflate against skeptics, making them only as bad as one thinks they are. A simple drive to stalk, terrify, and kill propels a brainchild, but the creature might also exhibit other behaviors ascribed to them through gossip.
