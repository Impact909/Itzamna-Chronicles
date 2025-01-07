---
title: "Warden of Oceans and Rivers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rYM9gJpxr9ps8j1G" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/22
  - remaster
statblock: inline
name: "Warden of Oceans and Rivers"
level: 22
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Warden of Oceans and Rivers"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[aquatic]]
trait_02: [[beast]]
trait_03: [[water]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; "
languages: "voices of nature"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Athletics: +40, Intimidation: +36, Nature: +39, Stealth: +42, Survival: +42"
abilityMods: [10, 9, 12, 6, 8, 6]
speed:  swim 100 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +39, __Ref__ +36, __Will__ +33; +1 to all saves vs primal"
hp: 540
health:
  - name: ""
  - name: HP
    desc: "540; __Immunities__  controlled,  emotion,  mental,  poison,  precision; __Weaknesses__ electricity 15; __Resistances__ bludgeoning 20, cold 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Scent|Scent (Imprecise) 200 feet]]"
    desc: "  Scent involves sensing creatures or objects by smell, and is usually a vague sense. The range is listed in the ability, and it functions only if the creature or object being detected emits an aroma (for instance, incorporeal creatures usually do not exude an aroma).\n\nIf a creature emits a heavy aroma or is upwind, the GM can double or even triple the range of scent abilities used to detect that creature, and the GM can reduce the range if a creature is downwind."

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Voice of Nature|Voice of Nature]]"
    desc: "  Though the Wardens of the Wild do not speak in words, they can communicate complex concepts flawlessly and wordlessly with any animal, beast, plant, or other creature of the natural world through prolonged eye contact. Sapient creatures with strong ties to the natural world, such as animal instinct barbarians or druids who speak the Wildsong, can somewhat understand a Warden of the Wild, though the meaning can be vague."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Warden's Crown|Warden's Crown]]"
    desc: "  A Warden of the Wild's horned crown commands respect from wild creatures. Wild creatures native to a warden's biome automatically improve their attitude toward it by one step (up to friendly) and typically do not take hostile actions towards each other while in the warden's presence."

abilities_mid:
  - name: ""
  - name: "Bioluminescent Maelstrom"
    desc: " (aura,primal,visual,water) 30 feet DC 45 Will check\n* * *\n\nThe warden's wrath conjures a dazzling storm around them that makes the area difficult terrain. Creatures that enter the storm must attempt a Will save. A creature that succeeds at this save is temporarily immune to the luring visuals for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round, and for the first action on its next turn, the creature must use a single action to move as close to the warden as possible.\n\n**Critical Failure** The creature is dazzled for as long as it remains in the aura. Whenever the creature begins its turn within the aura, the creature must use the first action of its turn to move as close to the warden as possible. It can attempt a new save at the end of its turn, ending this effect on a success."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horned Crown"
    desc: "+41 (magical, reach 10 feet)\n__Damage__  2d8 + 15 cold 2d8 + 15 poison"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+43 (agile, magical, reach 30 feet)\n__Damage__  4d10 + 16 bludgeoning plus grasp-of-the-deep"

  - name: "All Are One"
    desc: "`pf2:1`  **Frequency** once per turn\n* * *\n\n**Effect** The warden attracts organisms that extend their influence. The area of bioluminescent maelstrom and the reach of their tentacle Strike increase by 10 feet for 1 minute, to a maximum of an additional 30 feet."

  - name: "Arctic Embrace"
    desc: "`pf2:2` (cold) All creatures in the warden's bioluminescent maelstrom take 10d6 cold damage (DC 45 Fortitude check save). On a failure, the creature is also [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "Grasp of the Deep"
    desc: "  Creatures struck by one of the warden's tentacles gain cold weakness 10 and take a –2 status penalty to Fortitude saves for 1 round.\n\n[[Bestiary Effects/Effect_ Grasp of the Deep|Effect: Grasp of the Deep]]"

  - name: "I Am The Tide"
    desc: "`pf2:2` (primal,water) The warden creates three lines of rushing water, each 10 feet wide and 120 feet long. Creatures in the area take 18d8 bludgeoning damage (DC 45 Fortitude check save). The warden can either push or pull, and all creatures that fail this save move up to 40 feet in the direction chosen. The warden can't use I Am The Tide again for 1d4 rounds."

  - name: "What Lurks Beneath"
    desc: "`pf2:3`  The warden attacks with their tentacles six times."
 
```

```encounter-table
name: Warden of Oceans and Rivers
creatures:
  - 1: Warden of Oceans and Rivers
```



## A Vengeful Present

In past eras, the Warden of Oceans and Rivers was once connected to the world of landed creatures and deeply involved in their channels of commerce. Now the descendants of these creatures are unable to rely on the bounty of the sea and feel that they must take what they can to survive. Fishing folk must be swift and deliberate now that the oceans and rivers zealously protect their goods. It is for this reason not all agree with the new warden's tactics… and some wish to see the old ways restored.
