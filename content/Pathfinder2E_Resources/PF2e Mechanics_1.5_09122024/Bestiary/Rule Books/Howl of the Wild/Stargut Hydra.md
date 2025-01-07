---
title: "Stargut Hydra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3WEoS82I8jLR5vZY" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Stargut Hydra"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Stargut Hydra"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +20, Stealth: +18, Survival: +18"
abilityMods: [5, 3, 6, -3, 3, -1]
speed: 25 feet,  burrow 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 27
armorclass:
  - name: AC
    desc: "27 all-around vision; __Fort__ +21, __Ref__ +18, __Will__ +14"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, hydra regeneration"
abilities_top:
  - name: ""

  - name: "Skymetal Metamorphosis"
    desc: "  Each stargut hydra has at least one metamorphosis resulting from consuming a specific skymetal and internalizing its properties. If you give a stargut hydra more than one metamorphosis, you should consider increasing its level and changing its statistics.\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Adamantine)|Adamantine]]** The stargut hydra's Strikes bypass Hardness and are treated as adamantine. The stargut hydra gains resistance 10 to physical damage (except adamantine).\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Abysium)|Abysium]]** (aura, poison) The stargut hydra emits an aura of nauseating radiation from the abysium in its body. Any creature that begins its turn within 30 feet of the stargut hydra is [[Conditions/Sickened|Sickened 1]].\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Djezet)|Djezet]]** (magical) The stargut hydra gains a +2 status bonus to saves against magic.\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Inubrix)|Inubrix]]** The stargut hydra's Strikes ignore resistance to damage from metal armor's armor specialization effects and do not trigger the Shield Block reaction or reactions from armor property runes.\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Noqual)|Noqual]]** The stargut hydra's Strikes and abilities gain a +2 status bonus to damage against creatures with the ability to Cast a Spell.\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Orichalcum)|Orichalcum]]** When the stargut hydra has only two heads remaining, it is [[Conditions/Quickened|Quickened]]. It can use the extra action only to Stride or Strike.\n\n**[[Creature Family Ability Glossary/(Stargut Hydra) Skymetal Metamorphosis (Siccatite)|Siccatite]]** After the stargut hydra takes fire damage, it becomes superheated, gaining immunity to fire and weakness 10 to cold. While superheated, cold damage can be used to cauterize a stump. After the stargut hydra takes cold damage, it becomes chilled, gaining immunity to cold and weakness 10 to fire."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Hydra Regeneration"
    desc: "  The stargut hydra has regeneration equal to 3 × the number of heads it has. If a hydra's body is missing any heads and the remaining stumps have not been cauterized, the hydra attempts a DC 29 Fortitude check save after it regains Hit Points from regeneration. On a success, one uncauterized stump regrows two heads; on a critical success, two uncauterized stumps regrow into two heads each. The hydra can never grow more than double the number of heads it ordinarily has. The hydra's regeneration only fully deactivates if all its heads are severed and all stumps are cauterized, at which point it dies."

  - name: "Head Regrowth"
    desc: "  A stargut hydra ordinarily has five heads. A creature can attempt to sever one of the hydra's heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that is not completely severed returns to full Hit Points at the end of any creature's turn. A hydra can regrow a severed head using hydra regeneration. A creature can prevent this regrowth by dealing acid or fire damage to the stump, cauterizing it. Single-target acid or fire effects need to be targeted at a specific stump, but effects that deal splash damage or affect areas covering the hydra's whole space cauterize all stumps if they deal acid or fire damage. If the attack that severs a head deals any acid or fire damage, the stump is cauterized instantly. If all five heads are cauterized, the hydra dies.\n\n[[Bestiary Effects/Effect_ Hydra Heads|Effect: Hydra Heads]]"

  - name: "Reactive Heads"
    desc: "  A stargut hydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the hydra must use a different head for each Reactive Strike it makes. Whenever one of the hydra's heads is severed, the hydra loses 1 of its extra reactions per round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Stargut Hydra Heads"
    desc: "  **HP** (head) 22, head regrowth\n\n**Immunities** area damage\n\n**Weaknesses** slashing 10"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (reach 15 feet)\n__Damage__  2d8 + 8 piercing"

  - name: "Vomit Meteorites"
    desc: "`pf2:2`  The stargut hydra lurches its entire body, spewing forth chunks of meteorite in a 30-foot cone that deal 5d6 bludgeoning damage to all creatures in the area (DC 25 Reflex check). The area becomes difficult terrain for 1 minute, though a creature can use an Interact action to clear one square of the rubble. The stargut hydra can't Vomit Meteorites for 1d4 rounds."
 
```

```encounter-table
name: Stargut Hydra
creatures:
  - 1: Stargut Hydra
```




