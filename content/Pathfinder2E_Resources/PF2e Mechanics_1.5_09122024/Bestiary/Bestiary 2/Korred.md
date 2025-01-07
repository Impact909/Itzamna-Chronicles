---
title: "Korred"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.egFHyFbwpjAtwS3o" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Korred"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Korred"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[fey]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Crafting: +11, Deception: +13, Performance: +13, Stealth: +11"
abilityMods: [4, 3, 2, 1, 2, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +13, __Will__ +10; +1 status to all saves vs. magic"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Club|Club]], 5x Rock, [[Equipment/Sack|Pouch]]"
abilities_mid:
  - name: ""
  - name: "Animated Hair"
    desc: " (aura,primal) 5 feet. The korred's long, animated hair reaches out and interferes with creatures in the area. The korred can select which targets are affected by their animated hair. An affected creature that ends its turn in the emanation must succeed at a DC 18 Reflex check save or become [[Conditions/Clumsy|Clumsy 1]] ([[Conditions/Clumsy|Clumsy 2]] on a critical failure) as long as it remains in the aura."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+14 ()\n__Damage__  2d6 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Club"
    desc: "+14 (thrown 10 ft.)\n__Damage__  2d6 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+14 (brutal, range increment 20 feet)\n__Damage__  1d6 + 7 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 21, attack +11; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_; __4th __  _[[Spells/Shape Stone|Shape Stone (At will)]]_, _[[Spells/Shatter|Shatter (At will)]]_"

  - name: "Hair Snare"
    desc: "`pf2:1` (incapacitation,primal) The korred causes a long, tangled length of their hair to detach from their body and snake out to coil around an adjacent creature. The creature must attempt a DC 21 Reflex check save.\n\nThe korred cannot use Hair Snare again for 1d4 rounds.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The hair wraps around the creature. The creature takes a -10-foot circumstance penalty to all of its Speeds until it Escapes (DC 21) or until the korred uses Hair Snare again (at which point the previous snare drops to the ground, no longer animated).\n\n**Critical Failure** The creature is [[Conditions/Immobilized|Immobilized]] until it Escapes (DC 21) or the korred uses Hair Snare again."

  - name: "Otherworldly Laugh"
    desc: "`pf2:2` (auditory,fey,incapacitation,primal,sonic) **Frequency** three times per day\n* * *\n\n**Effect** The korred unleashes an otherworldly laugh. Each non-fey creature within a 30-foot burst must attempt a DC 21 Fortitude check save. On a failure, the creature is [[Conditions/Slowed|Slowed 1]] for 1 round (or [[Conditions/Stunned|Stunned 1]] on a critical failure)."

  - name: "Stone Stride"
    desc: "`pf2:2` (earth,primal,teleportation) The korred steps into a block of stone large enough for them to fit inside and instantly teleports to any other stone within 30 feet that has the same minimum size. Once the korred enters the stone, they instantly know the rough locations of other sufficiently large stones within 30 feet. They can exit from the original stone, if they prefer. They can't carry extradimensional spaces with them when they Stone Stride; if the korred attempts to do so, Stone Stride fails."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Korred
creatures:
  - 1: Korred
```



Korreds are reclusive fey in the form of small, hirsute individuals with long, animated manes of hair. While korreds have a natural affinity and admiration for stones and boulders, they prefer to dwell aboveground in areas of rocky forest or wooded hills rather than in caves. Korreds are a private people who don't take kindly to intruders, and they invariably work to drive off or kill any non-fey who stumble into their territory. Staunchly proud of their hair, korreds choose their minimal attire so as to allow their body hair to flow freely, often wearing only a belt with a pouch for throwing rocks and trimming shears-though this belt and pouch are rarely visible under their wild manes.
