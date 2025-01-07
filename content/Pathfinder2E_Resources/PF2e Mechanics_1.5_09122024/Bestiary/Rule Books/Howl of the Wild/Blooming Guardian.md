---
title: "Blooming Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VakMUwkeFOObQhmN" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Blooming Guardian"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Blooming Guardian"
level: "Creature 15"

alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; "
languages: "Fey; speak with animals, speak with plants"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Intimidation: +21, Nature: +29, Survival: +27"
abilityMods: [5, 3, 5, 1, 3, 1]
speed: 50 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +32, __Ref__ +23, __Will__ +25"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360; __Weaknesses__ fire 15; __Resistances__ void 15"
abilities_top:
  - name: ""

  - name: "Petal Form"
    desc: "  The blooming guardian can dissipate momentarily into a swirling cloud of petals and pollen to pass over brambles and slip through cracks. When Striding in woodland terrain, the blooming guardian ignores difficult terrain and can pass through obstacles so long as there is a small passageway."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 36 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Antlers"
    desc: "+28 ()\n__Damage__  4d12 + 5 piercing"

  - name: "**Melee** `pf2:1` Hooves"
    desc: "+26 ()\n__Damage__  4d10 + 5 bludgeoning plus improved-knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 33, attack +0; __3rd __  _[[Spells/Animal Vision|Animal Vision]]_\n__Constant__  __(4th)__ _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Budding Siphon"
    desc: "`pf2:1` (aura,primal,stance,void) 20 feet. A blooming guardian is in a constant state of decomposition; to keep this entropy at bay, the flowers that cover their antlers continually siphon life from the surrounding area. All living creatures that enter or start their turn in the emanation take 6d4 void damage (DC 36 Fortitude check save). At the start of their turn in any round that the blooming guardian deals damage with siphoning buds, they gain 10 temporary Hit Points, plus 2 temporary Hit Points for each creature damaged beyond the first since the blooming guardian's last turn, to a maximum of 20 temporary Hit Points."

  - name: "Full Bloom"
    desc: "`pf2:1` (poison,primal,stance) The flowers on the blooming guardian's antlers bloom, unveiling their brilliance as they eat away at their host. While in this stance, the blooming guardian's Strikes deal an additional 2d4 poison damage plus 5 persistent poison damage; on a hit, a target must succeed at a DC 36 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 2]]. The blooming guardian takes 5 persistent poison damage as long as it's in Full Bloom."

  - name: "Goring Charge"
    desc: "`pf2:2`  The blooming guardian Strides twice and makes an antlers Strike after either Stride. If the Strike hits, the blooming guardian deals an extra 2d12 bludgeoning damage, and the target takes a –2 circumstance penalty to its next Fortitude save against blossom siphon."

  - name: "Wail of the Forest"
    desc: "`pf2:2` (primal,void) **Requirements** The blooming guardian is in Full Bloom\n* * *\n\n**Effect** The blooming guardian confronts their mortality, causing their flowers to burst and spray their pollen. All creatures in a 40-foot cone take 10d10 void damage with a DC 36 Fortitude check save. The blooming guardian then exits Full Bloom and can't enter it again for 1d4 rounds.\n* * *\n\n**Critical Success** No effect.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and becomes [[Conditions/Drained|Drained 1]]. Creatures that are [[Conditions/Enfeebled|Enfeebled]] lose that condition and increase the drained condition by the same value.\n\n**Critical Failure** As failure, but double damage."
 
```

```encounter-table
name: Blooming Guardian
creatures:
  - 1: Blooming Guardian
```



The pestilent blossoms adorning the antlers of a blooming guardian are most beautiful in moonlight, when they achieve full bloom and reveal their celestial glow. When blooming guardians near the end of their life cycle, they walk one final patrol of their forest as their ancient body decomposes into the understory.
