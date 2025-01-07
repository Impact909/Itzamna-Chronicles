---
title: "Kun"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wL678KQCJIo7UCGW" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2e/creature/type/cold
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Kun"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Kun"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aquatic]]
trait_02: [[beast]]
trait_03: [[cold]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; "
languages: "Thalassic; (can&#x27;t speak any languages)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +29, Intimidation: +22, Survival: +25"
abilityMods: [8, 4, 7, 1, 5, 4]
speed:  swim 40 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +24, __Will__ +23"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Weaknesses__ holy 10; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "Spite"
    desc: "`pf2:r`  **Trigger** A creature within reach of the kun's tail uses an action to heal or help anyone else\n* * *\n\n**Effect** The kun bats the triggering creature away with their tail, making a tail Strike against the creature. On a hit, the action is disrupted and the creature is pushed 10 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (reach 15 feet)\n__Damage__  3d12 + 14 piercing plus grab,heart-of-darkness"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+28 (reach 20 feet, sweep)\n__Damage__  3d12 + 14 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +24; __7th __  _[[Spells/Darkness|Darkness (At Will) (x99)]]_, _[[Spells/Wall of Ice|Wall of Ice]]_; __5th __  _[[Spells/Control Water|Control Water (At Will) (x99)]]_"

  - name: "Funnel"
    desc: "`pf2:2` (cold,primal,water) The kun inhales violently, sucking in heat and all creatures in the water in a 60-foot cone. Creatures take 10d8 cold damage and must attempt a DC 33 Fortitude check save. The kun can't Funnel again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is pulled 30 feet toward the kun.\n\n**Critical Failure** The creature takes double damage and is pulled 60 feet toward the kun."

  - name: "Heart of Darkness"
    desc: "  Whenever the kun makes a jaws Strike from within an area of darkness, their jaws deals an additional 2d6 spirit damage and gains the unholy trait."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d12+7 bludgeoning, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."
 
```

```encounter-table
name: Kun
creatures:
  - 1: Kun
```



Hungry and resentful, the malevolent kuns are mythological fish monsters that dwell in the remotest, coldest depths of the ocean. These massively powerful creatures could easily rule a subaquatic domain if they cared to, but kuns are also famous for their total self-absorption and complete ambivalence toward other forms of life. Kuns remain as far away from other creatures as they can, subsisting on only their own icy hatred. They can consume and digest prey, but such feedings are incidental or driven more by spite than any physical need. Most kuns remain ignorant and uncaring, keeping themselves in the dark and disregarding any signs of life around them except to occasionally lash out when disturbed.

The kun hunts at the bottom of the cold, dark sea. But if shown the light of the sun, a kun begins to understand that it dwells within a different, bigger world. When flocks of birds or schools of fish cast their dappled shadows upon a kun, they might grow weary of their solitude or become curious about the realm above.
