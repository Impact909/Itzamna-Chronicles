---
title: "Davik Nettles"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.e51WZrji0pY8ihji" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Davik Nettles"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Davik Nettles"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +11"
abilityMods: [5, 3, 2, 0, 2, 3]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +11, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Resistances__ fire 7"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ranseur|+1 Ranseur]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Fearsome Gaze"
    desc: " (concentrate,divine,emotion,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it must attempt a DC 18 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature becomes [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature becomes [[Conditions/Frightened|Frightened 2]]."

  - name: "Rejuvenation"
    desc: " (divine) If Davik is reduced to 0 Hit Points, his bones and gear melt into water that runs back into the river or seeps into the ground, leaving nothing behind. The next night, he rises again from his original location in the rubble located downstream from the ruined ferry crossing. When he does, he is completely healed of all damage, but now his unholy anger is directed at those who previously destroyed him as well as at the Stag Lord. He can use nightmare to threaten the one who destroyed him, promising to drag them to a drowning death unless the Stag Lord's remains are given to the river. [[Spells/Dispel Magic|Dispel Magic]] (DC 19 counteract check) can remove this sinister link between Davik and his destroyer, preventing Davik from using nightmare on that creature again until they return to this location. As long as the PCs don't abandon their goal of hunting the Stag Lord, Davik remains content and does not plague their dreams."

  - name: "Rotting Stench"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting their turn in the aura must succeed at a DC 18 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] on a critical failure for as long as it's sickened). While within the aura, creatures also take a -2 circumstance penalty to saves against fear and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute and does not take the penalty to saves against fear effects.\n\n[[Bestiary Effects/Effect_ Rotting Stench|Effect: Rotting Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ranseur"
    desc: "+14 (disarm, magical, reach 10 feet)\n__Damage__  1d10 + 7 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile)\n__Damage__  2d4 + 7 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 21, attack +13; __4th __  _[[Spells/Nightmare|Nightmare]]_\n__Constant__  __(2nd)__ _[[Spells/Water Walk|Water Walk (Self Only)]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,emotion,fear,mental,visual) Davik fixes his glare at a creature he can see within 30 feet. The target must immediately attempt a Will save against Davik's Fearsome Gaze. On a failed save, if the target is already [[Conditions/Frightened|Frightened]], the value of its frightened condition is increased by 1 (or by 2 on a critical failure). After attempting its save, the creature is then temporarily immune until the start of Davik's next turn"

  - name: "Sure Possession"
    desc: "  As long as Davik Nettles continues to exist, his +1 ranseur cannot be taken from him. If disarmed of the +1 ranseur, if he drops it, or if it's destroyed, the ranseur melts into water; he can retrieve his +1 ranseur by pulling it out of any body of water as an Interact action. If Davik is put to rest permanently by fulfilling his quest, his +1 ranseur loses this ability and can be claimed by someone else."
 
```

```encounter-table
name: Davik Nettles
creatures:
  - 1: Davik Nettles
```




