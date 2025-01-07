---
title: "Straugh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Li805voi9uCC4TDx" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Straugh"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Straugh"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +22, Intimidation: +17, Stealth: +22, Survival: +22"
abilityMods: [8, 3, 7, -4, 3, 0]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +22, __Ref__ +16, __Will__ +16"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+23 ()\n__Damage__  2d12 + 12 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+23 (agile, reach 10 feet)\n__Damage__  2d8 + 12 piercing plus improved-grab,ghoul-paralysis"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 7d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "Fetid Screech"
    desc: "`pf2:1` (olfactory) Unaware that its vocal organs have withered and decayed, the straugh instinctively but ineffectively attempts to screech, instead releasing malodorous gas, half-digested corpse flesh, and small swarms of maggots from its open beak. The straugh releases a disgusting cloud of gas and decaying detritus in a 15-foot cone; any creature within the area must attempt a DC 28 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]]. On a critical failure, the creature also takes a -5 foot status penalty to its Speeds for 1 round. Any creature that succeeds at the save is temporarily immune to Fetid Screech for 24 hours.\n\n[[Bestiary Effects/Effect_ Fetid Screech (Critical Failure)|Effect: Fetid Screech (Critical Failure)]]"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 28 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 4d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 4d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 26 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Rock Tunneler"
    desc: "  A straugh can burrow through solid stone at a Speed of 10 feet. It can leave a tunnel if it desires, and it usually does."

  - name: "Tunneling Strike"
    desc: "`pf2:2` (earth) **Requirements** The straugh has Burrowed underground and remains undetected by the creature it plans to attack\n* * *\n\n**Effect** The straugh Burrows twice to emerge from the ground adjacent to at least one enemy and immediately makes a Strike against that foe."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Straugh
creatures:
  - 1: Straugh
```



When skirmishes break out between tunneling ghouls and creatures that dwell beneath the surface of Golarion, there's a chance that ghoul fever could infect such animals, producing strange new variants of ghoul beasts. However, letting the natural corruption run its course sometimes results in unsatisfying monsters, so some necromancers speed the process. This is the situation that led to the creation of the first straugh. A priest of Kabriri made the monstrosity to defend a claimed cemetery from another sect of ghouls who were preying upon the interred bodies. In some places, ghouls use straughs to tunnel into rival warrens or highly fortified mausoleums.
