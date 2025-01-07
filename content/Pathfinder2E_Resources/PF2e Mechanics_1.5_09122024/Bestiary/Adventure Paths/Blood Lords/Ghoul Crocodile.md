---
title: "Ghoul Crocodile"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kx4jd4GbzaDWS5eS" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Ghoul Crocodile"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Ghoul Crocodile"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12, Stealth: +9"
abilityMods: [4, 1, 3, -5, 1, -4]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +11, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

  - name: "Corpse Scent (Imprecise)"
    desc: "  The ghoul crocodile can smell humanoid corpses in the water up to 1 mile away."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d8 + 6 piercing plus ghoul-ghoul-fever,grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+14 (agile)\n__Damage__  2d6 + 6 bludgeoning plus ghoul-paralysis"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  **Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul crocodile is adjacent to the corpse of a creature that died within the last hour\n* * *\n\n**Effect** The ghoul crocodile devours a chunk of the corpse and regains 2d6 healing Hit Points. It can regain HP from any given corpse only once."

  - name: "Death Roll"
    desc: "`pf2:1` (attack) **Requirements** The ghoul crocodile must have a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The ghoul crocodile tucks its legs and rolls rapidly, twisting its victim. It makes a jaws Strike with a +2 circumstance bonus to the attack roll against the grabbed creature. If it hits, it also knocks the creature [[Conditions/Prone|Prone]]. If it fails, it releases the creature."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 19 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a ghoul the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living non-elf creature hit by a ghoul crocodile's tail must succeed at a DC 20 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ghoul Crocodile
creatures:
  - 1: Ghoul Crocodile
```




