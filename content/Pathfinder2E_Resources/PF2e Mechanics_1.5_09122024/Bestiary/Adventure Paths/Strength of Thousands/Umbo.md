---
title: "Umbo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7Q9AND5mJir9qg1y" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Umbo"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Umbo"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fungus]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Sakvroth; telepathy 100 feet (myceloids and those afflicted by purple pox only)"
skills:
  - name: "Skills"
    desc: "Stealth: +9, Survival: +8"
abilityMods: [3, 3, 4, -1, 2, 0]
speed: 20 feet
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +7, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet (Myceloids and Those Afflicted by Purple Pox Only)]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Spore Pop"
    desc: "  If Umbo is reduced to 0 HP by a critical hit, he pops, forcing him to immediately Emit Spores, even if he has already used the ability that day."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 ()\n__Damage__  1d8 + 3 bludgeoning plus purple-pox"

  - name: "Emit Spores"
    desc: "`pf2:1`  **Frequency** once per day\n* * *\n\n**Effect** Umbo expels spores in a 10-foot burst centered on a corner of his own space. This cloud lasts until the start of the myceloid's next turn. Each creature that is in the cloud or enters it is exposed to purple pox."

  - name: "Purple Pox"
    desc: " (disease) Myceloids are immune\n\n**Saving Throw** DC 18 Fortitude check\n\n**Onset** 1 minute\n\n**Stage 1** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 day)\n\n**Stage 2** 4d6 poison damage, [[Conditions/Stupefied|Stupefied 3]], and the creature is compelled to seek out the nearest myceloid colony-this compulsion is a mental emotion effect (1 day)\n\n**Stage 3** The creature dies. Over 24 hours, its corpse becomes bloated and bursts, releasing a new, fully grown myceloid."

  - name: "Spore Domination"
    desc: "`pf2:2` (emotion,incapacitation,mental,primal) Umbo targets one creature affected by purple pox within 30 feet. That creature must attempt a DC 18 Will check save. It is then temporarily immune to spore domination for 10 minutes.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** Until the end of its next turn, the target is helpful to myceloids and can't take hostile actions against them. If attacked by Umbo, the target is freed from this effect at the end of Umbo's turn.\n\n**Failure** As success, but for 1 minute.\n\n**Critical Failure** As success, but until the purple pox is cured."
 
```

```encounter-table
name: Umbo
creatures:
  - 1: Umbo
```




