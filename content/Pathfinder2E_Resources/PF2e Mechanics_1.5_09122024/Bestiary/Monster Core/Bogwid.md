---
title: "Bogwid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.U8j4YBwCSsVo3Pyr" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Bogwid"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Bogwid"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Intimidation: +11, Stealth: +10"
abilityMods: [5, 4, 4, -4, -2, 1]
speed: 25 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +15, __Ref__ +12, __Will__ +8"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Weaknesses__ cold 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Revolting Aura"
    desc: " (aura,olfactory) 20 feet.\n\nA creature entering the aura or begins their turn in the aura must succeed at a DC 20 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (or [[Conditions/Sickened|Sickened 2]] on a critical failure). A creature that succeeds is temporarily immune to the aura for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+15 ()\n__Damage__  2d8 + 8 bludgeoning plus bogwid-fever"

  - name: "**Ranged** `pf2:1` Larval Spit"
    desc: "+14 (range increment 10 feet)\n__Damage__  2d8 bleed plus ravenous-young"

  - name: "Bogwid Fever"
    desc: " (disease) **Saving Throw** DC 20 Fortitude check\n\n**Onset** 1 day\n* * *\n\n**Stage 1** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 2]], and the DC to recover from persistent bleed is increased by 2 (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 3]], and the DC to recover from persistent bleed is increased by 5 (1 day)\n\n**Stage 4** [[Conditions/Enfeebled|Enfeebled 4]], the DC to recover from persistent bleed is increased by 5, and you take 1d8 persistent bleed damage every 1d4 hours (1 day)\n* * *\n\n[[Bestiary Effects/Effect_ Bogwid Fever|Effect: Bogwid Fever]]"

  - name: "Ravenous Young"
    desc: "  The larvae launched from the bogwid attach themselves to the target and begin to feed. Once a larva is attached, the target becomes [[Conditions/Drained|Drained 1]]. While the larva remains attached, the target cannot recover from persistent bleed. To remove the larva, the target can attempt to [[/act escape dc=21]]. Additionally, any area damage dealt to the target destroys all attached larvae.\n* * *\n\n[[Bestiary Effects/Effect_ Ravenous Young|Effect: Ravenous Young]]"
 
```

```encounter-table
name: Bogwid
creatures:
  - 1: Bogwid
```



The abhorrent combination between a toad and an octopus, a bogwid drags its bloated green body through the swamps in search of a meal for the many larvae it carries on its back. Despite its absurd appearance and its pervasive scent, a bogwid is an ambush hunter. It will hide itself in sand, vegetation, or whatever happens to be around and wait patiently until a larger creature, such as a humanoid or a crocodile, approaches, before it attacks. A desperate bogwid may even attack a small group in search of food for both it and its young. Once it has a suitably large corpse, the larvae on its back will leap onto it and begin fighting each other for their one chance at survival. The remaining larva buries itself in the body and begins devouring it over the next couple of weeks. Afterward, a fully grown bogwid emerges from what is left of the rotting corpse. Within a week of its new life, the young bogwid too will begin asexually producing larvae on its back, repeating the cycle.

Bogwids earned their name due to their environment. They are almost exclusively found in bogs and swamps. Occasionally one might be found in a suitable warm environment closer to civilization, but they are too often hunted if they are seen near a town or settlement. Some have discovered that bogwids have an extremely negative reaction when introduced to the cold and will violently attack whatever they perceive to be the source.
